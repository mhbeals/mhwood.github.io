---
layout: page
title: Page Number
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/page-number">View Glossary Entry</a></h4>

## Technical Definition

Provides an ID for the page. This is divided into: unique identifiers,
page image numbers, identifiers across the database; URLs to
web-accessible versions of the page; relative numerical identifiers,
within the [**issue**](../issue-number); and string descriptors.

## Category Notes

This field is found in all collections.

## Individual Collection Notes

B1GL: The unique identifier is a page image ID. The
issue\\article\\pi\\pgref field specifies the relative page ID for the
unique page image ID. The issue\\article\\ci\\pgref specifies the page
ID for the clipped article image, and
issue\\article\\text\\text.cr\\pg@pgref specifies the relative page ID
for the generic clip rectangle, which is the same as the article zone.

B2GL: The unique identifier is a page image ID. The
issue\\article\\pi\\pgref field specifies the relative page ID for the
unique page image ID, the issue\\article\\ci\\pgref specifies the page
ID for the clipped article image,
issue\\article\\text\\text.cr\\pg@pgref specifies the relative page ID
for the generic clip rectangle (which is the same as the article zone),
and issue\\article\\text\\text.title\\pg@pgref specifies the relative
page ID for the article title. Clipref specifies the relative page image
ID.

CAAL: The number of the page within the physical document.

DEMP: didl:DIDL\\didl:Item\\didl:Item\\didl:Descriptor\\didl:Statement
contains the page number as a string (e.g. “page 1”). Each item and each
component have a descriptor that describes the role of that element in
the newspaper issue. The roles are listed in the statement element of
the descriptor.

SBME: The “ORDER” field provides the page number in sequence, starting
from 1. “ORDERLABEL” provides page numbers based on image file numbers,
starting from 0.

## Instantiations

### Unique Identifier  

| B1GL  |  issue\\article\\pi  | UID | WOJL-1822-01-03-0002  |
| B2GL  |  issue\\article\\pi  | UID | WOJL-1822-01-03-0002  |
| B2GI  |  issue\\page\\article\\id  | UID | YOHD-1813-07-31-0001-001  |
| CADI  |  sn\\year\\month\\day\\edition\\null\[sequence\]  | STR | seq-1  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Item@dc:identifier  | UID | ddd:010419500:mpeg21:p001  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcx:recordIdentifier | UID | ddd:010419500:mpeg21:p001  |
| F2AL  |  pageOCRDATA\\metadata\\pageIdentifier  | NUM | 7687234  |
| HNDM  |  $.publication.pagina.publicacion\_id  | STR | ObjectId(“558075bd7d1e63c9fea1a0eb”) |
| HNDM  |  $.publication.pagina.\_id  | STR | ObjectId(“558a32a47d1ed64f16885023”) |
| TDAG  |  issue\\page\\pageid  | UID | 0FFO-1812-JUL14-001  |
| TDAG  |  issue\\page\\article\\pi  | UID | 0FFO-1812-JUL14-001  |
| TDAG  |  issue\\page\\assetID  | UID | cs16791278  |

## **Relative**  

| B1GL  |  issue\\article\\pi@pgref  | NUM | 1  |
| B1GL  |  issue\\article\\ci@pgref  | NUM | 1  |
| B1GL  |  issue\\article\\text\\text.cr\\pg@pgref  | NUM | 2  |
| B2GL  |  issue\\article\\pi@pgref  | NUM | 2  |
| B2GL  |  issue\\article\\ci@pgref  | NUM | 2  |
| B2GL  |  issue\\article\\text\\text.title\\pg@pgref  | NUM | 2  |
| B2GL  |  issue\\article\\text\\text.cr\\pg@clipref  | NUM | 1  |
| B2GL  |  issue\\article\\text\\text.cr\\pg@pgref  | NUM | 2  |
| B1JI  |  BL\_newspaper\\BL\_page\\pageImage\\pageSequence  | NUM | 1  |
| CAME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Page metadata”\\xmlData\\mods:mods\\mods:part\\mods:detail\\mods:number | NUM | 2  |
| DEAL  |  alto\\Layout\\Page@PHYSICAL\_IMG\_NR  | NUM | 1  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\ddd:nativePageNumber  | NUM | 1  |
| F1AL  |  alto\\Layout\\Page@PHYSICAL\_IMG\_NR  | NUM | 1  |
| F2AL  |  pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page@PHYSICAL\_IMG\_NR  | NUM |  |
| CAAL  |  alto\\Layout\\Page@PHYSICAL\_IMG\_NR  | NUM | 195 |
| EUAL  |  alto\\Layout\\Page@PHYSICAL\_IMG\_NR  | NUM | 1  |
| F2AL  |  pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page@PRINTED\_IMG\_NR  | NUM | 204 |
| HNDM  |  $.publication.pagina.pagina  | NUM | 1  |
| PPAL  |  alto\\Layout\\Page@PHYSICAL\_IMG\_NR  | NUM | 1  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“PHYSICAL”\]\\mets:div\\mets:div@ORDER  | NUM | 6  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“PHYSICAL”\]\\mets:div\\mets:div@ORDERLABEL  | NUM | 5  |
| TDAG  |  issue\\page\\article\\pi@pgref  | NUM | 1  |
| TDAG  |  issue\\page\\article\\ci@pgref  | NUM | 1  |
| TDAG  |  issue\\page\\article\\text\\text.cr\\pg@pgref  | NUM | 1  |
| TDAG  |  issue\\page\\article\\text\\text.title\\pg@pgref  | NUM | 1  |
| TRAL  |  alto\\Layout\\Page@PHYSICAL\_IMG\_NR  | NUM | 1  |
| TRAP  |  article\\title\\page  | NUM | 1  |
| TRAP  |  article\\title\\page\\pageSequence  | STR | 1 S |

### String Descriptors  

| DEMP  |  didl:DIDL\\didl:Item\\didl:Item\\didl:Descriptor\\didl:Statement | STR | page 1  |
| F1AL  |  alto\\Layout\\Page@ID  | STR | P1  |
| F2AL  |  pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page@ID  | STR | P12  |
| PPAL  |  alto\\Layout\\Page@ID  | STR | P1  |
| CAAL  |  alto\\Layout\\Page@ID  | STR | PAGE.0  |
| DEAL  |  alto\\Layout\\Page@ID  | UID | P1  |
| EUAL  |  alto\\Layout\\Page@ID  | UID | P1  |
| TRAL  |  alto\\Layout\\Page@ID  | UID | PAGE1  |
| TRME  |  mets:mets\\mets:structMap\\mets:div\\mets:div@ID  | UID | divpage1 |

### URL  

| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl\_Resource@ref  | URL | http://resolver.kb.nl/resolve?urn=ddd:010419500:mpeg21:pdf  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Item\\didl:Component\\didl:Resource@ref  | URL | http://resolver.kb.nl/resolve?urn=ddd:010419500:mpeg21:p001:image  |
| TRAP  |  article\\pdf  | URL | http://trove.nla.gov.au/ndp/imageservice/nla.news-page2243325/print |
| TRME  |  mets:mets\\mets:fileSec\\mets:fileGrp\\mets:file\\mets:FLocat@xlink:href | URL | /pages/nla.news-issn22083111-s75000-b.tif  |
