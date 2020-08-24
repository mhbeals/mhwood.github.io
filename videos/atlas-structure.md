---
layout: page
title: Videos
subtitle: 
use-site-title: false
---


[![Researching the Atlas of Digitised Newspapers and Metadata YouTube Video](https://img.youtube.com/vi/ZPQD_rjT0cM/0.jpg)](https://www.youtube.com/watch?v=ZPQD_rjT0cM)
  
This video will take you the main product of our Ontologies collaboration, *The Atlas of Digitised Newspaper and Metadata*. The *Atlas* represents the culmination of two years 
of research into the histories, structures and potentialities of these collections and our hopes for a more integrated ecosystem of digitised historical material in the future.
 The *Atlas* began its life as a Google Sheets spreadsheet and a series of blog posts during the early months of our project, the latter of which are still available on the 
 [*Oceanic Exchanges* website](https://oceanicexchanges.org/news/).
   
The posts were written by different members of the various national teams and included basic information about each collection's composition, data quality and access rights. 
The first was written by Paul Fyfe and me, based upon his significant research into the history of the British Library Collections and our joint experience working with data 
sets, and largely set the parameters by which these entries would be written. However, each national team approached the topic somewhat differently, including different levels 
of detail under certain headings, adding sections of particular interest or removing sections where information seemed irrelevant or unavailable. These were translated into 
either the relevant "home" language (or into English from that initial language) and provide a snapshot of our initial understandings of these collections. In all honesty, 
these blogs were only meant to be works-in-progress, a transitory view into the workings of the *Oceanic Exchanges* project. However, as our work normalising and mapping the 
metadata progressed, we found that, to properly understand the data, we needed far more contextual information than either the individual collection websites or these brief 
posts could provide. We were relying far too heavily on "quick question" emails to librarians and team members, and the information gleaned in this way was uneven and haphazard.
  
As the prime editorial force behind the metadata spreadsheet, Emily and I began to work with our project colleagues to gather their first-hand experience of the data and 
digitisation projects, and with the librarians and digitisation teams at the various collection holding institutions to retrieve undocumented histories of the collections. 
Moreover, we undertook a wide-ranging literature review of the preservation projects that fed into these collections, including the initial collection or deposit of hardcopy 
issues, their later microfiliming and finally their digitisation over the past twenty years. 
  
The latter part of this material was not easy to come by — much of it was fragmentary or initial musing by librarians and archivists within industry journals, thus only giving 
us the start of an interesting story, or locked behind insurmountable paywalls, particularly the proceedings of the IFLA which we had to piece together from digitised sections 
on Google Books and the limited runs held by the British Library and National Library of Australia that I was able to go through (very quickly) when visiting these institutions. 
If I could suggest only one thing to make this sort of work easier, it would be providing Open Access to these crucial proceedings. How much data remains to be integrated owing 
to language is unknown. Although we had a multi-lingual team, the majority of the literature review was undertaken by Anglophone researchers, and so contributions from native 
speakers with access to relevant non-English literature will be crucial going forward. Overall, however, in understanding our metadata, we brought together, under one project 
heading and in one language, thousands of pages and hours of interviews relating to the histories and specific natures of these collections. It seemed only natural, therefore, 
to streamline this information, not just in journal articles or conference papers, but as part of the final dataset we intended to publish.
  
The initial aim of the ontologies project, however, was the ontology. As part of our initial conception of the project, we aimed to create both a machine-readable and 
human-readable ontology, a master list of all the high-level concepts that were represented in the metadata or textual data of these collections. At first, the process of doing 
so seemed relatively simple. One member of each national team volunteered to transcribe a set of example XML or JSON file into a single pan-collection spreadsheet. The fields 
they were asked to enter were fairly basic: the name of the field, its contents (by type and example) and the technical and institutional definitions provided by documentation 
and paradata sources, such as how they were populated. Once all of these were entered, it would a simple task to catagorise them into groups and sub-groups. 
  
Unfortunately, this part of the project was wholly unsuccessful in its first iteration.  Although the volunteers were all largely fluent in XML, or at least incredibly diligent 
in gaining such knowledge, the practical implementation of this transcription varied widely. Given only a simple "common sense" directive from me, to list every field in the 
file and fill in the various information about it, this was interpreted in every way imaginable. By and large, it meant that many fields were omitted (as not relevant or 
duplicates) and differentiation was not consistently made between fields with the same name but wholly different Xpaths (or instances). When it came to data type (string, 
numerical, etc) I had given some definitions, but these were in the end equally open to interpretation and the general sense, noted previously, was that documentation was 
either unavailable or unintelligible and therefore "folk" or "common sense" definitions were all that could be provided. 
  
About a year into the process, we completely restructured the project. Building upon the work of colleagues on the blog posts and initial data entry, we limited direct 
editorial control to the two people who had frequent face-to-face contact and could determine and document definitions consistently throughout — namely Emily and myself. What 
we had learned is that the balance between hands-on knowledge of the language and collection (which our team member obviously had more of than the Loughborough team on its own) 
and editorial consistency (which was the product of physical co-location, or at least by limiting the variables associated with personal and disciplinary experience) 
was not an easy one to strike. In the end, we decided that the latter was the more difficult to "teach", and that Emily and I would just have to learn the collection 
as well as our colleagues had. 
  
The final version of the spreadsheet, available on the [*Atlas* website](https://www.digitisednewspapers.net/introduction/web/) and [Figshare](https://figshare.com/articles/Full_Map_of_Digitised_Newspaper_Metadata/11560110), 
provides a much more robust version of our initial ambitions. While technical and institutional definitions remain largely elusive, for aforementioned reasons, we were able to 
much more consistently include all fields, differentiate clearly between different XML files and different Xpaths through parent/child and attribute/attributed indicators, 
and provide detailed and consistent datatype and example content. 
  
For both our initial and restructured spreadsheet projects, we attempted to categorise the metadata fields into a controlled vocabulary, either a taxonomy of types or, ideally, 
an ontology of relationships between those types. The first attempt at this was the ill-fated visual diagramming of fields.  Because each team member theoretically 
understood the intent of the fields within their national collection better than the spreadsheet might indicate, all members were asked to organically add to a single 
ontological mind-map.  As you can see here, this was only partially completed before we recognised the editorial chaos that was ensuing.  Concepts simply did not translate 
easily between collections, languages or individual researchers, and this was abandoned. After restructuring the input process, Emily and I worked together to create a series 
of different, overlapping taxonomies and ontologies that reflected both the typical data structure of the collections and our understanding of the physical and historical 
objects, as historical and literary scholars. The latter is, admittedly, partially a top-down catagorisation but one we both felt was common to users of the collections 
and therefore just as important as the "bottom-up" description of the data structure.  Once all content fields were catagorised into this controlled vocabulary, we could 
go about describing the general and particular nature of the data available. What was common and what was specific to particular databases or sub-projects within those 
databases? Where was the information pulled from and how was the material entered? Perhaps most importantly, what fields or data could be said to be universal, common or 
unusual across the digisited newspaper ecosystem?
  
When it came to publication, we had originally decided to release a "cookbook" of digitised newspaper metadata, a selection of guides and combinations of metadata fields that 
would allow users to work across collections. However, we later decided that the cookbook was not the ideal format—a more comprehensive discussion of the histories and 
trajectories of these collections had been crucial to our understanding of the metadata and it was therefore crucial it be included, integrated, with that discussion of the 
metadata. We included this at the start of our *Atlas* of metadata maps: a section of database histories. Although built upon the initial blog posts, these were updated and 
expanded in order to be as complete and comparable as possible across every collection. Moreover, the extensive bibliography we had accrued over two years of research was 
included in order to assist future researchers in understanding how the histories themselves had been constructed. We will therefore now take you through *Atlas* itself to 
show you what is included, why and how you can make use of this material.
  
So now I’m going to move onto the maps of the *Atlas*.
  
These are grouped into sections: content metadata, citation metadata, bibliographic, holdings, descriptive, social interaction, and technical. These mirror common 
divisions in metadata (technical and descriptive) and our attempts to group the kinds of things people may be looking for. Each map gives the category, which we have devised 
over many long conversations based on what exists in the metadata, the historical understanding of the newspaper, and how academic literature refers to these sections. 
We give language variants where appropriate – as mentioned in our last video, there are some collections that use the newspaper language for things like publication 
genre or geographic coverage. We offer a technical definition, drawn from the document type definitions, also discussed in the last video, and drawn from other metadata 
documentation.
  
We then offer usage notes that show how the term was used and developed in the nineteenth century, and/or how the term is understood by libraries today. This is 
supported with examples from academic literature and contemporary accounts, across periodicals research, literature, history and archival science. We have recorded 
alternatives and variations here. Category notes indicate how common the fields are, and any particular quirks to pay attention to.
  
Individual collection notes are even more specific about the individual instantiations, and then we give all instantiations in a table.This is to allow people to
understand firstly how the term is being used in different ways by different groups, and to help people map the type of information they really want with the data that is 
available. If you’re not technically minded, the most useful thing may be noting which collections do or don’t contain certain information like periodicity or 
geographic coverage, so you know where to look if you’re interested in these things.
  
The technical information, including data types and Xpaths for locating the information within that data set, enables you to understand the different structures of the 
collections and develop computational means for robustly comparing data sets. There’s also a bibliography of research representing the examples we use in the report, and 
it’s a good place to start if you’re looking for guides to the collections as well as periodicals research. 
  
Our index captures the variant terms, so you can look up the terms you’re more familiar with. On our website, we have a [hyperlinked version of the glossary](https://www.digitisednewspapers.net/glossary/).
  
Now I’m going to talk about some examples and use cases.
  
Issue number is a complicated example. You can see from these different instantiations – and this isn’t all of them – that some databases treat issue as numerical, 
others as the title, number and date, or a string, and so on. So if you’re interested in special or supplementary issues, you can see which collections record these kinds of 
titles; supplement may also be useful.
  
Edition is another complex one. By one definition of a newspaper ‘edition’, all newspapers have them. The copy you hold in your hands, or access online, is a specific edition, 
made the more significant because many researchers now interact with exactly the same one. Digitised newspapers become something new–a digital edition–in the digitisation 
process, because that single copy is preserved. The digital edition may be missing pages, or have set through, or have advertisements removed. In these terms, ‘edition’ 
provides you with important information regarding the object you’re interacting with, and highlights that it’s distinct from other issues of the same newspaper. As a 
digital object, it becomes representative. There’s also, in this case, some blurring with the term ‘issue’ that can be difficult to disentangle, and leads to some edition 
metadata fields being filled simply with issue numbers.
  
By another definition, not all newspapers have editions. An edition can refer to something much more specific, to do with geography (town papers versus country papers),
to do with size, to distinguish between multiple issues produced on the same day (morning versus evening editions), or to refer to issues published on different days, which 
might have different editors (notably the Sunday edition).
  
Although classifying editions might seem like a relatively straightforward point, the issues above muddy the waters significantly, and the decisions made as to what 
constitutes an ‘edition’ are often rendered invisible by the structure of digitised newspaper collections. Providers rarely digitise multiple editions; for example, 
the British Library’s Legal Deposit legislation in 1869 stipulated that a single issue is supplied per title, and this has generally been implemented by depositing 
the last edition of a newspaper for a specific day, if multiple editions exist (although in some cases these other editions may also be held by the library). 
In some collections of digitised newspapers, a Sunday variant of a newspaper is recorded as a separate title, breaking the link between the publications. 
This often makes sense: sometimes the publication has broken away from its parent title. But how do you record that break? When did it happen? And does the new 
publication still count as a Sunday ‘edition’, or is it now just a weekly paper?
  
Within the metadata samples in the *Atlas*, this variation is clear. Our edition metadata map includes numbered editions (“1” or “ed-1”); it also includes “Dag” 
(daily edition); (Friendship edition); “Special Edition”; and “Electronic ed.”. Because not all newspapers have these first categories of edition 
(numeric, indicating frequency, or indicating a one-off publication), the field is rare across collections. The final category, electronic edition, might seem 
redundant: if it’s indicating that this newspaper is digitised, perhaps our engagement with it through a database or XML file should be enough to remind us of that. 
Nonetheless, it serves an important function in reminding us of the role of “digital remediation” in engaging with digitised newspaper collections.
  
There are also more technical ‘maps’ such as starting column for the article and unique identifiers. It’s not aimed purely at historians or literary scholars, 
but designed to bring together the technical and the historical.
  
Another brief example: if you’re trying to find out if an article has been reprinted from a London newspaper, you might look at whether it goes over more than one page. 
As newspapers waited for the news from London before printing, they saved the inside pages of the newspaper for reprinted news and often cut and paste the articles in 
directly, known as scissors-and-paste journalism. By looking at the page count of the article in the metadata, you can begin to shape your historical research 
questions.
  
So the concluding question for this video which we would like you to consider before the workshop 
is: would this process of mapping work with your collections -- whether at your archive or library, or within the collections used for your research? Why/why not?
