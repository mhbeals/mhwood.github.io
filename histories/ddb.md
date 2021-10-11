---
layout: map
title: Deutsches Zeitungsportal (German Newspaper Portal)
subtitle: Deutsche Digital Bibliothek (DDB), Germany
use-site-title: false
---

## History of the Collection

The digitisation of newspapers in Germany was originally not a very uniform effort with many libraries or archives striking out on their own. The German Research Foundation (Deutsche Forschungsgemeinschaft, DFG) set out to improve the situation starting with a pilot project in 2013. The project “Digitisation of Historical Newspapers” („Digitalisierung historischer Zeitungen“) resulted in a master plan that sets out rules and recommendations for a variety of aspects regarding the digitisation process of historical newspapers. It furthermore stipulates that the German Digital Library should build a national portal which should one day give access to all historical newspapers digitised by German cultural heritage institutions.

Following this recommendation, work on the national newspaper portal began in January 2019. It was conceived as a „sub-portal“ of the German Digital Library, i.e. the newspapers available in the portal are also part of the general collection of the German Digital Library, but the newspaper portal has its own landing page and can be explored via purpose-built functionalities like a fulltext search. Project partners are the German National Library, the Berlin State Library, the Saxon State and University Library Dresden and FIZ Karlsruhe - Leibniz Institute for Information Infrastructure. The portal was launched in October 2021 completing the first phase of the project. There will follow another two-year project phase to further develop and optimise the portal. Funding for these first two phases came from the four project partners and the German Research Foundation which contributed ca. 1 mio. € for each phase. After the second project phase the German Newspaper Portal will be maintained by the German Digital Library.

### Consulted Libraries

The long term goal of the German Newspaper Portal is to give access to all historical newspapers digitised by German cultural heritage institutions. However, this will be an ongoing process of many years. At the launch of the portal the following nine institutions contributed newspapers from their collections to the German Newspaper Portal: S&auml;chsische Landesbibliothek - Staats- und Universit&auml;tsbibliothek Dresden (SLUB); Staatsbibliothek zu Berlin - Preu&szlig;ischer Kulturbesitz (SBB); Martin-Luther-Universit&auml;t Halle-Wittenberg; Universit&auml;ts- und Landesbibliothek Sachsen-Anhalt (ULB); Staats- und Universit&auml;tsbibliothek Hamburg Carl von Ossietzky (SUB Hamburg); Badische Landesbibliothek (BLB); Landesbibliothek Oldenburg (LBO); Heinrich-Heine-Universit&auml;t D&uuml;sseldorf Universit&auml;ts- und Landesbibliothek D&uuml;sseldorf (ULB D&uuml;sseldorf); Bibliothek der Friedrich-Ebert-Stiftung (FES); Deutsches Exilarchiv (DEA).

### Microfilming Projects

The German Newspaper Portal draws from multiple existing collections, so it does not undertake any microfilming or material preservation itself, but relies solely on the capture processes of its data partners, some of which have individual entries within this Atlas.

### Digitisation Projects

The German Newspaper Portal draws from multiple existing collections, so it does not undertake any digitisation itself, but relies solely on the capture processes of its data partners, some of which have individual entries within this Atlas.

#### Selection

