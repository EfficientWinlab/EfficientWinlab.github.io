---
title: ""  
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      text: |
        <!-- Two-column layout -->
        <div style="display: flex; flex-wrap: wrap; width: 100%; align-items: flex-start; justify-content: space-between; gap: 20px;">

          <!-- Left column: logos -->
          <div style="flex: 1 1 300px; text-align: center;">
            <img src="nsf.png" alt="NSF" style="height:150px; margin-bottom: 20px;">
            <img src="winlab.png" alt="WINLAB" style="height:150px; margin-bottom: 20px;">
            <div style="font-weight: bold; font-size: 18px;">Wireless Information Network Laboratory (WINLAB)</div>
          </div>

          <!-- Right column: title and paragraph -->
          <div style="flex: 2 1 400px; padding-left: 20px; min-width: 250px;">
            <h1 style="font-size: 2em; margin-bottom: 15px;">
              BackscattEr FabrIC For MultidImensional Spectrum Situational Awareness and Protection
            </h1>
            <p style="font-size: 1em; line-height: 1.5;">
              The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
            </p>
          </div>

        </div>

        <!-- Image below the columns -->
        <div style="text-align: center; margin-top: 30px;">
          <img src="efficient.png" alt="Efficient" style="max-width: 80%; height: auto; border-radius: 8px;">
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
