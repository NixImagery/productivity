---
title: Report
subtitle: An interesting report
author: Nick Hood
date: 27 September 2019
keywords: report, markdown
# abstract: An optional abstract

documentclass: amsart
header-includes:
  - \usepackage{color}
  - \usepackage{caption}
  - \usepackage{hyperref}
  - \usepackage{anysize}
pagestyle: plain # headings, plain or empty
# papersize: a4
# fontsize: 12pt
# secunmdepth: 2

# bibliography: path/to/bibliography.bib
# csl: styles/institute-of-physics-harvard.csl
link-citations: true
---

# Introduction
In Ted Chiang's *Story of Your Life* [@Chiang2013], the linguist heroine Louise Banks asserts that interaction or specific instructional material is required in order to learn an alien language. When she does interact with aliens, she discovers that they have two distinct language systems: spoken and written, which are complete, independent and used for different purposes.

# How to make this
The document source is in markdown, with a YAML header containing information about it. You can make pdf, docx, or html versions of these documents in one of two ways:

* In Visual Studio, with appropriate settings, using the vscode-pandoc extension. Issue the command by pressing cmd-K, then P. Select the format you need. pdf is default, so hit return.
* On the command line, in the source folder, type:
```sh
$ pandoc filename.md -o filename.pdf --bibliography="path/to/bibliography.bib"
```

# Some quotes from the literature

>...there is a knife moving here. A very deadly one; an intellectual scalpel so swift and so sharp you sometimes don't see it moving. You get the illusion that all those parts are just there and are being named as they exist. But they can be named quite differently and organized quite differently depending on how the knife moves.

>For example, the feedback mechanism which includes the camshaft and cam chain and tappets and distributor exists only because of an unusual cut of this analytical knife. If you were to go to a motorcycle parts department and ask them for a feedback assembly they wouldn't know what the hell you were talking about. -- @Pirsig1984 [pp.68-69]

In this passage, the narrator shows that language conveys no meaning unless participants in the expression both understand the language in the same way. Science tries to use language in its various forms to explain models that infer the underlying truths they explain but even this has had its limitations.

>All science is either physics or stamp collecting -- Rutherford, quoted in @Birks1963 [p.108].


<!--\newpage-->
# References