The main selection criteria for the aggregation of digitised newspapers is the conformance with the requirements of the German Newspaper Portal for metadata content. Newspaper collections can only be added to the German Newspaper Portal if they fulfill certain metadata criteria: For example, each newspaper must be registered at the [German Union Catalogue of Serials](https://zdb-katalog.de/) (Zeitschriftendatenbank, ZDB) and its metadata must contain the corresponding ZDB identifier. Furthermore, the metadata for each issue must contain the issue’s date of publication in ISO 8601 format as well as a standardized license (for re-use purposes). The full metadata requirements can be accessed [here](https://wiki.deutsche-digitale-bibliothek.de/display/DFD/Ausgabe+Zeitung+1.0) (available in German only). 

There do not exist any criteria regarding content. The German Newspaper Portal provides the infrastructure to bring together separate collections. It does not, however, curate this process in regards to criteria such as importance, place of origin, longevity or political affiliation of newspapers.

#### Preservation and Access

Since the German Newspaper Portal is an aggregator platform for digitised newspapers, it does not undertake any preservation activities itself, but does act as an additional access site for digitised newspapers.

## Composition of the Collection

### Selection Available

The German Newspaper Portal aggregates already existing collections from German cultural heritage institutions. It assembles digitised historical newspaper content from several data partners, each with their own data parameters and histories. The German Newspaper Portal was launched with a collection of 247 newspapers, 591,834 newspaper issues and 4,464,846 newspaper pages provided by nine institutions. However, the collection of the German Newspaper Portal is growing continuously.

Because of the multiple origins of the data and the migration process, it holds data in varying degrees of refinement – while roughly 4.5 million pages of the originally aggregated 3.7 million pages have machine-readable full text from OCR, another approximately 0.8 million pages are only available through their metadata.

### Data Quality

#### Text

The German Newspaper Portal brings together content that was created by the institutions holding the original newspapers in their collections, mostly libraries. Most institutions included some form of automatic text recognition by means of OCR in their digitisation processes, but some did not. As an aggregator, the German Newspaper Portal has no control over the OCR quality, nor does it collect systematic information about the OCR quality from its content providers. What can be said is that the newspapers available in the German Newspaper Portal were digitised over a long time frame, by many different institutions and using a variety of workflows and softwares. As a result, the full text quality that can be found in the German Newspaper Portal varies greatly. Therefore, one work package of the second project phase will look at the possibility of reprocessing and improving low quality OCR texts.

#### Images

The newspaper viewer (based on [Kitodo-Presentation](https://www.kitodo.org/software/kitodopresentation)) allows users to download and display any image type. Data partners provide images to the German Newspaper Portal in various formats but mostly as JPEG and TIFF files. The viewer also offers the option to download images as PDF files.

### Metadata Schema

Building on the recommendation of the DFG’s master plan for newspaper digitisation in Germany and the established METS/MODS profile used by the German Digital Library for library resources, the German Newspaper Portal developed a special METS/MODS profile for digitised newspapers. Using the ZDB’s persistent identifiers, some standardised metadata fields are extracted directly from the ZDB database such as the title, place of publication and periods of publication. ALTO is used as the format to store the OCR full text. Only institutions that employ this METS/MODS profile can submit their newspaper collections into the German Newspaper Portal. The full metadata requirements can be accessed [here](https://wiki.deutsche-digitale-bibliothek.de/display/DFD/Ausgabe+Zeitung+1.0) (available in German only). 

### Backend Structure

In the backend of the German Newspaper Portal a newspaper issue corresponds to one XML file. The XML file contains the issue’s metadata including the primary key of the newspaper (ID of the Zeitschriftendatenbank) and sections for each page of the issue. Each section, in turn, contains the links to the image of the page and to the ALTO file for the page. The ALTO files contain the recognized words of a particular page and the absolute pixel coordinates for the location of each word on the scan of the page. The XML files are stored in an Apache Cassandra database.
The backend enables several search functions.The search for newspaper issues and in newspaper issues is realised by indexing the issue metadata and the ALTO files (full text search) into a SOLR index (newspaper issues index). Highlighting of the search terms on the scan of the newspaper page is realized with the [Solr OCR highlighting plugin](https://github.com/dbmdz/solr-ocrhighlighting). The search for newspapers is realized by indexing a [dump file](https://www.zeitschriftendatenbank.de/services/schnittstellen/linked-data/) containing all newspapers into a Solr index (newspaper index).
For opening a newspaper, a viewer software is employed. This newspaper viewer (based on [Kitodo-Presentation](https://www.kitodo.org/software/kitodopresentation)) loads the newspaper issue XML file and presents the scans of the newspaper pages. Full text search is realised by querying the newspaper issues index and rendering of the highlighted search term on the scan of the corresponding newspaper page.

## User Interface Structure

### Web Interface

In the German Newspaper Portal, users can search for terms across the full texts of all available newspapers or for the newspaper title in connection with a date (required format: dd.mm.yyyy). It is also possible to filter the results by year of publication, newspaper title, place of publication, data provider and language. There is also a fulltext search option within one specific newspaper or within one specific newspaper issue. Furthermore, users can browse content through title, place and a calendar function. Registered users can save their searches or their favourite results to their personal space.

### API

The German Newspaper Portal provides an API for the digitised newspapers, which allows retrieval of images, full text and metadata. It is documented at [https://api.deutsche-digitale-bibliothek.de/](https://api.deutsche-digitale-bibliothek.de/). Before using the API, users first need to register with the German Newspaper Portal and set up an access code („API key“).

### Direct Download or Drives

Currently, the API is the only way to bulk-download digitised newspapers from the German Newspaper Portal. Users can also directly download individual digitised newspaper pages via the user interface. Here, they can choose between downloading a single page, a complete issue and the full text of a newspaper issue (if available).

## Rights and Usage

The German Newspaper Portal only accepts collections that are provided with one of the standardised licenses employed by the German Digital Library. The licenses can be found [here](https://pro.deutsche-digitale-bibliothek.de/node/848). The decision which license to choose lies with each data partner. For each newspaper issue, the corresponding information is displayed in the viewer page.

### Re-Publication

Out-of-copyright text and images are in the public domain and may be used or republished for both personal and commercial purposes. The evaluation which newspapers are out-of-copyright lies with each data partner who chooses a corresponding standardised license.

Newspapers which are tagged with a Creative Commons license can be re-used according to the terms of the specific Creative Commons license.

Newspapers that remain under third-party copyright may not be redistributed or republished, in print or digitally. They may, however, be linked to directly.

Each newspaper issue is provided with a stable link for citation purposes.

## Suggested Citation

Beals, M. H. and Emily Bell, with contributions by Ryan Cordell, Paul Fyfe, Isabel Galina Russell, Tessa Hauswedell, Clemens Neudecker, Julianne Nyhan, Sebastian Padó, Miriam Peña Pimentel, Mila Oiva, Lara Rose, Hannu Salmi, Melissa Terras, and Lorella Viola. "Deutsches Zeitungsportal." *The Atlas of Digitised Newspapers and Metadata: Reports from Oceanic Exchanges.* Loughborough: 2020. DOI: [10.6084/m9.figshare.11560059](https://figshare.com/articles/The_Atlas_of_Digitised_Newspapers_and_Metadata_Reports_from_Oceanic_Exchanges/11560059).