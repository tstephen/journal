---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
draft: true
tags:
- "{{ dateFormat "2006" .Date }}"
categories:
- 
---