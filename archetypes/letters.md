---
date: "{{ .Date }}"
draft: true
title: "{{ replace (replaceRE `^\d{6}-` "" .File.ContentBaseName) "-" " " | title }}"
author: "Aai, and Baba"
tags: []
categories: ["letters"]
---
