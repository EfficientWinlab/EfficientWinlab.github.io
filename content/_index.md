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
        <div style="display: flex; align-items: flex-start; gap: 60px; max-width: 7000px; margin: 0 auto; padding: 40px 60px; box-sizing: border-box;">

          <!-- Left column: Sponsors -->
          <div style="flex: 0 0 220px; display: flex; flex-direction: column; gap: 30px;">

            <div style="text-align: center;">
              <a href="https://www.nsf.gov/awardsearch/show-award?AWD_ID=2433991/" target="_blank">
                <img src="nsf.png" alt="NSF" style="height:80px; width:auto; max-width:100%;">
                <div style="font-weight:bold; text-align:center;">National Science Foundation (NSF)</div>
              </a>
            </div>

            <div style="text-align: center;">
              <a href="https://soe.rutgers.edu/" target="_blank">
                <img src="rutgers_eng.png" alt="SOE" style="height:80px; width:auto; max-width:100%;">
                <div style="font-weight:bold; text-align:center;">Rutgers - New Brunswick School of Engineering</div>
              </a>
            </div>

            <div style="text-align: center;">
              <a href="https://winlab.rutgers.edu/" target="_blank">
                <img src="winlab.png" alt="WINLAB" style="height:80px; width:auto; max-width:100%;">
                <div style="font-weight:bold; text-align:center;">Wireless Information Network Laboratory (WINLAB)</div>
              </a>
            </div>

          </div>

          <!-- Right column: Main content -->
          <div style="flex: 1; max-width: 640px;">

            <!-- Title -->
            <h1 style="text-align: center; margin-bottom: 30px; font-size: 2.5em;">
              EFFICIENT: Backscatter Fabric For Multidimensional Spectrum Situational Awareness and Protection
            </h1>

            <!-- Main Image -->
            <div style="max-width: 100%; margin: 0 auto 30px;">
              <img src="efficient.png" alt="Efficient" style="width: 100%; height: auto; max-width: 1200px; display: block;">
            </div>

            <!-- Text -->
            <p style="text-align: center; margin-bottom: 40px; font-size: 1.1em; line-height: 1.6;">
              The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
            </p>

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
