---
layout: page
title: How to Contribute
subtitle:  
use-site-title: false
---

The *Atlas of Digitised Newspapers and Metadata* is the result of the two-year project *Oceanic Exchanges*. Now that the project has concluded, we are hoping that you, the GLAM, digital humanities and periodical studies community will help develop and expand our initial work. In order to ensure consistency and robustness of the information, we ask that you contribute to the *Atlas* using the procedures listed below.  If you have any questions, or want to discuss a possible addition more informally, feel free to contact [Melodee Beals](m.h.beals@lboro.ac.uk) or [Emily Bell](e.bell@lboro.ac.uk).

## Simple Edits

### I found a typo!

### I want to add a link or clarification

## Database Histories

### Building a new Database History

### Updating an existing Database History

## Metadata Maps
If you have, or can request, sample metadata from a digitised newspaper collection, we encourage you to add it to the *Atlas*. We also welcome corrections and additions. 
  
The first step when adding a new instantiation is to map the relationships between the metadata elements and attributes using your sample file. 
  
Assigning an **NUID** (starting after the highest number in our [existing dataset]( https://figshare.com/articles/Full_Map_of_Digitised_Newspaper_Metadata/11560110)), enter a new line for every element and attribute in the metadata sample. Even repeated fields (such as @ID) should be filled separately **where they contain different information**. If the same field is used but with different attributes, this can be indicated in the XPath with square brackets, for example:
> mets:mets\mets:dmdSec\mets:mdWrap\mets:xmlData\mods:mods\mods:name[@type="personal"]\mods:role\mods:namePart@
  
Assign a **collection ID** (which is usually a 4-character abbreviation of the database name, followed by the type of file e.g. PPAL is Papers Past ALTO). When recording **XPaths**, ensure attributes are indicated by an @ symbol and record the name of the field itself separately under **Name**. Record the **format** as accurately as possible for each field (e.g. even if it is a METS file, it might use MIX or another XML standard for specific elements).  
  
**Content types** are as follows: 
  
| BOO | A Boolean char such as 0/1 or Y/N  |
| COO | A set of numeric coordinates to delineate a segment of an image |
| DAT | A single date  |
| DAR | A range of dates  |
| FIN | A filename  |
| STR | An open-ended string of content (alphanumeric)  |
| MCH | Multiple pre-defined choices  |
| NUL | Holds no content; used as a container element for other fields  |
| NUM | Numeric value; may include the symbols . , -  |
| UID | Any form of unique ID or acronym  |
| URL | A url  |
    
**Example content** should be copied and pasted from the sample metadata. Where a whole article is contained in one field, this should be truncated. **Multiple choice values** should be included in a separate column, as found in metadata documentation or inferred from the metadata sample. Once these fields are defined, you can fill out the **Category** and **Sub-Category**. Please use the categories from our *Atlas*, unless mapping something that does not already have an entry. The categories are the main entry titles, and sub-categories are indicated under Instantiations where applicable.
  
**Definition** information should be succinct and consistent with other fields of the same type across the dataset: please do look at existing definitions for your category of field. Many archives include downloadable documentation on their websites which explain the fields. Otherwise, the Library of Congress maintains many of the standards commonly used, and sources can be found in our [bibliography](https://www.digitisednewspapers.net/introduction/bibliography/). 
  
There are three **field types**: mappable data, containers, and technical data. Technical data refers to namespace information and other data that is not likely to be of interest to researchers. Containers are fields that do not directly hold any data themselves. Fields containing data should otherwise be categorised as mappable data. **Element type** is either XML_ELEMENT, XML_ATTRIBUTE or directory_structure_layer. 

**Parent**, **Attributed**, **Child(ren)** and **Attributes** should be used to create a hierarchy of the fields using the NUIDs. Starting with the root element, please indicate which elements are nested under others by using the Parent and Children columns, separating entries with a comma. For attributes, please ensure the field is filled out in both directions (indicating both the element that has attributes, and for the attribute which element it belongs to). For example:

| **NUID**  | **Xpath**  | **Name**  | **Parent**  | **Attributed**  | **Child(ren)**  | **Attributes**  |
| -- | -- | -- | -- | -- | -- | -- |
| 43  | issue\article\text\text.title\p\  | wd  | 40 |  |  | 44  |
| 44  | issue\article\text\text.title\p\wd\@  | pos  |  | 43 |  |   |
| 45  | issue\article\text\text.cr\  | pg  | 38 |  | 46 | 47, 48, 49  |
    
### Updating existing maps
Once the above process has been completed, fields that map to existing categories and sub-categories should be added to the appropriate map. Please use our existing headings.
  
**Category Notes** should be used to link to URIs for the field type or make general comments about the fields. If you are only adding instantiations from one collection, it is unlikely that you will need to make significant changes to this section.
  
**Individual Collection Notes** is a heading for you to add any quirks of the data from your new collection, such as inconsistencies when compared with our other collections, and multiple choice options. 
  
Under **Instantiations**, please add the collection ID, XPath, content type and sample content.
  
Please also add your new [collection ID](https://www.digitisednewspapers.net/maps/) to the introductory page. 

### Building a new map
If you find a field that does not already have a category or sub-category, please create a new map under [http://atlasofdigitisednewspapers.github.io/maps/](http://atlasofdigitisednewspapers.github.io/maps/) as \[chosen-title.md\]. It should also be added to the relevant index ([Content](https://www.digitisednewspapers.net/maps/content/), [Citation](https://www.digitisednewspapers.net/maps/citation/), [Bibliographic](https://www.digitisednewspapers.net/maps/bibliographic/), [Holdings](https://www.digitisednewspapers.net/maps/holdings/), [Descriptive](https://www.digitisednewspapers.net/maps/descriptive), [User-Generated](https://www.digitisednewspapers.net/maps/social/), [Technical](https://www.digitisednewspapers.net/maps/technical/)).
  
**Technical Definition** should contain the broadest description of the category. It might indicate whether this is generally a field taken from a MARC record, or as printed on the object, etc. It should cross-reference other categories where appropriate by linking to the relevant page, to show how it is distinct from existing entries. 
  
As described above, **Category Notes** should be used to make general comments such as how common the field is, and **Individual Collection Notes** should provide more specific detail about the collections, such as multiple choice options and pertinent information from the documentation.
  
**Instantiations** can be divided into sub-categories where sensible, marked with a section heading. Collection ID, XPath, content type and sample content should be included in the table.
  
Ensure you list the new [collection ID](https://www.digitisednewspapers.net/maps/) on the overview page, indicating format and file type. 

#### A new version of a static dataset

If the database periodically releases new version, but the older versions still exist.

#### Changes to a dynamic static set

If the database updates on a periodic or rolling basis and replaces older versions

## Glossary Entries

### Updating an existing glossary entry  
The glossary entries are intended to provide a short literature review of each term 'in the wild', as well as an account of how it was understood in the nineteenth century. We also welcome additional language variants, usage notes and examples to our existing entries. 
  
For **language variants**, please simply add the term alongside the existing variants.
  
**Usage notes** encompasses both the history of the term and its use in digitised newspaper collections. When adding information to this section, please also add any sources to our [bibliography](https://www.digitisednewspapers.net/introduction/bibliography/) using MLA style. We especially welcome historical information concerning the development of the newspaper in non-Anglophone countries. Please ensure these usage notes are focused on the nineteenth century newspaper. 
  
We are particularly interested to record variant terms and their use (for example, frequency versus periodicity) and more granular detail (such as the distinctions between daily, weekly, and monthly publications). These alternate terms can also be added to the [glossary index](https://www.digitisednewspapers.net/glossary/). 
  
### Creating a new entry  
We welcome new entries in our glossary. The glossary is not meant to be an exhaustive guide to newspaper history and layout as there is a wealth of scholarly literature on this subject, but should be tied to what is present in the metadata.
  
Please create a new glossary entry under [http://atlasofdigitisednewspapers.github.io/glossary/](http://atlasofdigitisednewspapers.github.io/glossary/) as \[chosen-title.md\]. 
  
Ensure you also add the new entry to AtlasOfDigitisedNewspapers.github.io/glossary/index.md as a link, so that it is visible on the [glossary page](https://www.digitisednewspapers.net/glossary/).
  
**Language Variants**  
For content, citation, bibliographic and holdings metadata, we aim to include language variants representing the countries we have worked with on the project (Dutch, Finnish, German, Spanish). Please feel free to include other languages. These variants should be verified with reference to the literature rather than drawn from a translation tool.
  
**Usage Notes**  
This section should include relevant information about the entry's evolution in the nineteenth century, and what term(s) would have been understood by contemporaries. For those based on layout terminology, please provide a specific description that makes it clear what is being referred to. You may also want to include relevant detail from the history of digitisation itself, where applicable.  Please link your glossary entry to the corresponding [metadata map](https://www.digitisednewspapers.net/maps/). 
  
**Examples**  
These can be drawn from nineteenth-century primary sources, but should primarily focus on how periodicals researchers, historians, digitisers, archivists and library scientists have used the term. Please add any new sources to our [bibliography](https://www.digitisednewspapers.net/introduction/bibliography/) using MLA referencing.
  
## Resources, Tools and Example Projects

### Resources

For written or visual resources discussing or aiding the use of digitised newspapers and metadata

### Tools

For scripts or other tools to manipulate or make use of digitised newspaper databases

### Example Projects

External projects using digitised newspaper data

 

