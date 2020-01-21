---
layout: page
title: Europeana
subtitle: Europeana Foundation, Netherlands
use-site-title: false
---

## History of the Collection

[Europeana](https://www.europeana.eu) is a collection of collections,
drawing from more than 2,000 cultural heritage partners all throughout
Europe. The full Europeana platform contains over 50 million artworks,
artefacts, books, films and music from European museums, galleries,
libraries and archives.

A thematic newspapers collection within Europeana was established in
July 2019. It mainly builds on the [Europeana Newspapers project
(2012-2015)](http://www.europeana-newspapers.eu) that was funded by the
European Commission’s ICT Policy Support Programme, as part of the
Competitiveness and Innovation framework Programme (CIP). The project
received an initial €5.2 million with a maximum European Commission
contribution of €4.1 million. Europeana Newspapers aggregated metadata
for more than 20 million digitised newspaper pages from a variety of
European libraries, collected around 12 million page images of digitised
newspapers and processed them with OCR and OLR, and developed a
prototype portal for full-text search in digitised newspapers at The
European Library (TEL). Following the closing of the TEL service at the
end of 2016, the newspaper collection was migrated to a “thematic
collection” subsite of the main Europeana platform.

### Consulted Libraries

The following full Europeana Newspapers project partners have typically
contributed a public domain subset of their digitised newspaper
collections to the project: National Library of Austria, National
Library of France, National Library of Netherlands, Dr. Friedrich
Teßmann State Library, National Library of Estonia, National Library of
Latvia, National Library of Finland, State and University Library of
Hamburg, Berlin State Library, University Library of Belgrade, National
Library of Poland, and National Library of Turkey. Furthermore, these
associate partners have shared some data, but generally only metadata:
National and University Library of Slovenia, National and University
Library of Iceland, Royal Library of Belgium, National and University
Library of Zagreb, St. Cyril and Methodius National Library of Bulgaria,
National Library of Romania, National Library of Luxembourg, National
Library of the Czech Republic, National Library of Spain, National
Library of Portugal, National Library of Wales, National Library of
Serbia, and National and University Library of Slovakia.

### Microfilming Projects

Europeana draws from existing databases, so it does not undertake any
microfilming or material preservation but relies solely on the capture
processes of its project partners, some of which have individual entries
within this Atlas.

### Digitisation Projects

Europeana draws from existing databases, so it does not undertake any
digitisation but relies on contributions of digitised materials from
gallery, library, archive and museum (GLAM) institutions.

#### Selection

The main selection criteria for the aggregation of digitised newspapers
to Europeana is the conformance with the [Europeana Publishing Framework](https://pro.europeana.eu/post/publishing-framework), which details
several tiers of quality requirements and recommendations for metadata,
text and image content. For inclusion within the thematic collection,
the most general requirement is that the data provider populates the
dc:type field with one of the following terms: Newspaper Title,
Newspaper Issue, Analytic serial, Newspaper, journal, or printed serial.

#### Preservation and Access

Since Europeana is an aggregator platform for digitised cultural
heritage, it does not undertake any preservation activities itself, but
does act as an additional access site for included digitised newspapers.

## Composition of the Collection

### Selection Available

Europeana Newspapers is a collection of collections. It assembles
digitised historical newspaper content from more than twenty distinct
data providers, each with their own data parameters and histories. In
total, the Europeana Newspapers collection includes 28,816,750 pages in
forty different languages. Because of the multiple origins of the data
and the migration process, it now holds data in varying degrees of
refinement – while roughly 12 million pages of the originally aggregated
20 million pages have machine-readable full text from OCR, another
approximately 8 million pages are only available in Europeana through
their metadata. Furthermore, a wide variety of digitised newspaper data
that already existed on Europeana prior to the migration of Europeana
Newspapers from TEL to the main Europeana platform has since also been
merged into the thematic collection.

### Data Quality

#### Text

The overall OCR quality of the Europeana Newspapers collection is
approximately 70-85% but varies widely; a full report from 2015 is
available via the Europeana Newspapers project website. The majority of
the Europeana newspapers were scanned from microfilm. A performance
evaluation has shown that this only slightly impacts OCR quality, with
less than 1% loss of accuracy, while it enables an efficient
digitisation of large-scale volumes.

#### Images

Images from project partners were provided to Europeana Newspapers in
various formats. Since Europeana Newspapers conducted the OCR and OLR
for these images, images were only used if they were considered to be of
archival quality. For the purposes of OCR/OLR processing, all images
were converted to TIFF. In addition, JPEG2000 versions were created for
all images to enable display and zooming on the web.

### Metadata Schema 

All Europeana Newspapers project data and metadata follows the [ENMAP
profile](http://www.europeana-newspapers.eu/wp-content/uploads/2015/05/D5.3_Final_release_ENMAP_1.0.pdf),
a dedicated metadata profile for digital newspapers based on established
community standards METS and ALTO. Full details of the encoding schema
(v 1.0, 2015) are available on the Europeana Newspapers project website.
For aggregation into Europeana, [a special profile for representing full
text alongside the Europeana Data Model was created](https://docs.google.com/document/d/1t5yGEzQ0KV2rqU0sFDoKnI2bIDBGrmj0f1gSOCRUgJ4/edit).
It is also [aligned with the IIIF standard](https://docs.google.com/document/d/1vhQstotXm4b-t8FHCzStHNCoz1dVzGFsaXLrn2vCPVI/edit).
Europeana metadata has also been released in [EDM in
XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.edm.xml),
[EDM in
JSON-LD](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.edm.jsonld),
[Dublin Core in
XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.dc.xml),
and [CLARIN CMDI in
XML](http://test-solr-mongo.eanadev.org/europeana-research-newspapers-dump/sample-2017-06-23/Staatsbibliothek_zu_Berlin_-_Preu%25C3%259Fischer_Kulturbesitz/Berliner_Tageblatt/newspaper_title_metadata.cmdi.xml).

## User Interface Structure

### Web Interface

In Europeana, users can search for terms across the full text or the
newspaper title. It is also possible to filter by collection, media,
rights availability, providing country, language, aggregator and
institution. Users can browse content through date, title, or a map. The
search results display the issue-level metadata of the content-providing
libraries, with varying degrees of information: full text and newspaper
page image are displayed, with links to view the original in the source
library, if available.

### API

Europeana provides several APIs to use with the newspaper collection:

  - Newspapers Search API, which allows searching of the full text and
    metadata of the newspapers

  - IIIF Manifest API, which allows access to IIIF manifests

  - IIIF Image API, which allows access to newspaper images

  - IIIF Fulltext API, which allows access to the full text of the
    newspapers

Documentation and examples of use are [available](https://pro.europeana.eu/resources/apis).

### Direct Download or Drives

Newspaper metadata and full text sets per data provider are available
for [direct download](https://pro.europeana.eu/resources/apis/iiif\#download). Users can also
directly download individual digitised newspaper pages via the Europeana
user interface.

## Rights and Usage

### Web Interface

All titles are freely searchable through Europeana and each individual
object contains information about its [terms of use](https://rightsstatements.org/en). 
However, full access to recent
twentieth-century content is problematic owing to copyright. Europeana
Newspapers has developed a “Roadmap for Improving Access to Newspapers”
to urge policy makers to consider more open licences for digitised
newspapers.

### API 

Item-specific information about terms of use is also available via the
API.

### Re-Publication

Most of the newspapers assembled by Europeana Newspapers are dedicated
to the public domain with all metadata being released under a CC0
license and may therefore be re-published freely. See individual terms
of use for further details.