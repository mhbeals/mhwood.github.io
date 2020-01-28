---
layout: page
title: Coordinates
subtitle:  
use-site-title: false
---

<h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../maps/coordinate">View Metadata Map</a></h4>

## Usage Notes

The coordinates will depend on whether the pages are automatically recognised by the [**OCR**](ocr.md) engine. **Zoning** is done by OCR, 
as part of the pre-processing stage. Different collections include different zoning and, as such, not all have 
article zones; the older collections tend to analyse data at page level. Gale segment by article, but 
with older newspapers do not try to figure out where one article starts and ends because it is subjective. 
Each article, however, has an individual title. They manually check all titles (though not the entire OCR) 
to make sure they are meaningful and accurate. In Delpher, article segmentation is done semi-automatically and 
checked by an operator. Articles are zoned rather than pages, to support users searching for specific topics and the 
creation of a search relevance ranking; if the word is in the article title, the ranking increases. 
For Trove, when the project was first proposed in 2006, they have based their decisions on other newspaper 
digitisation projects and what standards were used at that time, including the Netherlands and some US projects such as 
the Library of Congress programme. However, they did deviate in that they OCR and analysed the data at the article level 
rather than just the page level, which was common at the time. Newspapers in the nineteenth century made the best use they 
could of the available print space, having much smaller margins than other kinds of publication. This was to make the most of 
paper when paper was expensive; in the UK this was before the abolition of the paper tax in 1861 and improvements in technology made it 
cheaper, and to make the most of advertising space afterwards. When (rarely) discussed in academic literature, the 
margins are a point of interest when they grow larger, representing a shift to a more ‘respectable’ format or audience. 

## Examples:

“In addition, during the start-up phase of a digitization project, the decision should be made if 
pages get rotated automatically by the OCR engine or not. If the answer is yes than the consequence is 
that the OCR coordinates of the rotated page either do not match the original **page coordinates** or that 
the rotated page must afterwards be regarded as a new ‘original’.” \[Neudecker and Antonacopoulos, 408\]  
  
“With their generous **margins**, clear type and good quality paper the bound volumes of the quarterlies 
resembled books rather than periodical publications.” \[DNCJ JS, 523\]  
  
"The overall effect was that the new review's pages, which were slightly larger, with a taller bottom **margin**, 
and a line shorter than the old quarterly pages, appeared lighter, brighter and more leaded." \[Shattock 2017a, 58\]

"Some form of division of the newspaper pages into **‘zones’** or **‘segments’**" \[Edmund King, 180\]  
  
"Optical Character Recognition works through analysis of a document image where a scanned digital image that 
contains machine-printed text is input into an OCR software engine and translated into a machine-readable digital text 
format. OCR works by first pre-processing the digital page image into its smallest component parts with layout analysis 
to find text blocks, sentence/line blocks, word blocks and character blocks – a process known as **zoning**. Other features, 
such as lines, graphics, photographs, etc., are recognized and may be discarded for the purpose of text recognition. 
The assignment of zones becomes more challenging as the layout becomes more complex, and correct zoning remains a 
significant issue for newspaper OCR accuracy.” \[Tanner, Muñoz and Ros, par. 5\]  

“After raw data verification and ingest, the conversion process starts off with page analysis to determine page frames, 
followed by several **zoning** and structure recognition steps, where each element is assigned a specific zone category, 
and the individual elements (e.g. headlines, text blocks, illustrations) are grouped together into articles.” 
\[Neudecker and Antonacopoulos, 408\]
