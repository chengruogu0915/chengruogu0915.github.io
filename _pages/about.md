---
permalink: /
title: "🌈Hello, I'm Jo-Ku Cheng!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

🧑‍🎓 I'm a final year master student at [Peking University, School of Mathematical Sciences](http://english.math.pku.edu.cn). Majoring in Applied Mathematics under the supervision of [Prof. Jinwen Ma](https://www.math.pku.edu.cn/teachers/jwma/homepage/).

I am the Teaching Assistant for the undergraduate course 'Mathematical Modelling' at the School of Mathematical Sciences, Peking University.

🧐 My research interests include Multimodal Large Language Models (MLLMs) and Large Language Models (LLMs), with a particular focus on solving geometry problems.

🥊🏋️ I am also interested in doing sports.  I do <a href="/images/boxing.png">boxing</a> and <a href="/images/weight.png">crossfit</a>.


# Selected Experience
### **GeoUni: A Unified Model for Generating Geometry Diagrams, Problems and Problem Solutions** 
![overview](/images/overviewgeoouni.png){:style="width: 60%;"}

[Paper](http://arxiv.org/abs/2504.10146) 
- Proposed the first unified multi-modal geometry expert model, GeoUni,capable of solving geometry problems, generating precise geometric diagrams using both formal and natural language, and creating geometry problems based
on knowledge points. 
- Proposed Geo-MAGVIT, a module specifically designed for the tokenization of geometric diagrams. By introducing topo-structural awareness loss and text region loss, it significantly improves the precision of geometry structure and text reconstruction.
- Combined GRPO and LoRA to train the Geo-Reasoning-Adapter, which effectively boosts geometric reasoning capability and seamlessly integrates into the unified model architecture.
- Established a novel diagram generation evaluation metrics, which includes the Geometry Semantic Matching Scores (GSMSs) and Geometry Pixel Matching Score (GPMS) to comprehensively evaluate the diagram generation task.

### **Diagram Formalization Enhanced Geometry Problem Solver**  
![pipeline](/images/pipeline.png){:style="width: 60%;"}

[Project Homepage](https://github.com/zezeze97/DFE-GPS) | [Dataset](https://huggingface.co/datasets/JO-KU/SynthGeo228K) | [Paper](https://arxiv.org/pdf/2409.04214) 
<iframe width="560" height="315" src="https://www.youtube.com/embed/kI6_DDXweWE?si=q6kwaekFNJjUinyD" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
- Designed a multimodal framework integrating visual features and geometric formal languages for solving complex geometry problems.  
- Proposed a synthetic data approach (SynthGeo228K dataset) for improving model training and diagram interpretation.  
- Achieved an accuracy of 82.38% on the publicly available FormalGeo7k dataset, significantly outperforming existing multi-modal and language models, including GPT-4.