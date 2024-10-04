---
# This file represents the main content of the page.
headless: true

# Activate this section? true/false
active: true

# Order that this section appears on the page.
weight: 10

title: 그외 프로젝트

# Projects section
projects:
  - title: 프로젝트 1
    description: '프로젝트 1에 대한 설명입니다.'
    date: '2023-01-01'
    url: 'https://example.com/project1'
  - title: 프로젝트 2
    description: '프로젝트 2에 대한 설명입니다.'
    date: '2023-02-01'
    url: 'https://example.com/project2'
  - title: 프로젝트 3
    description: '프로젝트 3에 대한 설명입니다.'
    date: '2023-03-01'
    url: 'https://example.com/project3'

design:
  columns: '1'
---

{{ range .Params.projects }}
<div class="achievement-card">
  <div class="achievement-title">{{ .title }}</div>
  <div class="achievement-date">{{ .date }}</div>
  <div class="achievement-description">{{ .description }}</div>
  {{ if .url }}
    <a href="{{ .url }}" class="achievement-button">자세히 보기</a>
  {{ end }}
</div>
{{ end }}
