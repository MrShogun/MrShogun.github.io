---
# Leave the homepage title empty to use the site title
title: Публикации
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"
  background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: universe-watercolors.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

sections:
  #- block: collection
  #  id: papers
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2
  - block: collection
    content:
      title: Недавние публикации
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---