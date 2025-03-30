---
title: Projects
cms_exclude: true

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: project
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 2
---