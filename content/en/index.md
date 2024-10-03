---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title:
      text: <br><span style="font-size:125%">At Macs, we are conducting research using AI and deep learning in various fields such as healthcare, EMR, vision, aviation, and defense, and are also conducting medical mathematics and AI-based research. In addition, we are focusing on practical areas of development and deployment, such as full-stack development and application development using AI.</span>

  - block: slider
    content:
      slides:
        - title: <span style="font-size:70%">Recruit</span>
          content: <span style="font-size:70%">Interested in MacsLAB?</span>
          align: center
          background:
            image:
              filename: recruitment.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"
          link:
            icon: user
            icon_pack: fas
            text: <span style="font-size:60%">Join Us</span>
            text-color: "#000"
            url: contact

        - title: <span style="font-size:70%">AI</span>
          content: <span style="font-size:70%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
          align: center
          background:
            image:
              filename: Ai.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Healthcare</span>
          content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
          align: center
          background:
            image:
              filename: healthcare.jpg
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Mathematics</span>
          content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
          align: center
          background:
            image:
              filename: mathematics.jpg
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

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: "350px"
      slide_width: "100px"
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
---
