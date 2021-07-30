---

# for listing page layout
layout: list-sidebar # list, list-sidebar

# for list-sidebar layout
sidebar:
  title: Courses
  description: |
    I teach substantive and method courses at both undergraduate and graduate level.
    The right sections collect the course briefs and preview slides.
    Free to learn more about them by contacting me directly.
  show_sidebar_adunit: false # show ad container

# set up common front matter for all pages inside blog/
cascade:
  type: blog
  author: "HU Yue"
  show_post_thumbnail: true
  show_author_byline: false
  show_post_date: true
  show_post_time: true
  show_disqus_comments: false # see disqusShortname in site config
  # for single-sidebar layout
  # sidebar:
  #   text_link_label: View recent talks
  #   text_link_url: /talk/
  #   show_sidebar_adunit: false # show ad container
---

** No content below YAML for the talk _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside talk/. You may still override any of these by changing them in a page's front matter.**