---
layout: page
title: How to Contribute
subtitle:  Metadata Maps
use-site-title: false
---

If you have, or can request, sample metadata from a digitised newspaper collection, we encourage you to add it to the *Atlas*. We also welcome corrections and additions. 
  
### <a name="new_db"></a>Mapping a New Database

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
    
### <a name="existing"></a>Updating Existing Maps
Once the above process has been completed, fields that map to existing categories and sub-categories should be added to the appropriate map. Please use our existing headings.
  
**Category Notes** should be used to link to URIs for the field type or make general comments about the fields. If you are only adding instantiations from one collection, it is unlikely that you will need to make significant changes to this section.
  
**Individual Collection Notes** is a heading for you to add any quirks of the data from your new collection, such as inconsistencies when compared with our other collections, and multiple choice options. 
  
Under **Instantiations**, please add the collection ID, XPath, content type and sample content.
  
Please also add your new [collection ID](https://www.digitisednewspapers.net/maps/) to the introductory page. 

### <a name="new"></a>Building a New Map
  
<b>Map page template</b>
  
    ---
    layout: map
    title: [Title]
    subtitle:  
    use-site-title: false
    ---
    
    <h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"></a><a href="../../glossary/[filename.md]">View Glossary Entry</h4>
    
    ## Technical Definition
    
    ## Category Notes
    
    ## Individual Collection Notes
    
    ## Instantiations
    
    ### [Sub-Category Title]
     
    | [Collection ID]  |  [XPath including element/attribute name] | [Content type] | [Example content] |


If you find a field that does not already have a category or sub-category that is of use to researchers, please create a new map under [http://atlasofdigitisednewspapers.github.io/maps/](http://atlasofdigitisednewspapers.github.io/maps/) as \[chosen-title.md\]. It should also be added to the relevant index ([Content](https://www.digitisednewspapers.net/maps/content/), [Citation](https://www.digitisednewspapers.net/maps/citation/), [Bibliographic](https://www.digitisednewspapers.net/maps/bibliographic/), [Holdings](https://www.digitisednewspapers.net/maps/holdings/), [Descriptive](https://www.digitisednewspapers.net/maps/descriptive), [User-Generated](https://www.digitisednewspapers.net/maps/social/), [Technical](https://www.digitisednewspapers.net/maps/technical/)).
  
**Technical Definition** should contain the broadest description of the category. It might indicate whether this is generally a field taken from a MARC record, or as printed on the object, etc. It should cross-reference other categories where appropriate by linking to the relevant page, to show how it is distinct from existing entries. 
  
As described above, **Category Notes** should primarily be used to make general comments such as how common the field is, and **Individual Collection Notes** should provide more specific detail about the collections, such as multiple choice options and pertinent information from the documentation.
  
**Instantiations** can be divided into sub-categories where sensible, marked with a section heading. Collection ID, XPath, content type and sample content should be included in the table. These sub-categories should also be indicated in the dataset. 
  
Ensure you list the new [collection ID](https://www.digitisednewspapers.net/maps/) on the overview page, indicating format and file type. 

#### Multiple Versions

For data from a database that periodically releases new versions, but the older versions still exist, please *add* rows in clearly delimited batches and send them to us as a pull request. We will review new submissions and either accept or send comments back for revisions. If the database updates on a periodic or rolling basis and replaces older versions, please *update* the existing cells in a clearly delimited batch (i.e. do one set at a time, rather than lots of different types of update/additions) and send to us as a pull request. We will review the changes and either accept or send comments back for revisions.
