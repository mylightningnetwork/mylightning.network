---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
seo_description: ""
seo_keyword:
  - keyword1
  - keyword2
thumbnail: "posts/example.jpg"
audio_url: "/assets/audios/file.mp3"
tags:
  - tags1
  - tags2
category:
  - Workshop
  - Podcast
slug: "{{ lower .Name | urlize }}"
---

