---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: book

weight: 10

toc: true

# But this in the body to list children pages
# {{< list_children >}}
---