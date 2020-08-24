---
layout: page
title: Researching the Atlas of Digitised Newspapers and Metadata
subtitle: 
use-site-title: false
---

[![Researching the Atlas of Digitised Newspapers and Metadata YouTube Video](https://img.youtube.com/vi/5bHGIFiGfhA/0.jpg)](https://www.youtube.com/watch?v=5bHGIFiGfhA)
  
## Transcript
In 2017, historians, literary scholars, computer scientists, digital humanities specialists, librarians and commercial publishers came together to form the *Oceanic Exchanges* 
project, funded by the Transatlantic Partnership for Social Sciences and Humanities 2016 Digging into Data Challenge.  Researchers and contributors to the project came from the 
University of Stuttgart, the Berlin State Library, Europeana, the National Autonomous University of Mexico, Utrecht University, the Dutch National Library, the University of 
Turku, the National Library of Finland, Loughborough University, University College London, University of Edinburgh, the British Library, Gale: A Cengage Company, Northeastern 
University, University of Nebraska-Lincoln, North Carolina State University, the National Library of Australia and the National Library of New Zealand. 
  
The project had a relatively flat structure with two overlapping team frameworks: national teams and work package teams. The national teams worked primarily as practical units, 
and as liaisons to the relevant national libraries or working through language-specific material. The work package teams comprised individuals across all six countries and 
disciplines, and meet virtually via Skype, with some face-to-face meetings at convenient workshops and conferences. There were six work packages, with the primary research for 
the project falling into three main aims. One was to develop methodologies and provide examples of best practice, in tracing the movement (that is, the reprinting) of newspaper 
text across linguistic and political borders. Most of the team members had already undertaken significant research into so-called "scissors-and-paste" journalism within their 
national or linguist borders; *Oceanic Exchanges* offered the opportunity to see not only the extent to which news travelled between cultural silos, the extent to which news 
really was transnational, but also to test our ability as digital humanities scholars to robust trace textual reappearance across multiple collections and data formats. 
A second aim of the project was to develop the means to track semantic drift across these same borders, not only direct transcriptions and translations, but concepts and ideas 
as they travel and evolve over time. This form of migration had not been tracked on a large scale before this project, and presented several new technical and scholarly 
challenges to our team.
  
In order to facilitate these two, I would say, content-driven aims, *Oceanic Exchanges* developed a third work package, Ontologies. The aim of the Ontologies project was deceptively 
simple. Working with team members in all six countries, as well as sympathetic data providers, we were to gather representative samples of data as stored (in the backend) 
and made available (in the front end) of these collections, and, using the relevant official documentation, carefully map the metadata fields on a like-for-like basis across all 
ten collections. We would then translate this simple mapping into both human- and machine-readable formats. The particular aim of this work was to support the data and periodical 
specialists on the team in leveraging content across collections. In the initial phases of the project, for example, reprinting matches were listed with all possible metadata 
fields across all collections, leading to huge spreadsheets with large empty spaces. This work would make like-for-like comparisons and, in particular, bibliographic 
identification, across collections more straightforward. Because we already had access to the relevant collections, gathered and deposited under the management of my colleague 
Paul Fyfe from North Carolina State University, and we had colleagues who had previously worked with (or had indeed had a hand in creating) the data from all ten collections, 
we allocated the ontologies project what we conceived to be generous one month for the mapping process. 
  
The first challenge we faced in the Ontologies project was the level of inconsistency across the collections, in the broad as well and the specific. Having worked extensively 
with the data behind the British Library Collections, particularly the JISC dataset, and having a general familiarity with the front-end of most of the other collections, I had 
a very particular idea about the nature and structure of the material I would be working with. I was somewhat shocked to find that there was so much variation in the structure of 
the data and metadata, the availability of technical and researcher-friendly documentation, and even the accessibility of different types and formats of text and image data. 
My colleague, Emily, will go into the finer detail of the data and metadata, but I will paint some broad strokes here.  First, in terms of documentation, there was very little 
available. There British Library collections, namely those provided by Gale rather than JISC, contained some industry-standard document-type definition (or DTD) information. 
Europeana, likewise, had extensive documentation on its particular variant of the METS/ALTO protocol and the Library of Congress contained the core METS/ALTO specifications. 
This gave us a basic starting point for tackling the data across all the connections. Fortunately for our team, who used English as a *lingua franca*, this documentation was 
all in English, but much of the surrounding information was not, including official webpages about the collections, and we were forced to rely on certain team members to do 
unpaid translation work or to rely heavily on Google Translate, which is not ideal for technical work.
  
Moreover, the official documentation gave almost no information on selection criteria, input protocols (especially the sources of the metadata from catalogues, physical 
collection pages, and so on) or who had actually been involved in the data collections and cataloguing. There was simply no human-relevant provenance for the data. In the end, 
we spent months interviewing very patient librarians and digitisation specialists, most of whom had not been involved in the initial projects and were relying on folk knowledge 
from their institution or who undertook significant internal research on our behalf, and a sprawling web of user-generator information, particular from people like Bob Nicholson, 
Paul Fyfe, Tim Sherritt and Yvonne Perkins, all of whom had (to use Yvonne's term) stumbled through the collections and left breadcrumbs for the rest of us. I want to clarify 
that this was not malevolence or neglect by the collection providers (who as I said were incredibly generous with us in terms of retroactively creating histories and 
documentation for these collections). Instead, it was, as several noted, an artefact of a rapidly changing funding and political landscape and an increasing understanding of 
who these collections were being used by, and why exactly, as they were being deployed. As a result, there was a long web-history of documentation (blog posts, forums, 
conference proceedings) from people within and beyond the digitising institutions trying to make sense of the new and immensely powerful collections at their disposal.
  
In terms of the data itself. First, with the exception of front-end database system for Mexican collections, which was held stored in JSON for indexing reasons, the front and 
backend for the other collections were all stored in various XML structures; these however were not the same.  There was a general usage of METS/ALTO or METS/ALTO-like 
structures across the board: a separation of low-level (newspaper title), mid-level (issue), and high-level (page or article) data. There was also in most cases information 
relating to the data (or file) structure, which would be useful for data scientists and those manipulating the computational content, and the bibliographical or typographical 
structure, which would be more readily recognised by historians, literary scholars and the like. However, the number of layers or resolution varied from collection to collection, 
and between front- and backends of the same collections, and some of this variation was the result of the wider structures in which they were contained — for example, 
cross-compatibility with modern newspapers or contemporary publications in other formats. If we take just the text and image of the text as an example, some collections allowed 
direct access to a word-separated XML structure, others to text-blocks (which might represent a typographical paragraph or a conceptual article—running across typographical 
boundaries), others to text matching the physical sheets of paper scanned. Some provided cleaned or tidied (that is XML-free) OCR-text, as a plain-text file, separate from the 
XML entirely.  In terms of images, there were the archival-quality JP2 or TIFF files, some of which were internet-accessible, as well as web-resolution JPGs and images that were 
cut up or embedded into HTML or other viewers.  In most cases, I would say, the backend was more consistent than the front end, but we had an unprecedented level of access to 
backend data across many collections, so we had to take that into account when describing these collections — what would most scholar actually work with? The main take-away 
from this discovery was that a significant amount of thought had gone into the organisation of these datasets by the libraries and publishers involved. However, at almost every 
stage, the tendency had been to collect and store the data in a way that made indexing or computational storage of the material most efficient, and then make editorial choices 
that lowered the resolution of the data in order to make it more human-readable.  The more the data was tailored for the end-consumer, the less information was accessible about 
its relation to the backend dataset and the more metadata was lost.
  
Finally, one of the most difficult inconsistencies we found, and this does relate back to documentation, was the lack of a firm connections between the physical (and I include 
microfilm here) and digital collections. There was (perhaps is) a general conception of these collections as complete representations of not only the exisiting but the 
ever-in-existence collections of historical newspapers. However, as we found out through extensive interviews with these and other collection and digitisation providers, 
there is a huge level of variance in how the materials that are digitised are selected. Speaking to different commercial publishers (Readex, Proquest and Gale) as well as some 
libraries that had not yet or were in the process of digitising, in addition to our main collection holders, we found that selection was almost always a compromise between 
completeness (whether by title or date or region or physical collection) and value (determined by analytics, or market research, or academic advisory boards or librarian 
experience). This is fine. I really want to stress this. This is fine. We did not expect, nor do we think it is possible or even ideal (well, maybe ideal) to digitise every 
newspaper edition that has ever existed. What was disconcerting was the lack of documentation on the process. When we published our recent article in [*Archival Science*](https://link.springer.com/article/10.1007/s10502-020-09332-1)
on why selection matters, and the different rationales for selection in these collections, we had a particularly interesting response. First, our results were wholly 
unsurprising. Everyone sort of knew, subconsciously, there were gaps and choices. Whether they fully understood this consciously or in detail when working with these collections, 
I very much doubt. I have almost never seen historians or literary scholars acknowledge in particular detail the constraints of the datasets when discussing their results. 
It is vague; assumed. Archives are incomplete. My question, however, is how? What is the actual shape of your actual dataset? Some providers were cagier about this than others 
but in general all had reasons for their selection choices, but these were either implicit (and not documented), documented only internally, or left black-boxed under the 
guise of unnamed advisory panels and user-focus groups. This had significant repercussions for not only how the collections were structured overall, but also how the metadata 
was entered and provided. 
  
Okay so, most of the metadata is written in English – that goes for both the content as well as the field types. However, it is not true for all collections, and we did focus on 
a lot of English-language collections. English has become the standard language for XML but the JSON file for the Mexican collections is in Spanish, both fields and content.
Some other collections use English for the metadata fields, but their language of the content for things like publication genre. When working with international collections, 
you might be interested in what the language fields apply to. On the *Oceanic Exchanges* project, for example, several researchers were looking at immigrant Italian communities 
in America, where the newspapers were in both English and Italian. So having language fields for specific articles, or even pages, is helpful. You also need to know what the 
multiple choice options are, when dealing with content in other languages. Most collections have language information for the issue or the publication as a whole. 
You can see Chronicling America has language for the text block. Europeana, Papers past and the *Times* Digital Archive have language of the article, Papers Past has 
language of the section, and the Finnish collection and Mexican collections have language of the page. This is primary language, and there can also be language tags for 
multiple of these within one collection or even one metadata file.
  
What I’m going to focus on now is some of the kinds of differences you might spot in the collections, which if you’re managing a collection like this or creating a new one 
may be useful to think about in terms of what decisions you will make.
  
Here you can see a short sample of metadata from the British Library and the National Library of Mexico. Mexico includes a standardised date that also gives the time, and a 
date of registration in the database, and tells you if it was a daily or a weekly publication. The ID also includes data information. This version of the British Library 
metadata – and there are several versions in their collections – is formatted differently and specifies it is the printed date – which is itself ambiguous, as it could be 
inferred to mean the date the newspaper was printed or the date as printed on the newspaper, which are often different. It’s also true that most archives only digitise one 
edition per day of their newspapers, and newspapers did change things in different editions during the day, so the ‘time’, while it might not seem relevant or possible to 
specify for a daily or weekly newspaper published two hundred years ago, can be used to indicate periodicity. If you’re looking for morning and evening editions, some databases 
may either 1. Not have them at all, or 2. Not have a way to search them specifically. If you’re creating other kinds of collections, consider what the most useful date format 
will be for your collection: there should be some form of standardised date, but having a specific time is rarely going to be useful for 19th-century documents.
  
As you can see, even from this short example it becomes clear why the fields cannot be mapped directly, which brings me to this horrible diagram, which we made using draw.io 
and used to try to map each metadata field from each collection into four broad categories, metadata containing content, metadata about the physical object, metadata about the 
digital object, and metadata pertaining to both. The aim was to eventually create an OWL ontology, which would tell you all the fields containing a specific kind of metadata. 
Don’t worry if you can’t read it here in the video – that’s part of the point I’m trying to make! You can find a version you can zoom in on, on our website 
[digitisednewspapers.net](https://www.digitisednewspapers.net/introduction/methodology/). We tried to map all of the fields – over 3300 different lines in a spreadsheet – 
directly. Our TSV file includes our own categories and sub-categories, field names, collection IDs, Xpaths, format, multiple choice options, example content, definitions drawn 
from the documentation, and content types. 
  
We faced several problems: firstly, as indicated, even fields which seemed as if they might map at the broadest resolution, like date, really contained slightly different 
content – printed date, standardised date, and so on. Secondly, having a team of around ten different people inputting each collection separately introduced inconsistencies 
which replicated metadata input problems: essentially, all the little decisions we as individuals made about defining categories or creating hierarchies introduced the same 
kinds of issues as the many hands involved in inputting the metadata originally. 
  
With the millions of newspaper pages digitised and continually being digitised, this is inevitable for the metadata. For our team, it meant we needed a stronger editorial 
oversight to work through all the collections and ensure consistency, but it was very revealing to us about the kinds of problems digitisers face. 
  
One way to try to handle this issue is to have clear documentation packaged with the data, and/or forums or other avenues for people to share their own issues and 
workarounds. 
  
Here is an example of a section of a DTD, a document type definition file. We were only given these for the British Library; no other collections seem to have them, and I can’t 
stress enough how useful they are. What it does is provide a guide for exactly what goes into each field. These need to be updated regularly – there were still fields in the 
collection without a definition – and should be readily available to users. 
  
There are other kinds of documentation that are worth considering. Europeana is a great model here. As it’s a collection that aggregates from other collections, it’s based on 
existing metadata and did the kind of OWL ontology that we did not do in order to make it possible to work across collections. I highly recommend looking at what they have made 
available if you’re considering metadata for a new or existing collection.
  
Other models include having forums, as Trove used to, and/or allowing user-generated metadata such as comments and lists, which only Trove does at the moment. While there’s 
obviously a risk in allowing untrained hands to contribute, it improves their article transcription quality and it facilitates finding items because they are tagged with new 
keywords that people might be interested in, and added to new sub-collections.
  
So we used all of this in making our data file. We will talk about the *Atlas* in more detail in the next video, but I’d like to draw attention to the information we’ve 
aggregated here. We’ve given each item its own identifier, so that we can indicate the relationships between them. We’ve then categorised them (and these relate to our 
*Atlas* entries), with sub-categories where needed. The collection is indicated, and the XPath for the field and the field name are given. We give the format, the 
content type – whether multiple choice, a string, a container, a number, and so on, and example content. Where we can find them, we give the multiple choice options. We 
haven’t always been able to find them, due to a lack of documentation. Then we give a definition, based on the standards used for which there is centralised documentation, 
the DTDs, or any other documentation like the Europeana guide or the forums. We give element type – so an element or an attribute, and then we’ve mapped the relationships. 
We’ve focused on fields with content data, and we don’t have definitions for everything. So I’d like to stress just how important it is, and that one of the things we’d like 
to cover in the workshop is what kind of information would be helpful. The document type definitions could include a bit more historical detail to explain how the field 
should be filled in. 
  
So final prompt question: what data is missing that would be useful? In previous discussions, people have suggested being able to look specifically at newspaper 
mastheads would be useful. An example not collected by us for this project is the Impresso project, which includes newspaper political affiliations where available. 
So this question is something we’d like to be able to discuss in the workshop – we look forward to hearing your thoughts! 
