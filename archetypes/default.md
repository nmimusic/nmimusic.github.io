---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
banner: /img/{{ replace .File.ContentBaseName "-" " " | title }}/thumb.png
draft: true
categories:
- category
tags:
- category
comments: false
showMeta: true
showActions: false
---
