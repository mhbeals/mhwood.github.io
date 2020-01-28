---
layout: page
title: ID
subtitle:  
use-site-title: false
---

## Technical Definition

Provides a unique ID for the component of the image.

## Usage Notes

This can be a URL, a <a href="https://www.digitisednewspapers.net/maps/filename/">**filename**</a>, a numerical string, or a string
incorporating an <a href="https://www.digitisednewspapers.net/maps/abbreviated-newspaper-title/">**abbreviated title**</a>.  
  
  “A string of characters used to identify (or name) some element of a program. The kind of element that may be named depends on the programming language; it may be a variable, a data structure, a procedure, a statement, a higher-level unit, or the program itself.” \[Butterfield, Ngondi and Kerr, 'identifier'\]

## Category Notes

These field are very common and used for linking individual newspapers,
issues and articles as well as style information.

## Individual Collection Notes

SBMY: There are two newspaper URLs, one referring to the catalogue page
of the SBB itself and one referring to the catalogue page of the ZEFYS.

## Instantiations

### Collection  

| B1GI::issue\\metadataInfo\\dviCollectionID | UID | BNCNC0001 |  
| B2GI::issue\\metadataInfo\\dviCollectionID | UID | BNCNC0002 |  

### Newspaper  

| B1GI::issue\\metadataInfo\\assetID  | UID | 3405609147  |  
| B1GI::issue\\page\\assetID  | UID | 3305609147  |  
| B1GI::issue\\page\\article\\assetID  | UID | 3305609147  |  
| B1GI::issue\\metadataInfo\\newspaperID  | UID | BNCN0001  |  
| B2GI::issue\\metadataInfo\\newspaperID  | UID | NCBL0127  |  
| B2GI::issue\\metadataInfo\\assetID  | UID | 3411020871  |  
| B2GI::issue\\page\\assetID  | UID | 3500902290  |  
| B2GI::issue\\page\\article\\assetID  | UID | 3211020871  |  
| CADI::\_ROOT\\null\[sn\]  | UID | sn85032923  |  
| DEMP::didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dc:identifier  | URL | http://resolver.kb.nl/resolve?urn=ddd:010419500:mpeg21  |  
| HNDM::$.publication.\_id  | STR | ObjectId(“558075bd7d1e63c9fea1a0eb”)  |  
| SBMY::mets:mets\\mets:amdSec\\mets:digitprovMD\\mets:mdWrap\\mets:xmlData\\dv:links\\dv:reference  | URL | http://www.stabikat.de/DB=1/PPN?PPN=791048292  |  
| SBMY::mets:mets\\mets:amdSec\\mets:digitprovMD\\mets:mdWrap\\mets:xmlData\\dv:links\\dv:presentation  | URL | http://zefys.staatsbibliothek-berlin.de/list/title/zdb/27450028/ |  
| TDAG::issue\\metadatainfo\\newspaperID  | UID | TDAO0001  |  
| TRAP::article\\title@title@id  | UID | 42  |  
| TRME::mets:mets\\mets:amdSec\\mets:techMD\\mets:mdWrap\\mets:xmlData\\premis:object\\premis:objectIdentifier\\premis:objectIdentifierValue | FIN | nla.news-issn22083111-s75000-b.tif  |  

### Newspaper (Alternate Title)  

| B1GP::PubInfo\\VariantTitles\\NewspaperID | UID | BNCN0001 |  
| B2GP::PubInfo\\VariantTitles\\NewspaperID | UID | NCBL0126 |  

### Article (Unique/Database)  

| B1GI::issue\\page\\article\\id  | UID | WO1\_ANJO\_1798\_01\_02-0001-001 |  
| B1GL::issue\\article\\id  | UID | WOJL-1822-01-03-0002-003  |  
| B1GT::articles\\artInfo@id  | UID | WO1\_ANJO\_1798\_01\_02-0001-001 |  
| B2GL::issue\\article\\id  | UID | WOJL-1822-01-03-0002-003  |  
| B2GT::articles\\artInfo@id  | UID | YOHD-1813-07-31-0002-003  |  
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Item@dc:identifier  | UID | ddd:010069811:mpeg21:a0001  |  
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Item@ddd:article\_id  | UID | ddd:010419500:mpeg21:a0001  |  
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcx:recordIdentifier | UID | ddd:010069811:mpeg21:a0001  |  
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Item@ddd:article\_id  | UID | ddd:010419500:mpeg21:a0001  |  
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Item\\didl:Component\\srw\_dc:dcx\\dcx:recordIdentifier  | UID | ddd:010419500:mpeg21:a0001  |  
| TDAG::issue\\page\\article\\assetID  | UID | cs17301582  |  
| TDAG::issue\\page\\article\\id  | UID | 0FFO-1785-FEB14-001-004  |  
| TRAP::article@article@id  | UID | 18341291  |  

