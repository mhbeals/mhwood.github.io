---
layout: post
title: How to Contribute
subtitle:  
use-site-title: false
---
<p>The <em>Atlas of Digitised Newspapers and Metadata</em> is the result of the two-year project <em>Oceanic Exchanges</em>. Now that the project has concluded, we are hoping that you, the GLAM, digital humanities and periodical studies community will help develop and expand our initial work. In order to ensure consistency and robustness of the information, we ask that you contribute to the <em>Atlas</em> using the procedures listed below.  If you have any questions, or want to discuss a possible addition more informally, feel free to contact <a href="/AtlasOfDigitisedNewspapers/AtlasOfDigitisedNewspapers.github.io/blob/master/introduction/m.h.beals@lboro.ac.uk">Melodee Beals</a> or <a href="/AtlasOfDigitisedNewspapers/AtlasOfDigitisedNewspapers.github.io/blob/master/introduction/e.bell@lboro.ac.uk">Emily Bell</a>.</p>

<p><strong>All updates should be written in markdown, following <a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet">GitHub's guidelines</a>.</strong></p>
<h2><img src="../../img/pointinghand.png" width="50" style="margin:0px 20px 0px 0px"><a id="user-content-simple-edits" class="anchor" aria-hidden="true" href="#simple-edits"></a>Simple Edits</h2>

<p>To make changes, please go to our <a href="https://github.com/AtlasOfDigitisedNewspapers/AtlasOfDigitisedNewspapers.github.io">GitHub</a> and submit a pull request. <a href="https://www.digitisednewspapers.net/histories/" rel="nofollow">Database histories</a> can be found in the 'histories' folder. <a href="https://www.digitisednewspapers.net/maps/" rel="nofollow">Metadata maps</a> can be found in the 'maps' folder. <a href="https://www.digitisednewspapers.net/glossary/" rel="nofollow">Glossary entries</a> can be found in the 'glossary' folder. All other pages (including the bibliography, timeline, resources and all the information under About) can be found in the 'introduction' folder.</p>
<details>
  <summary><b>Typographical Errors</b></summary>

<p>Thank you for spotting it! Please find the relevant page on our <a href="https://github.com/AtlasOfDigitisedNewspapers/AtlasOfDigitisedNewspapers.github.io">GitHub</a> (in the folders as indicated above) and fix it directly, indicating in the commit what the change is, and submit a pull request. We will review and approve corrections.</p>
</details>
  
<details>
  <summary><b>Links</b></summary>

<p>We welcome new links to other relevant pages in the <em>Atlas</em>, other URIs for fields, and documentation pertaining to the collections we have analysed. If you would like to add a new external <a href="https://www.digitisednewspapers.net/introduction/web/" rel="nofollow">Resource</a>, please see the relevant sections at the bottom of this page.</p>

<p>Adding links in markdown is very easy. Just surround your chosen term with square brackets, and put the link in brackets immediately after.</p>
<blockquote>

<p>[Like this](link)</p>
</blockquote>

<p>If you would like to add a clarification (e.g. explaining a term, adding in a new key date in a database history, expanding on a point in a metadata map or glossary entry), please go to the relevant file (in the folders indicated above) and make the change directly. Please specify in the commit what the change is and submit a pull request. We will review and approve the submitted request.</p>
</details>
<h2><img src="../../img/pointinghand.png" width="50" style="margin:0px 20px 0px 0px"><a id="user-content-database-histories" class="anchor" aria-hidden="true" href="#database-histories"></a>Database Histories</h2>
<details>
  <summary><b>Building a new Database History</b></summary>
</details>
  
<details>
  <summary><b>Updating an existing Database History</b></summary>
</details> 
<h2><img src="../../img/pointinghand.png" width="50" style="margin:0px 20px 0px 0px"><a id="user-content-metadata-maps" class="anchor" aria-hidden="true" href="#metadata-maps"></a>Metadata Maps</h2>

<p>If you have, or can request, sample metadata from a digitised newspaper collection, we encourage you to add it to the <em>Atlas</em>. We also welcome corrections and additions.</p>
<details>
  <summary><b>Inputting Metadata Information</b></summary>

<p>The first step when adding a new instantiation is to map the relationships between the metadata elements and attributes using your sample file. If you are using Excel or any other spreadsheet software, ensure you can save as a .tsv file and ensure your headings correspond to <a href="https://figshare.com/articles/Full_Map_of_Digitised_Newspaper_Metadata/11560110" rel="nofollow">our dataset</a>.</p>

