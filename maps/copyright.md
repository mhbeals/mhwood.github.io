---
layout: page
title: Copyright
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/copyright">View Glossary Entry</a></h4>

## Technical Definition

Specifies the copyright holder of the **issue**. **Access conditions**
provides additional information about the status of a physical object,
i.e. any restrictions on access.

## Category Notes

The “copyright” field appears in the adapted Dublin Core file
structures, always as a string. Access condition information is only
included in the SBB collections. One field gives a string that describes
its status, and a second field provides a persistent uniform resource
locator (PURL) link to explain the given status.

## Individual Collection Notes

DEMP: There are different fields for the copyright holder for the
**newspaper title**
(didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\
dc:rights) and the digital record
(DEMP::didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcx:recordRights).

## Instantiations

### Copyright Holder  

| B1GI::issue\\metadataInfo\\sourceLibrary\\copyrightStatement  | STR | Copyright © The British Library Board  |
| B1GL::issue\\cp  | STR | Copyright &\#x00A9; The British Library Board  |
| B2GL::issue\\cp  | STR | Copyright &\#x00A9; The British Library Board  |
| B2GI::issue\\metadataInfo\\sourceLibrary\\copyrightStatement  | STR | Copyright © The British Library Board  |
| DEMP::didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\ dc:rights  | STR | AD NieuwsMedia B.V.  |
| DEMP::didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcx:recordRights  | STR | Koninklijke Bibliotheek Den Haag  |
| SBME::mets:mets\\mets:amdSec\\mets:rightsMD\\mets:mdWrap\\mets:xmlData\\dv:rights\\dv:owner | STR | Staatsbibliothek zu Berlin - Preußischer Kulturbesitz |
| SBMA::mets:mets\\mets:amdSec\\mets:rightsMD\\mets:mdWrap\\mets:xmlData\\dv:rights\\dv:owner | STR | Staatsbibliothek zu Berlin - Preußischer Kulturbesitz |
| SBMY::mets:mets\\mets:amdSec\\mets:rightsMD\\mets:mdWrap\\mets:xmlData\\dv:rights\\dv:owner | STR | Staatsbibliothek zu Berlin - Preußischer Kulturbesitz |
| TDAG::issue\\sourceLibrary\\copyrightStatement  | STR | &\#x00A9; Times Newspapers Limited  |

### Access Conditions  

| SBME::mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:accessCondition  | STR | open access  |
| SBME::mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:accessCondition@xlink:href  | URL | http://purl.org/coar/access\_right/c\_abf2 |
| SBMA::mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:accessCondition@displayLabel | STR | open access  |
| SBMA::mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:accessCondition@xlink:href  | URL | http://purl.org/coar/access\_right/c\_abf2 |
| SBMY::mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mets:mods\\mods:accessCondition  | STR | open access  |
| SBMY::mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mets:mods\\mods:accessCondition@xlink:href  | URL | http://purl.org/coar/access\_right/c\_abf2 |
