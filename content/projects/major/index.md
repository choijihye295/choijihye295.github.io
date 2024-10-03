---
title: "major"
draft: false
type: widget_page
---


<div class="card-deck">  <!-- 카드가 나란히 표시되도록 설정 -->
    {{ partial "project_card.html" (dict "title" "프로젝트 A" "description" "이 프로젝트는 ..." "link" "/major/project-a" "image" "/images/project-a.jpg") }}
    {{ partial "project_card.html" (dict "title" "프로젝트 B" "description" "이 프로젝트는 ..." "link" "/major/project-b" "image" "/images/project-b.jpg") }}
    {{ partial "project_card.html" (dict "title" "프로젝트 C" "description" "이 프로젝트는 ..." "link" "/major/project-c" "image" "/images/project-c.jpg") }}
    {{ partial "project_card.html" (dict "title" "프로젝트 D" "description" "이 프로젝트는 ..." "link" "/major/project-d" "image" "/images/project-d.jpg") }}
    {{ partial "project_card.html" (dict "title" "프로젝트 E" "description" "이 프로젝트는 ..." "link" "/major/project-e" "image" "/images/project-e.jpg") }}
</div>
