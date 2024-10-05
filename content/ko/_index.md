---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing
featured_image: "/media/video.jpg"
sections:
  - block: features
    content:
      title:
      text: <br><span style="font-size:125%">저는 전북대학교 컴퓨터공학부에 재학중인 22학번 학부생 신철언입니다. 웹 개발자에서 백엔드 기반 개발에 관심이 있습니다. 개발뿐만 아니라 영상이나 음악에도 관심이 있습니다.</span>

  - block: slider
    content:
      slides:
        - title: <span style="font-size:70%">Music</span>
          content: <span style="font-size:70%">힙합, R&B, 록, 재즈등 다양한 음악 감상</span>
          align: center
          background:
            image:
              filename: madvillainy.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Video</span>
          content: <span style="font-size:70%">촬영, 편집<span style="font-size:70%">
          align: center
          background:
            image:
              filename: video.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Development</span>
          content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
          align: center
          background:
            image:
              filename: development.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Fashion</span>
          content: <span style="font-size:70%">다양한 브랜드의 제품 디깅</span>
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
---
