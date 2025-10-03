---
title: ""  
date: 2022-10-24
type: landing

sections:

  # CTA Image Paragraph: separate logos on left, text + CTA on right
  - block: cta_image_paragraph
    content:
      image: |
        <div style="display: flex; flex-direction: column; align-items: center;">
          <img src="nsf.png" alt="NSF" style="height:150px; margin-bottom: 20px;">
          <img src="winlab.png" alt="WINLAB" style="height:150px; margin-bottom: 20px;">
          <div style="font-weight: bold; font-size: 18px; margin-top: 10px;">Wireless Information Network Laboratory (WINLAB)</div>
        </div>
      image_alt: "NSF and WINLAB Logos"
      title: "BackscattEr FabrIC For MultidImensional Spectrum Situational Awareness and Protection"
      text: |
        The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
      cta_link: "./people/"
      cta_text: "Meet the team →"
      layout: "image-left" # image on the left, text + CTA on the right

  # Image below the CTA Image Paragraph
  - block: image
    content:
      image: "efficient.png"
      image_alt: "Efficient"
      caption: ""
      align: center

  # Collection block
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
---
