---
layout: map
title: Edition
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/edition">View Glossary Entry</a></h4>

## Technical Definition

Provides edition information for the [**issue**](../issue-number), including morning,
afternoon, evening, day, special and [**supplemental**](../supplement-title). In SBMA and SBME,
it also specifies that it is an electronic edition of the issue.

## Category Notes

This field is uncommon and can include a string with the full edition
title, a number, a multiple-choice option, or a unique identifier. MODS:number URI: https://www.loc.gov/standards/mods/userguide/part.html#number. Dublin Core ‘temporal’ URI: http://dublincore.org/specifications/dublin-core/dcmi-terms/2012-06-14/?v=terms#temporal.

## Individual Collection Notes

DEMP: The multiple-choice options are Ochtend (morning edition), Middag
(afternoon edition), Avond (evening edition) and Dag (daily edition).

TRAP: If this article appeared in a special newspaper/periodical
edition, the name of that edition is included here. In the Trove web
interface, this is shown on the page view. e.g.
http://trove.nla.gov.au/ndp/del/page/4298413.

## Instantiations  

| CADI  |  sn\\year\\month\\day\\null\[edition\]  | STR | ed-1  |
| CAME  |  mets\\dmdSec\\mdWrap\\xmlData\\mods:mods\\mods:relatedItem\\mods:Identifier\\mods:part\\mods:detail\\mods:number  | NUM | 1  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcterms:temporal  | MCH | Dag  |
| SBMA  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:originInfo\[@eventType=“digitization”\]\\mods:edition | STR | \[Electronic ed.\]  |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:originInfo\[@eventType=“digitization”\]\\mods:edition | STR | \[Electronic ed.\]  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div\\mets:div\\mets:div\\mets:div\\mets:div@LABEL  | STR | Freundschaftsausgabe  |
| SBMY  |  mets:mets\\mets:structMap\\mets:div\\mets:div\\mets:div\\mets:div\\mets:div@LABEL  | STR | Freundschaftsausgabe  |
| TRAP  |  article\\title\\edition  | STR | 2, SPECIAL EDITION TO THE QUEANBEYAN AGE |

