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

    {%- assign _articles = site.docs|where:'category','computer-science' -%}
    {{_articles}}
