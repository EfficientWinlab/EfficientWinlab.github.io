---
title: "BackscattEr FabrIC For MultidImensional Spectrum Situational Awareness and Protection"
date: 2022-10-24
type: landing

sections:

  # Hero Section: Logos left, text + CTA right
  - block: hero
    content:
      text: |
        <div style="display:flex; flex-wrap:wrap; gap:20px; align-items:flex-start;">

          <!-- Left column: logos -->
          <div style="flex:1 1 300px; text-align:center;">
            <img src="nsf.png" alt="NSF" style="height:150px; margin-bottom:20px;">
            <img src="winlab.png" alt="WINLAB" style="height:150px; margin-bottom:20px;">
            <div style="font-weight:bold; font-size:18px; margin-top:10px;">Wireless Information Network Laboratory (WINLAB)</div>
          </div>

          <!-- Right column: text + CTA -->
          <div style="flex:2 1 400px; min-width:250px; padding-left:20px;">
            <p style="font-size:1em; line-height:1.5;">
              The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
            </p>
            <a href="./people/" style="display:inline-block; margin-top:15px; padding:10px 20px; background:#007ACC; color:#fff; border-radius:5px; text-decoration:none;">Meet the team →</a>
          </div>

        </div>

  # Image Below Hero Section
  - block: image
    content:
      image: "efficient.png"
      image_alt: "Efficient"
      caption: ""
      align: center

  # Recent Publications via Collection Block
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

  # Team CTA
  - block: markdown
    content:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
