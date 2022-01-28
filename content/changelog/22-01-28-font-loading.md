---
title: "Font loading"
date: 2022-01-28T15:41:58Z
draft: false
slug: "font-loading"
badges: 
  - Fixed
---

### Bug fixes & improvements

Now using [ExecuteAsTemplate](https://gohugo.io/hugo-pipes/resource-from-template/) to pass {{ .BaseURL }} to critical CSS and form absolute URLs. 

Fonts now loading on subpages as URLs are no longer relative.