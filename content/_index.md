---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-28
type: landing

sections:
  # ===== HERO =====
  - block: hero
    content:
      title: "NanoBioMech-AI Lab"
      text: |
        Multiscale mechanics • Biomaterials • **AI-driven design**

        We integrate in-situ experiments, multiscale modeling, and machine learning to
        design resilient nano-bio-structured materials for healthcare and engineering.
      image:
        filename: welcome.jpg
    design:
      background:
        color: ""
      spacing:
        padding: ["40px","0","20px","0"]

  # ===== RESEARCH TILES =====
  - block: features
    content:
      title: "What we do"
      items:
        - name: "Bioinspired Materials"
          description: "Resilient, sustainable, multifunctional composites"
          icon: leaf
          cta:
            label: "Learn more"
            url: "/research/bioinspired-materials/"
        - name: "Single-Cell Mechanics"
          description: "Micro/nano tools & mechanobiology"
          icon: activity
          cta:
            label: "Learn more"
            url: "/research/single-cell-mechanics/"
        - name: "1D/2D Materials"
          description: "In-situ experiments & multiscale modeling"
          icon: layers
          cta:
            label: "Learn more"
            url: "/research/2d-materials/"
        - name: "Metamaterials & AI"
          description: "Architected design, inverse models (DeepONet, GNN, PINNs)"
          icon: grid
          cta:
            label: "Learn more"
            url: "/research/metamaterials/"
    design:
      columns: "2"

  # ===== LATEST NEWS (posts) =====
  - block: collection
    content:
      title: "Latest News"
      count: 5
      filters:
        page_type: post
        exclude_featured: false
      order: desc
    design:
      view: card
      columns: "1"

  # ===== HIGHLIGHTED PUBLICATIONS / PREPRINTS =====
  - block: collection
    content:
      title: "Latest Preprints & Publications"
      text: ""
      count: 5
      filters:
        folders: ["publication"]
        # You can narrow by type later, e.g. publication_type: 'article'
      order: desc
    design:
      view: citation
      columns: "1"

  # ===== PEOPLE & OPENINGS CTA =====
  - block: markdown
    content:
      text: |
        {{% cta cta_link="/people/" cta_text="Meet the team →" %}}

        {{% cta cta_link="/openings/" cta_text="Join the lab →" %}}
    design:
      columns: "1"
---
