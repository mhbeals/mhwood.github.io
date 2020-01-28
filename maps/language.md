---
layout: map
title: Language
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/language">View Glossary Entry</a></h4>

## Technical Definition

Specifies the language of the textual unit, often, but not always, using
the ISO language code. This can refer to the language of the newspaper,
the article text, or the specific block of text.

## Category Notes

This field appears in all databases. Dublin Core language URI: http://purl.org/dc/terms/language. languageTerm URI (MODS), including xml:lang sub-element: https://www.loc.gov/standards/mods/userguide/language.html#languageterm. In ALTO, the language should be recorded at the highest level possible.

## Individual Collection Notes

B1GI: issue\\dcLanguage specifies the language of the [**issue**](../issue-number) (given
in abbreviated form), issue\\metadataInfo\\language specifies the
language of the [**newspaper title**](../newspaper-title), issue\\metadataInfo\\language@ocr
specifies the [**OCR**](../ocr) language of the newspaper, and
issue\\page\\article\\ocrLanguage specifies the OCR language of the
article.

B1GP: The field refers to the language of the [**alternate title for this
newspaper**](../alternative-newspaper-title).

B2GL: Specifies the language of the [**issue**](../issue-number) (given in abbreviated
form)

B2GI: issue\\metadataInfo\\language specifies the language of the
[**newspaper title**](../newspaper-title), issue\\metadataInfo\\language@ocr specifies the OCR
language of the newspaper, issue\\page\\article\\ocrLanguage specifies
the OCR language of the article.

B2GP: The field refers to the language of the  [**alternate title for this
newspaper**](../alternative-newspaper-title).

CAAL: Declares the language of the textblock. On a practical level, this
declaration applies to the contents of the @content attribute on the
\<STRING\> element.

DEMP: Provides a UID for the language.

METS:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods\\language\\languageTerm
refers to the language of the printed version. All instantiations of
@xml:lang provide an ISO code for the language.

F1ME: Fields give an ISO code for the language.

HNDM: Language of the country of publication. See collection
“catLanguage” to see options. Idioma del país de la Publicación. Ver
colección “catIdioma” para conocer las opciones.

PPME: Fields give an ISO code for the language.

TDAG: issue\\metadatainfo\\language provides the language for the
[**issue**](../issue-number), issue\\metadatainfo\\language@ocr specifies the OCR language
for the issue, and issue\\page\\article\\ocrLanguage provides the OCR
language for the article.

TRME: Fields give an ISO code for the language.

## Instantiations

### Language of the Text Block  

| CAAL  |  alto\\Layout\\Page\\PrintSpace\\TextBlock@language | UID | en |

### Language of the Article  

| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\[@LABEL=“Bibliographic meta-data of article”\]\\mets:xmlData\\mods:mods\\mods:titleInfo@xml:lang | UID | de  |
| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of article”\]\\xmlData\\MODS:mods\\MODS:titleInfo@xml:lang  | UID | en  |
| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of article”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm  | UID | en  |
| TDAG  |  issue\\page\\article\\ocrLanguage  | STR | English |

### Language of the Section  

| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of section”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm | UID | en |

### Language of the Page  

| F2AL  |  pageOCRDATA\\metadata\\language | STR | fin  |
| HNDM  |  $.publication.pagina.idioma  | MCH | Español |

### Language of the Issue  

| B1GL  |  issue\\dcLanguage  | STR | eng  |
| B1GI  |  issue\\metadataInfo\\language  | STR | English  |
| B1GI  |  issue\\metadataInfo\\language@ocr  | STR | English  |
| B1GI  |  issue\\page\\article\\ocrLanguage  | STR | English  |
| B2GL  |  issue\\dcLanguage  | STR | eng  |
| B2GI  |  issue\\metadataInfo\\language  | STR | English  |
| B2GI  |  issue\\metadataInfo\\language@ocr  | STR | English  |
| B2GI  |  issue\\page\\article\\ocrLanguage  | STR | English  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dc:language@ xsi:type  | STR | dcterms:ISO639-1 |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\[@LABEL=“Bibliographic meta-data of the issue”\]\\mets:xmlData\\mods:mods\\mods:titleInfo@xml:lang  | UID | de  |
| F1ME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of the printed version”\]\\xmlData\\MODS:mods\\MODS:titleInfo@xml:lang  | UID | sv  |
| F1ME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of the printed version”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm  | UID | sv  |
| F1ME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of the electronic version”\]\\xmlData\\MODS:mods\\titleInfo@xml:lang  | UID | sv  |
| F1ME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of the electronic version”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm | UID | sv  |
| F1ME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of Issue”\]\\xmlData\\MODS:mods\\MODS:titleInfo@xml:lang  | UID | sv  |
| HNME  |  METS:mets\\METS:dmdSec\\METS:mdWrap\\METS:xmlData\\DC:language  | STR | SPANISH  |
| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of Issue”\]\\xmlData\\MODS:mods\\MODS:titleInfo@xml:lang  | UID | en  |
| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of Issue”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm  | UID | en  |
| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of the printed version”\]\\xmlData\\MODS:mods\\MODS:titleInfo@xml:lang  | UID | en  |
| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of the printed version”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm  | UID | en  |
| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of the electronic version”\]\\xmlData\\MODS:mods\\MODS:titleInfo@xml:lang  | UID | en  |
| PPME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of the electronic version”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm | UID | en  |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:language\\mods:languageTerm  | UID | ger  |
| SBMA  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:language\\mods:languageTerm  | UID | ger  |
| TDAG  |  issue\\metadatainfo\\language  | STR | English  |
| TDAG  |  issue\\metadatainfo\\language@ocr  | STR | English  |

### Language of the Publication as a Whole  

| B1GP  |  PubInfo\\VariantTitles\\language  | STR | English |
| B2GP  |  PubInfo\\VariantTitles\\Language  | STR | English |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dc:language  | UID | n1  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods\\language\\languageTerm  | STR | German  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\[@LABEL=“Bibliographic meta-data of table”\]\\mets:xmlData\\mods:mods\\mods:titleInfo@xml:lang | UID | de  |
| F1ME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of Issue”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm  | UID | sv  |
| F1ME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of list”\]\\xmlData\\MODS:mods\\MODS:titleInfo@xml:lang  | UID | sv  |
| F1ME  |  mets\\dmdSec\\mdWrap\[LABEL=“Bibliographic meta-data of list”\]\\xmlData\\MODS:mods\\MODS:language\\MODS:languageTerm  | UID | fi  |
| HNDM  |  $.publication.idioma  | MCH | Español |
| TRME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:language\\mods:languageTerm  | UID | en  |
