---
title: Talks & Presentations
type: landing   # <-- CRITICAL: This tells Hugo to use the blocks below instead of a basic list!

sections:
  # BLOCK 1: Featured Talks (2 Columns)
  - block: collection
    id: featured-talks
    content:
      title: Featured Talks & Presentations
      filters:
        folders:
          - events      # Change this to 'talks' if your folder is named 'talks'
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # BLOCK 2: All Talks (List view)
  - block: collection
    id: all-talks
    content:
      title: All Talks & Presentations
      count: 0
      filters:
        folders:
          - events      # Change this to 'talks' if your folder is named 'talks'
    design:
      view: compact    # 'compact' creates a clean list. You can also try 'list'.
---
