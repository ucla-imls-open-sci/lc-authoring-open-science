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

There are many collaborative authoring tools available today; DOC, DOCX, and PDF are the file formats most requested by scholarly publishers. The trouble with these formats is that they are not open source. So how do we work within the confines of the scholarly publishing landscape while still adhering to our open science values? By finding other ways to author manuscripts, of course! 
https://alternativeto.net/

By finding other ways to author manuscripts, of course! <https://alternativeto.net/>

## Alternative authoring tools

### WYSIWYG

If you prefer a *What-You-See-Is-What-You-Get* (WYSIWYG) editor, here are some common options:

- **Google Docs**: free but not open source.
- **LibreOffice**: free and open source — [feature comparison with Microsoft Office](https://wiki.documentfoundation.org/Feature_Comparison:_LibreOffice_-_Microsoft_Office)
- **Apache OpenOffice**: free and open source, though not regularly updated.

Most journals have manuscript templates in DOCX format, which can be opened using these programs.

These programs allow you to collaborate, show version history, and publish documents easily. 
However, these programs do not easily create semantic, machine-readable documents. 
To produce manuscripts, documentation, or other narrative research outputs that can be 
Findable, accessible, interoperable, and reproducible it may be time to transition to a 
*what-you-see-is-what-you-mean* (WYSIWYM) document editor. That is, a document editor that 
focuses on the structure rather than the format.

## WYSIWYM Tools

For semantic authoring, consider *What-You-See-Is-What-You-Mean* (WYSIWYM) formats such as:

### Markdown

What’s different? Plain text editor with semantic commands for visuals.

You can use any text editor to create a markdown file, change the extension from .txt to .md. 
hackmd.io However, there is a new syntax you have to learn to do things like creating headings, 
links, bold, italic, lists, etc. It’s easier to learn those things using a tutorial or an online web editor.

Let’s try the 10 minute Commonmark tutorial together:

::::: challenge 

## Getting Started with Markdown 

1. Open the CommonMark tutorial: https://commonmark.org/help/tutorial/

2. Complete as many of the exercises as you can in 10 minutes. Try to explore:

* Headings
* Lists
* Links
* Code blocks

::::: 

Now you can create a markdown file, but how do you get it to the publisher? We already know 
that most of them will only take DOCX or PDF files. While out of scope of this lesson, 
there are many tutorials and open source software for converting Markdown into other formats 
that publishers may accept:

- [PoisotLab manuscript template](https://github.com/PoisotLab/manuscript-template)
- [Markdown for Manuscripts](https://github.com/djhocking/Markdown-for-Manuscripts)
- [Sustainable authorship with Pandoc](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)
- [The Carpentries Markdown lesson](https://swcarpentry.github.io/modern-scientific-authoring/02-markdown/)

### RMarkdown

RMarkdown is markdown that integrates with R to create the formats required by a publisher. If you’re already using R in your work, this integration would be the best for 
keeping your project files together. Tutorials on using RMarkdown are available through data carpentry: 

- [RMarkdown in Data Carpentry](https://datacarpentry.org/r-socialsci/instructor/06-rmarkdown.html)

And researchers have a tutorial on how to produce a msncuript for submission to Journal of Mass Spectrometry & Advances in the Clinical Lab (JMSACL)

- [Reproducible submission to JMSACL](https://github.com/drdanholmes/jmsacl_reproducible_research)

### LaTeX

What’s different? Instructions to the ‘compiler’ on what each section should be, the .TEX file is not the product, 
the PDF that is produced is.
[Lesson 2 of Learn LaTeX](https://www.learnlatex.org/en/lesson-02) explains how LaTeX works by 
combining multiple tools, rather than functioning as a single application. Unlike many computer programs, LaTeX is not a single application containing ‘everything’ in one. 
Instead, there are separate programs that work together. We can divide those up into two things 
you actually need:

- A TeX system
- A text editor (often a LaTeX-specific one)

::::::: challenge 

## Getting Started with LaTex

Let’s do this structure exercise together:https://www.learnlatex.org/en/lesson-04 

:::

Other tutorials:

- [LaTeX: Document Structure Exercise](https://www.learnlatex.org/en/lesson-04)
- [LaTeX Novice Typesetting (Carpentries Incubator)](https://carpentries-incubator.github.io/latex-novice-typesetting/)
- [LaTeX Course (Parts 1 & 2)](https://jdlm.info/latex-course/en/)

## How to meet submission requirements

If most publishers only accept proprietary formats like DOCX and PDF files, how do you use 
open source or alternative authoring tools to submit to publishers?

There are options:

1. Most WYSIWYG editors allow export to DOCX or PDF.
   - **Caveat**: These may not be digitally accessible or semantically rich.

2. Depending on the language you use to author your document, you may be able to use 
open source programs like PANDOC to transform your file into one of the required file formats.

3. Some publishers may accept open source formats like LaTeX or Markdown.
   a. Many publishers will ask for your LaTeX files for final formatting if your article is accepted, but they will have their own requirements for the structure  
   b. Publishers are starting to use their own online collaborative authoring platforms that use Markdown and LaTeX   
      1. Authorea [https://authorservices.wiley.com/author-resources/Journal-Authors/Prepare/authorea.html](https://authorservices.wiley.com/author-resources/Journal-Authors/Prepare/authorea.html)  
      2. [https://www.knowledgefutures.org/pubpub/](https://www.knowledgefutures.org/pubpub/)   
      3. Overleaf   
   c. Some journals focused on publishing open source publications will only accept markdown submissions  
      1. [https://www.theoj.org/](https://www.theoj.org/)  
      2. https://programminghistorian.org/en/author-guidelines

::: keypoints
- Authors can use open source tools to write and produce manuscript submissions.
- The open science community continues to develop workflows for submitting manuscripts to publishers that require proprietary formats.
- Some journals do accept open source file formats during the initial submission or review stage.
:::
