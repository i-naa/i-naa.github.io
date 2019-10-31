---
layout: articles
title: Computer science
articles:
  data_source: site.docs
  show_cover: false
  show_excerpt: true
  show_readmore: true
  show_info: true
sidebar:
  nav: docs_navigation
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

    {%- assign _articles = site.docs|where:'category','computer-science' -%}
    {{_articles}}
    {%- include article-list.html articles=_articles type='brief' show_info=true reverse=true group_by='year' -%}