<p>Assigning an <strong>NUID</strong> (starting after the highest number in our <a href="https://figshare.com/articles/Full_Map_of_Digitised_Newspaper_Metadata/11560110" rel="nofollow">existing dataset</a>), enter a new line for every element and attribute in the metadata sample. Even repeated fields (such as <a href="https://www.digitisednewspapers.net/maps/id/" rel="nofollow">@ID</a>) should be filled separately <strong>where they contain different kinds of information</strong> (e.g. @ID might be a newspaper ID, an issue ID, or an article ID). If the same field is used but with different attributes, this can be indicated in the XPath with square brackets, for example:</p>
<blockquote>

<p>mets:mets\mets:dmdSec\mets:mdWrap\mets:xmlData\mods:mods\mods:name[@type="personal"]\mods:role\mods:namePart@</p>
</blockquote>

<p>Assign a <strong>collection ID</strong> (which should be a 2-character abbreviation of the database name, followed by a 2-character abbreviation of the type of file e.g. PPAL for Papers Past ALTO). When recording <strong>XPaths</strong>, ensure attributes are indicated by an @ symbol and record the name of the field itself separately under <strong>Name</strong>. Record the <strong>format</strong> as accurately as possible for each field (e.g. even if it is a METS file, it might use MIX or another XML standard for specific elements).</p>

<p><strong>Content types</strong> are as follows:</p>

<p>| BOO | A <strong>Boolean</strong> char such as 0/1 or Y/N  |
| COO | A set of numeric <strong>coordinates</strong> to delineate a segment of an image |
| DAT | A single <strong>date</strong>  |
| DAR | A <strong>range</strong> of dates  |
| FIN | A <strong>filename</strong>  |
| STR | An open-ended <strong>string</strong> of content (alphanumeric)  |
| MCH | <strong>Multiple choices</strong> (pre-defined)  |
| NUL | Holds no content; used as a <strong>container</strong> element for other fields  |
| NUM | <strong>Numeric</strong> value; may include the symbols . , -  |
| UID | Any form of unique <strong>ID</strong> or acronym  |
| URL | A <strong>URL</strong>  |</p>

<p><strong>Example content</strong> should be copied from the sample metadata. Where a whole article is contained in one field, this should be truncated. <strong>Multiple choice values</strong> should be included in a separate column, as found in metadata documentation or inferred from the metadata sample. Once these fields are defined, you can fill out the <strong>Category</strong> and <strong>Sub-Category</strong>. Please use the categories from our <em>Atlas</em>, unless mapping something that does not already have an entry. The categories are the main entry titles, and sub-categories are indicated under Instantiations where applicable.</p>

<p><strong>Definition</strong> information should be succinct and consistent with other fields of the same type across the dataset: please do look at existing definitions for your category of field. Many archives include downloadable documentation on their websites which explain the fields. Otherwise, the Library of Congress maintains many of the standards commonly used, and sources can be found in our <a href="https://www.digitisednewspapers.net/introduction/bibliography/" rel="nofollow">bibliography</a>.</p>

<p>There are three <strong>field types</strong>: mappable data, containers, and technical. Technical data refers to namespace information and other data that is not likely to be of interest to researchers. Containers are elements that do not directly hold any data themselves. Fields containing data should otherwise be categorised as mappable data. <strong>Element type</strong> is either XML_ELEMENT, XML_ATTRIBUTE or directory_structure_layer.</p>

<p><strong>Parent</strong>, <strong>Attributed</strong>, <strong>Child(ren)</strong> and <strong>Attributes</strong> should be used to create a hierarchy of the fields using the NUIDs. Starting with the root element, please indicate which elements are nested under others by using the Parent and Children columns, separating entries with a comma. For attributes, please ensure the field is filled out in both directions (indicating both the element that has attributes, and for the attribute which element it belongs to). For example:</p>
<table>
<thead>
<tr>
<th><strong>NUID</strong></th>
<th><strong>Xpath</strong></th>
<th><strong>Name</strong></th>
<th><strong>Parent</strong></th>
<th><strong>Attributed</strong></th>
<th><strong>Child(ren)</strong></th>
<th><strong>Attributes</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>43</td>
<td>issue\article\text\text.title\p\</td>
<td>wd</td>
<td>40</td>
<td></td>
<td></td>
<td>44</td>
</tr>
<tr>
<td>44</td>
<td>issue\article\text\text.title\p\wd@</td>
<td>pos</td>
<td></td>
<td>43</td>
<td></td>
<td></td>
</tr>
<tr>
<td>45</td>
<td>issue\article\text\text.cr\</td>
<td>pg</td>
<td>38</td>
<td></td>
<td>46</td>
<td>47, 48, 49</td>
</tr>
</tbody>
</table>
</details>
  
<details>
  <summary><b>Updating Existing Metadata Maps</b></summary>

