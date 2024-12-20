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
          filename: dark-purple-hand-painted-alcohol-ink-background.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume-en.pdf
    design:
      css_class: dark
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I focus on applied mathematics and telecommunications, particularly in the areas of queueing theory, stochastic modeling, and teletraffic systems. My work includes developing mathematical models for analyzing network performance, optimizing system processes, and solving real-world telecommunication challenges. I actively collaborate with other researchers and participate in international conferences to present findings and share insights.

        Feel free to reach out for collaborations or discussions on mathematical theory applications and system optimization.
    design:
      columns: '1'
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
