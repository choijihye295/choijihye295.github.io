---
title: "Your Title"
date: 2024-03-25
type: landing

sections:
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
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      loop: true
      interval: 3000

  # 다른 섹션 추가
  - block: features
    content:
      title: "연구 분야"
      text: "여기에 연구 분야에 대한 설명을 추가하세요."
      items:
        - name: "AI 기술"
          description: "의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발."
        - name: "웹개발"
          description: "웹 애플리케이션 및 서비스 개발."

  - block: collection
    content:
      title: "최신 뉴스"
      count: 3
      filters:
        folders:
          - notification
          - post
      design:
        view: community/custom_card
        columns: '2'
---
