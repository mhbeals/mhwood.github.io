---
layout: page
title: ZEFYS
subtitle: Staatsbibliothek zu Berlin, Germany
use-site-title: false
---

## History of the Collection

<img src="https://blog.sbb.berlin/wp-content/uploads/stabi-logo.png" width="258" height="65" align="right">[ZEFYS](http://zefys.staatsbibliothek-berlin.de) is a “creative acronym”
for the Newspaper Information System, which was expanded to serve as the
newspaper portal for the Berlin State Library (SBB). The SBB has the
largest and most extensive newspaper collection in Germany. In 1993 the
State Library of Berlin established its dedicated newspaper department,
the first such department in Germany. In addition to German newspapers,
the collection benefitted from funding from the Deutsche
Forschungsgemeinschaft (DFG) to facilitate the acquisition of newspapers
from abroad that were held in card catalogue form at the library. In
2009, the SBB launched its digitised newspaper portal ZEFYS. ZEFYS
currently gives access to 193 newspaper titles with roughly 7 million
pages overall.

## Consulted Libraries

Digitised newspapers published in ZEYFS typically stem from the
collection of the Staatsbibliothek zu Berlin. However, in some cases
there have also been collaborations with other libraries or archives to
digitise historical German newspapers from their holdings that are not
part of the SBB collection and to make them available through ZEFYS,
including some newspapers from former German colonies. The *Deutsches
Nachrichtenbüro*, for example, was digitised in collaboration with the
University of California, Los Angeles. The British Library contributed
around 13,000 volumes, and the Federal Press and Information Office
provided 40,000 volumes and packages.

## Preservation Projects

Newspapers have been included in the Prussian legal deposit regulations
since 1699, though it was not until 1824 that an amendment added a
specific provision for periodicals. During the mid-nineteenth century,
the library (then the Königliche Bibliothek, under the direction of
Friedrick Wilcken) expanded its holdings, making the newspaper
collection the most comprehensive in Germany. As a result of the
evacuations of the holdings during the Second World War, many items of
the newspaper collection suffered severe damage and loss. After the war,
the library (then the Deutsche Staatsbibliothek), received every
newspaper which was published in the German Democratic Republic via
legal deposit legislation. The holdings of the Preußische
Staatsbibliothek, which were evacuated to western parts of Germany
during the war, were the foundation of the Westdeutsche Bibliothek.
These collections form the basis of the modern newspaper department,
formed after reunification.

The library aims to make available microfilms of newspapers that are in
high demand or exposed to frequent use. In 1999 a reprographic company
was placed in a studio in the library’s Newspaper Department with
microfilming supported by the DFG and the conservation funds of the
Staatsbibliothek. The Berlin State Library generally digitises from
microfilm masters rather than from hard copy original. In addition to
the increased efficiency of digitisation, this also preserves the paper
originals and internal evaluations of its OCR have shown that there is
next to no quality loss when the microfilm master is used for image
capture. Preservation microfilming is still supported on a small scale
and the German Research Associate has mandated that the newly created
microfilm be listed in the ZDB catalogue.

## Digitisation Projects

In addition to the continuous digitisation of newspapers based on user
demand, the Berlin State Library carried out a number of specific
newspaper digitisation projects such as the “Amtspresse Preußens”, which
digitised the Prussian political press collection, “DDR Presse”, which
digitised three popular newspapers from the German Democratic Republic
(for reasons of copyright, these are only available after log-in), and
most recently the Europeana “Rise of Literacy” project, which digitised
the *Vossische* *Zeitung*.

## Selection

The primary driver behind digitisation at the Berlin State Library has
been user demand. In addition, the aim of the “Digitisation of the
Amtspresse Preußens” project was to create a collection of the most
influential political press of the last third of the nineteenth century,
together with a commentary and a search function.

## Preservation and Access

Microfilm is used as the main means for preservation of the Berlin State
Library newspaper collection. Hard copies that have been microfilmed are
not typically available for manual inspection and visitors are instead
directed to the microfilm. Digitisation is done mainly for reasons of
access, and digitised copies of newspapers do not constitute a
replacement of the microfilm masters for archiving purposes.

## Composition of the Collection

## Selection Available

ZEFYS provides access to 193 newspaper titles, or 311,234 issues,
between 1857 and 1939. The main focus of digitisation is on newspapers
from Berlin and its surroundings that were of national influence.
Highlights of the collection include early papers such as *Berlinische
Nachrichten* (founded 1740), foreign German-language papers such as
*Deutsche La Plata-Zeitung*, and Russian-language papers published in
Berlin. A full list of titles can be found on the [ZEFYS website](http://zefys.staatsbibliothek-berlin.de/index.php?id=list).

## Data Quality

## Text

Only about 50% of the digitised newspapers available in ZEFYS have been
processed with OCR. Currently, the OCR text is neither used for full
text search nor displayed in ZEFYS. There are plans to integrate the
digitised newspapers in ZEFYS with the main presentation platform for
digitised collections at the Berlin State Library and, as part of this,
implement full text search and display.

The quality of the OCR that does exist varies between 70-80% word
accuracy, with newspapers in Fraktur typically having somewhat lower
accuracy than those printed in Antiqua. In the past, OCR processing was
done using ABBYY FineReader 10 and 11 because of its layout segmentation
performance, which is much better than that delivered by open source OCR
engines for historic newspaper layouts.

## Images

Images are captured with 300 PPI and 8-bit colour (greyscale) in TIFF
format with 90% JPEG compression. This slightly decreases file size
without negative effects for OCR/OLR processing or viewing images on the
web.

## Metadata Schema 

For the digitised newspapers, the Berlin State Library follows the
METS/MODS profile for digitised newspapers, established in collaboration
with the [German Digital Library](https://wiki.deutsche-digitale-bibliothek.de/display/DFD/Anwendungsprofile+und+Best+Practice+Guides\#AnwendungsprofileundBestPracticeGuides-GesamtaufnahmeeinerZeitung).
ALTO is used to store the OCR full text.

## Backend Structure

Digitised newspapers are organised by title, with subdirectories for
year and date of issue. In the case of multiple editions on a single
day, issues are separated by unique identifiers.

## User Interface Structure

## Web Interface

The ZEFYS portal allows users to search and access the digitised
newspapers by title and date of the issue. Titles can be browsed by year
and country of publication.

## API

The Berlin State Library provides an API for the digitised newspapers,
which allows retrieval of images, full text and metadata. It is
documented at [https://lab.sbb.berlin/5393/?lang=en](https://lab.sbb.berlin/5393/?lang=en).

## Direct Download or Drives

Currently, the API is the only way to bulk-download digitised newspapers
from ZEFYS. On request, full exports of images, full text and metadata
can be provided via external hard disk.

## Rights and Usage

## Web Interface

The title-level metadata displayed in ZEFYS provides information about
the rights and usage for each newspaper.

## Re-Publication

All digitised newspapers assembled in ZEFYS are dedicated to the public
domain. Specific terms of use apply for the sub-collections “Amtspresse
Preußens” and “DDR Presse”.
