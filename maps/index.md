---
layout: page
title: The Metadata Maps
subtitle: 
use-site-title: false
---

This report contains a series of maps to better align and compare data
from different digitised newspaper collections. Each page is devoted to
a low-resolution category of the metadata, such as *title*, *publisher*
or *text*. Within that category, we have attempted to subdivide the
relevant elements and fields into categories of metadata that are the
most comparable across databases, for example *normalised title* or
*individual word*.

Each section provides a technical definition of that category as well as
an exploration of how the term, or variant terms, have been used by
modern researchers in periodical studies, literary studies, library
science and computer science (where appropriate) as well as in a
nineteenth-century context. This is followed by a discussion of any
exceptions or eccentricities regarding this category within the data
collections. It concludes with a list of relevant XPaths, or other
identifiers, and key information regarding the nature of the data in
each element. With this information, the reader should be able to
understand the different structures of these collections and develop
computational means for robustly comparing datasets.

These maps represent data and metadata that is comparable, to
varying degrees, across the collection. They have been grouped
teleological, by their most likely use: content, citation, bibliography,
holdings, description, social interaction and technical information.
Scholarly, technical and industry terms have been included and indexed
to facilitate information retrieval throughout.

In addition to descriptive information, each map provides a table with
the following information:

  - A locater, comprised of the four-letter collection ID
  - The XPath or JSON path to that data
  - A data type indicator, comprised of a three-letter ID
  - An example of the content of that field with long strings of content
    text begin truncated with \[…\]

The data type and collection IDs are as follows:

### Data Types

| BOO | A Boolean char such as 0/1 or Y/N  |
| COO | A set of numeric coordinates to delineate a segment of an image |
| DAT | A single date  |
| DAR | A range of dates  |
| FIN | A filename  |
| STR | An open-ended string of content (alphanumeric)  |
| MCH | Multiple pre-defined choices  |
| NUL | Holds no content; used as a container element for other fields  |
| NUM | Numeric value; may include the symbols . , -  |
| UID | Any form of unique ID or acronym  |
| URL | A url  |

### Collection IDs
| B1GI  | British Library 19<sup>th</sup> Century Newspapers, Part I, Gale’s Current Text-Mining Drives  | GIFT  | Issue Metadata XML File  |
| B1GP  | British Library 19<sup>th</sup> Century Newspapers, Part I, Gale’s Current Text-Mining Drives  | GIFT  | Publication Metadata XML File  |
| B1GT  | British Library 19<sup>th</sup> Century Newspapers, Part I, Gale’s Current Text-Mining Drives  | GIFT  | Text Content XML File  |
| B2GI  | British Library 19<sup>th</sup> Century Newspapers, Part II, Gale’s Current Text-Mining Drives  | GIFT  | Issue Metadata XML File  |
| B2GP  | British Library 19<sup>th</sup> Century Newspapers, Part II, Gale’s Current Text-Mining Drives  | GIFT  | Publication Metadata XML File  |
| B2GT  | British Library 19<sup>th</sup> Century Newspapers, Part II, Gale’s Current Text-Mining Drives  | GIFT  | Text Content XML File  |
| B1JI  | British Library 19<sup>th</sup> Century Newspapers, Part I, British Library’s Text-Mining Drives | Bespoke  | Content and Metadata XML File  |
| B1GL  | British Library 19<sup>th</sup> Century Newspapers, Part I, Gale’s Legacy Text-Mining Drives  | GIFT  | Content and Metadata XML File  |
| B2GL  | British Library 19<sup>th</sup> Century Newspapers, Part II, Gale’s Legacy Text-Mining Drives  | GIFT  | Content and Metadata XML File  |
| CAAL  | Chronicling America  | ALTO  | Content and Layout XML File  |
| CADI  | Chronicling America  |  | Directory Structure  |
| CAME  | Chronicling America  | METS  | Issue Metadata XML File  |
| DEAL  | Delpher  | ALTO  | Content and Layout XML File  |
| DEMP  | Delpher  | MPEG  | Issue Metadata XML File  |
| DEOC  | Delpher  | Bespoke  | OCR Text XML File  |
| EUAL  | Europeana  | ALTO  | Content and Layout XML File  |
| EUME  | Europeana  | METS  | Issue Metadata XML File  |
| F1AL  | Finnish National Library 1771–1910  | ALTO  | Content and Layout XML File  |
| F2AL  | Finnish National Library 1771–1910  | ALTO+  | Content, Layout and Metadata XML File |
| F1ME  | Finnish National Library 1771–1910  | METS  | Issue Metadata XML File  |
| HNME  | Hemeroteca Nacional Digital de México  | METS+  | Content, Layout and Metadata XML File |
| HNDM  | Hemeroteca Nacional Digital de México  | Bespoke  | Content and Metadata JSON File  |
| PPAL  | Papers Past  | ALTO  | Content and Layout XML File  |
| PPDI  | Papers Past  |  | Directory Structure  |
| PPME  | Papers Past  | METS  | Issue Metadata XML File  |
| SBAL  | State Library of Berlin  | ALTO  | Content and Layout XML File  |
| SBME  | State Library of Berlin  | METS  | Issue Metadata XML File  |
| SBMA  | State Library of Berlin  | METS  | Publication Metadata XML File  |
| SBMY  | State Library of Berlin  | METS  | Publication-Issue Metadata XML File  |
| TDAG  | Times Digital Archive  | GIFT  | Content and Metadata XML File  |
| TRAL  | Trove  | ALTO  | Content and Layout XML File  |
| TRAP  | Trove  | Bespoke  | API XML Return  |
| TRME  | Trove  | METS  | Issue Metadata XML File  |

These maps are accurate to October 2019 for the specific the collection
dataset listed above; however, it has been our experience that data
providers frequently update, tweak or otherwise modify their metadata
schema, both for new collections and in order to retrofit previous
collections based on end-user feedback. We are also aware of specific
forthcoming updates to several of these collections, details of which
have not yet been made publicly available. It is therefore advisable
that you consult with the data provider on their current schema before
undertaking any data mining project.