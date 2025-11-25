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
        <div style="max-width: 8000px; margin: 0 auto; padding: 40px 60px; box-sizing: border-box;">

          <!-- Title -->
          <h1 style="text-align: center; margin-bottom: 30px; font-size: 2.5em;">
            EFFICIENT: Backscatter Fabric For Multidimensional Spectrum Situational Awareness and Protection
          </h1>

          <!-- Image (matches text width, responsive) -->
          <div style="max-width: 100%; margin: 0 auto 30px;">
            <img src="efficient.png" alt="Efficient" style="width: 100%; height: auto; max-width: 1200px; display: block;">
          </div>

          <!-- Text -->
          <p style="text-align: center; margin-bottom: 40px; font-size: 1.1em; line-height: 1.6;">
            Funded by the National Science Foundation under Award No. 
            <a href="https://www.nsf.gov/awardsearch/show-award/?AWD_ID=2433991&HistoricalAwards=false" target="_blank">
              2433991
            </a>,  this project explores the next era of spectrum, which is envisioned to have spatially and spectrally adjacent systems that are dynamic, resulting in frequent cross-system interference effects. A desired aspect of this vision and spectrum management, is to empower these systems to be able to autonomously adapt and optimize their transmissions and receptions. Mechanisms used in the current and past eras of spectrum management, such as cloud-based spectrum access systems (SAS), spectrum servers, cognitive radio primary/secondary coexistence, cooperative relay networks, multiuser-multiple input multiple output (MU-MIMO) systems, or more recently, reconfigurable intelligent surface (RIS)-assisted networks, have all run up against limitations owing to the cost and potential lack of scalability of such solutions. What is required is affordable, accurate, near-real-time spectrum situational awareness, including simple spectrum sensing algorithms, distributed mechanisms, limited channel state information (CSI) estimation overhead and relevant spectrum sensing hardware. Further, using such near-real-time spectrum situational awareness to devise mechanisms at the physical layer that provide some form of radio waveform protection against malicious or unwanted interference would be even better.

            To this end, the proposed research project develops affordable, accurate, near-real-time spectrum situational awareness to the changing environment using a fabric of backscatter radios. The spectrum situational awareness afforded by the backscatter fabric (e.g. signal powers, carrier frequencies, bandwidths and directions of arrivals of transmissions in a given spatial area) can be used to address the near-real-time spectrum usage information needed for facilitating different spectrum management regimes. The same fabric of backscatter radios can also be used to provide spectrum protection by actively canceling out interfering transmissions from both legitimate and malicious transmitters.
          </p>

          <!-- Logos side by side, responsive -->
          <div style="display: flex; justify-content: center; align-items: flex-start; gap: 80px; flex-wrap: wrap;">
            <div style="display: flex; flex-direction: column; align-items: center; gap: 10px; flex: 1 1 200px; max-width: 200px;">
              <a href="https://www.nsf.gov/awardsearch/show-award?AWD_ID=2433991/" target="_blank">
              <img src="nsf2.png" alt="NSF" style="height:80px; width:auto; max-width:100%;">
              <div style="font-weight:bold; text-align:center;">National Science Foundation (NSF)</div>
            </div>
            <div style="display: flex; flex-direction: column; align-items: center; gap: 10px; flex: 1 1 200px; max-width: 300px;">
              <a href="https://soe.rutgers.edu/" target="_blank">
              <img src="rutgers_eng2.png" alt="SOE" style="height:80px; width:auto; max-width:100%;">
              <div style="font-weight:bold; text-align:center;">Rutgers - New Brunswick School of Engineering</div>
            </div>
            <div style="display: flex; flex-direction: column; align-items: center; gap: 10px; flex: 1 1 200px; max-width: 400px;">
              <a href="https://winlab.rutgers.edu/" target="_blank">
              <img src="winlab.png" alt="WINLAB" style="height:80px; width:auto; max-width:100%;">
              <div style="font-weight:bold; text-align:center;">Wireless Information Network Laboratory (WINLAB)</div>
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
