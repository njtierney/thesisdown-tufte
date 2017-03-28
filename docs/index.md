--- 
title: "A Minimal Thesis Using Bookdown and Tufte"
author: "Your Name"
date: "2017-03-29"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
description: "This is a minimal example of using the bookdown package to write a thesis using tufte formatting"
output: 
  bookdown::tufte_book2:
    includes:
      in_header: preamble.tex
      before_body: doc_preface.tex
      after_body: appendix.tex
---



