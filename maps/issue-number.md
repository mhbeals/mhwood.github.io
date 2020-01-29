---
layout: map
title: Issue Number
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/issue-number">View Glossary Entry</a></h4>

## Technical Definition

Gives the issue number for the item. This is sometimes a string, as
printed, and other times a numerical value. It can also take the form of
a unique identifier for the newspaper issue.

## Category Notes

This field is common. In F1ME and PPME, a string including the
publication [**date**](../date) and [**newspaper title**](../newspaper-title) is given rather than a
numerical value. METS LABEL URI: <a href="https://www.loc.gov/standards/mets/docs/mets.v1-5.html">loc.gov/standards/mets/docs/mets.v1-5.html</a>. MODS:number URI: <a href="https://www.loc.gov/standards/mods/userguide/part.html#number">loc.gov/standards/mods/userguide/part.html#number</a>. MODS:partNumber URI: <a href="https://www.loc.gov/standards/mods/userguide/titleinfo.html#partnumber">loc.gov/standards/mods/userguide/titleinfo.html#partnumber</a>. 

## Individual Collection Notes

B1GL: issue\\id specifies that this is the source issue number.
issue\\id is composed of an abbreviated title and issue date. The
issue\\newspaperId is a unique identifier assigned to the newspaper
issue for online delivery.

B1GI: Specifies that this is the source issue number. The UID includes
an abbreviation for the [**newspaper title**](../newspaper-title) and [**date**](../date).

B1GL: issue\\id specifies that this is the source issue number.
issue\\id is composed of an abbreviated title and issue date. The
issue\\newspaperId is a unique identifier assigned to the newspaper
issue for online delivery.

B2GI: Specifies that this is the source issue number. The UID includes
an abbreviation for the [**newspaper title**](../newspaper-title) and [**date**](../date).

DEMP: Issue number as printed on the original.

TDAG: Specifies that this is the source issue number.

## Instantiations

### **Relative to Newspaper Title**  

| B1GL  |  issue\\is  | NUM | 6209  |
| B1GI  |  issue\\metadataInfo\\is  | NUM | 2608  |
| B1JI  |  BL\_newspaper\\BL\_page\\issue\_metadata\\issueNumber  | NUM | 2731  |
| B2GL  |  issue\\is  | NUM | 6209  |
| B2GI  |  issue\\metadataInfo\\is  | NUM | 1196  |
| CAME  |  mets\\dmdSec\\mdWrap\\xmlData\\mods:mods\\mods:relatedItem\\mods:Identifier\\mods:part\\mods:detail\[@TYPE=“ISSUE”\]\\mods:number | NUM | 5  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcx:issuenumber  | NUM | 81  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:titleInfo\\mods:partNumber  | NUM | 613  |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:titleInfo@ID  | UID | MODSMD\_ISSUE1\_TI1 |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:titleInfo@ID  | UID | MODSMD\_ISSUE1\_TI1 |
| EUME  |  METS:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:relatedItem@ID  | UID | MODSMD\_ISSUE1\_RI1 |
| EUME  |  METS:mets\\mets:dmdSec@ID  | UID | MODSMD\_ISSUE1  |
| F1ME  |  mets\\dmdSec@ID  | UID | MODSMD\_ISSUE1  |
| F1ME  |  mets\\structMap\\div\\div\\div@DMDID  | UID | MODSMD\_ISSUE1  |
| F1ME  |  mets\\dmdSec\\mdWrap\\xmlData\\MODS:mods\\MODS:titleInfo\\MODS:partNumber  | NUM | 1  |
| PPME  |  mets\\structMap\\div\\div\\div@DMDID  | UID | MODSMD\_ISSUE1  |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:part\\mods:detail\[@type=“issue”\]\\mods:number  | STR | Stück 9  |
| TDAG  |  issue\\metadatainfo\\is  | NUM | 8652  |
| TRME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:relatedItem\\mods:part\\mods:detail\\mods:number  | NUM | 2044  |

**Unique Identifier**  

| B1GL  |  issue\\id  | UID | WOJL-1822-01-03  |
| B1GL  |  issue\\newspaperId  | UID | NCBL0081  |
| B1GI  |  issue\\metadataInfo\\PSMID  | UID | WO1\_ANJO\_1798\_01\_02  |
| B2GL  |  issue\\id  | UID | WOJL-1822-01-03  |
| B2GL  |  issue\\newspaperId  | UID | NCBL0081  |
| B2GI  |  issue\\metadataInfo\\PSMID  | UID | YOHD-1813-07-31  |
| CAME  |  mets@LABEL  | UID | National tribune (Washington, D.C.), 1898-11-10  |
| DEMP  |  didl:DIDL\\didl:Item\\dc:identifier  | UID | ddd:010419500:mpeg21  |
| DEMP  |  didl:DIDL\\didl:Item\\didl:Component\\didl:Resource\\srw\_dc:dcx\\dcx:recordIdentifier  | UID | ddd:010419500:mpeg21  |
| EUME  |  METS:mets@LABEL  | STR | Hamburger Nachrichten no. 613 31.12.1932  |
| EUME  |  METS:mets\\mets:structMap\[@LABEL=“Logical Structure” @TYPE=“LOGICAL”\]\\mets:div\\@LABEL  | STR | Hamburger Nachrichten no. 613 31.12.1932  |
| F1ME  |  mets@LABEL  | STR | Suomi no. 1 1841  |
| F1ME  |  mets\\structMap\[@LABEL=“Logical Structure” @TYPE=“LOGICAL”\]\\div\\div\\div@LABEL  | STR | Suomi no. 1 1841  |
| F1ME  |  mets\\structMap\[@LABEL=“Logical Structure” @TYPE=“LOGICAL”\]\\div@LABEL  | STR | Suomi no. 1 1841  |
| PPDI  |  \[abbreviatedTitle\]\_\[yearmonthday\]  | UID |  |
| PPME  |  mets\\@LABEL  | STR | Daily Southern Cross no. I 1843-04-22  |
| PPME  |  mets\\structMap\[@LABEL=“Logical Structure” @TYPE=“LOGICAL”\]\\div@LABEL  | STR | Daily Southern Cross no. I 1843-04-22  |
| PPME  |  mets\\structMap\[@LABEL=“Logical Structure” @TYPE=“LOGICAL”\]\\div\\div\\div@LABEL  | STR | Daily Southern Cross Southern Cross;New Zealand Herald no. I 1843-04-22 |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:recordInfo\\mods:recordIdentifier  | UID | PPN1053698984\_19340510\_020  |
| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:part@order  | UID | 19340510020  |
| SBME  |  mets:mets\\mets:structMap\[@TYPE=“LOGICAL”\]\\mets:div\\mets:div\\mets:div\\mets:div\\mets:div@ORDERLABEL  | UID | 19340510020  |
| SBMA  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:identifier  | UID | PPN791048292  |
| SBMY  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mets:mods\\mets:recordInfo\\mods:recordIdentifier  | UID | PPN1053698984\_1934  |
| SBMY  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mets:mods\\mods:relatedItem\\mods:recordInfo\\mods:recordIdentifier | UID | PPN1053698984\_1934  |
| TDAG  |  issue\\metadatainfo\\PSMID  | UID | 0FFO-1812-JUL14  |

### **URL**  

| SBME  |  mets:mets\\mets:dmdSec\\mets:mdWrap\\mets:xmlData\\mods:mods\\mods:identifier | URL | http://resolver.staatsbibliothek-berlin.de/SNP27779154-19340510-20-0-0-0 |
