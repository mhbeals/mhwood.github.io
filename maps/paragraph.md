---
layout: map
title: Paragraph
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/paragraph">View Glossary Entry</a></h4>

## Technical Definition

Information about paragraphs, including XML containers, text alignment,
and UIDs.

## Category Notes

These fields appear irregularly in ALTO files and in some of the other
file structures. They are primarily used as XML containers, rather than
holding data, to which style attributes can be attached.

## Individual Collection Notes

DEAL: String-Choice: “Left”, “Right”, “Center”, “Block”.

EUAL: String-Choice: “Left”, “Right”, “Center”, “Block”.

F1AL: String-Choice: “Left”, “Right”, “Center”, “Block”.

F2AL: String-Choice: “Left”, “Right”, “Center”, “Block”.

PPAL: String-Choice: “Left”, “Right”, “Center”, “Block”.

TRAL: String-Choice: “Left”, “Right”, “Center”, “Block”.

## Instantiations

### As an XML Container  

| B1GL  |  issue\\article\\text\\text.title\\p  | NUL |  |
| -- | -- |  |
| B1GL  |  issue\\article\\text\\text.cr\\p  | NUL |  |
| B2GL  |  issue\\article\\text\\text.title\\p  | NUL |  |
| SBAT  |  PcGts\\Page\\TextRegion  | NUL |  |
| TDAG  |  issue\\page\\article\\text\\text.cr\\p | NUL |  |

### The Description of Text Alignment for Paragraph Text  

| DEAL  |  alto\\Styles\\ParagraphStyle@ALIGN  | MCH | Right  |
| EUAL  |  alto\\Styles\\ParagraphStyle@ALIGN  | MCH | Right  |
| F1AL  |  alto\\Style\\ParagraphStyle@ALIGN  | MCH | Left  |
| F2AL  |  pageOCRDATA\\content\\altoXML\\alto\\Styles\\ParagraphStyle@ALIGN | MCH | Center |
| PPAL  |  alto\\Styles\\ParagraphStyle@ALIGN  | MCH | Right  |
| TRAL  |  alto\\Styles\\ParagraphStyle@ALIGN  | MCH | Left  |

### Unique Identifier for Paragraph Text  

| DEAL  |  alto\\Styles\\ParagraphStyle@ID  | UID | PAR\_RIGHT  |
| EUAL  |  alto\\Styles\\ParagraphStyle@ID  | UID | PAR\_CENTER |
| F1AL  |  alto\\Style\\ParagraphStyle@ID  | UID | PAR\_LEFT  |
| F2AL  |  pageOCRDATA\\content\\altoXML\\alto\\Styles\\ParagraphStyle@ID | UID | PAR\_CENTER |
| PPAL  |  alto\\Styles\\ParagraphStyle@ID  | UID | PAR\_RIGHT  |
| SBAT  |  PcGts\\Page\\TextRegion@id  | UID | R0  |
| TRAL  |  alto\\Styles\\ParagraphStyle@ID  | UID | PAR1  |
