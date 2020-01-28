---
layout: page
title: Publication Date Range
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/publication-date-range">View Glossary Entry</a></h4>

## Technical Definition

Provides the date range, in either years or full dates, of the
[**publication**](../newspaper-title). It does so without [**date**](../date) or other restrictions and
should be considered to refer to the newspaper as defined by ontological
subcategory normalised title. There are three variants, the dates
included in the collection (collection range), those that to our
knowledge existed (full range), and all the individual days, months and
years of publication.

Newspaper start date and end date provide the full ISO date
for the publication’s first and last [**issue**](../issue-number). Instantiations are
divided into container elements Instantiations are divided into
container elements, which hold no specific data, and attributes or
specific elements, which hold the year, month and day separately.

## Category Notes

These fields are uncommon; more usually, only the date for the specific
issue is given. Start and end dates only appear in B1JI. URI for Dublin Core property ‘issued’: http://dublincore.org/specifications/dublin-core/dcmi-terms/2012-06-14/?v=terms#issued.

## Individual Collection Notes

B1GL: Several date ranges can be listed, separated by a semicolon.
Refers **to the digitised holdings, rather than the newspaper’s actual
run**.

B1JI: Several date ranges can be listed, separated by a semicolon. The
start and end date refer to a specific **alternate title for this
newspaper and only to the digitised holdings, rather than the
newspaper’s actual run**.

DEMP: The ddd:yearsDigitized field refers only to years of publication
held in the “Databank Digitale Dagbladen” collection.

HNDM: All the individual days, months and years of publication are
listed.

## Instantiations

### Full Publication Date Range  

| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\datesOfPublication  | DAR | 1 Jan 1800 - 23 Aug 1876; 30 Aug 1876 - 31 Dec 1900  |
| B1GL  |  issue\\citation\\datesOfPublication  | DAR | 1 Jan 1800 - 27 Aug 1859; 29 Aug 1859 - 21 Feb 1860; 22 Feb 1860 - 20 Apr 1867 |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\ddd:yearsDigitized  | DAR | 1940-1945  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcterms:issued  | DAR | 1856-2002  |
| HNDM  |  $.publication.fecha  | DAR | “fecha”:\[{“aa”:”1900”,”mes”:\[ {“mm”:”01”,”dia”:\[“01”\]}\]}\]  |
| SBMA  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:note\[@type=“date\\sequential designation”\] | STR | 1932,4(14.Nov.) - 1936,39(26.Okt.); 1939,45(27.Jan.); mehr nicht digitalisiert |

### Publication Start Date

### Container  

| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\startDate | NUL |  |

### Day  

| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\startDate@day | DAT | 30 |

### Month 

| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\startDate@month | DAT | 8 |

### Year  

| B1JI:BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\startDate@year | DAT | 1876 |

### Combined  

| SBMA  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:originInfo\[@eventType=“publication”\]\\mods:dateIssued\[@point=“start”\] | DAT | 1930-01-01 |

### Publication End Date

### Container  

| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\endDate | NUL |  |

### Day  

| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\endDate@day | DAT | 30 |

### Month  

| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\endDate@month | DAT | 8 |

### Year  

| B1JI:BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\endDate@year | DAT | 1876 |

### Combined  

| SBMA  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:originInfo\[@eventType=“publication”\]\\mods:dateIssued\[@point=“end”\] | DAT | 1945-12-31 |
