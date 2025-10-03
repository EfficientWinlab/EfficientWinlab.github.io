---
title: ""  
date: 2022-10-24
type: landing

sections:
  # Hero section with two columns
  - block: hero
    content:
      text: |
        <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; width: 100%;">

          <!-- Left column: logos and WINLAB name -->
          <div style="flex: 1 1 50%; text-align: center; padding-right: 10px;">
            <img src="nsf.png" alt="NSF" style="height:140px; margin-bottom: 20px;">
            <img src="winlab.png" alt="WINLAB" style="height:140px; margin-bottom: 20px;">
            <div style="font-weight: bold; font-size: 18px;">Wireless Information Network Laboratory (WINLAB)</div>
          </div>

          <!-- Right column: project title and paragraph -->
          <div style="flex: 1 1 50%; padding-left: 10px; text-align: left;">
            <h1 style="font-size: 2em; margin-bottom: 15px;">BackscattEr FabrIC For MultidImensional Spectrum Situational Awareness and Protection</h1>
            <p style="font-size: 1em; line-height: 1.5;">
              The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
            </p>
          </div>

        </div>

  # Full-width image below the two columns
  - block: markdown
    content:
      text: |
        <div style="text-align: center; margin-top: 30px;">
          <img src="efficient.png" alt="Efficient" style="max-width: 80%; height: auto; border-radius: 8px;">
        </div>

  # Publications
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

  # CTA
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
