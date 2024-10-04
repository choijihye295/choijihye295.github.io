---
title: 
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: <span style="font-size:70%"> JiHye Choi </span>
      text: <br><span style="font-size:130%">👋 Hello! I'm Choi Ji-hye, majoring in computer engineering at Chonbuk National University! </span> 

  - block: markdown
    content:
      title: 
      subtitle: 
      text: |
        <div style="text-align: center;">
          <a href="./about/" class="cta-button">More detailed introduction</a>  
        </div>
    design:
      columns: '1'

  # 모든 이미지는 unsplash에서 다운로드 받았습니다. 
  - block: slider
    content:
      slides:
        - title: <span style="font-size:70%">Fintech</span>
          content: <span style="font-size:70%">Incorporating IT technology into traditional financial services</span>
          align: center
          background:
            image:
              filename: fintech.jpg 
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">Web development</span>
          content: <span style="font-size:70%">Web site or Web application design, build and maintenance</span>
          align: center
          background:
            image:
              filename: web.jpg  
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">Communication</span>
          content: <span style="font-size:70%">Key factors that enhance understanding and collaboration among team members in the project, resulting in successful results</span>
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
      title: <span style="font-size:70%">a thing of interest</span>
      text: <div class="justify">I'm interested in these things these days</div> <br><br> #br : 줄바꿈
      items:
        - name: Web development
          icon: code
          icon_pack: fas
          description: <div class="justify"><span style="font-size:100%;">I'm interested in designing and building websites and web applications</span></div>
        - name: Fintech
          icon: credit-card
          icon_pack: fas
          description: <div class="justify"><span style="font-size:100%;">We are interested in providing innovative financial services through the convergence of finance and technology</span></div>
        - name: Communication
          icon: users
          icon_pack: fas
          description: <div class="justify"><span style="font-size:100%;">I think it is important to achieve cooperation through smooth communication in team projects</span></div>
        - name: Contest
          icon: star
          icon_pack: fas
          description: <div class="justify"><span style="font-size:100%;">I'm improving my skills by participating in various hackathon and programming competitions</span></div>
        - name: Trip
          icon: plane
          icon_pack: fas
          description: <div class="justify"><span style="font-size:100%;">I enjoy traveling to experience different cultures and people</span></div>
        - name: Reading
          icon: book-open
          icon_pack: fas
          description: <div class="justify"><span style="font-size:100%;">I like to read books of various genres to expand my knowledge and expand my thinking</span></div>



  - block: accomplishments
    content:
      title: "major project"  # 제목 추가
      subtitle: "Let me introduce the major projects related to my major."  # 필요 시 서브타이틀 추가
      widget: accomplishments  # accomplishments 위젯 추가
      background: 
        color: '#e6f0f5'
      items:
        - certificate_url: ''
          date_end: '2023-12-10'
          date_start: '2023-09-02'
          description: ''
          organization: 후추수정
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

  - block: accomplishments
    content:
      title: "전공 외 프로젝트"  # 제목 추가
      subtitle: "저의 전공 외 수행했던 다양한 프로젝트를 소개합니다."  # 필요 시 서브타이틀 추가
      widget: accomplishments  # accomplishments 위젯 추가
      background: 
        color: '#e6f0f5'
      items:
        - certificate_url: ''
          date_end: '2023-02-17'
          date_start: '2023-02-14'
          description: ''
          organization: 소소리
          organization_url: ''
          title: 제주도 창업캠프
          url: ''
        - certificate_url: ''
          date_end: '2024-02-15'
          date_start: '2023-12-01'
          description: ''
          organization: 컴계일학
          organization_url: ''
          title: 기업의 달인
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2024-07-15'
          description: ''
          organization: 박은송, 최지혜, 홍사강
          organization_url: ''
          title: 엔비디아 현직자 인터뷰
          url: 'https://bead-hornet-56a.notion.site/4a9c3041159e494a98762a3d12e63b2e?pvs=4'


  - block: experience
    content:
      title: 경력 
      subtitle:
      widget: experience  # experience 위젯 추가
      background:
        color: '#f9f9f9'
      items:
        - title: 동아리 임원
          company: 전북대학교 중앙동아리 필담
          company_url: ''
          company_logo: 
          location: 
          date_start: '2022-04-01'
          date_end: '2022-12-01'
          description: |2-
              * 동아리 홍보부스 운영
              * 정기 전시 기획 및 참여

        - title: 동아리 스터디 멘토
          company: 전북대학교 컴퓨터공학부 과동아리 who
          company_url: ''
          company_logo: 
          location: 
          date_start: '2023-03-01'
          date_end: '2023-06-30'  # 수정된 날짜
          description: C언어 스터디 멘토링 활동에서 멘토로 참여함

        - title: ADsP
          company: 데이터자격시험
          company_url: 'https://www.dataq.or.kr/www/main.do'
          company_logo: 
          location: 
          date_start: '2024-07-01'
          date_end: '2024-08-10'
          description: 데이터분석 준전문가 자격증 취득함

    design:
      columns: '2'
---
