---
title: "Open Authoring Tools"
teaching: 30
exercises: 20
---

::: questions
- What open authoring tools are available for writing scholarly articles?
- How can I create manuscripts using Markdown, LaTeX, or RMarkdown?
- How can open documents be converted to publisher-required formats like DOCX or PDF?
:::

::: objectives
- Describe collaborative, open authoring tools that can be used to write scholarly articles.
- Locate templates in Markdown and LaTeX that can be used to write a scholarly article.
- Understand what tools can convert open document formats to proprietary ones required by scholarly publications.
:::



## Overview

There are many collaborative authoring tools available today. DOC, DOCX, and PDF are the formats most commonly requested by scholarly publishers. Unfortunately, these formats are not open source. So how do we align our open science values with these constraints?

By using alternative, open authoring tools.

[AlternativeTo](https://alternativeto.net/) is a useful resource for discovering open-source or privacy-respecting alternatives to common proprietary tools.

## WYSIWYG Tools

If you prefer a *What-You-See-Is-What-You-Get* (WYSIWYG) editor, here are some common options:

- **Google Docs**: free but not open source.
- **LibreOffice**: free and open source — [feature comparison with Microsoft Office](https://wiki.documentfoundation.org/Feature_Comparison:_LibreOffice_-_Microsoft_Office)
- **Apache OpenOffice**: free and open source, though not regularly updated.

These tools support DOCX files and include features like collaboration and version history. However, they do not easily create semantically structured, machine-readable documents — a key goal for FAIR (Findable, Accessible, Interoperable, Reusable) outputs.

## WYSIWYM Tools

For semantic authoring, consider *What-You-See-Is-What-You-Mean* (WYSIWYM) formats such as:

### Markdown

Markdown is a plain text format with lightweight semantic markup.

You can write Markdown in any text editor and save the file with a `.md` extension. A good place to get started is:

- [CommonMark Tutorial (10 minutes)](https://commonmark.org/help/tutorial/)

#### Markdown Resources

- [PoisotLab manuscript template](https://github.com/PoisotLab/manuscript-template)
- [Markdown for Manuscripts](https://github.com/djhocking/Markdown-for-Manuscripts)
- [Sustainable authorship with Pandoc](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)
- [The Carpentries Markdown lesson](https://swcarpentry.github.io/modern-scientific-authoring/02-markdown/)

### RMarkdown

RMarkdown combines Markdown with embedded R code to create reproducible research documents. It supports output to PDF, Word, and HTML.

- [RMarkdown in Data Carpentry](https://datacarpentry.org/r-socialsci/instructor/06-rmarkdown.html)
- [Reproducible submission to JMSACL](https://github.com/drdanholmes/jmsacl_reproducible_research)

### LaTeX

LaTeX is a document preparation system using plain text and markup for structure and formatting. You write `.tex` files and compile them into PDF.

Start learning LaTeX:

- [LaTeX: Document Structure Exercise](https://www.learnlatex.org/en/lesson-04)
- [LaTeX Novice Typesetting (Carpentries Incubator)](https://carpentries-incubator.github.io/latex-novice-typesetting/)
- [LaTeX Course (Parts 1 & 2)](https://jdlm.info/latex-course/en/)

## Meeting Publisher Requirements

If publishers only accept proprietary formats, how can you still use open tools?

1. Most WYSIWYG editors allow export to DOCX or PDF.
   - **Caveat**: These may not be digitally accessible or semantically rich.

2. Tools like **Pandoc** can convert Markdown, LaTeX, and other open formats into publisher-accepted ones.

3. Some publishers accept open formats:
   - **LaTeX**: Commonly accepted at submission or for typesetting post-acceptance.
   - **Markdown**: Some open publishing platforms accept markdown submissions.

### Examples

- [Authorea](https://authorservices.wiley.com/author-resources/Journal-Authors/Prepare/authorea.html)
- [PubPub](https://www.knowledgefutures.org/pubpub/)
- [Overleaf](https://www.overleaf.com/)
- [Journal of Open Source Software (JOSS)](https://www.theoj.org/)
- [Programming Historian Guidelines](https://programminghistorian.org/en/author-guidelines)

## Exercise: Markdown Basics

Complete the [CommonMark tutorial](https://commonmark.org/help/tutorial/). Try creating headings, lists, links, and formatting text using a plain text editor.

## Exercise: LaTeX Document Structure

Work through the [LaTeX structure lesson](https://www.learnlatex.org/en/lesson-04) to get familiar with sections, document classes, and compiling.


::: keypoints
- Authors can use open source tools to write and produce manuscript submissions.
- The open science community continues to develop workflows for submitting manuscripts to publishers that require proprietary formats.
- Some journals do accept open source file formats during the initial submission or review stage.
:::
