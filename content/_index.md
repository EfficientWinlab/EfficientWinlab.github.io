---
# Leave the browser tab title unchanged
title: ""  
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      # Replace the top-left site title with an icon
      title: '<img src="icon.png" alt="Site Icon" style="height:40px;">'
      text: |
        <br>
        <img src="nsf.png" alt="NSF" style="height:80px; margin-right:20px;">
        <img src="winlab.png" alt="WINLAB" style="height:80px;">
        <br><br>
        BackscattEr FabrIC For MultidImensional
        SpEctrum SituatioNal AwarEness and ProTection
  
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
