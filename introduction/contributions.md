---
layout: page
title: How to Contribute
subtitle:  
use-site-title: false
---

The *Atlas of Digitised Newspapers and Metadata* is the result of the two-year project *Oceanic Exchanges*. Now that the project has concluded, we are hoping that you, the GLAM, digital humanities and periodical studies community will help develop and expand our initial work. In order to ensure consistency and robustness of the information, we ask that you contribute to the *Atlas* using the procedures listed below.  If you have any questions, or want to discuss a possible addition more informally, feel free to contact [Melodee Beals](m.h.beals@lboro.ac.uk) or [Emily Bell](e.bell@lboro.ac.uk).
  
**All updates should be written in markdown, following [GitHub's guidelines](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).**

## Simple Edits

To make changes, please go to our [GitHub](https://github.com/AtlasOfDigitisedNewspapers/AtlasOfDigitisedNewspapers.github.io) and submit a pull request. [Database histories](https://www.digitisednewspapers.net/histories/) can be found in the 'histories' folder. [Metadata maps](https://www.digitisednewspapers.net/maps/) can be found in the 'maps' folder. [Glossary entries](https://www.digitisednewspapers.net/glossary/) can be found in the 'glossary' folder. All other pages (including the bibliography, timeline, resources and all the information under About) can be found in the 'introduction' folder.

<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Typographical Errors</b></summary>
  
Thank you for spotting it! Please find the relevant page on our [GitHub](https://github.com/AtlasOfDigitisedNewspapers/AtlasOfDigitisedNewspapers.github.io) (in the folders as indicated above) and fix it directly, indicating in the commit what the change is, and submit a pull request. We will review and approve corrections.
</details>
</br>
<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Links</b></summary>
  
We welcome new links to other relevant pages in the *Atlas*, other URIs for fields, and documentation pertaining to the collections we have analysed. If you would like to add a new external [Resource](https://www.digitisednewspapers.net/introduction/web/), please see the relevant sections at the bottom of this page.  
  
Adding links in markdown is very easy. Just surround your chosen term with square brackets, and put the link in brackets immediately after.  
>    \[Like this\](link)
  
If you would like to add a clarification (e.g. explaining a term, adding in a new key date in a database history, expanding on a point in a metadata map or glossary entry), please go to the relevant file (in the folders indicated above) and make the change directly. Please specify in the commit what the change is and submit a pull request. We will review and approve the submitted request.
</details>

## Database Histories

<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Building a new Database History</b></summary>
  
</details>
<br/>
<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Updating an existing Database History</b></summary>
  
</details> 

## Metadata Maps
If you have, or can request, sample metadata from a digitised newspaper collection, we encourage you to add it to the *Atlas*. We also welcome corrections and additions. 

<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Inputting Metadata Information</b></summary>
   
The first step when adding a new instantiation is to map the relationships between the metadata elements and attributes using your sample file. If you are using Excel or any other spreadsheet software, ensure you can save as a .tsv file and ensure your headings correspond to [our dataset](https://figshare.com/articles/Full_Map_of_Digitised_Newspaper_Metadata/11560110).
  
Assigning an **NUID** (starting after the highest number in our [existing dataset]( https://figshare.com/articles/Full_Map_of_Digitised_Newspaper_Metadata/11560110)), enter a new line for every element and attribute in the metadata sample. Even repeated fields (such as [@ID](https://www.digitisednewspapers.net/maps/id/)) should be filled separately **where they contain different kinds of information** (e.g. @ID might be a newspaper ID, an issue ID, or an article ID). If the same field is used but with different attributes, this can be indicated in the XPath with square brackets, for example:
> mets:mets\mets:dmdSec\mets:mdWrap\mets:xmlData\mods:mods\mods:name[@type="personal"]\mods:role\mods:namePart@
  
Assign a **collection ID** (which should be a 2-character abbreviation of the database name, followed by a 2-character abbreviation of the type of file e.g. PPAL for Papers Past ALTO). When recording **XPaths**, ensure attributes are indicated by an @ symbol and record the name of the field itself separately under **Name**. Record the **format** as accurately as possible for each field (e.g. even if it is a METS file, it might use MIX or another XML standard for specific elements).  
  
**Content types** are as follows: 
  
| BOO | A **Boolean** char such as 0/1 or Y/N  |
| COO | A set of numeric **coordinates** to delineate a segment of an image |
| DAT | A single **date**  |
| DAR | A **range** of dates  |
| FIN | A **filename**  |
| STR | An open-ended **string** of content (alphanumeric)  |
| MCH | **Multiple choices** (pre-defined)  |
| NUL | Holds no content; used as a **container** element for other fields  |
| NUM | **Numeric** value; may include the symbols . , -  |
| UID | Any form of unique **ID** or acronym  |
| URL | A **URL**  |
    
**Example content** should be copied from the sample metadata. Where a whole article is contained in one field, this should be truncated. **Multiple choice values** should be included in a separate column, as found in metadata documentation or inferred from the metadata sample. Once these fields are defined, you can fill out the **Category** and **Sub-Category**. Please use the categories from our *Atlas*, unless mapping something that does not already have an entry. The categories are the main entry titles, and sub-categories are indicated under Instantiations where applicable.
  
**Definition** information should be succinct and consistent with other fields of the same type across the dataset: please do look at existing definitions for your category of field. Many archives include downloadable documentation on their websites which explain the fields. Otherwise, the Library of Congress maintains many of the standards commonly used, and sources can be found in our [bibliography](https://www.digitisednewspapers.net/introduction/bibliography/). 
  
There are three **field types**: mappable data, containers, and technical. Technical data refers to namespace information and other data that is not likely to be of interest to researchers. Containers are elements that do not directly hold any data themselves. Fields containing data should otherwise be categorised as mappable data. **Element type** is either XML_ELEMENT, XML_ATTRIBUTE or directory_structure_layer. 

**Parent**, **Attributed**, **Child(ren)** and **Attributes** should be used to create a hierarchy of the fields using the NUIDs. Starting with the root element, please indicate which elements are nested under others by using the Parent and Children columns, separating entries with a comma. For attributes, please ensure the field is filled out in both directions (indicating both the element that has attributes, and for the attribute which element it belongs to). For example:

| **NUID**  | **Xpath**  | **Name**  | **Parent**  | **Attributed**  | **Child(ren)**  | **Attributes**  |
| -- | -- | -- | -- | -- | -- | -- |
| 43  | issue\article\text\text.title\p\  | wd  | 40 |  |  | 44  |
| 44  | issue\article\text\text.title\p\wd\@  | pos  |  | 43 |  |   |
| 45  | issue\article\text\text.cr\  | pg  | 38 |  | 46 | 47, 48, 49  |
</details>
<br/>
<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Updating Existing Metadata Maps</b></summary>
  
Once the above process has been completed, fields that map to existing categories and sub-categories should be added to the appropriate map. Please use our existing headings.
  
**Category Notes** should be used to link to URIs for the field type or make general comments about the fields. If you are only adding instantiations from one collection, it is unlikely that you will need to make significant changes to this section.
  
**Individual Collection Notes** is a heading for you to add any quirks of the data from your new collection, such as inconsistencies when compared with our other collections, and multiple choice options. 
  
Under **Instantiations**, please add the collection ID, XPath, content type and sample content.
  
Please also add your new [collection ID](https://www.digitisednewspapers.net/maps/) to the introductory page. 
</details>
<br/>
<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Building a New Map</b></summary>
  
If you find a field that does not already have a category or sub-category that is of use to researchers, please create a new map under [http://atlasofdigitisednewspapers.github.io/maps/](http://atlasofdigitisednewspapers.github.io/maps/) as \[chosen-title.md\].

The standard map entry is as follows:

<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Map page template</b></summary>
  
    ---
    layout: map
    title: [Title]
    subtitle:  
    use-site-title: false
    ---
    
    <h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../glossary/[filename.md]">View Glossary Entry</a></h4>
    
    ## Technical Definition
    
    ## Category Notes
    
    ## Individual Collection Notes
    
    ## Instantiations
    
    ### [Sub-Category Title]
     
    | [Collection ID]  |  [XPath including element/attribute name] | [Content type] | [Example content] |
</details>

It should also be added to the relevant index ([Content](https://www.digitisednewspapers.net/maps/content/), [Citation](https://www.digitisednewspapers.net/maps/citation/), [Bibliographic](https://www.digitisednewspapers.net/maps/bibliographic/), [Holdings](https://www.digitisednewspapers.net/maps/holdings/), [Descriptive](https://www.digitisednewspapers.net/maps/descriptive), [User-Generated](https://www.digitisednewspapers.net/maps/social/), [Technical](https://www.digitisednewspapers.net/maps/technical/)).
  
**Technical Definition** should contain the broadest description of the category. It might indicate whether this is generally a field taken from a MARC record, or as printed on the object, etc. It should cross-reference other categories where appropriate by linking to the relevant page, to show how it is distinct from existing entries. 
  
As described above, **Category Notes** should primarily be used to make general comments such as how common the field is, and **Individual Collection Notes** should provide more specific detail about the collections, such as multiple choice options and pertinent information from the documentation.
  
**Instantiations** can be divided into sub-categories where sensible, marked with a section heading. Collection ID, XPath, content type and sample content should be included in the table. These sub-categories should also be indicated in the dataset. 
  
Ensure you list the new [collection ID](https://www.digitisednewspapers.net/maps/) on the overview page, indicating format and file type. 
</details>
<br/>
<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Upload Changes to the Dynamic Data Set</b></summary>

Please update the cells in a clearly delimited batch (i.e. do one set at a time, rather than lots of different types of update/additions) and send to us as a pull request. We will review the changes and either accept or send comments back for revisions.
</details>

## Glossary Entries

If you work with a particular aspect of newspaper history or otherwise have an in-depth knowledge of it, we encourage you to add a glossary entry for it to the *Atlas*. We also welcome corrections and additions. 

<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Updating an Existing Glossary Entry</b></summary>

The glossary entries are intended to provide a short literature review of each term 'in the wild', as well as an account of how it was understood in the nineteenth century. We also welcome additional language variants, usage notes and examples to our existing entries. 
  
For **language variants**, please simply add the term alongside the existing variants.
  
**Usage notes** encompasses both the history of the term and its use in digitised newspaper collections. When adding information to this section, please also add any sources to our [bibliography](https://www.digitisednewspapers.net/introduction/bibliography/) using MLA style. We especially welcome historical information concerning the development of the newspaper in non-Anglophone countries. Please ensure these usage notes are focused on the nineteenth-century newspaper rather than modern newspapers. 
  
We are particularly interested to record variant terms and their use (for example, frequency versus periodicity) and more granular detail (such as the distinctions between daily, weekly, and monthly publications). These alternate terms can also be added to the [glossary index](https://www.digitisednewspapers.net/glossary/). 
</details>  
<br/>  
<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Creating a new entry</b></summary>

We welcome new entries in our glossary. The glossary is not meant to be an exhaustive guide to newspaper history and layout as there is a wealth of scholarly literature on this subject, but should be tied to what is present in the metadata.
  
Please create a new glossary entry under [http://atlasofdigitisednewspapers.github.io/glossary/](http://atlasofdigitisednewspapers.github.io/glossary/) as \[chosen-title.md\]. 

<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Glossary page template</b></summary>
  
    ---
    layout: page
    title: [Title]
    subtitle:  
    use-site-title: false
    ---
    
    <h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"><a href="../../maps/[filename.md]">View Metadata Map</a></h4>
    
    ## Language Variants
    
    ## Usage Notes
    
    ## Examples
    
    ### [Sub-Type Examples]
     
</details>
  
Ensure you also add the new entry to [http://atlasofdigitisednewspapers.github.io/glossary/](http://atlasofdigitisednewspapers.github.io/glossary/)index.md as a link (the entries are in alphabetical order), so that it is visible on the [glossary page](https://www.digitisednewspapers.net/glossary/).
  
**Language Variants**  
For content, citation, bibliographic and holdings metadata, we aim to include language variants representing the countries we have worked with on the project (Dutch, Finnish, German, Spanish). Please feel free to include other languages. These variants should be verified with reference to the literature rather than drawn from a translation tool.
  
**Usage Notes**  
This section should include relevant information about the entry's evolution in the nineteenth century, and what term(s) would have been understood by contemporaries. For those based on layout terminology, please provide a specific description that makes it clear what is being referred to. You may also want to include relevant detail from the history of digitisation itself, where applicable.  Please link your glossary entry to the corresponding [metadata map](https://www.digitisednewspapers.net/maps/). 
  
**Examples**  
These can be drawn from nineteenth-century primary sources, but should primarily focus on how periodicals researchers, historians, digitisers, archivists and library scientists have used the term. Please add any new sources to our [bibliography](https://www.digitisednewspapers.net/introduction/bibliography/) using MLA referencing. A good starting point is *[Victorian Periodicals Review](https://muse.jhu.edu/journal/304)* or the *Dictionary of Nineteenth-Century Journalism* (ed. Marysa Demoor and Laurel Brake, 2009) for historical uses, and published [IFLA proceedings](https://www.ifla.org/annual-conference/proceedings) for archive and library science usage.
</details>

## Resources, Tools and Example Projects

We hope the *Atlas* will be a place for users not only to learn about digitised newspaper collections and metadata, but also  to find other [resources](https://www.digitisednewspapers.net/introduction/web/) — particularly (but not exclusively) scripts and tools that have used our guide and/or dataset. You are very welcome to add links to the following:

<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Example Projects</b></summary>

External projects using digitised newspaper data. Please provide a short summary of the project (3-5 lines).
</details>
<br/>
<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Tools</b></summary>

Scripts or other tools to manipulate or make use of digitised newspaper databases. Please include a few words to explain what the tool does.
</details>
<br/>  
<details>
  <summary><img src="../../img/pointinghand.png" width="50"> <b>Resources</b></summary>

Written or visual resources discussing or aiding the use of digitised newspapers and metadata.
</details>
