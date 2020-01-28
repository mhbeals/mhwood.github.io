---
layout: map
title: Issue Date
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/date">View Glossary Entry</a></h4>

## Technical Definition

Gives the **date** of the [**issue**](../issue-number). May refer to the publication date,
the date as printed on the issue, the ISO standard date or a part of the
date, such as the day of the week, day, month or year. In some cases,
this is normalised and in others it is the date as printed on the image.

## Category Notes

This field is common, but there are various date formats (e.g. month
only, day of the week). Dublin Core ‘date’ URI: <a href="http://dublincore.org/specifications/dublin-core/dcmi-terms/2012-06-14/?v=elements#date">dublincore.org/specifications/dublin-core/dcmi-terms/2012-06-14/?v=elements#date</a>. MODS:dateIssued URI: <a href="https://www.loc.gov/standards/mods/userguide/origininfo.html#dateissued">loc.gov/standards/mods/userguide/origininfo.html#dateissued</a>, which may be in textual or structured form.

## Individual Collection Notes

F2AL: Year and month only.

SBME: The separate fields for year, month and date build, so that “year”
contains year only, “month” contains year-month, and “day” contains
year-month-day.

SBMY: The separate fields for year, month and date build, so that “year”
contains year only, “month” contains year-month, and “day” contains
year-month-day.

## Instantiations

### Publication Date  

| B1GL  |  issue\\da  | DAT | January 03, 1822  |
| B2GL  |  issue\\da  | DAT | January 03, 1822  |
| B1GI  |  issue\\metadataInfo\\da\\composed  | DAT | January 2, 1798  |
| B2GI  |  issue\\metadataInfo\\da\\composed  | DAT | July 31, 1813  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\ dc:date  | DAT | 18/04/1945  |
| F2AL  |  pageOCRDATA\\metadata\\published  | DAT | 1881-11  |
| HNDM  |  $.publication.pagina.fecha  | DAT | ISODate(“1900-01-01T18:00:00.000Z”) |
| PPME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of the printed version”\]\\xmlData\\MODS:mods\\MODS:originInfo\\MODS:dateIssued | DAT | 1843-04-22  |
| PPME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of Issue”\]\\xmlData\\MODS:mods\\MODS:originInfo\\MODS:dateIssued  | DAT | 1843-04-22  |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:originInfo\[@eventType=“publication”\]\\mods:dateIssued  | DAT | 1934-05-10  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div\\mets:div\\mets:div\\mets:div\\mets:div@ORDERLABEL  | DAT | 1934-05-10  |
| SBMY  |  mets:mets\\mets:structMap\\mets:div\\mets:div\\mets:div\\mets:div\\mets:div@ORDERLABEL  | DAT | 1934-05-10  |
| TDAG  |  issue\\da\\composed  | DAT | July 14, 1812  |
| TRAP  |  article\\title\\date  | DAT | 1876-05-27  |
| TRME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:originInfo\\mods:dateIssued  | DAT | 19350706  |

### Printed Date  

| B1GL  |  issue\\printedDate  | DAT | January 03, 1822  |
| B1JI  |  BL\_newspaper\\BL\_page\\issue\_metadata\\printedDate | DAT | Monday, January 6, 1800 |
| B2GL  |  issue\\printedDate  | DAT | January 03, 1822  |

### Standardised Date of Publication  

| B1GL  |  issue\\pf  | DAT | 18220103  |
| B1GI  |  issue\\metadataInfo\\da\\searchableDateStart  | DAT | 17980102  |
| B2GL  |  issue\\pf  | DAT | 18220103  |
| B2GI  |  issue\\metadataInfo\\da\\searchableDateStart  | DAT | 18130731  |
| B1JI  |  BL\_newspaper\\BL\_page\\issue\_metadata\\normalisedDate  | DAT | 1800.01.06 |
| HNME  |  METS:mets\\METS:dmdSec\\METS:mdWrap\\METS:xmlData\\DC:date | DAT | 19240101  |
| TDAG  |  issue\\da\\searchableDateStart  | DAT | 18120714  |

### Day of the Week of Publication  

| B1GL  |  issue\\dw  | MCH | Thursday |
| B1GI  |  issue\\metadataInfo\\dw | MCH | Tuesday  |
| B2GL  |  issue\\dw  | MCH | Thursday |
| B2GI  |  issue\\metadataInfo\\dw | MCG | Friday  |

### Day of Publication  

| B1GI  |  issue\\metadataInfo\\da\\day  | DAT | 2  |
| B2GI  |  issue\\metadataInfo\\da\\day  | DAT | 31  |
| CADI  |  sn\\year\\month\\null\[day\]  | DAT | 4  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div\\mets:div\\mets:div\\mets:div@ORDERLABEL | DAT | 1934-05-10 |
| SBMY  |  mets:mets\\mets:structMap\\mets:div\\mets:div\\mets:div\\mets:div@ORDERLABEL  | DAT | 1934-05-10 |
| TDAG  |  issue\\da\\day  | DAT | 14  |

### Month of Publication  

| B1GI  |  issue\\metadataInfo\\da\\month  | DAT | January |
| B2GI  |  issue\\metadataInfo\\da\\month  | DAT | July  |
| CADI  |  sn\\year\\null\[month\]  | DAT | 8  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div\\mets:div\\mets:div@ORDERLABEL | DAT | 1934-05 |
| SBMY  |  mets:mets\\mets:structMap\\mets:div\\mets:div\\mets:div@ORDERLABEL  | DAT | 1934-05 |
| TDAG  |  issue\\da\\month  | DAT | July  |

### Year of Publication  

| B1GI  |  issue\\metadataInfo\\da\\year  | DAT | 1798 |
| B2GI  |  issue\\metadataInfo\\da\\year  | DAT | 1813 |
| CADI  |  sn\\null\[year\]  | DAT | 1915 |
| F1ME  |  mets\\dmdSec\\mdWrap\\xmlData\\MODS:mods\\MODS:originInfo\\MODS:dateIssued  | DAT | 1841 |
| PPDI  |  Newspaper Data\\Papers Past\\\\\[abbreviated newspaper title\]\\\[year\]  | DAT |  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div\\mets:div@ORDERLABEL | DAT | 1934 |
| SBMA  |  mets:mets\\mets:structMap\\mets:div\\mets:div@ORDERLABEL  | DAT | 1934 |
| SBMY  |  mets:mets\\mets:structMap\\mets:div\\mets:div@ORDERLABEL  | DAT | 1934 |
| TDAG  |  issue\\da\\year  | DAT | 1812 |
