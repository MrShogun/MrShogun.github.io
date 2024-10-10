---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: abstract-dark-blue-polygonal-background.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: abstract-dark-blue-polygonal-background.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
      show_skill_percentage: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
    design:
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: abstract-dark-blue-polygonal-background.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: resume-languages
    content:
      title: Languages
      username: admin
---
