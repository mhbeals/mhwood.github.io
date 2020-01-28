---
layout: map
title: Text
subtitle:  
use-site-title: false
---
<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/text">View Glossary Entry</a></h4>

## Technical Definition

Article text content. For text content in article titles, See title of
the article . For text content in subheadings, see [**article subheading.**](../article-subheading)

## Category Notes

This field is common across the collections.

## Individual Collection Notes

B1GT: Full text of article, run through OCR.

B2GL: issue\\article\\text\\text.title\\pg\\wd refers to words in the
title, while issue\\article\\text\\text.cr\\p\\wd refers to text. 

B2GT: Full text of article, run through OCR.

CAAL: Can indicate half of a hyphenated word. 

TDAG: issue\\article\\text\\text.title\\pg\\wd refers to words in the
title, while issue\\article\\text\\text.cr\\p\\wd refers to text.

TRAP: The full text of the article, including all corrections. Article
paragraphs are enclosed in a \<p\> element. Lines are enclosed by
\<span\>. Article text is not available for some articles, such as those
from the Australian Women’s Weekly and articles with a status of “coming
soon”. For these articles, there will be no articleText element present.

## Instantiations

### At Word Level  

| B1JI  |  BL\_newspaper\\BL\_page\\pageText\\pageWord  | STR | The  |
| B2GL  |  issue\\article\\text\\text.cr\\p\\wd  | STR | PROVINCIAL |
| HNME  |  METS:mets\\METS:dmdSec\\METS:amdSec\\METS:mdWrap\\METS:xmlData\\hiddentext\\pagecolumn\\region\\paragraph\\line\\word | STR | BALTAS  |
| SBAT  |  PcGts\\Page\\TextRegion\\Textline\\Word\\TextEquiv\\Unicode  | STR | futeſte  |
| TDAG  |  issue\\page\\article\\text\\text.cr\\p\\wd  | STR | PA.  |

### At String Level  

| CAAL  |  alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CONTENT  | STR | .vet  |
| DEAL  |  alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CONTENT  | STR | WOENSDAG  |
| EUAL  |  alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CONTENT  | STR | Moren-Ausgabe |
| F1AL  |  alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CONTENT  | STR | I  |
| F2AL  |  pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin\\TextBlock\\ TextLine\\String@CONTENT  | STR | 204  |
| F2AL  |  pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\ PrintSpace\\TextBlock\\TextLine\\String@CONTENT | STR | omat  |
| PPAL  |  alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CONTENT  | STR | Hawke’s  |
| TRAL  |  alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\ TextBlock\\TextLine\\String@CONTENT  | STR | y  |

### At Text Line Level 

| SBAT  |  PcGts\\Page\\TextRegion\\Textline\\TextEquiv | STR | futeſte Feimatzeitung für die Stadt Garuth und für die Amtsbezirke papſitz und Radeland (gegr. 1865) |

### At Paragraph Level  

| SBAT  |  PcGts\\Page\\TextRegion\\TextEquiv | STR | — futeſte Feimatzeitung für die Stadt Garuth und für die Amtsbezirke papſitz und Radeland (gegr. 1865) |

### At Article Level  

| B1GT  |  articles\\artInfo\\ocrText | STR | AUgck aul tirn}fr,\[…\]  |
| B2GT  |  articles\\artInfo\\ocrText | STR | Lt-vtUJu. \[…\]  |
| DEOC  |  text\\p  | STR | fcdi.\&apos; hl \[…\]  |
| TRAP  |  article\\articleText  | STR | \&lt;p\>\&lt;span\> \[…\] |