### Article (URL)  

| B1GT::articles\\artInfo\\ProductLink  | URL | http://gdc.galegroup.com/gdc/artemis/NewspapersDetailsPage/NewspapersDetailsWindow?prodId=BNCN\&amp;windowstate=normal\&amp;mode=view\&amp;displayGroupName=DVI-Newspapers\&amp;p=GDCS\&amp;action=e\&amp;documentId=GALE%7CBA3205609147 |  
| B2GT::articles\\artInfo\\ProductLink  | URL | http://gdc.galegroup.com/gdc/artemis/NewspapersDetailsPage/NewspapersDetailsWindow?prodId=BNCN\&amp;windowstate=normal\&amp;mode=view\&amp;displayGroupName=DVI-Newspapers\&amp;p=GDCS\&amp;action=e\&amp;documentId=GALE%7CR3211020873  |  
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Item\\didl:Component\\srw\_dc:dcx\\dc:identifier | URL | http://resolver.kb.nl/resolve?urn=ddd:010419500:mpeg21:a0001  |  
| SBME::mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div@CONTENTIDS  | URL | http://resolver.staatsbibliothek-berlin.de/SNP27779154-00000000-0-0-0-0  |  
| TRAP::article\\identifier  | URL | http://nla.gov.au/nla.news-article18341291  |  
| TRAP::article\\troveUrl  | URL | http://trove.nla.gov.au/ndp/del/article/18342701  |  

### Article (Relative/Issue)  

| EUME::METS:mets\\mets:structMap\[@LABEL=“Logical Structure”\]\\mets:div\\mets:div\\mets:div\\mets:div\\mets:div\[@TYPE=“ARTICLE”\]@ID | UID | DIVL7  |  
| EUME::METS:mets\\mets:dmdSec@ID  | UID | MODSMD\_ARTICLE1  |  
| EUME::METS:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:titleInfo@ID  | UID | MODSMD\_ARTICLE1\_TI1 |  
| PPME::mets\\structMap\\div\\div\\div@DMDID  | UID | MODSMD\_ARTICLE1  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock@ID  | UID | ART1  |  
| TRME::mets:mets\\mets:structMap\[@TYPE=“logical”\]\\mets:div\\mets:div@DMDID  | UID | modsarticle1  |  

### Article Zone ID  

Provides an ID for the article, as zoned on the image. These fields are
highly inconsistent and include unique IDs, across the database,
relative IDs within the issue, and URLs to the web-accessible version of
the image.  

| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Component\\didl:Component@dc:identifier  | UID | ddd:010419500:mpeg21:p001:a0001:zoning |  
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Item@dc:identifier  | UID | ddd:010419500:mpeg21:p001:a0001  |  
| PPAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock@ID  | UID | P1\_CB00001  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock@ID  | UID | ZONE1-1  |  
| TRME::mets:mets\\mets:structMap\\mets:div\\mets:div\\mets:div@ID  | UID | divarticle1-1  |  
| TRME::mets:mets\\mets:structMap\\mets:div\\mets:div\\mets:div\\mets:fptr\\mets:area@FILEID | FIN | nla.news-issn22083111-s75003-b.tif  |  
| TRME::mets:mets\\mets:structMap\\mets:div\\mets:div@ID  | UID | artzone1-1  |  
| TRME::mets:mets\\mets:structMap\\mets:div\\mets:div\\mets:fptr\\mets:area@FILEID  | FIN | nla.news-issn22083111-s75003-b.tif  |  
| TRME::mets:mets\\mets:structMap\\mets:div\\mets:div\\mets:fptr\\mets:area@FILEID  | FIN | nla.news-issn22083111-s75003-b.xml  |  

### Clipped Article Image (Unique)  

Provides a unique identifier for the article, as segmented on a single
page. These are unique to each segment of an article spanning multiple
pages.  

| B1GL::issue\\article\\ci  | UID | WOJL-1822-01-03-0002-003-001 |  
| B2GL::issue\\article\\ci  | UID | WOJL-1822-01-03-0002-003-001 |  
| TDAG::issue\\page\\article\\ci | UID | 0FFO-1812-JUL14-001-001-001  |  

### Clipped Article Image (Relative)
  