<p>Once the above process has been completed, fields that map to existing categories and sub-categories should be added to the appropriate map. Please use our existing headings.</p>

<p><strong>Category Notes</strong> should be used to link to URIs for the field type or make general comments about the fields. If you are only adding instantiations from one collection, it is unlikely that you will need to make significant changes to this section.</p>

<p><strong>Individual Collection Notes</strong> is a heading for you to add any quirks of the data from your new collection, such as inconsistencies when compared with our other collections, and multiple choice options.</p>

<p>Under <strong>Instantiations</strong>, please add the collection ID, XPath, content type and sample content.</p>

<p>Please also add your new <a href="https://www.digitisednewspapers.net/maps/" rel="nofollow">collection ID</a> to the introductory page.</p>
</details>
  
<details>
  <summary><b>Building a New Map</b></summary>

<p>If you find a field that does not already have a category or sub-category that is of use to researchers, please create a new map under <a href="http://atlasofdigitisednewspapers.github.io/maps/" rel="nofollow">http://atlasofdigitisednewspapers.github.io/maps/</a> as [chosen-title.md].</p>

<p>The standard map entry is as follows:</p>
<details>
  <summary><b>Map page template</b></summary>
<pre><code>---
layout: map
title: [Title]
subtitle:  
use-site-title: false
---

&lt;h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"&gt;&lt;a href="../../glossary/[filename.md]"&gt;View Glossary Entry&lt;/a&gt;&lt;/h4&gt;

## Technical Definition

## Category Notes

## Individual Collection Notes

## Instantiations

### [Sub-Category Title]
 
| [Collection ID]  |  [XPath including element/attribute name] | [Content type] | [Example content] |
</code></pre>
</details>

<p>It should also be added to the relevant index (<a href="https://www.digitisednewspapers.net/maps/content/" rel="nofollow">Content</a>, <a href="https://www.digitisednewspapers.net/maps/citation/" rel="nofollow">Citation</a>, <a href="https://www.digitisednewspapers.net/maps/bibliographic/" rel="nofollow">Bibliographic</a>, <a href="https://www.digitisednewspapers.net/maps/holdings/" rel="nofollow">Holdings</a>, <a href="https://www.digitisednewspapers.net/maps/descriptive" rel="nofollow">Descriptive</a>, <a href="https://www.digitisednewspapers.net/maps/social/" rel="nofollow">User-Generated</a>, <a href="https://www.digitisednewspapers.net/maps/technical/" rel="nofollow">Technical</a>).</p>

<p><strong>Technical Definition</strong> should contain the broadest description of the category. It might indicate whether this is generally a field taken from a MARC record, or as printed on the object, etc. It should cross-reference other categories where appropriate by linking to the relevant page, to show how it is distinct from existing entries.</p>

<p>As described above, <strong>Category Notes</strong> should primarily be used to make general comments such as how common the field is, and <strong>Individual Collection Notes</strong> should provide more specific detail about the collections, such as multiple choice options and pertinent information from the documentation.</p>

<p><strong>Instantiations</strong> can be divided into sub-categories where sensible, marked with a section heading. Collection ID, XPath, content type and sample content should be included in the table. These sub-categories should also be indicated in the dataset.</p>

<p>Ensure you list the new <a href="https://www.digitisednewspapers.net/maps/" rel="nofollow">collection ID</a> on the overview page, indicating format and file type.</p>
</details>
  
<details>
  <summary><b>Upload Changes to the Dynamic Data Set</b></summary>

<p>Please update the cells in a clearly delimited batch (i.e. do one set at a time, rather than lots of different types of update/additions) and send to us as a pull request. We will review the changes and either accept or send comments back for revisions.</p>
</details>
<h2><img src="../../img/pointinghand.png" width="50" style="margin:0px 20px 0px 0px"><a id="user-content-glossary-entries" class="anchor" aria-hidden="true" href="#glossary-entries"></a>Glossary Entries</h2>

<p>If you work with a particular aspect of newspaper history or otherwise have an in-depth knowledge of it, we encourage you to add a glossary entry for it to the <em>Atlas</em>. We also welcome corrections and additions.</p>
<details>
  <summary><b>Updating an Existing Glossary Entry</b></summary>

<p>The glossary entries are intended to provide a short literature review of each term 'in the wild', as well as an account of how it was understood in the nineteenth century. We also welcome additional language variants, usage notes and examples to our existing entries.</p>

<p>For <strong>language variants</strong>, please simply add the term alongside the existing variants.</p>

