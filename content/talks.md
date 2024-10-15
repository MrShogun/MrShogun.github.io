---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"
  background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: abstract-splashed-watercolor-textured-background.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

sections:
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
      view: article-grid
      columns: 1
---