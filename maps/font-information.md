---
layout: page
title: Font Information
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/font-information">View Glossary Entry</a></h4>

## Technical Definition

Provides information about the font of the text, as recognised by the
OCR software. This includes font **size**, font **style** (whether bold,
italics, underlined, small caps, etc.), font **type** (whether serif or
sans serif), font **width** (whether proportional or fixed), and font
**family**.

## Category Notes

Font size, style and family are quite common fields in ALTO files. Font
type and font width appear in CAAL only.

## Individual Collection Notes

CAAL: The font size is in points (1/72 of an inch). Font style: list of
any combination of font styles as a string choice: “bold”, “italics”,
“subscript”, “superscript”, “smallcaps”, “underline”. Font type:
String choice of “serif” or “sans-serif”. Font width: String choice of
“proportional” or “fixed”.

DEAL: Font style: list of any combination of font styles. String-Choice:
“bold”, “italics”, “subscript”, “superscript”, “smallcaps”, “underline”.

EUAL: Font style: list of any combination of font styles. String-Choice:
“bold”, “italics”, “subscript”, “superscript”, “smallcaps”, “underline”.

F1AL: Font style: list of any combination of font styles. String-Choice:
“bold”, “italics”, “subscript”, “superscript”, “smallcaps”, “underline”.

F2AL: Though labelled **Font Style**, font size contains numeric data.

PPAL: Font style: list of any combination of font styles. String-Choice:
“bold”, “italics”, “subscript”, “superscript”, “smallcaps”, “underline”.

## Instantiations

### Font Size  

| CAAL::alto\\Styles\\TextStyle@FONTSIZE  | NUM | 10  |
| DEAL::alto\\Styles\\TextStyle@FONTSIZE  | NUM | 9  |
| EUAL::alto\\Styles\\TextStyle@FONTSIZE  | NUM | 15  |
| F1AL::alto\\Style\\TextStyle@FONTSIZE  | NUM | 15  |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Styles\\TextStyle@FONTSTYLE | NUM | 9  |
| PPAL::alto\\TextStyle@FONTSIZE  | NUM | 10  |
| TRAL::alto\\Styles\\TextStyle@FONTSIZE  | NUM | 7.7 |

### Font Style  

| CAAL::alto\\Styles\\TextStyle@FONTSTYLE | STR | small caps |
| DEAL::alto\\Styles\\TextStyle@FONTSTYLE | STR | bold  |
| EUAL::alto\\Styles\\TextStyle@FONTSTYLE | STR | bold  |
| F1AL::alto\\Style\\TextStyle@FONTSTYLE  | STR | bold  |
| PPAL::alto\\TextStyle@FONTSTYLE  | STR | italics  |

### Font Type  

| CAAL::alto\\Styles\\TextStyle\\FONTTYPE1 | MCH | Serif |

### Font Width  

| CAAL::alto\\Styles\\TextStyle\\FONTWIDTH | MCH | proportional |

### Font Family  

| DEAL::alto\\Styles\\TextStyle@FONTFAMILY  | STR | Times New Roman |
| EUAL::alto\\Styles\\TextStyle@FONTFAMILY  | STR | Fraktur  |
| F1AL::alto\\Style\\TextStyle@FONTFAMILY  | STR | Times New Roman |
| F2AL::pageOCRDATA\\content\\altoXML\\alto\\Styles\\TextStyle@FONTFAMILY | STR | Fraktur  |
| PPAL::alto\\TextStyle@FONTFAMILY  | STR | Times New Roman |
