---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
# page title background image
bg_image: "images/backgrounds/page-title.webp"
# meta description
description: "This is meta description"
# post thumbnail
image: "images/publication/{{ .Name }}.png"
# type
type: "publication"
---
