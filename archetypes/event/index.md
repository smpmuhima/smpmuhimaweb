---
title: "{{ replace .Name "-" " " | title }}"
# Schedule page publish date
publishDate: {{ .Date }}
# event date
date: {{ .Date }}
# post save as draft
draft: false
# page title background image
bg_image: "images/backgrounds/page-title.webp"
# meta description
description: "This is meta description"
# Event image
image: "images/events/{{ .Name }}.png"
# location
location: "Ngoro, Mojokerto"
# entry fee
fee: "Rp. -"
# apply url
apply_url : "#"
# event speaker
speaker:
  - name : "Mr. Speaker"
    image : "images/event-speakers/speaker.png"
    designation : "Speaker"
  - name : "Mr. Moderator"
    image : "images/event-speakers/moderator.png"
    designation : "Moderator"
  - name : "Mr. Qori"
    image : "images/event-speakers/moderator.png"
    designation : "Qori"
# type
type: "event"
---
