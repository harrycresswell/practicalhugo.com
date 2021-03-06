---
title: "Font loading"
date: 2022-01-28T15:41:58Z
draft: false
slug: "font-loading"
badges: 
  - Fixed
---

### Bug fixes & improvements

Now using [ExecuteAsTemplate](https://gohugo.io/hugo-pipes/resource-from-template/) to pass `{{ .BaseURL }}` to critical CSS and form absolute URLs. 

Fonts now loading on subpages as URLs are no longer relative.

### Resources

- [Use Hugo template variables in SCSS files](https://blog.fullstackdigital.com/how-to-use-hugo-template-variables-in-scss-files-in-2018-b8a834accce)
- [Error Hugo variable inside SASS](https://discourse.gohugo.io/t/error-hugo-variable-inside-sass/15127)
