---
type: landing
title: "연락"
draft: false

# 이 페이지의 특정 디자인이나 배너를 설정할 수 있습니다.
banner:
  image: 'contact.jpg' # 필요 시 배너 이미지 경로
  caption: "unsplash" # 필요 시 캡션 추가

sections:
  - block: banner
    content:
      image: 'contact.jpg' # 배너 이미지
      caption: "unsplash" # 배너 캡션

  - block: contact
    content:
      title: 연락
      text: |-
        <br> <span style="font-size:95%">저에게 이메일을 보내시려면 아래 주소로 보내주세요.</span> <br>
      email: choijihye295@jbnu.ac.kr
      phone: 010-6487-3021
      address:
        street: 전북대학교 공과대학 7호관
        city: 전주시
        region: 전라북도
        postcode: '54896'
        country: 대한민국
        country_code: KO
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'
      directions: 
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '3'
---
