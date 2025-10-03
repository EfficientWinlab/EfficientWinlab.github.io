---
# Leave the browser tab title unchanged
title: ""  
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      text: |
        <div style="display: flex; align-items: flex-start; justify-content: space-between; width: 100%;">
          
          <!-- Left column: logos and WINLAB name -->
          <div style="flex: 0 0 40%; text-align: center;">
            <img src="nsf.png" alt="NSF" style="height:120px; display:block; margin: 0 auto 15px auto;">
            <img src="winlab.png" alt="WINLAB" style="height:120px; display:block; margin: 0 auto 15px auto;">
            <div style="font-weight: bold; font-size: 16px;">Wireless Information Network Laboratory (WINLAB)</div>
          </div>

          <!-- Right column: project title and description -->
          <div style="flex: 0 0 55%; padding-left: 20px;">
            <h1 style="font-size: 2em; margin-bottom: 15px;">BackscattEr FabrIC For MultidImensional Spectrum Situational Awareness and Protection</h1>
            <p style="font-size: 1em; line-height: 1.5;">
              The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
            </p>
            <img src="efficient.png" alt="Efficient" style="width:100%; margin-top: 20px; border-radius: 8px;">
          </div>

        </div>
  
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

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
