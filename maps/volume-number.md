---
layout: map
title: Volume Number
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/volume-number">View Glossary Entry</a></h4>

## Technical Definition

Provides the volume information, either a numerical volume number
relative to the [**newspaper title**](../newspaper-title) or a [**unique identifier**](../id). One
volume comprises many [**issues**](../issue-number).

## Category Notes

This field is relatively uncommon. In F1ME and PPME, volume information
is located within a string including [**newspaper title**](../newspaper-title) and [**date**](../date)
information.  MODS:number URI: https://www.loc.gov/standards/mods/userguide/part.html#number. METS label URI: https://www.loc.gov/standards/mets/docs/mets.v1-5.html#div. 

## Individual Collection Notes

DEMP: Refers to the volume number as printed on the original.

F1ME: The volume information provided includes the [**newspaper title**](../newspaper-title)
and the [**year**](../date) of publication.

PPME: The volume information provided includes the [**newspaper title**](../newspaper-title)
and the [**date**](../date) of publication as well as a numerical volume number.

## Instantiations

### Relative  

| B1GL  |  issue\\volNum  | NUM | 1  |
| B1JI  |  BL\_newspaper\\BL\_page\\issue\_metadata\\volumeNumber  | NUM | 1  |
| CAME  |  mets\\dmdSec\\mdWrap\\xmlData\\mods:mods\\mods:relatedItem\\mods:Identifier\\mods:part\\mods:detail\[@type=“volume”\]\\mods:number | NUM | 18  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcx:volume  | NUM | 10  |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:part\\mods:detail\[@type=“volume”\]\\mods:number  | STR | Vol. 3 |
| TRME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:relatedItem\\mods:part\\mods:detail@mods:number  | NUM | 41  |

### Unique Identifier  

| F1ME  |  mets\\structMap\\div\\div\[@TYPE=“VOLUME”\]@LABEL | STR | Suomi no. 1 1841  |
| PPME  |  mets\\structMap\\div\\div\[@TYPE=“VOLUME”\]@LABEL | STR | Daily Southern Cross no. I 1843-04-22 |
