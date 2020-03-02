---
layout: page
title: How to Contribute
subtitle:  Simple Edits
use-site-title: false
---

### Additional details 

If you would like to add a clarification (e.g. explaining a term, adding in a new key date in a database history, expanding on a point in a metadata map or glossary entry), please go to the relevant file and make the change directly. Please specify in the commit what the change is and submit a pull request. We will review and approve the submitted request.

<a name="typos"></a>
### Links

We welcome new links to other relevant pages in the *Atlas*, other URIs for fields, and documentation pertaining to the collections we have analysed. If you would like to add a new external [Resource](https://www.digitisednewspapers.net/introduction/web/), please see the relevant sections at the bottom of this page.  
  
Adding links in markdown is very easy. Just surround your chosen term with square brackets, and put the link in brackets immediately after.  
>    \[Like this\](link)


<a name="database_histories"></a>
### Typographical errors

Thank you for spotting it! Please find the relevant page on our [GitHub](https://github.com/AtlasOfDigitisedNewspapers/AtlasOfDigitisedNewspapers.github.io) (in the folders as indicated on our [How to Contribute page](https://www.digitisednewspapers.net/contribute/)) and fix it directly, indicating in the commit what the change is, and submit a pull request. We will review and approve corrections.

### Updating an existing Database History

Over the course of time, databases evolve, and we want to reflect this in our histories. The areas you will most likely wish to update in an existing database history are its history, its composition and its technical or access details.

#### History

We have attempted to provide an overview of each collection's history, in chronological order. This includes sub-projects that have led to or contributed to the main database, as well as major changes to its objectives, funding or governance. If you have additional information regarding these factors, please add it to the relevant markdown file, listed under the sub-directory 'histories', and submit a pull request. 

#### Composition

If a database has removed a selection of titles or dates or has discontinued use of materials from a particular source, please replace the current information with a note that the material was previously included, but has since been removed, rather than simply delete the original information. If you feel the selection was never available, and has been included in error, please delete the relevant lines and indicate this in your pull request.

#### Technical Details

If a database has altered their technical specifications, backend structure or metadata schema, rather than replace the existing information, please indicate the new technical information by *adding a new sub-section to the relevant sub heading*.  For an example of this, see the [British Library 19th Century Newspapers](../../histories/bl.md) entry:

	### Metadata Schema

	The data contained within the British Library Newspapers is available
	under three distinct metadata schemes: two provided by Gale and one held
	for project work by the British Library.

	#### Gale Legacy Text Mining Drives

	Before 2016, the Gale Text Mining Drive contained metadata and text
	content in a single XML file. Although similar in coverage to the
	METS/ALTO schema used [...]

	#### Gale Current Text Mining Drives

	After 2016, the Gale Text Mining Drive separated metadata and text
	content into three XML files: title or publication-level metadata,
	issue-level metadata, and issue-level content data [...]

	#### British Library Project Drives

	A pre-processed version of the data is held by British Library Labs and
	has been used by BL Labs Competition winners and award recipients in
	supported projects. [...]

<a name="glossary_entries"></a> 

In the case of changes to the user interface or access requirements, please *replace* the existing information in these sub-sections.

### Updating an existing glossary entry  

<a name="resources"></a> 

The glossary entries are intended to provide a short literature review of each term 'in the wild', as well as an account of how it was understood in the nineteenth century. We also welcome additional language variants, usage notes and examples to our existing entries. 
  
For **language variants**, please simply add the term alongside the existing variants.
  
**Usage notes** encompasses both the history of the term and its use in digitised newspaper collections. When adding information to this section, please also add any sources to our [bibliography](https://www.digitisednewspapers.net/introduction/bibliography/) using MLA style. We especially welcome historical information concerning the development of the newspaper in non-Anglophone countries. Please ensure these usage notes are focused on the nineteenth-century newspaper rather than modern newspapers. 
  
We are particularly interested to record variant terms and their use (for example, frequency versus periodicity) and more granular detail (such as the distinctions between daily, weekly, and monthly publications). These alternate terms can also be added to the [glossary index](https://www.digitisednewspapers.net/glossary/). 
 
## Resources
 
We hope the *Atlas* will be a place for users to learn not only about digitised newspaper collections and metadata but also about other [resources](https://www.digitisednewspapers.net/introduction/web/) — particularly (but not exclusively) scripts and tools that have used our guide or dataset. You are very welcome to add links to the following sections on our resources page:

### Example Projects

External projects using digitised newspaper data. Please provide a short summary of the project (3-5 lines) and a link to a relevant website.

### Tools

Scripts or other tools to manipulate or make use of digitised newspaper databases. Please include a few words to explain what the tool does, including what data it uses and what it outputs, as well as a link to the relevant website or Github repository.
  
### Resources

Written or visual resources discussing or aiding the use of digitised newspapers and metadata. Please provide a short summary as well as a link to the resource.
