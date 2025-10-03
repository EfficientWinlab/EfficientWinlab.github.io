---
# Leave the browser tab title unchanged
title: ""  
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      text: |
        <div style="text-align: center; max-width: 800px; margin: 0 auto;">

          <!-- Project title -->
          <h1 style="font-size: 2.5em; margin-bottom: 15px;">
            BackscattEr FabrIC For MultidImensional Spectrum Situational Awareness and Protection
          </h1>

          <!-- Project description -->
          <p style="font-size: 1.1em; line-height: 1.5; margin-bottom: 20px;">
            The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
          </p>

          <!-- Image -->
          <img src="efficient.png" alt="Efficient" style="width:100%; max-width:400px; display:block; margin: 20px auto;">

          <!-- Logos side by side with names below -->
          <div style="display: flex; justify-content: center; gap: 50px; margin-top: 30px; flex-wrap: wrap;">

            <!-- NSF logo and name -->
            <div style="text-align: center;">
              <img src="nsf.png" alt="NSF" style="height:80px; display:block; margin-bottom: 10px;">
              <div style="font-weight: bold; font-size: 16px;">National Science Foundation (NSF)</div>
            </div>

            <!-- WINLAB logo and name -->
            <div style="text-align: center;">
              <img src="winlab.png" alt="WINLAB" style="height:80px; display:block; margin-bottom: 10px;">
              <div style="font-weight: bold; font-size: 16px;">Wireless Information Network Laboratory (WINLAB)</div>
            </div>

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
