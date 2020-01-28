---
layout: map
title: OCR Information
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/ocr">View Glossary Entry</a></h4>

## Technical Definition

Provides technical information on the OCR software used, including
Description ID, Agency, Date and Time, Step Description, Step Settings,
Creator, Name, Version, Relevance and Confidence Level.

## Category Notes

This field is very common, appearing in all except B1GP and B2GP, which
only provide information about <a href="https://www.digitisednewspapers.net/maps/alternate-newspaper-title/">**alternate newspaper titles**</a>. Only DEAL
and TRAL have a processing agency and date.

## Individual Collection Notes

B1GI: @primary specifies the OCR language is the primary language (see
<a href="https://www.digitisednewspapers.net/maps/language">**language**</a>).

B2GL: Relevance is a string choice “yes” or “no”.

B2GI: Relevance is a numerical score. @primary specifies the OCR
language is the primary language (see **language**).

CAAL: sourceImageInformation contains information to identify the image
file from which the OCR text was created. processingStepSettings: A
description of any setting of the processing application. For example,
for a multi-engine OCR application this might include the engines which
were used. Ideally, this description should be adequate so that someone
else using the same application can produce identical results.
Confidence is given as a numerical value for page and word, with a value
between 0 (unsure) and 1 (sure). processingStepDescription provides an
ordinal listing of the image processing steps performed, for example
“image despeckling“.

DEAL: **Page confidence**, with a value between 0 (unsure) and 1 (sure);
string confidence, as a list of numbers, one number between 0 (sure) and
9 (unsure) for each character; word confidence, with a value between 0
(unsure) and 1 (sure).

DEMP: **Confidence level** of the correctness of the character
recognition on this page, 0 is no confidence at all, 1 is highest
confidence. (This page confidence level is an aggregate of the
confidence levels for each word and character, as listed in the alto
files.)

EUAL: Page confidence, with a value between 0 (unsure) and 1 (sure);
string confidence, as a list of numbers, one number between 0 (sure) and
9 (unsure) for each character; word confidence, with a value between 0
(unsure) and 1 (sure).

F1AL: String confidence as a list of numbers, with one number between 0
(sure) and 9 (unsure) for each character; word confidence, with a value
between 0 (unsure) and 1 (sure).

F2AL: Page confidence, with a value between 0 (unsure) and 1 (sure);
string confidence, with a value 0-9 for each character; word confidence,
with a value 0-1; character confidence, with a value between 0 (unsure)
and 1 (sure).

PPAL: Estimated percentage of OCR Accuracy in range from 0 to 100;
character confidence level 0-9 for each character in string; word
confidence for whole string.

SBAT: Word confidence, with a value between 0 (unsure) and 1 (sure).

TRAL: Page confidence, with a value between 0 (unsure) and 1 (sure);
string confidence with a value 0-9 for each character; word confidence
for whole string.

TRAP: Relevance is a string choice, with the options “very relevant”,
“likely to be relevant”, “may have relevance” or “vaguely relevant”,
and a numerical representation.

## Instantiations

### Relevance

| B2GL::issue\\article\\ocr\\relevant  | STR | yes  |
| B2GI::issue\\page\\article\\ocr  | NUM | 41.29  |
| TRAP::article\\relevance  | MCH | very relevant |
| TRAP::article\\relevance@relevance@score | NUM | 0.009942865  |

### Confidence Level  

| CAAL::alto\\Layout\\Page@PC  | NUM | 1  |
| CAAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@WC  | NUM | 1  |
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\ddd:OCRConfidencelevel  | NUM | 0.885  |
| DEAL::alto\\Layout\\Page@PC  | NUM | 0.885  |
| DEAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CC  | NUM | 80150190  |
| DEAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@WC  | NUM | 0.99  |
| DEMP::didl:DIDL\\didl:Item\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\ddd:OCRConfidencelevel  | NUM | 0.885  |
| EUAL::alto\\Layout\\Page@PC  | NUM | 0.853  |
| EUAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CC  | NUM | 77800000000000 |
| EUAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@WC  | NUM | 0.98  |
| F1AL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CC  | NUM | 2030626684413  |
| F1AL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@WC  | NUM | 0.65  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page@PC  | NUM | 0.825  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin\\TextBlock\\TextLine\\String@CC  | NUM | 0  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\TopMargin\\TextBlock\\TextLine\\String@WC  | NUM | 0.49  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\PrintSpace\\TextBlock\\TextLine\\String@CC | NUM | 4444  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Layout\\Page\\BottomMargin\\PrintSpace\\TextBlock\\TextLine\\String@WC | NUM | 0.53  |
| PPAL::alto\\Layout\\Page@ACCURACY  | NUM | 93.58  |
| PPAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@CC  | NUM | 0  |
| PPAL::alto\\Layout\\Page\\PrintSpace\\TextBlock\\TextLine\\String@WC  | NUM | 1  |
| SBAT::PcGts\\Page\\TextRegion\\Textline\\Word\\TextEquiv@conf  | NUM | 0.68334  |
| TDAG issue\\metadatainfo\\ocr  | NUM | 32.73  |
| TDAG::issue\\page\\article\\ocr  | NUM | 13.28  |
| TRAL::alto\\Layout\\Page@PC  | NUM | 0  |
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\TextBlock\\TextLine\\String@CC  | NUM | 3  |
| TRAL::alto\\Layout\\Page\\PrintSpace\\ComposedBlock\\ComposedBlock\\TextBlock\\TextLine\\String@WC  | NUM | 0.7  |

### Primary Language  

| B1GI::issue\\metadataInfo\\language@primary | BOO | Y |
| B2GI::issue\\metadataInfo\\language@primary | BOO | Y |
| TDAG::issue\\metadatainfo\\language@primary | BOO | Y |

### Unique Identifiers  

