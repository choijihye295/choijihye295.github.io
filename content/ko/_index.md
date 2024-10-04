---
title: 
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: <span style="font-size:70%"> 최지혜 </span>
      text: <br><span style="font-size:130%">👋 안녕하세요! 전북대학교 컴퓨터공학부에 재학중인 최지혜입니다! </span> 

# 모든 이미지는 unsplash에서 다운로드 받았습니다. 
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
  
  - block: features
    id: features
    content:
      title: <span style="font-size:70%">관심있는 것</span>
      text: 저는 요즘 이런 것들에 관심이 있어요 
      items:
        - name: 웹 개발
          icon: code
          icon_pack: fas
          description: <span style="font-size:100%">내용추가</span>

  - block: accomplishments
    content:
      title: "주요 프로젝트"  # 제목 추가
      subtitle: "나의 주요 프로젝트를 소개합니다."  # 필요 시 서브타이틀 추가
      widget: accomplishments  # accomplishments 위젯 추가
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: 객체지향 프로그래밍
          organization_url: ''
          title: Neural Networks and Deep Learning
          url: 'https://bead-hornet-56a.notion.site/java-team-project-2023-05-06-15-d63c3805214240cdbf6abef23f77a7ea?pvs=4'
---
