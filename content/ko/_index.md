---
title: 
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: <span style="font-size:70%"> 최지혜 </span>
      text: <br><span style="font-size:130%">👋 안녕하세요! 전북대학교 컴퓨터공학부에 재학중인 최지혜입니다! </span> 

  - block: markdown
    content:
      title: 
      subtitle: 
      text: |
        <div style="text-align: center;">
          <a href="./about/" class="cta-button">더 자세한 소개</a>  
        </div>
    design:
      columns: '1'

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
  
  #https://bootstrap.hugoblox.com/blocks/features/
  
  - block: features
    id: features
    content:
      title: <span style="font-size:70%">관심있는 것</span>
      text: 저는 요즘 이런 것들에 관심이 있어요 <br><br> #br : 줄바꿈
      items:
        - name: 웹 개발
          icon: code
          icon_pack: fas
          description: <span style="font-size:100%">내용추가</span>
        - name: 핀테크
          icon: credit-card
          icon_pack: fas
          description: <span style="font-size:100%">내용추가</span>
        - name: 소통
          icon: users
          icon_pack: fas
          description: <span style="font-size:100%">내용추가</span>
        - name: 대회
          icon: star
          icon_pack: fas
          description: <span style="font-size:100%">내용추가</span>
        - name: 여행
          icon: plane
          icon_pack: fas
          description: <span style="font-size:100%">내용추가</span>
        - name: 독서
          icon: book-open
          icon_pack: fas
          description: <span style="font-size:100%">내용추가</span> <br><br><br><br>
          

  - block: accomplishments
    content:
      title: "주요 프로젝트"  # 제목 추가
      subtitle: "저의 전공관련 주요 프로젝트를 소개합니다."  # 필요 시 서브타이틀 추가
      widget: accomplishments  # accomplishments 위젯 추가
      background: 
        color: '#e6f0f5'
      items:
        - certificate_url: ''
          date_end: '2023-12-10'
          date_start: '2023-09-02'
          description: ''
          organization: 모바일 프로그래밍, 해커톤 
          organization_url: ''
          title: 실시간 이미지 번역 어플리케이션 
          url: 'https://bead-hornet-56a.notion.site/2023-09-2023-12-e30477df581246af8cf88b6ec92a901b'

        - certificate_url: ''
          date_end: '2023-08-15'
          date_start: '2023-06-20'
          description: ''
          organization: 3M
          organization_url: ''
          title: 하계 자기설계, 큰사람프로젝트 앱 개발 
          url: 'https://bead-hornet-56a.notion.site/2023-06-08-e6f6e475357f42eab892f3018fb285da?pvs=4'

        - certificate_url: ''
          date_end: '2023-01-18'
          date_start: '2022-12-01'
          description: ''
          organization: 공간정보
          organization_url: ''
          title: 공간정보 AI 경진대회
          url: 'https://bead-hornet-56a.notion.site/AI-2022-12-2023-01-40ca1cabe58248ae84ee0f1ef082bb87'

  

---
