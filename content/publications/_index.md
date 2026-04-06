---
title: Publications
type: landing   # <-- CRITICAL: This tells Hugo to use the blocks below instead of a basic list!

sections:
  # BLOCK 1: Featured Talks (2 Columns)
  - block: collection
    id: featured-publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publications      # Change this to 'talks' if your folder is named 'talks'
        featured_only: true
        count: 0
    design:
      view: article-grid
      columns: 2

  # BLOCK 2: All Talks (List view)
  - block: collection
    id: all-publications
    content:
      title: All Publications
      count: 0
      filters:
        folders:
          - publications      # Change this to 'talks' if your folder is named 'talks'
    design:
      view: citation    # 'compact' creates a clean list. You can also try 'list'.
---