Provides a relative identifier for the article, as segmented on a single
page. These are sequential to each segment of an article.  

| B1GL::issue\\article\\ci\\clip  | NUM | 1 |  
| -- | -- | - |  
| B1GL::issue\\article\\text\\text.cr\\pg@clipref  | NUM | 1 |  
| B1GI::issue\\page\\article\\il@clipref  | NUM | 1 |  
| B2GL::issue\\article\\ci\\clip  | NUM | 1 |  
| B2GL::issue\\article\\text\\text.title\\pg\\clipref  | NUM | 1 |  
| TDAG::issue\\page\\article\\text\\text.cr\\pg@clipref  | NUM | 1 |  
| TDAG::issue\\page\\article\\text\\text.title\\pg@clipref | NUM | 1 |  

### Text or Paragraph Style

#### Individual Collection Notes

The contents of @STYLEREFS declare the Text or Paragraph style of its
parent element via linking. The value of this @STYLEREFS attribute
matches the value of the @ID attribute on the \<TextStyle\> or
\<ParagraphStyle\> element (both children of the \<Styles\> element.  

| CAAL::alto\\Styles\\TextStyle@ID  | UID | TS\_10.0  |  
| CAAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@STYLEREFS  | UID | TS\_10.0  |  
| DEAL::alto\\Styles\\TextStyle@ID  | UID | TXT\_0  |  
| DEAL::alto\\Layout\\Page\\PrintSpace\\TextBlock@STYLEREFS  | UID | TXT\_0 PAR\_RIGHT  |  
| EUAL::alto\\Styles\\TextStyle@ID  | UID | TXT\_0  |  
| EUAL::alto\\Layout\\Page\\PrintSpace\\TextBlock@STYLEREFS  | UID | TXT\_0 PAR\_CENTER |  
| EUAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@STYLEREFS  | UID | TXT\_2  |  
| F1AL::alto\\Style\\TextStyle@ID  | UID | TXT\_0  |  
| F1AL::alto\\Layout\\Page\\PrintSpace\\TextBlock@STYLEREFS  | UID | TXT\_0 PAR\_LEFT  |  
| F1AL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@STYLEREFS  | UID | TXT\_1  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Styles\\TextStyle@ID  | UID | TXT\_0  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin\\TextBlock@STYLEREFS  | UID | TXT\_0 PAR\_CENTER |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\PrintSpace\\TextBlock@STYLEREFS | UID | TXT\_1 PAR\_Block  |  
| PPAL::alto\\TextStyle@FONTFAMILY  | UID | TXT\_0  |  
| PPAL::alto\\Layout\\Page\\PrintSpace\\TextBlock@STYLEREFS  | UID | TXT\_0 PAR\_CENTER |  
| TRAL::alto\\Styles\\TextStyle@ID  | UID | TS7.7  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\TextBlock@STYLEREFS  | UID | PAR1  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock@STYLEREFS  | UID | PAR1  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\TextBlock\\TextLine@STYLEREFS  | UID | TS.10.2  |  

### Print Space  

| CAAL::alto\\Layout\\Page\\PrintSpace@ID  | UID | PS.0  |  
| DEAL::alto\\Layout\\Page\\PrintSpace@ID  | UID | P1\_PS00001  |  
| EUAL::alto\\Layout\\Page\\PrintSpace@ID  | UID | P1\_PS00001  |  
| F1AL::alto\\Layout\\Page\\PrintSpace@ID  | UID | P1\_PS00001  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\PrintSpace@ID | UID | P12\_PS00001 |  
| PPAL::alto\\Layout\\Page\\PrintSpace@ID  | UID | P1\_PS00001  |  
| TRAL::alto\\Layout\\Page\\PrintSpace@ID  | UID | SPACE1  |  

### Text Block  

| CAAL::alto\\Layout\\Page\\PrintSpace\\TextBlock@ID  | UID | TB.0195.1  |  
| DEAL::alto\\Layout\\Page\\PrintSpace\\TextBlock@ID  | UID | P1\_TB00001  |  
| EUAL::alto\\Layout\\Page\\PrintSpace\\TextBlock@ID  | UID | P1\_TB00001  |  
| F1AL::alto\\Layout\\Page\\PrintSpace\\TextBlock@ID  | UID | P1\_TB00001  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin\\TextBlock@ID  | UID | P12\_TB00001 |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\PrintSpace\\TextBlock@ID | UID | P12\_TB00002 |  
| PPAL::alto\\Layout\\Page\\PrintSpace\\TextBlock@ID  | UID | P1\_TB00001  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\TextBlock\\@ID  | UID | BLOCK1  |  

### Text Line  

| CAAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine@ID  | UID | TB.0195.1\_0 |  
| DEAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine@ID  | UID | P1\_TL00001  |  
| EUAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine@ID  | UID | P1\_TL00001  |  
| F1AL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine@ID  | UID | P1\_TL00001  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin\\TextBlock\\TextLine@ID  | UID | P12\_TL00001 |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\PrintSpace\\TextBlock\\TextLine@ID | UID | P12\_TL00002 |  
| PPAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine@ID  | UID | P1\_TL00001  |  
| SBAT::PcGts\\Page\\TextRegion\\Textline@id  | UID | l1  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\TextBlock\\TextLine@ID  | UID | LINE1  |  

### String

| CAAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@ID  | UID | TB.0195.1\_0\_0 |  
| DEAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@ID  | UID | P1\_ST00001  |  
| EUAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@ID  | UID | P1\_ST00001  |  
| F1AL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@ID  | UID | P1\_ST00001  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin\\TextBlock\\TextLine\\String@ID  | UID | P12\_ST00001  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\PrintSpace\\TextBlock\\TextLine\\String@ID | UID | P12\_ST00002  |  
| PPAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@ID  | UID | P1\_ST00001  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\TextBlock\\TextLine\\String@ID  | UID | S1  |  

### Word

| SBAT::PcGts\\Page\\TextRegion\\Textline\\Word@id | UID | w2 |  

### White Space  

| DEAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\SP@ID  | UID | P1\_SP00002  |  
| EUAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\SP@ID  | UID | P1\_SP00304  |  
| F1AL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\SP@ID  | UID | P1\_SP00001  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin\\TextBlock\\TextLine\\String\\SP@ID  | UID | P12\_SP00001 |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\PrintSpace\\TextBlock\\TextLine\\String\\SP@ID | UID | P12\_SP00006 |  
| PPAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\SP@ID  | UID | P1\_SP00001  |  
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\TextBlock\\TextLine\\SP@ID  | UID | SP1  |  

### Margin

| DEAL::alto\\Layout\\Page\\TopMargin@ID  | UID | P1\_TM00001  |  
| DEAL::alto\\Layout\\Page\\LeftMargin@ID  | UID | P1\_LM00001  |  
| DEAL::alto\\Layout\\Page\\RightMargin@ID  | UID | P1\_RM00001  |  
| DEAL::alto\\Layout\\Page\\BottomMargin@ID  | UID | P1\_BM00001  |  
| EUAL::alto\\Layout\\Page\\TopMargin@ID  | UID | P1\_TM0001  |  
| EUAL::alto\\Layout\\Page\\LeftMargin@ID  | UID | P1\_LM0001  |  
| EUAL::alto\\Layout\\Page\\RightMargin@ID  | UID | P1\_RM0001  |  
| EUAL::alto\\Layout\\Page\\BottomMargin@ID  | UID | P1\_BM0001  |  
| F1AL::alto\\Layout\\Page\\TopMargin@ID  | UID | P1\_TM00001  |  
| F1AL::alto\\Layout\\Page\\LeftMargin@ID  | UID | P1\_LM00001  |  
| F1AL::alto\\Layout\\Page\\RightMargin@ID  | UID | P1\_RM00001  |  
| F1AL::alto\\Layout\\Page\\BottomMargin@ID  | UID | P1\_BM00001  |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin@ID  | UID | P12\_TM00001 |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\LeftMargin@ID  | UID | P12\_LM00001 |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\RightMargin@ID  | UID | P12\_RM00001 |  
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin@ID | UID | P12\_BM00001 |  
| PPAL::alto\\Layout\\Page\\TopMargin@ID  | UID | P1\_TM00001  |  
| PPAL::alto\\Layout\\Page\\LeftMargin@ID  | UID | P1\_LM00001  |  
| PPAL::alto\\Layout\\Page\\RightMargin@ID  | UID | P1\_RM00001  |  
| PPAL::alto\\Layout\\Page\\BottomMargin@ID  | UID | P1\_BM00001  |  
| TRAL::alto\\Layout\\Page\\TopMargin@ID  | UID | MARGIN1  |  
| TRAL::alto\\Layout\\Page\\LeftMargin@ID  | UID | MARGIN2  |  
| TRAL::alto\\Layout\\Page\\RightMargin@ID  | UID | MARGIN3  |  
| TRAL::alto\\Layout\\Page\\BottomMargin@ID  | UID | MARGIN4  |  
