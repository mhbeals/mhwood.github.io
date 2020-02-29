---
layout: page
title: How to Contribute
subtitle:  Database Histories
use-site-title: false
---

With so many collections around the world, we appreciate efforts by the library, archive and scholarly community to keep the Atlas up to date and growing. Wwhile we appreciate and will accept contributions from both database providers and end-users, we ask that you include references or other provenance details (such as your role within the organisation) to the "pull request" message, so that we can better evaluate claims before integrating them into the *Atlas*. This is especially the case for details regarding policies, funding or governance.

### Updating an Existing Database History

Over the course of time, databases evolve, and we want to reflect this in our histories. The areas you will most likely wish to update in an existing database history are its history, its composition and its techincal or access details.

#### History

We have attempted to provide an overview of each collection's history, in chronological order. This includes sub-projects that have led to or contributed to the main database, as well as major changes to its objectives, funding or governance. If you have additional information regarding these factors, please add it to the relevant markdown file, listed under the sub-directory 'histories', and submit a pull request. 

#### Composition

If a database has removed a selection of titles or dates, or has discontinued use of materials from a particular source, please replace the current information with a note that the material was previously included, but has since been removed, rather than simply delete the original information. If you feel the selection was never available, and has been included in error, please delete the relevant lines and indicate this in your pull request.

#### Technical Details

If a database has altered their techincal specifications, backend structure or metadata schema, rather than replace the existing information, please indicate the new techincal information by *adding a new sub-section to the relevant sub heading*.  For an example of this, see the [British Libary 19th Century Newspapers](../../histories/bl.md) entry:

	### Metadata Schema

	The data contained within the British Library Newspapers is available
	under three distinct metadata schemes: two provided by Gale and one held
	for project work by the British Library.

	#### Gale Legacy Text Mining Drives

	Before 2018, the Gale Text Mining Drive contained metadata and text
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

In the case of changes to the user interface or access requirements, please *replace* the exisiting information in these sub-sections.

 <a name="new"></a>
 
### Building a New Database History

If you would like a new collection or database added to the *Atlas*, you will need to provide a fully referenced collection history, technical specifications, and interface and access information. To begin your entry, use the following history template:

<b>Database history template</b>
  
    ---
    layout: map
    title: [Name of Database]
    subtitle:  [Provider, Location of Database]
    use-site-title: false
    ---
    
	## History of the Collection
	
	[A brief 1-2 paragraph summary of the history of the collection, including its predecessor projects, its aims and objectives, its main funders and its governance structure. You may wish to include an inline logo for the collection]

	### Consulted Libraries
	
	[A semi-colon separated list of all the libraries or other organisations that contributed materials to the collection, whether in microfilm, hardcopy or digitised form]

	### Microfilming Projects
	
	[A brief history of the microfilming processes that have affected the selection and quality of the database]

	### Digitisation Projects
	
	[A brief history of the digitisation projects or development phases that contributed to the current database]

	#### Selection
	
	[A brief summary and history of the selection rationale for the collection, including the aims of funders or preceding projects as well as the role and composition of any selection advisory boards]

	#### Preservation and Access
	
	[A brief summary of the role of the digitised collection in terms of preservation and conservation as well as public or commercial access to the materials]

	## Composition of the Collection

	### Selection Available
	
	[A brief summary of the main contours of the collection in terms of chronology, geography, language, periodical type and major thematic sub-collections. This should give an indication of percentages as well as absolute numbers of titles, issues and pages in these catagories]

	### Data Quality

	#### Text

	[A brief summary of the quality of the text, namely the OCR or manually-corrected metadata and datafields within the database, and how this was gauged. This should attempt to give an overall indication of accuracy as well as discuss which parts of the collection (language, period, geography, time of digitisation) are likely to have better or worse than average accuracy ratings]

	#### Images
	
	[A brief summary of the filetypes and resolutions of the images in the database, both in the backend collection as well as those available through the user interface and direct download]

	### Metadata Schema
	
	[A summary of the metadata schemas employed by the collection in the data, metadata and structure files. Links to bespoke standards or documentation should be suplied if available]

	### Backend Structure
	
	[A summary of the backend file structure of the database, including an indication of the data (text or image) that is available, even if this is not accessible by end users. It should include file directory structures if possible]

	## User Interface Structure
	
	### Web Interface

	[A summary of the *current* web user interface. If no web interface is currently available, please indicate this rather than leaving this section blank or removing it]

	### API

	[A summary of the *current* API. If no API is currently available, please indicate this rather than leaving this section blank or removing it]

	### Direct Download or Drives

	[A summary of the structure of the *current* direct download packages or text-mining drives. If these are currently unavailable, please indicate this rather than leaving this section blank or removing it]

	## Rights and Usage
	
	[A general notice of the rights for scholarly, commercial and personal use of the materials and the accessibility of the collection to various end-users]

	### Web Interface
	
	[A brief summary of copyright and other terms of conditions of use for material obtained through the web interface]

	### API and Direct Download
	
	[A brief summary of copyright and other terms of conditions of use for material obtained through the API, direct downloads or text-mining drives]

	### Re-Publication
	
	[A brief summary, including links to relevant documentation or notices, on the ability of users to republish text or images from the collection for personal, scholarly and commerical purposes]
	
#### A Completed Entry

Once you have completed your entry, submit a pull request, placing a full bibliography in your pull request comment as well as by editing the [bibliography page](../../introduction/bibliography).

#### A Partial Entry	
	
It is important for the consistency of the *Atlas* that all sections be completed prior to publication. If you feel you can only provide information for a sub-section of the history, please begin the project and then post your contribution to [GitHub Issues](https://github.com/AtlasOfDigitisedNewspapers/AtlasOfDigitisedNewspapers.github.io/issues) so that other members of the community can contribute to or complete the entry.