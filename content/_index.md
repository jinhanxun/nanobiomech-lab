---
# Leave the homepage title empty to use the site title
title:
date: 2025-11-07
type: landing

sections:
  # ===== HERO =====
  - block: hero
    content:
      title: "NanoBioMech Lab"
      text: |
        • **Experimental Mechanics** • **BioManufacturing** • **Mechanobiology** •**Scientific AI/ML**

      image:
        filename: home_cover.png
      cta:
        - label: "Research"
          url: "/research/"
        - label: "Join Us"
          url: "/openings/"
    design:
      background:
        color: ""
      spacing:
        padding: ["40px","0","20px","0"]

  # ===== OUR VISION =====
  - block: markdown
    content:
      title: "Our Vision"
      text: |
        We envision a future where nano-bio-structured materials revolutionize personalized healthcare and sustainable engineering. By bridging experimental mechanics, biomanufacturing, and artificial intelligence, we aim to create a new generation of materials that adapt, heal, and perform like living systems—ushering in transformative solutions for human health.
    design:
      columns: "1"

  # ===== RESEARCH AREAS =====
  - block: features
    content:
      title: "Research Areas"
      items:
        - name: "Biomanufacturing & Mechanobiology"
          description: "Sustainable bioinks, bio-printing, and multiscale characterization of cell-matrix interactions"
          icon: leaf
          cta:
            label: "Learn more"
            url: "/research/#topic-1-biomanufacturing-and-multiscale-mechanobiological-characterization"
        - name: "AI/ML-Driven Materials Design"
          description: "Neural operators, PINNs, and graph neural networks for rapid design and characterization of nano-bio-structured materials"
          icon: grid
          cta:
            label: "Learn more"
            url: "/research/#topic-2"

  # ===== ABOUT US =====
  - block: markdown
    content:
      title: "About Us"
      text: |
        Dr. Hanxun Jin will join the Department of Mechanical and Materials Engineering at the University of Cincinnati as an Assistant Professor in January 2026. Before joining UC, he was a postdoctoral researcher at Washington University, Caltech, and Northwestern. He obtained his Ph.D. from Brown University in 2022. His research focuses on developing experimental, computational, and AI tools to design resilient and sustainable nano-bio-materials for personalized healthcare and engineering applications. His research has been published in leading journals including *Advanced Materials*, *Science Advances*, *Journal of the Mechanics and Physics of Solids*, and *Applied Mechanics Reviews*.
    design:
      columns: "1"

  # ===== PUBLICATIONS =====
  - block: publications
    content:
      title: "Selected Publications"
      items:
        - title: "Characterization and Inverse Design of Stochastic Mechanical Metamaterials Using Neural Operators"
          authors: "H. Jin, B. Zhang, Q. Cao, E. Zhang, A. Bora, S. Krishnaswamy, G.E. Karniadakis, H.D. Espinosa"
          journal: "Advanced Materials"
          year: "2025"
          doi: "https://doi.org/10.1002/adma.202420063"
        - title: "Recent advances and applications of machine learning in experimental solid mechanics: A review"
          authors: "H. Jin, E. Zhang, H.D. Espinosa†"
          journal: "Applied Mechanics Reviews"
          year: "2023"
          doi: "https://doi.org/10.1115/1.4062966"
        - title: "Dynamic fracture of a bicontinuously nanostructured copolymer: A deep-learning analysis of big-data-generating experiment"
          authors: "H. Jin, T. Jiao, R.J. Clifton, K.-S. Kim†"
          journal: "Journal of the Mechanics and Physics of Solids"
          year: "2022"
          doi: "https://doi.org/10.1016/j.jmps.2022.104898"
        - title: "Ultrastrong colloidal crystal metamaterials engineered with DNA"
          authors: "Y. Li*, H. Jin*, W. Zhou, Z. Wang, Z. Lin, C.A. Mirkin†, H.D. Espinosa†"
          journal: "Science Advances"
          year: "2023"
          doi: "https://doi.org/10.1126/sciadv.adj8103"
        - title: "Identifying constitutive parameters for complex hyperelastic materials using physics-informed neural networks"
          authors: "S. Song, H. Jin†"
          journal: "Soft Matter"
          year: "2024"
          doi: "https://doi.org/10.1039/D4SM00001C"

  # ===== PEOPLE & OPENINGS CTA =====
  - block: markdown
    content:
      text: |
        <div style="display: flex; gap: 2rem; justify-content: center; margin: 3rem 0;">
          <a href="/team/" style="background: #2563eb; color: white; padding: 1rem 2rem; border-radius: 8px; text-decoration: none; font-weight: 600; transition: all 0.3s;">Meet the team →</a>
          <a href="/openings/" style="background: #2563eb; color: white; padding: 1rem 2rem; border-radius: 8px; text-decoration: none; font-weight: 600; transition: all 0.3s;">Join the lab →</a>
        </div>
    design:
      columns: "1"
---