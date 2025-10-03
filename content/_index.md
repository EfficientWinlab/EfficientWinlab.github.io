---
title: ""  
date: 2022-10-24
type: landing

sections:

  # CTA Image Paragraph: logos on left, text on right
  - block: cta_image_paragraph
    content:
      image: "nsf_winlab.png" # combine logos into one image or use CSS for multiple images
      image_alt: "NSF and WINLAB Logos"
      title: "BackscattEr FabrIC For MultidImensional Spectrum Situational Awareness and Protection"
      text: |
        The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
      cta_link: "./people/"
      cta_text: "Meet the team →"
      layout: "image-left" # places image on the left, text + CTA on the right

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
