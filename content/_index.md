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
        **Multiscale mechanics** • **Biomaterials** • **AI-driven design**

        We integrate in-situ experiments, multiscale modeling, and machine learning to
        design resilient nano-bio-structured materials for healthcare and engineering.
      image:
        filename: welcome.jpg
      cta:
        - label: "Research"
          url: "/research/"
        - label: "Publications"
          url: "/publications/"
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
          description: "Resilient, sustainable, multifunctional composites inspired by nature's design principles"
          icon: leaf
          cta:
            label: "Learn more"
            url: "/research/bioinspired-materials/"
        - name: "Single-Cell Mechanics"
          description: "Micro/nano tools & mechanobiology for understanding cellular behavior"
          icon: activity
          cta:
            label: "Learn more"
            url: "/research/single-cell-mechanics/"
        - name: "1D/2D Materials"
          description: "In-situ experiments & multiscale modeling of nanomaterials"
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

  # ===== RESEARCH HIGHLIGHTS =====
  - block: research
    content:
      title: "Research Highlights"
      items:
        - title: "AI-Driven Biomaterial Design"
          description: "Machine learning approaches for designing bioinspired materials with tailored mechanical properties"
          icon: "🧬"
          journal: "Nature Materials"
          year: "2024"
        - title: "Multiscale Mechanics of 2D Materials"
          description: "Understanding failure mechanisms in 2D materials through in-situ experiments and modeling"
          icon: "⚛️"
          journal: "Science Advances"
          year: "2024"
        - title: "Single-Cell Mechanobiology"
          description: "Novel microfluidic platforms for studying cellular mechanics and mechanotransduction"
          icon: "🔬"
          journal: "Cell"
          year: "2023"
        - title: "Metamaterial Optimization"
          description: "Physics-informed neural networks for inverse design of architected materials"
          icon: "🏗️"
          journal: "Advanced Materials"
          year: "2023"

  # ===== PUBLICATIONS =====
  - block: publications
    content:
      title: "Recent Publications"
      items:
        - title: "Machine Learning-Driven Design of Bioinspired Materials"
          authors: "Jin, H., Smith, A., Johnson, B."
          journal: "Nature Materials"
          year: "2024"
        - title: "Multiscale Modeling of 2D Material Failure"
          authors: "Jin, H., Chen, L., Wang, M."
          journal: "Science Advances"
          year: "2024"
        - title: "Single-Cell Mechanics in Microfluidic Environments"
          authors: "Jin, H., Brown, K., Davis, R."
          journal: "Cell"
          year: "2023"
        - title: "Physics-Informed Neural Networks for Metamaterial Design"
          authors: "Jin, H., Wilson, T., Lee, S."
          journal: "Advanced Materials"
          year: "2023"
        - title: "Bioinspired Composite Materials for Healthcare Applications"
          authors: "Jin, H., Garcia, M., Thompson, P."
          journal: "Materials Today"
          year: "2023"

  # ===== PEOPLE & OPENINGS CTA =====
  - block: markdown
    content:
      text: |
        {{% cta cta_link="/team/" cta_text="Meet the team →" %}}

        {{% cta cta_link="/openings/" cta_text="Join the lab →" %}}
    design:
      columns: "1"
---