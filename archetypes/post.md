---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
year: {{ dateFormat "2006" .Date }}
month: {{ dateFormat "2006/01" .Date }}
day: {{ dateFormat "2006/01/02" .Date }}
tags: []
author: Shane 
---
