---
title: Blog
summary: Blog entries and news about Jose
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: post
    content:
      title: Blog
      filters:
        folders:
          - post
    design:
      view: compact
      columns: '1'
---
