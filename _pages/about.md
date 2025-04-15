---
permalink: /
title: "🌈Hello, I'm Jo-Ku Cheng!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

🧑‍🎓 I'm a final year master student at [Peking University, School of Mathematical Sciences](http://english.math.pku.edu.cn). Majoring in Applied Mathematics under the supervision of [Prof. Jinwen Ma](https://www.math.pku.edu.cn/teachers/jwma/homepage/).

🧐 My research interests include multi-modal reasoning and natural language processing with a particular focus on using synthetic data to enhance the performance of LLMs.

📑 I'am currently working towards my Master's Thesis in the field of developing a unified multi-modal large model that integrates geometry diagram generation, problem-solving, and diagram understanding.

🥊🏋️ I am also interested in doing sports.  I do <a href="/images/boxing.png">boxing</a> and <a href="/images/weight.png">crossfit</a>.

# Selected Experience
### **GeoUni: A Unified Model for Generating Geometry Diagrams, Problems and Problem Solutions** 
![overview](/images/overviewgeoouni.png)
[Paper](http://arxiv.org/abs/2504.10146) 
- Proposed the first unified multi-modal geometry expert model, GeoUni,capable of solving geometry problems, generating precise geometric diagrams using both formal and natural language, and creating geometry problems based
on knowledge points. 
- Proposed Geo-MAGVIT, a module specifically designed for the tokenization of geometric diagrams. By introducing topo-structural awareness loss and text region loss, it significantly improves the precision of geometry structure and text reconstruction.
- Combined GRPO and LoRA to train the Geo-Reasoning-Adapter, which effectively boosts geometric reasoning capability and seamlessly integrates into the unified model architecture.
- Established a novel diagram generation evaluation metrics, which includes the Geometry Semantic Matching Scores (GSMSs) and Geometry Pixel Matching Score (GPMS) to comprehensively evaluate the diagram generation task.

### **Diagram Formalization Enhanced Geometry Problem Solver**  
![pipeline](/images/pipeline.png)  
[Project Homepage](https://github.com/zezeze97/DFE-GPS) | [Dataset](https://huggingface.co/datasets/JO-KU/SynthGeo228K) | [Paper](https://arxiv.org/pdf/2409.04214) | [Video](https://youtu.be/kI6_DDXweWE?si=q6kwaekFNJjUinyD)
- Designed a multimodal framework integrating visual features and geometric formal languages for solving complex geometry problems.  
- Proposed a synthetic data approach (SynthGeo228K dataset) for improving model training and diagram interpretation.  
- Achieved an accuracy of 82.38% on the publicly available FormalGeo7k dataset, significantly outperforming existing multi-modal and language models, including GPT-4.
