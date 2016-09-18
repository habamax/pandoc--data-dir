---
title: Various Pandoc templates
subtitle: Tailored for RU business documents
author: Maxim Kim
lang: en
date: 2016-03-23
...

LaTeX
=====
There are YAML options available:

- title:
- subtitle:
- author:
- titlepage: if present, there would be separate title page generated
- lang: en, ru or whatever
- date: in ISO format 2016-03-23, if omitted \today would be used
- toc: Table of contents if set
- documentclass: report (article of book), article by default
- logoleft: logo-1.png, filename which is in ~/Pictures/logo/ folder (no underscores or special markdown symbols). It would apper on the top-left.
- logoleft-scale: 0.5, scale factor of logoleft.
- logoright: logo-2.png, filename which is in ~/Pictures/logo/ folder (no underscores or special markdown symbols). It would appear on the top right.
- logoright-scale: 0.5, scale factor of logoright.
