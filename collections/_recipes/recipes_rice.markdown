---
output: true

title:  "collections test"
date:   2022-10-17 10:38:55 +0900
categories: jekyll update
header:
  teaser: /assets/images/notice_contents.png
  overlay_image: /assets/images/bg.jpg
  # image: /assets/images/notice_contents.png

  video:
    id: cTuokF7-RXA
    provider: youtube



layout: single
# classes: wide

# author_profile: false
# sidebar: false


figure:
  image_path: /assets/images/notice_contents.png
  alt : "this is a placeholder image"
  caption : "This is a figure caption."

feature_row:
  - image_path: /assets/images/sample01.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/sample02.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/sample03.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."


toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
toc_sticky: true

sidebar:
  nav: "foo"
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

# 첫번째 1
```
  ghghgh
    html > 
```
## 두번째 1-1
### 유튜브 1-1-1
{% include video id="cTuokF7-RXA" provider="youtube" %}
### 유튜브 1-1-2

### 비메오 1-1-2
{% include video id="212731897" provider="vimeo" %}
### Google Drive 1-1-3
{% include video id="1u41lIbMLbV53PvMbyYc9HzvBug5lNWaO" provider="google-drive" %}


# 첫번째 2
## 두번째 2-1
### 세번째 2-1-1
### 세번째 2-1-2



Jekyll requires blog post files to be named according to the following format:

-end-