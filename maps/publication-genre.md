---
layout: map
title: Publication Genre
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/publication-genre">View Glossary Entry</a></h4>

## Technical Definition

Specifies the genre of the publication at the broadest level,
i.e. whether a newspaper, periodical or magazine. The British Library
Newspaper Programme used the following ISO standard definition of a
newspaper to decide which titles formerly held at the Newspaper Library
were newspapers: “a serial publication which contains news of current
events of special or general interest. The individual parts are listed
chronologically or numerically and usually appear at least once a week.
Newspapers usually appear without a cover, with a masthead, and are
normally larger than 297mm x 420mm in size”. Newspapers usually appear
without a cover, with a masthead, and are normally larger than 297mm x
420mm in size” \[Sagendorf and Moore, 7\].

For Delpher, a newspaper must meet the following criteria: it must be a
product from the printing press, in multiple identical copies (therefore
not handwritten); it must be published [**periodically**](../publication-frequency) (in the
seventeenth century that normally starts at once a week, but later more
frequently to even twice a day in the early twentieth century, and on a
fixed day of the week); its content has to have news and has to be for a
wide audience; and it must be publicly available (“Selection Criteria”).

The Australian Newspaper Plan libraries have adopted the following
definition of a newspaper, similarly drawn from the ISO standard
definition but with several expansions: “A newspaper is a serial
publication which contains news on current events of special or general
interest. The individual parts are listed chronologically or numerically
and appear frequently usually at least once a week but sometimes
fortnightly or monthly. Traditionally newspapers are printed on
newsprint paper, usually appear without a cover, folded rather than
bound together, with a masthead, and are normally larger than 297 mm
x 420 mm in size. They may include supplements such as colour magazines,
or other inserts for special features or events.”

## Category Notes

This field is common in METS files and the British Library adapted
Dublin Core files. In METS, it is an optional attribute rather than an
element. URI: <a href="https://www.loc.gov/standards/mets/docs/mets.v1-5.html#metsType">loc.gov/standards/mets/docs/mets.v1-5.html#metsType</a>. In MODS, it is a top-level element: <a href="">loc.gov/standards/mods/userguide/genre.html</a>. For the suggested MARC genres, see: <a href="https://www.loc.gov/standards/valuelist/marcgt.html">loc.gov/standards/valuelist/marcgt.html</a>.

## Individual Collection Notes

B1GP: In this collection, the genre specified refers to alternate title
for this newspaper.

B2GP: In this collection, the genre specified refers to alternate title
for this newspaper.

HNDM: The multiple-choice options are periodico and monografia.

TRME: The same field name is used to describe both the file and also
related items.

## Instantiations  

| B1GL  |  issue\\citation\\typeOfPublication\\  | MCH | Newspaper  |
| B1GP  |  PubInfo\\VariantTitles\\Format  | MCH | Newspaper  |
| B1JI  |  BL\_newspaper\\BL\_page\\title\_metadata\\typeofPublication  | MCH | Newspaper  |
| B2GL  |  issue\\citation\\typeOfPublication  | MCH | Newspaper  |
| B2GP  |  PubInfo\\VariantTitles\\Format  | MCH | Newspaper  |
| EUME  |  METS:mets@TYPE  | MCH | Newspaper  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods\\mods:genre  | STR | newspaper issue |
| EUME  |  METS:mets\\mets:structMap\[@LABEL=“Physical Structure” @TYPE=“PHYSICAL”\]\\mets:div@TYPE  | MCH | Newspaper  |
| EUME  |  METS:mets\\mets:structMap\[@LABEL=“Logical Structure” @TYPE=“LOGICAL”\]\\mets:div@TYPE  | MCH | Newspaper  |
| F2AL  |  pageOCRDATA\\metadata\\contentType  | STR | serial  |
| HNDM  |  $.publication.tipoPublicacion  | MCH | Monografía  |
| HNDM  |  $.publication.pagina.tipoPublicacion  | MCH | Monografía  |
| HNME  |  METS:mets\\METS:dmdSec\\METS:mdWrap\\METS:xmlData\\DC:category  | MCH | Monografias  |
| PPME  |  mets@TYPE  | MCH | Newspaper  |
| PPME  |  mets\\structMap\[@LABEL=“Logical Structure” @TYPE=“LOGICAL”\]\\div@TYPE  | MCH | Newspaper  |
| PPME  |  mets\\structMap\\div@TYPE  | MCH | Newspaper  |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:classification  | MCH | Zeitungen  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div@TYPE  | MCH | newspaper  |
| SBMA  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:classification  | MCH | Zeitungen  |
| SBMA  |  mets:mets\\mets:structMap\\mets:div@TYPE  | MCH | newspaper  |
| SBMY  |  mets:mets\\mets:structMap\\mets:div@TYPE  | MCH | newspaper  |
| TDAG  |  issue@contentType  | MCH | Newspaper  |
| TRME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:genre  | STR | newspaper issue |
| TRME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:relatedItem\\mods:genre | MCH | newspaper  |
