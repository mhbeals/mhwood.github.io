---
layout: map
title: Page Position
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/page-position">View Glossary Entry</a></h4>

## Technical Definition  

Indicates the position of the page within the <a href="https://www.digitisednewspapers.net/maps/issue-number/">**issue**</a>.

## Category Notes

This field is uncommon.

## Individual Collection Notes

DEAL: String-Choice: “Left”, “Right”, “Foldout”, “Single”, “Cover”.

TDAG: Options are “Single” or “Double”.

TRAL: String-Choice: “Left”, “Right”, “Foldout”, “Single”, “Cover”.

TRAP: Sometimes used to indicate what is printed on the page, or perhaps
the page number within a section/supplement. Not displayed in the Trove
web interface. Sometimes numeric and sometimes not. e.g.
http://api.trove.nla.gov.au/newspaper/45649893?reclevel=full\&key=\<insert
key here\>.

## Instantiations

| DEAL  |  alto\\Layout\\Page@POSITION  | MCH | Single  |
| TDAG  |  issue\\page\\pageid@pageIndicator  | MCH | Single  |
| TRAL  |  alto\\Layout\\Page@POSITION  | MCH | Single  |
| TRAP  |  article\\title\\page\\pageLabel  | STR | Front cover |
| F1ME  |  mets\\structMap\\div\\div\\div\\div@TYPE | STR | FRONT  |
