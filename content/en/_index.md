---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing
featured_image: "/assets/media/video.jpg"
sections:
  - block: features
    content:
      title:
      text: <br><span style="font-size:125%">I'm Shin Cheol-eon, a 22-year undergraduate student in the Department of Computer Engineering at Chonbuk National University. I'm interested in developing a backend-based development in a web developer. I'm interested in video or music as well as development.</span>

  - block: slider
    content:
      slides:
        - title: <span style="font-size:70%">Music</span>
          content: <span style="font-size:70%">Listen to various music such as hip-hop, R&B, rock, jazz, etc</span>
          align: center
          background:
            image:
              filename: madvillainy.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Video</span>
          content: <span style="font-size:70%">Filming, editing<span style="font-size:70%">
          align: center
          background:
            image:
              filename: video.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Development</span>
          content: <span style="font-size:70%">Full-Stack Application Development Using Foundation Technology</span>
          align: center
          background:
            image:
              filename: development.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Fashion</span>
          content: <span style="font-size:70%">Digging products from different brands</span>
          align: center
          background:
            image:
              filename: labros.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: "350px"
      slide_width: "100px"
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: collection
    content:
      id: section-1
      title: Project
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - project
    design:
      view: community/custom_card
      columns: "2"
      background:
      # Choose a color such as from https://html-color-codes.info
      color: "grey"
      # Text color (true=light, false=dark, or remove for the dynamic theme color)
      text_color_light: true

  - block: collection
    content:
      id: section-1
      title: fashion & music
      subtitle:
      text:
      count: 6
      offset: 0
      order: desc
      filters:
        folders:
          - interest
    design:
      view: community/custom_card
      columns: "2"
      background:
      # Choose a color such as from https://html-color-codes.info
      color: "#A4A4A4"
      # Text color (true=light, false=dark, or remove for the dynamic theme color)
      text_color_light: true
---
