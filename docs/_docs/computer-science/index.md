---
layout: article
title: Computer science
date: 2019-10-31
aside:
  toc: true
sidebar:
  nav: docs
---

## This is doc index page
<!--more-->

### Please look at sidebar and concentrate on the main content!
This is a content#1
### Sample content
This is a content#2

    ---
    layout: article
    title: Page - Sidebar
    aside:
      toc: true
    sidebar:
      nav: layouts
    ---

    ## This is doc index page
    ### Please look at sidebar and concentrate on the main content!
    This is a content#1
    ### Sample content
    This is a content#2

    {%- include article-list.html articles=site.docs|where:'category','computer-science' type='brief' show_info=true reverse=true group_by='year' -%}
