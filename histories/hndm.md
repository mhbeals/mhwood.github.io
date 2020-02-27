---
layout: page
title: Hemeroteca Nacional Digital de México
subtitle: Universidad Nacional Autónoma de México
use-site-title: false
---

## History of the Collection

<img src="https://www.unamenlinea.unam.mx/recursos/img/81165/default_biblioteca.jpg" width="200" height="200" align="right">The [Hemeroteca Nacional Digital de México](http://www.hndm.unam.mx/index.php/es/) is the online repository of
digitised printed material from Mexico. The digital collections were
derived from materials belonging to the Fondo Reservado (special
collections) of the Hemeroteca Nacional (National Newspaper Library).
The Hemeroteca Nacional and the Biblioteca Nacional (Mexico’s National
Library) are under the stewardship of the Universidad Nacional Autónoma
de México (UNAM), Mexico’s national university, and both the physical
and digital collections are housed and maintained on campus. Planning
for the HNDM began in 2000. The project focused on digitising the
National Newspaper Library’s microfilm collection, which was created in 1960. 
Work began in earnest in 2002 and the first version was made
available that same year, with restricted access. Since then, the HNDM
has undergone several system migrations and new designs, the latest one
being in 2015.

### Consulted Libraries

The HNDM includes the newspaper collections belonging to the Fondo
Reservado (special collections) of the Hemeroteca Nacional.

### Microfilming Projects

Microfilming began at the Hemeroteca Nacional in the 1960s, when the
National Newspaper Library was moved from downtown Mexico City to the
new, purpose-built facility on the UNAM campus in the south of the city.
The microfilm collection has two copies for each newspaper, one in
silver halide for preservation purposes and the other in diazo film for
public lending. Currently there are approximately 28 million microfilmed
pages.

### Digitisation Projects

Although plans to digitise the library’s microfilm collection began in
2000, finding a company in Mexico City that had the equipment and the
experience to do the work proved more complicated than expected.
Eventually, a company based in another Mexican city began work in 2002.
The same company undertook the OCR as well as the digital platform and
hosting. In later years, the system was updated by UNAM and the system
migrated to UNAM servers.

#### Selection

The project was designed to include digitisation of the complete
microfilm collection. This was founded on the idea that the materials on
microfilm had already undergone a selection process which was based on
the following criteria: the newspaper’s degree of conservation, demand,
and historical, heritage, journalistic, and documentary importance. One
of the main problems in the early stages was that there was not a
reliable catalogue of the microfilm collection that included the
technical micrographic characteristics for the physical artifacts as
well as their state of conservation and the metadata about the
newspapers themselves. Therefore, the quality of the microfilm varies
leading to variation in the quality of the digitised images and OCR.

### Preservation and Access

The library continues to use microfilm as its main preservation strategy
for the newspaper collection. In recent years the library has turned its
attention to the digital preservation of the approximately 8 million
original digitised TIFF images from which the HNDM collection is
created.

## Composition of the Collection

### Selection Available

Currently, the HNDM has almost 8 million digitised pages from 941
newspaper titles between 1722 and 2006. Out of these, 516 titles
(1722–1889) are open access, and 425 (1890–2006) are restricted and
can only be accessed from inside the newspaper library’s facilities and
on campus. The microfilmed and digital archives can be found in the
National Newspaper Library’s Fondo Reservado (special collections),
which includes Mexican periodical publications between 1722 and 1917,
foreign periodical publications from 1665 to 1920, the Garcia Valseca
collection and the newspaper miscellanea and important newspapers
microfilms collections. Newspapers from the long nineteenth century,
1800 to 1914, contain 771 titles and 2,069,247 pages.

### Data Quality

#### Text

According to an analysis by the Dirección General de Cómputo y de
Tecnologías de Información y Comunicación at UNAM (the National
University’s Computing and Communication and Information Technologies
General Office), the OCR average success rate is 54%. It was found that
72% of the images have good readability, about 15% regular, and 13%
poor. The image quality was 56% good, 34% regular, and less than 10%
poor.

#### Image

The HNDM’s digitisation was obtained from 35mm microfilm rolls that the
National Newspaper Library created. Publication stills have been reduced
relative to their original size and contain between 140- and 180-line
pairs per millimeter (pl/mm). This reduces the impact of the
deterioration of paper and ink tones from the original documents over
time and produces a better contrast. To create the HNDM collection,
every page of every item from the newspaper was digitised as a bitonal
TIFF image.

### Backend Structure

The HDNM backend structure has been modified several times since its
creation in 2002. The current platform was developed in-house in a
collaboration between the UNAM’s central computing services and the
library’s computing service department. This collaboration was launched
in 2011. It is held in a MongoDB v.3.6 database and Solr for indexing.
This database is in JSON format, with metadata descriptions of the
collection, publication, item, page, and publication; it does not
include the actual OCR content. Work on the platform is ongoing and new
modules are being developed, particularly ones that allow the library to
administer the digital collection, such as uploading new images, adding
or modifying new metadata.

The dataset’s XML archive, containing the OCR of the digitized images,
works with three metadata schemes (Dublin Core, custom OCR/XML data, and
METS)*. In the OC*Red documents, the METS metadata schema includes, at
the beginning of the file, a publication description in Dublin Core with
date, title, city, state, country, category, collection and language. It
is followed by an OCR structure that divides page content into columns,
regions, paragraphs, lines, and words with an associated coordinate,
allowing the search terms to be highlighted by user.

## User Interface Structure

The current user interface was designed in-house and released in 2015.

### Search

The interface allows users to perform simple searches by title, year or
place, or advanced searches which combine the previous options together
with language, type of access and frequency of publication. The
interface also includes indexes which allows users to restrict their
searches by country, state, city, type of access, language, frequency of
publication, title and dates. Users can also search by word, which uses
the system’s underlying OCR files, and the results highlight the search
terms in the PDF. The interface also allows users to access detailed
bibliographic descriptions of the newspaper titles.

### API

There is currently no API available for the HNDM.

### Direct Download or Drives

The HNDM does not allow bulk downloads or access to any of its files,
neither the images nor the OCR. Newspaper titles can be printed or
downloaded one at a time as PDFs. However, in both cases the print
version is either extremely large, showing only one part of the image,
or extremely small image, with the newspaper page occupying just a
fraction of the PDF page. This renders the print option unviable. Users
who would like printouts must go to the HNDM office located in the
library.

## Rights and Usage

Materials in the HNDM which are considered under Mexican law to be in
the public domain are freely available online. The library worked in
close collaboration with the UNAM’s legal team, but it was difficult to
determine what is uncontestably within the public domain. The UNAM made
the decision to be cautious and so the cut off year was set as 1889.
This decision was made a few years ago and should, logically, be updated
each year, but to our knowledge this has not been done yet. Newspapers
from 1890 onwards are restricted access and can only be consulted from
within the library or the university campus. These are clearly indicated
in the interface with a padlock icon. The HNDM uses the term “open
access” for the newspapers that are freely available, although there are
restrictions. Materials can only be used for personal or educational
purposes and due credit must be given to the HNDM.

### Web Interface

The complete collection can be searched and, in the results, metatextual
information is presented and a thumbnail image of the newspaper. Closed
access newspapers are indicated with an icon and the PDFs cannot be
accessed.

### Re-Publication

Direct access to the OCR and image files is not available. Open access
PDFs cannot can be printed. Digital content cannot be incorporated into
any digital platform or application without prior authorization by the
HNDM.
  
## Suggested Citation

Beals, M. H. and Emily Bell, with contributions by Ryan Cordell, Paul Fyfe, Isabel Galina Russell, Tessa Hauswedell, Clemens Neudecker, Julianne Nyhan, Sebastian Padó, Miriam Peña Pimentel, Mila Oiva, Lara Rose, Hannu Salmi, Melissa Terras, and Lorella Viola. "Hemeroteca Nacional Digital de México." *The Atlas of Digitised Newspapers and Metadata: Reports from Oceanic Exchanges.* Loughborough: 2020. DOI: [10.6084/m9.figshare.11560059](https://figshare.com/articles/The_Atlas_of_Digitised_Newspapers_and_Metadata_Reports_from_Oceanic_Exchanges/11560059).
