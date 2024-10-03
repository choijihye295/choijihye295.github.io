---
# Homepage
title: "홈페이지"
date: 2024-03-25
type: widget_page

# Homepage is headless, other widget pages are not.
headless: true

sections:
  - block: intro
    content:
      page: "intro.md"  # intro.md를 포함

  - block: landing
    content:
      slides:
        - title: <span style="font-size:70%">핀테크</span>
          content: <span style="font-size:70%">내용작성</span>
          align: center
          background:
            image:
              filename: "images/fintech.jpg"  # static/images/fintech.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">웹개발</span>
          content: <span style="font-size:70%">내용작성</span>
          align: center
          background:
            image:
              filename: "images/web.jpg"  # static/images/web.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">커뮤니티</span>
          content: <span style="font-size:70%">내용작성</span>
          align: center
          background:
            image:
              filename: "images/team.jpg"  # static/images/team.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

    design:
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: true
      loop: true
      interval: 3000
---
