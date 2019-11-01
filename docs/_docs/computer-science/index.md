---
layout: articles
title: Computer science
articles:
  data_source: site.docs|where:'category','computer-science'
  # filter:
  #   condition: 'category'
  show_cover: false
  show_excerpt: true
  show_readmore: true
  show_info: true
sidebar:
  nav: docs_navigation
---

    {%- assign _articles = site.docs|where:'category','operating-system' -%}
    {{_articles}}
