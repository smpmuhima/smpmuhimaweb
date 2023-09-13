---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
# page title background image
bg_image: "images/backgrounds/page-title.webp"
# meta description
description: "This is meta description"
# teacher portrait
image: "images/teachers/{{ .Name }}.png"
# biography
bio: "My biography"
# interest
interest:
  - "Education"
  - "Agricultural"
# course
course:
  - "Education"
# contact info
contact:
  - name : "mail@email.com"
    icon : "ti-email"
    link : "mailto:mail@email.com"
  - name : "+62812345"
    icon : "ti-mobile"
    link : "tel:+62812345"
  - name : "My Facebook"
    icon : "ti-facebook"
    link : "#"
  - name : "My Twitter"
    icon : "ti-twitter-alt"
    link : "#"
  - name : "My Instagram"
    icon : "ti-instagram"
    link : "#"
  - name : "mywebsite.com"
    icon : "ti-world"
    link : "#"
  - name : "My Location, City"
    icon : "ti-location-pin"
    link : "#"
# type
type: "profile/teacher"
---
