---
title: 
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: <span style="font-size:70%"> 최지혜 </span>
      text: |
        <span style="font-size:125%;">👋 안녕하세요! 전북대학교 컴퓨터공학부에 재학중인 최지혜입니다!</span>
        <br>
        <span style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">
          저에 대해 더 자세히 알고싶다면? [소개](/about/)를 클릭해주세요!
        </span>
        <br><br>
        {{% cta cta_link="./about/" cta_text="소개" %}} 

  - block: slider
    content:
      slides:
        - title: <span style="font-size:70%">핀테크</span>
          content: <span style="font-size:70%">내용작성</span>
          align: center
          background:
            image:
              filename: fintech.jpg 
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">웹개발</span>
          content: <span style="font-size:70%">내용작성</span>
          align: center
          background:
            image:
              filename: web.jpg  
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">커뮤니티</span>
          content: <span style="font-size:70%">내용작성</span>
          align: center
          background:
            image:
              filename: team.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

    design:
      slide_height: '400px'
      slide_width: '100px'
      is_fullscreen: false
      loop: true
      interval: 3000

  
---
