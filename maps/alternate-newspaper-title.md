---
layout: page
title: Alternate Newspaper Title
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/alternate-newspaper-title">View Glossary Entry</a></h4>

## Technical Definition

Provides an alternate title for the publication, where the title may
have changed during its run. Occasionally this is a minor change, such
as dropping the article, but this can also be a more radical restyling
of the publication. Standardised title information can be found in
[**newspaper title**](../newspaper-title). 

## Category Notes

This field appears most commonly in the adapted Dublin Core format. URI for MODS sub-element: https://www.loc.gov/standards/mods/userguide/titleinfo.html#title. This is the same sub-element type as for newspaper title. Dublin Core ‘alternative’ term URI: http://dublincore.org/specifications/dublin-core/dcmi-terms/2012-06-14/?v=terms#terms-alternative. Dublin Core ‘isVersionOf’ URI: http://www.dublincore.org/specifications/dublin-core/dcmi-terms/#terms-isVersionOf. 

## Individual Collection Notes

PPME: Multiple alternate titles are listed within the string, separated
by semi-colons

DEMP: The alternate title listed in dcterms:alternative can take one of
two forms: either the value starts with “Ook bekend onder de naam” (also
known as), or “Eerder verschenen onder de naam” (previously published
as). dcterms:isVersionOf is the same as “Ook bekend onder de naam”, but
in this case only the alternate newspaper title is listed, without the
leading text, giving a normalised title.

## Instantiations  

| B1GP  |  PubInfo\\VariantTitles\\Title  | STR | Aberdeen Weekly Journal  |
| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\changeToTitle\\name  | STR | Aberdeen Weekly Journal  |
| B2GP  |  PubInfo\\VariantTitles\\Title  | STR | The York Herald, and General Advertiser  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\ dcterms:alternative  | STR | Eerder verschenen onder de naam Delflandsche courant : nieuws- en advertentieblad |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\ dcterms:isVersionOf  | STR | Delflandsche courant : nieuws- en advertentieblad  |
| PPME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of the printed version”\]\\xmlData\\MODS:mods\\MODS:titleInfo\\MODS:title  | STR | Southern Cross;New Zealand Herald  |
| PPME  |  mets\\dmdSec\\mdWrap\[@LABEL=“Bibliographic meta-data of Issue”\]\\xmlData\\MODS:mods\\MODS:relatedItem\\MODS:titleInfo\\MODS:title | STR | Southern Cross; New Zealand Herald  |
