---
title: "{{ replace .Name "-" " " | title }}"
linktitle: "{{ replace .Name "-" " " | title }}"
summary: 
date: {{ .Date }}
type: book

weight: 10

toc: true

icon_pack: fas #fas, fab, ai, emoji
icon: 

# But this in the body to list children pages
# {{< list_children >}}
---

