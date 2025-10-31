---
# Leave the browser tab title unchanged
title: ""  
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: ""
      text: |
        <div style="max-width: 1200px; margin: 0 auto; padding: 40px 60px; box-sizing: border-box;">
          <h1 style="text-align: center;">EFFICIENT: Backscatter Fabric …</h1>
          <img src="efficient.png" alt="Efficient" style="width:100%; max-width:100%; display:block; margin: 0 auto;">
          <p style="text-align: center;">The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.</p>
          <div style="display: flex; justify-content: center; gap: 80px; flex-wrap: wrap;">
            <div style="text-align: center;">
              <img src="nsf.png" alt="NSF" style="height:80px;">
              <div style="font-weight:bold;">National Science Foundation (NSF)</div>
            </div>
            <div style="text-align: center;">
              <img src="winlab.png" alt="WINLAB" style="height:80px;">
              <div style="font-weight:bold;">Wireless Information Network Laboratory (WINLAB)</div>
            </div>
          </div>
        </div>
    design:
      columns: 1


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
