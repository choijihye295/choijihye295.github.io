---
widget: portfolio  # 위젯 유형으로 변경
headless: true  # This file represents a page section.

# 배너 정보 (필요한 경우 추가)
banner:
  image: 'reading.jpg'  # 필요 시 배너 이미지 경로
  caption: "unsplash"  # 필요 시 캡션 추가

# ... Put Your Section Options Here (title etc.) ...
title: "독서"
subtitle: ''

content:
  # Choose which content to display in the widget
  filters:
    # Folders to display content from
    folders:
      - .  # 현재 폴더에서 가져오도록
    # Uncomment below to only show content with specific tags:
    # tags:
    #   - Machine Learning
    # Uncomment below to exclude content with specific tags:
    # exclude_tags:
    #   - preface    
    # Uncomment below to show specific Hugo Page kinds
    kinds:
      - page

  # Field to sort by, such as Date or Title
  sort_by: 'Date'  # 정렬 기준
  sort_ascending: false

  # Filter toolbar (optional).
  filter_button:
    - name: All
      tag: '*'
    # 추가적인 필터 버튼을 원하면 아래와 같이 추가
    # - name: Deep Learning
    #   tag: Deep Learning
    # - name: Other
    #   tag: Demo

  # Default filter toolbar button
  filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'
  # Choose a listing view
  view: masonry
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