| CAAL::alto\\Description\\OCRProcessing@ID  | UID | OCR.0  |
| CAAL::alto\\Layout\\Page@PROCESSING  | UID | OCR.0  |
| DEAL::alto\\Description\\OCRProcessing@ID  | UID | OCRPROCESSING\_1 |
| EUAL::alto\\Description\\OCRProcessing@ID  | UID |  |
| F1AL::alto\\Description\\OCRProcessing@ID  | UID | OCRPROCESSING\_1 |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Description\\OCRProcessing@ID | UID | OCRPROCESSING\_1 |
| PPAL::alto\\Description\\OCRProcessing@ID  | UID | OCRPROCESSING\_1 |
| TRAL::alto\\Description\\OCRProcessing@ID  | UID | OCR1  |
| TRAL::alto\\Layout\\Page@PROCESSING  | UID | OCR1  |

### Processing Step Settings  

| CAAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingStepSettings | STR | <Conf:1> abbyy9.option.analyze manual-zones:false Lang:en\_US Inverted:false \[…\] |
| DEAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingStepSettings | STR | CCS OCR Processing  |

### Software Creator  

| CAAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareCreator  | STR | iArchives  |
| DEAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareCreator  | STR | CCS Content Conversion Specialists GmbH, German  |
| DEAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareCreator  | STR | ABBYY (BIT Software), Russia  |
| EUAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingSoftware\\softwareCreator  | STR | CCS Content Conversion Specialists GmbH, Germany |
| EUAL::alto\\Description\\OCRProcessing\\OCRProcessingStep\\processingSoftware\\softwareCreator  | STR | ABBYY (BIT Software), Russia  |
| F1AL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingSoftware\\softwareCreator  | STR | CCS Content Conversion Specialists GmbH, Germany |
| F1AL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareCreator  | STR | ABBYY (BIT Software), Russia  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Description\\OCRProcessing\\preProcesssingStep\\processingSoftware\\softwareCreator | STR | CCS Content Conversion Specialists GmbH, Germany |
| PPAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingSoftware\\softwareCreator  | STR | CCS Content Conversion Specialists GmbH, Germany |
| PPAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareCreator  | STR | ABBYY (BIT Software), Russia  |
| TRAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareCreator  | STR | ABBYY  |
| TRAL::alto\\Description\\OCRProcessing\\postProcessingStep\\processingSoftware\\softwareCreator  | STR | iSolve Technologies Pvt Ltd  |

### Software Name  

| CAAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareName  | STR | iArchives OCR Framework |
| DEAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareName  | STR | CCS docWORKS  |
| DEAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareName  | STR | FineReader  |
| EUAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingSoftware\\softwareName  | STR | CCS docWorks  |
| EUAL::alto\\Description\\OCRProcessing\\OCRProcessingStep\\processingSoftware\\softwareName  | STR | FineReader  |
| F1AL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingSoftware\\softwareName  | STR | CCS docWORKS  |
| F1AL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareName  | STR | Finereader  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Description\\OCRProcessing\\preProcesssingStep\\processingSoftware\\softwareName | STR | CCS docWORKS  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareName  | STR | FineReader  |
| PPAL::pageOCRDATA\\content\\altoXML\\alto\\Description\\OCRProcessing\\preProcesssingStep\\processingSoftware\\softwareName | STR | CCS docWORKS  |
| PPAL::pageOCRDATA\\content\\altoXML\\alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareName  | STR | FineReader  |
| TRAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareName  | STR | FineReader  |
| TRAL::alto\\Description\\OCRProcessing\\postProcessingStep\\processingSoftware\\softwareName  | STR | iClip  |

### Software Version  

| CAAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareVersion  | STR | Multiple |
| DEAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareVersion  | STR | 6.3-0.91 |
| DEAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareVersion  | STR | 8.1  |
| EUAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingSoftware\\softwareVersion  | STR | 6.7-1.35 |
| EUAL::alto\\Description\\OCRProcessing\\OCRProcessingStep\\processingSoftware\\softwareVersion  | STR | 10  |
| F1AL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingSoftware\\softwareVersion  | STR | 6.0-8.19 |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Description\\OCRProcessing\\preProcesssingStep\\processingSoftware\\softwareVersion | STR | 6.4-0.29 |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareVersion  | STR | 7.1  |
| PPAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingSoftware\\softwareVersion  | STR | 6.2-1.5  |
| TRAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingSoftware\\softwareVersion  | STR | 12  |
| TRAL::alto\\Description\\OCRProcessing\\postProcessingStep\\processingSoftware\\softwareVersion  | STR | 5  |

### Application Description  

| DEAL::alto\\Description\\OCRProcessing\\preProcessingStep\\applicationDescription | STR |  |

### Processing Agency  

| DEAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingAgency  | STR | CCS Content Conversion Specialists GmbH, www.content-conversion.com |
| TRAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingAgency  | STR | iSolve Technologies Pvt Ltd  |
| TRAL::alto\\Description\\OCRProcessing\\postProcessingStep\\processingAgency | STR | iSolve Technologies Pvt Ltd  |

### Processing Date  

| DEAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingDateTime  | DAT | 13/10/2009  |
| TRAL::alto\\Description\\OCRProcessing\\ocrProcessingStep\\processingDateTime  | DAT | 2017-09-13T05:47:57 |
| TRAL::alto\\Description\\OCRProcessing\\postProcessingStep\\processingDateTime | DAT | 2017-09-13T05:47:58 |

### Processing Step Description  

| DEAL::alto\\Description\\OCRProcessing\\preProcessingStep\\processingStepDescription  | STR | align  |
| TRAL::alto\\Description\\OCRProcessing\\postProcessingStep\\processingStepDescription | STR | iSolve -\&gt; ALTO |