<p><strong>Usage notes</strong> encompasses both the history of the term and its use in digitised newspaper collections. When adding information to this section, please also add any sources to our <a href="https://www.digitisednewspapers.net/introduction/bibliography/" rel="nofollow">bibliography</a> using MLA style. We especially welcome historical information concerning the development of the newspaper in non-Anglophone countries. Please ensure these usage notes are focused on the nineteenth-century newspaper rather than modern newspapers.</p>

<p>We are particularly interested to record variant terms and their use (for example, frequency versus periodicity) and more granular detail (such as the distinctions between daily, weekly, and monthly publications). These alternate terms can also be added to the <a href="https://www.digitisednewspapers.net/glossary/" rel="nofollow">glossary index</a>.</p>
</details>  
    
<details>
  <summary><b>Creating a new entry</b></summary>

<p>We welcome new entries in our glossary. The glossary is not meant to be an exhaustive guide to newspaper history and layout as there is a wealth of scholarly literature on this subject, but should be tied to what is present in the metadata.</p>

<p>Please create a new glossary entry under <a href="http://atlasofdigitisednewspapers.github.io/glossary/" rel="nofollow">http://atlasofdigitisednewspapers.github.io/glossary/</a> as [chosen-title.md].</p>
<details>
  <summary><b>Glossary page template</b></summary>
<pre><code>---
layout: page
title: [Title]
subtitle:  
use-site-title: false
---

&lt;h4 style="text-align:center;font-style:italic;margin-top:-20px;margin-bottom:50px;"&gt;&lt;a href="../../maps/[filename.md]"&gt;View Metadata Map&lt;/a&gt;&lt;/h4&gt;

## Language Variants

## Usage Notes

## Examples

### [Sub-Type Examples]
</code></pre>
</details>

<p>Ensure you also add the new entry to <a href="http://atlasofdigitisednewspapers.github.io/glossary/" rel="nofollow">http://atlasofdigitisednewspapers.github.io/glossary/</a>index.md as a link (the entries are in alphabetical order), so that it is visible on the <a href="https://www.digitisednewspapers.net/glossary/" rel="nofollow">glossary page</a>.</p>

<p><strong>Language Variants</strong>  
For content, citation, bibliographic and holdings metadata, we aim to include language variants representing the countries we have worked with on the project (Dutch, Finnish, German, Spanish). Please feel free to include other languages. These variants should be verified with reference to the literature rather than drawn from a translation tool.</p>

<p><strong>Usage Notes</strong>  
This section should include relevant information about the entry's evolution in the nineteenth century, and what term(s) would have been understood by contemporaries. For those based on layout terminology, please provide a specific description that makes it clear what is being referred to. You may also want to include relevant detail from the history of digitisation itself, where applicable.  Please link your glossary entry to the corresponding <a href="https://www.digitisednewspapers.net/maps/" rel="nofollow">metadata map</a>.</p>

<p><strong>Examples</strong>  
These can be drawn from nineteenth-century primary sources, but should primarily focus on how periodicals researchers, historians, digitisers, archivists and library scientists have used the term. Please add any new sources to our <a href="https://www.digitisednewspapers.net/introduction/bibliography/" rel="nofollow">bibliography</a> using MLA referencing. A good starting point is <em><a href="https://muse.jhu.edu/journal/304" rel="nofollow">Victorian Periodicals Review</a></em> or the <em>Dictionary of Nineteenth-Century Journalism</em> (ed. Marysa Demoor and Laurel Brake, 2009) for historical uses, and published <a href="https://www.ifla.org/annual-conference/proceedings" rel="nofollow">IFLA proceedings</a> for archive and library science usage.</p>
</details>
<h2><img src="../../img/pointinghand.png" width="50" style="margin:0px 20px 0px 0px"><a id="user-content-resources-tools-and-example-projects" class="anchor" aria-hidden="true" href="#resources-tools-and-example-projects"></a>Resources, Tools and Example Projects</h2>

<p>We hope the <em>Atlas</em> will be a place for users not only to learn about digitised newspaper collections and metadata, but also  to find other <a href="https://www.digitisednewspapers.net/introduction/web/" rel="nofollow">resources</a> — particularly (but not exclusively) scripts and tools that have used our guide and/or dataset. You are very welcome to add links to the following:</p>
<details>
  <summary><b>Example Projects</b></summary>

<p>External projects using digitised newspaper data. Please provide a short summary of the project (3-5 lines).</p>
</details>
  
<details>
  <summary><b>Tools</b></summary>

<p>Scripts or other tools to manipulate or make use of digitised newspaper databases. Please include a few words to explain what the tool does.</p>
</details>
    
<details>
  <summary><b>Resources</b></summary>

<p>Written or visual resources discussing or aiding the use of digitised newspapers and metadata.</p>
</details>
