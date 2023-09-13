---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
# page title background image
bg_image: "images/backgrounds/page-title.webp"
# meta description
description: "This is meta description"
# course thumbnail
image: "images/blog/{{ .Name }}.png"
# taxonomy
category:
    - "Course"
# teacher
teacher: "Takmir Al-Mujahidin"
# duration (depend language)
duration : "06 Month"
# weekly
weekly : "03 Hours"
# course fee
fee : "Rp. -"
# apply url
apply_url : "#"
# type
type: "course"
---
