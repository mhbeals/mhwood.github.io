---
layout: map
title: Newspaper Title
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/newspaper-title">View Glossary Entry</a></h4>

## Technical Definition

There are two kinds of newspaper title provided: first, the title as it
appears on that particular [**issue**](../issue-number); second, the title in a
normalised format. This may or may not be a version of the title as
printed but rather an amalgamation chosen by the cataloguer. It is
usually derived from the earliest available issue from that newspaper,
after which [**alternate newspaper titles**](../alternative-newspaper-title) will be recorded. 

## Category Notes

This field appears in all collections (though not all file types) except
Chronicling America, which only includes the newspaper title in the
[**issue**](../issue-number) data. Not all collections identify if the title is the printed
title or a normalised one. URI for MODS sub-element: https://www.loc.gov/standards/mods/userguide/titleinfo.html#title. URI for Dublin Core term: http://dublincore.org/specifications/dublin-core/dcmi-terms/2012-06-14/?v=terms#title. 

## Individual Collection Notes

TRAP: Also contains [**place of publication**](../place-of-publciation) and [**date range**](../date)
information. 

PPME: The title associated with the bibliographic metadata for the
article also contains the [**date**](..date).

## Instantiations** 

### Printed Title  

| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\title  | STR | The Aberdeen Journal  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\[@LABEL=“Bibliographic meta-data of the printed version”\]\\mets:xmlData\\mods:mods\\mods:titleInfo\\mods:title | STR | Hamburger Nachrichten |
| F1ME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of the printed version”\]\\xmlData\\MODS:mods\\titleInfo\\MODS:title  | STR | Suomi  |
| PPME  |  mets\\dmdSec\\mdWrap@LABEL=“Bibliographic meta-data of the printed version”\]\\xmlData\\MODS:mods\\MODS:titleInfo\\MODS:title  | STR | Daily Southern Cross  |
| SBMA  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:titleInfo\\mods:title  | STR | Baruther Heimatland  |
| SBMY  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mets:mods\\mods:relatedItem\[@type=original”\]\\mods:titleInfo\\mods:title  | STR | Baruther Heimatland  |

### Normalised Title  

| B1GL  |  issue\\citation\\titlegroup\\marcTitle  | STR | Berrow\&apos;s Worcester Journal  |
| B1GP  |  PubInfo\\PublicationTitle  | STR | Aberdeen Journal  |
| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\normalisedTitle  | STR | Aberdeen Journal  |
| B2GL  |  issue\\citation\\titlegroup\\marcTitle  | STR | Berrow\&apos;s Worcester Journal  |
| B2GP  |  PubInfo\\PublicationTitle  | STR | The York Herald  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\ srw\_dc:dcx\\dc:title | STR | Delftsche courant : nieuwsblad voor Delft en Delfland |
| TRAP  |  article\\title  | STR | The Queenslander (Brisbane, Qld. : 1866-1939)  |

### Unspecified  

| B1GL  |  issue\\jn  | STR | Berrow&apos;s Worcester Journal  |
| B2GL  |  issue\\jn  | STR | Berrow&apos;s Worcester Journal  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\[@LABEL=“Bibliographic meta-data of the issue”\]\\mets:xmlData\\mods:mods\\mods:titleInfo\\mods:title | STR | Hamburger Nachrichten  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\[@LABEL=“Bibliographic meta-data of article”\]\\mets:xmlData\\mods:mods\\mods:titleInfo\\mods:title  | STR | Hamburger Nachrichten  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\[@LABEL=“Bibliographic meta-data of table”\]\\mets:xmlData\\mods:mods\\mods:titleInfo\\mods:title  | STR | Hamburger Nachrichten  |
| EUME  |  METS:mets\\mets:structMap\[@LABEL=“Physical Structure” @TYPE=“PHYSICAL”\]\\mets:div@LABEL  | STR | Hamburger Nachrichten  |
| EUME  |  METS:mets\\mets:structMap\[@LABEL=“Logical Structure” @TYPE=“LOGICAL”\]\\mets:div\\mets:div\\mets:div\\mets:div\\mets:div@LABEL  | STR | Hamburger Nachrichten  |
| F1ME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of the electronic version”\]\\xmlData\\MODS:mods\\titleInfo\\MODS:title  | STR | Suomi  |
| F1ME  |  mets\\structMap\[@LABEL=“Physical Structure” @TYPE=“PHYSICAL”\]\\div@LABEL  | STR | Suomi  |
| F1ME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of Issue”\]\\xmlData\\MODS:mods\\MODS:titleInfo\\MODS:title  | STR | Suomi  |
| F2AL  |  pageOCRDATA\\metadata\\title  | STR | Kirkollinen kuukauslehti : uskonnollista lukemista perheille  |
| HNDM  |  $.publication.titulo  | STR | Actas de Cabildo  |
| HNME  |  METS:mets\\METS:dmdSec\\METS:mdWrap\\METS:xmlData\\DC:title  | STR | Historia de los Descubrimientos Antiguos y Modernos de la Nueva Espana |
| PPME  |  mets\\structMap\[@LABEL=“Physical Structure” @TYPE=“PHYSICAL”\]\\div@LABEL  | STR | Southern Cross;New Zealand Herald  |
| PPME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of article”\]\\xmlData\\MODS:mods\\MODS:titleInfo\\MODS:title  | STR | Southern Cross. Saturday, April 22.  |
| PPME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of the electronic version”\]\\xmlData\\MODS:mods\\MODS:titleInfo\\MODS:title  | STR | Daily Southern Cross  |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:relatedItem\\mods:relatedItem\\mods:titleInfo\\mods:title  | STR | Baruther Heimatland  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div@LABEL  | STR | Baruther Heimatland  |
| SBMY  |  mets:mets\\mets:structMap\\mets:div@LABEL  | STR | Baruther Heimatland  |
| SBMA  |  mets:mets\\mets:structMap\\mets:div@LABEL  | STR | Baruther Heimatland  |
| TRME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:relatedItem\\mods:titleInfo\\mods:title  | STR | mullewamail  |
