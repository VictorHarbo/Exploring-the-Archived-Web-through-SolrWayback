# Programming Historian English Language Lesson Template

This file can be used as a template for writing your lesson. It includes information and guidelines on formatting which supplement but do not replace the author's guidelines (/en/author-guidelines)

## Some Important Reminders:

*	Tutorials should not exceed 8,000 words (including code).
*	Keep your tone formal but accessible.
*	Talk to your reader in the second person (you).
*	Adopt a widely-used version of English (British, Canadian, Indian, South African etc).
*	The piece of writing is a "tutorial" or a "lesson" and not an "article".
*  Adopt open source principles
*  Write for a global audience
*  Write sustainably

# Lesson Metadata

**Delete everything above this line when ready to submit your lesson**.

---
title: Exploring the Archived Web with SolrWayback  
collection: lessons  
layout: lesson  
authors:
- Victor Harbo Johnston 
---

# A Table of Contents

Include the following short code to automatically generate a table of contents for your lesson (mandatory).

{% include toc.html %}

--

## Some Markdown Formatting Examples:

# Lesson Aims
When readers have finished this lesson, they will be able to:
* Set up SolrWayback on their local computer
* Load data from the archived web into their SolrWayback instance
* Investigate and analyse the archived web through SolrWayback 

# Lesson Structure

The lesson is divided into four distinct sections: 
1. Introduction
2. Installation 
3. Indexing
4. Querying and Visualising

The introduction present some of the existing challenges of working with the archived web and how a tool as SolrWayback can mitigate the entry barrier for historians. The next two sections revolves around installing, starting and getting data into the software. Finally the lesson explores how the archived web can be investigated through SolrWayback. Furthermore this section provides insights into some of the build in visualisation tools of the software.

# Exploring the Archived Web with SolrWayback  

## Introduction

When institutions such as the Internet Archive (IA), the Royal Danish Library (RDL) or the Bibliothèque nationale de France (BnF) archives the internet, they store the data in [WARC-files](https://en.wikipedia.org/wiki/WARC_(file_format)).

## Installation

To get started with SolrWayback, the first thing you need to do is downloading the software from the SolrWayback Github page. The software can be installed in multiple ways, in this lesson you will install it through the bundle release version. To get started navigate to the [release page](https://github.com/netarchivesuite/solrwayback/releases) of SolrWayback and download version 5.2.1 (Newer versions will be released over time. 5.2.1 was the newest when this lesson was drafted. This guide will most likely work for newer versions as well).



## Indexing

## Querying and Visualising


### Font Formatting
**bold text**
*italic text*
`reserved words` (eg "for loop", or "myData.csv")

### Links

Create [a link to *Programming Historian*](/) using the format in this sentence. Ensure linked phrases are semantically meaningful. Do not link terms that are meaningful only to sighted users such as "click here".

### Inserting Images:

Copy this short-code to insert an image. Replace words in all caps with your image information (eg, Figure1.jpg). Captions should include sequential image numbering (eg "Figure 1: ..."). 

{% include figure.html filename="IMAGE-FILENAME" caption="CAPTION TO IMAGE" %}

### Alerts and Warnings

If you want to include an aside or a warning to readers, you can set it apart from the main text:

<div class="alert alert-warning">
 Be sure that you follow directions carefully!
</div>

It will appear in a coloured box and can be useful for drawing attention to particular warnings.


### Referencing

*	Links rather than endnotes may be appropriate in most cases.
*	Ensure linked phrases are semantically meaningful. Do not link terms that are meaningful only to sighted users such as "click here".
*	All traditionally published and academic literature should be end-noted rather than linked.
*	If you are writing an "analysis" tutorial, you must refer to published scholarly literature.
*	Endnote superscripts should be outside the final punctuation like this.[^1] Not inside like this[^1].
*	Use the "Notes and Bibliography" system found in the [The Chicago Manual of Style, 17th Edition](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-1.html) for endnotes.

#### An End Note:

This is some text.[^1]
This is some more text.[^2]

##### Endnotes
[^1]: Properly formatted citation using Chicago Manual of Style
[^2]: Properly formatted citation using Chicago Manual of Style
