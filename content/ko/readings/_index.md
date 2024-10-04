---
type: widget_page
title: "독서"
draft: false
view: landing

# 배너 정보
banner:
  image: 'reading.jpg'  # 배너 이미지 경로
  caption: "unsplash"  # 배너 캡션

sections:
  - block: portfolio
    id: books  # ID를 projects에서 books로 변경
    content:
      title: "읽은 책"  # 섹션 제목
      subtitle: "내가 읽은 책들"  # 섹션 부제목
      text: "여기에서 내가 읽은 책들을 카드 형식으로 확인하세요!"
      filters:
        # Folders to display content from
        folders:
          - .  # 읽은 책 정보를 포함할 폴더
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      default_button_index: 0
      # Filter button toolbar (optional).
      buttons:
        - name: All
          tag: '*'
        - name: Fiction
          tag: Fiction
        - name: Non-Fiction
          tag: Non-Fiction
    design:
      columns: '1'  # 열 수
      view: masonry  # 카드 뷰 설정
      flip_alt_rows: false

---

[더 많은 책 목록 보기](https://bead-hornet-56a.notion.site/My-book-List-a4f24f3ec3794b76827d5f0b02cc4427?pvs=4) <!-- 링크 추가 -->
