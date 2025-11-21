---
# Leave the browser tab title unchanged
title: ""  
date: 2022-10-24
type: landing

sections:

  # =============================
  # Main content with sponsors
  # =============================
  - block: markdown
    content:
      text: |
        <div style="display: flex; align-items: flex-start; gap: 40px;">

          <!-- Sponsors column (left) -->
          <div style="flex: 0 0 200px; display: flex; flex-direction: column; gap: 20px;">

            <div style="text-align: center;">
              <a href="https://www.nsf.gov/awardsearch/show-award?AWD_ID=2433991" target="_blank">
                <img src="nsf.png" alt="NSF" style="height:80px; width:auto;">
                <div><strong>National Science Foundation (NSF)</strong></div>
              </a>
            </div>

            <div style="text-align: center;">
              <a href="https://winlab.rutgers.edu/" target="_blank">
                <img src="winlab.png" alt="WINLAB" style="height:80px; width:auto;">
                <div><strong>Wireless Information Network Laboratory (WINLAB)</strong></div>
              </a>
            </div>

            <div style="text-align: center;">
              <a href="https://soe.rutgers.edu/" target="_blank">
                <img src="rutgers_eng.png" alt="Rutgers Engineering" style="height:80px; width:auto;">
                <div><strong>Rutgers - New Brunswick School of Engineering</strong></div>
              </a>
            </div>

          </div>

          <!-- Main content column (right) -->
          <div style="flex: 1; max-width: 640px;">
            <h1>EFFICIENT: Backscatter Fabric For Multidimensional Spectrum Situational Awareness and Protection</h1>

            <img src="efficient.png" alt="Efficient" style="width:100%; height:auto; margin-bottom: 20px;">

            <p>
              The next era of spectrum is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference. This project enables affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, and relevant spectrum sensing hardware. In addition, it targets mechanisms at the physical layer that provide radio waveform protection against unwanted interference without modifying existing infrastructure. Techniques include model-based and machine learning approaches, focusing on multidimensional awareness and interference protection. The work aims to demonstrate these principles in the FR3 band using the COSMOS Testbed for next-generation wireless coexistence scenarios.
            </p>
          </div>

        </div>

  # =============================
  # Recent Publications
  # =============================
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

  # =============================
  # Call-to-action
  # =============================
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

---
