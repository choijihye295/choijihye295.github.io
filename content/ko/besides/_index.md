---
# This file represents a page section.
headless: true

# Activate this section? true/false
active: true

# Order that this section appears on the page.
weight: 10

title: 그외 프로젝트

# Accomplishments Section
accomplishments:
  - certificate_url: ''
    date_end: '2022-06-15'
    date_start: '2022-03-01'
    description: |2-
      <div class="achievement-card">
        <div class="achievement-title">경제스터디</div>
        <div class="achievement-organization">스터디모임</div>
        <div class="achievement-date">2022-03-01 - 2022-06-15</div>
        <div class="achievement-description">스터디 활동을 통해 경제 지식 습득</div>
      </div>
  - certificate_url: ''
    date_end: '2023-02-17'
    date_start: '2023-02-14'
    description: |2-
      <div class="achievement-card">
        <div class="achievement-title">제주도 창업캠프</div>
        <div class="achievement-organization">소소리</div>
        <div class="achievement-date">2023-02-14 - 2023-02-17</div>
        <div class="achievement-description">캠프를 통해 창업 아이디어 개발</div>
      </div>
  - certificate_url: ''
    date_end: '2024-02-15'
    date_start: '2023-12-01'
    description: |2-
      <div class="achievement-card">
        <div class="achievement-title">기업의 달인</div>
        <div class="achievement-organization">컴계일학</div>
        <div class="achievement-date">2023-12-01 - 2024-02-15</div>
        <div class="achievement-description">기업 분석 및 경영 전략 학습</div>
      </div>
  - certificate_url: ''
    date_end: ''
    date_start: '2024-07-15'
    description: |2-
      <div class="achievement-card">
        <div class="achievement-title">엔비디아 현직자 인터뷰</div>
        <div class="achievement-organization">박은송, 최지혜, 홍사강</div>
        <div class="achievement-date">2024-07-15 - 현재</div>
        <div class="achievement-description">엔비디아 현직자와의 인터뷰 진행</div>
        <a href="https://bead-hornet-56a.notion.site/4a9c3041159e494a98762a3d12e63b2e?pvs=4" class="achievement-button">자세히 보기</a>
      </div>

# Design settings for layout
design:
  columns: '1'
---

{{ range .Params.accomplishments }}
<div class="achievement-card">
  <div class="achievement-title">{{ .title }}</div>
  <div class="achievement-organization">{{ .organization }}</div>
  <div class="achievement-date">{{ .date_start }} - {{ if .date_end }}{{ .date_end }}{{ else }}현재{{ end }}</div>
  <div class="achievement-description">{{ .description }}</div>
  {{ if .url }}
    <a href="{{ .url }}" class="achievement-button">자세히 보기</a>
  {{ end }}
</div>
{{ end }}
