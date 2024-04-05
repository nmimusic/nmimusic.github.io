---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
banner: /images/{{ replace .File.ContentBaseName "-" " " | title }}/thumb.png
draft: true
categories:
- category
tags:
- category
comments: false
shouMeta: true
showActions: false
---
