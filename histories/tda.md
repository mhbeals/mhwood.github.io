---
layout: page
title: The Times Digital Archive
subtitle: Gale, a Cengage Company
use-site-title: false
---

## History of the Collection

<img src="https://3.bp.blogspot.com/-cVcrsbyDAI8/W5owN3KDa8I/AAAAAAAABaY/gyxyLZkeWFwN6DGXIG2al8WYviTonZucgCPcBGAYYCw/s1600/timesDigital.png" width="300" height="53" align="right">[*The Times* Digital
Archive](https://www.gale.com/intl/c/the-times-digital-archive) was the
first online digitised newspaper collection of British newspapers.
Produced by Gale (then Thomson Gale Publishers), the collection debuted
in 2002 with an initial remit to make available the entirety of *The
Times*, including its previous incarnations, from 1785–1985, after which
date digital text files were already available. This early adoption of
digitisation, and its building upon the popularity of the Palmer’s index
of *The Times*, ensured its prominence in historical and journalistic
research, including its use by the House of Lords in researching past
legal debates. As of 2019, it was the most searched digitised newspaper
database among Cengage’s news media collections. The archive is
refreshed annually, adding new issues in one-year sets on a rolling
basis.

## Consulted Libraries

As *The Times Digital Archive* is a single newspaper archive of a
continuing title, the entire database is derived from *The Times*’s
own archive, which included a complete backfile on microfilm.

## Microfilming Projects

Up through 1985, *The Times* backfile is preserved on 35mm microfilm.
After that date, issues have been archived using both microfilm and
born-digital files. The majority of the backfile microfilming was
undertaken in the 1990s, though some reels were processed by Gale’s
predecessors as early as 1974. The microfilm archives preserve the final
London edition of each issue and excluded regional editions, such as the
Irish or Scottish editions or editions which came out earlier in the
day. *The Times* was microfilmed from a variety of sources, including
bound volumes, and conditions, including defects such folding, tearing,
the use of adhesive tape and bad trimming.

## Digitisation Projects

Digitisation of *The Times* began in 2002 through the scanning of
existing microfilm. Because the initial 1785-1985 material was digitised
over just two years, there was a consistency of staff, equipment, method
and product, both in terms of image and OCR quality. The reels were
scanned using the Mekel M500 greyscale scanner and converted into 300
PPI bitonal TIFFs at a rate of six frames a minute, allowing the
digitisation of between two and five reels a day, depending on the
quality of the source material and the degree of intervention required
by the operator. After filming, the images were subdivided by month and
then cropped and de-skewed in preparation for OCR processing. Digital
restoration was undertaken to reduce the appearance or impact of damaged
pages, including manually cropping and cleaning and the insertion of
digital titles or page number where needed. Zoning of articles was done
partially through automated processes, leading to the amalgamation of
smaller individual units such as classified advertisements, and
partially by manual clipping, as was the case for birth, death and
marriage notices in order to aid family historians and professional
genealogists using the service.

## Selection

The aim of the initial project was to digitise the microfilm collection,
in its entirety, from 1785 until 1985. The content was released in
several batches: the first was 1936–1946, growing monthly to include
1880–1985 by the end of 2002. The entire microfilm run was completed by
the close of 2003. Since its acquisition by Cengage in 2007, Gale has
continued to expand the collection, which currently offers the complete
run of the publication from 1785 to 2013.

## Preservation and Access

While the full historical archive of *The Times* has now been
digitised, and new issues meet legal deposit legislation digitally, Gale
continues to microfilm *The Times* on a monthly basis as a commercial
product and as a preservation archive for *The Times* itself. Access
is via purchase or subscription only.

## Composition of the Collection

## Selection Available

*The Times* Digital Archive currently contains material from 1785–2013.
This includes over 1.6 million pages from 70,000 issues, sub-divided or
zoned into 11.8 million articles. These are catalogued by category,
including advertising, editorial and commentary, news, business, news,
people and photojournalism. Although the modern *Times* began
publication in 1788, the collection includes digital issues of its
precursors, *The Daily Universal Register* (1785–1787) and *The Times,
or, Daily Universal Register* (1788). The collection continues to expand
with additional content added on an annual basis.

## Data Quality

## Text

As OCR software provides only a digital confidence rating, which cannot
be meaningfully translated into a quality metric, and independent
quality studies have not yet been undertaken, the overall OCR quality of
*Times Digital Archive* is currently unknown.

The machine-readable text appears within a single XML file per issue,
surrounded by layered metadata that describes the features of the issue,
pages and articles. Issues between 1785–1985 were created during a
single project, undertaken by the same staff, using the same equipment
and processes, and working with microfilm that had been filmed over a
short period. Therefore, the data for these years has a relatively
consistent level of metadata and OCR quality, depending on the age or
preservation status of the source material at time of microfilm
creation. All issue-level metadata is hand keyed, alongside the article
title, article subheadings, attribution information and illustration
captions. Subsequent additions have been included on a rolling basis and
their data is contained in a separate but similar substructure within
the collection, using the same metadata schema, capture requirements and
level of detail but with new metadata fields to provide additional image
metadata including the height, width, file format and colour map.

## Image

Images in the collection before 2007 were captured as 300 PPI bitonal
TIFF files; since then, they have been captured at 400 PPI. These are
not compressed or reformatted before display through the web interface.

## Metadata Schema

## Gale Legacy Text Mining Drives

Before 2016, *The Times Digital Archive* data contains metadata and
text content in a single XML file at issue level. Although similar in
coverage to the METS/ALTO schema used by many public institutions, Gale
established a bespoke metadata schema to label information consistently
across its different newspapers and collections. A DTD file is provided
on the text-mining drives and the fields are comparable to those found
in Dublin Core, MARC and other standard bibliographical standards, to
which they have been successfully mapped when working with external
content partners.

Each XML file contains bibliographic information for the entire issue,
automatically zoned during the OCR process, with individual pages and
articles are represented as child elements. At the article-level, each
individual word is encoded with spatial coordinates of its location on
the corresponding image, as well as marker elements indicating new pages
or columns. Metadata fields including publication name, year, date,
issue number, page number, article title, article subheading,
attribution and illustration capture were manually entered or verified
by those processing the data.

## Gale Current Text Mining Drives

After 2018, the Gale Text Mining Drive separated metadata and text
content into three XML files: title or publication-level metadata,
issue-level metadata, and issue-level content data. As with the previous
schema, the data is encoded using Gale’s standardised metadata schema
and a DTD file is provided on the text-mining drives. Although distinct
from the METS/ALTO schema, this system is similar to a combination of
library MARC records and METS/ALTO XMLs.

## Backend Structure

The definitive dataset is kept in a proprietary XML format, known as the
Gale Interchange Format or GIFT, and from this its text-mining and
online datasets are derived. In addition to the metadata provided on
text-mining drives or online, this database stores image metadata on
resolution, file format, bit depth, colour map, file size and image
dimensions. Our image database stores image metadata, including image
resolution, file format, bit depth, colour map, file size, width and
height.

## User Interface Structure

## Web Interface

*The Times* Digital Archive can be searched using the Gale Primary
Sources interface. The basic search can be filtered to a specific
metadata field or the full text, a date range, a specific title or a
specific digitised collection. The advanced search allows for standard
Boolean operators and fuzzy searching as well as filtering by
publication date, publication section, document type and whether an
image is included. Results can be sorted by publication date, article
title, publication title or relevance and page number. On the search
results page, users are presented with additional filters and simple
analysis tools, such as term clusters and frequency. Individual results
can be viewed at article, page, or issue level. At article level, the
searched terms are highlighted, and users can navigate the issue by
moving to other pages or articles within it or refining their search
terms. Then can also adjust the image contrast and brightness to improve
legibility and download it using standard browser context menus. The
image may also be downloaded as a PDF as can the plain text of the OCR
content. Bibliographic information and a suggested citation are provided
at the bottom of the page.

## Direct Download or Drives

Gale Cengage offers to make available content from its collections to
academic researchers for data mining and textual analysis through
physical hard drives containing source data for a nominal cost recovery
charge. This includes directories, title manifests, XML files and image
files, containing metadata, article segmentation, and page facsimiles.

## Rights and Usage

## Web Interface 

*The Times Digital Archive is* accessible by institutional subscription
or purchase and is currently held by many public or national libraries
worldwide; there is currently no individual subscription model
available.

## API

API access is not currently available. However, users can create batches
of specific issues or titles for bulk download through the Gale [Digital
Scholar Lab](https://www.gale.com/intl/primary-sources/digital-scholar-lab), a
separate subscription service.

## Direct Download or Drives

Gale Cengage makes content from its collections available to academic
researchers for data mining and analysis through physical hard drives
for a nominal cost recovery charge. This includes directories, title
manifests, XMLs and image files. This data is only accessible to those
with institutional subscriptions or purchases of the relevant Gale
products. Material obtained on text mining drives may be used to examine
individual text for large-scale analysis for purposes of performing
personal or non-commercial research but cannot be duplicated or shared
without expressed permission.

## Re-Publication

As part of the user agreement, XML, OCR and image data cannot be
re-published in any form, physical or digital, without the express
permission and [licensing of News UK](https://newslicensing.co.uk/en/page/show_home_page.html). Small
quotations, using standard citation practices, may be reproduced in
accordance with local fair use provisions and should be accompanied by a
DOI link that points back to the individual full text article or book
chapter and a proprietary notice in the following form: “Some rights
reserved. This work permits non-commercial use, distribution, and
reproduction in any medium, provided the original author and source are
credited.”
  
## Suggested Citation

Beals, M. H. and Emily Bell, with contributions by Ryan Cordell, Paul Fyfe, Isabel Galina Russell, Tessa Hauswedell, Clemens Neudecker, Julianne Nyhan, Sebastian Padó, Miriam Peña Pimentel, Mila Oiva, Lara Rose, Hannu Salmi, Melissa Terras, and Lorella Viola. "The Times Digital Archive." *The Atlas of Digitised Newspapers and Metadata: Reports from Oceanic Exchanges.* Loughborough: 2020. DOI: [10.6084/m9.figshare.11560059](https://figshare.com/articles/The_Atlas_of_Digitised_Newspapers_and_Metadata_Reports_from_Oceanic_Exchanges/11560059).

