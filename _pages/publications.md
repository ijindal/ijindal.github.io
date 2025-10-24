---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Load Font Awesome for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
/* Core text styling */
body {
  font-family: "Segoe UI", Helvetica, sans-serif;
  line-height: 1.6;
  color: #222;
}

/* --- NAVIGATION BAR --- */
.topic-nav {
  text-align: center;
  margin: 25px 0;
  padding: 10px 0;
  background: #f4f6fa;
  border-radius: 10px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}

.topic-nav a {
  color: SteelBlue;
  font-weight: 600;
  margin: 0 15px;
  text-decoration: none;
  font-size: 1.05em;
  transition: color 0.2s ease-in-out;
}

.topic-nav a:hover {
  color: DarkRed;
  text-decoration: underline;
}

/* Section Headers */
h2 {
  color: SteelBlue;
  border-bottom: 2px solid #ddd;
  padding-bottom: 4px;
  margin-top: 2em;
}

h3 {
  color: DarkRed;
  margin-top: 1.2em;
}

/* Publication card styling */
.pub-card {
  background: #f9f9fc;
  border-left: 4px solid SteelBlue;
  border-radius: 10px;
  padding: 10px 15px;
  margin: 10px 0 15px 0;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05);
}

.pub-card:hover {
  background: #f2f6ff;
}

/* Title links */
.pub-title a {
  color: #003399;
  font-weight: 600;
  text-decoration: none;
}

.pub-title a:hover {
  text-decoration: underline;
}

/* Metadata links */
.pub-links a {
  color: #0056b3;
  text-decoration: none;
  margin-right: 14px;
  font-size: 0.9em;
}

.pub-links a:hover {
  text-decoration: underline;
}

/* Icons */
.pub-links i {
  margin-right: 4px;
  color: SteelBlue;
}

/* Collapsible sections */
details {
  margin-top: 1em;
  margin-bottom: 1em;
}
summary {
  font-weight: 600;
  cursor: pointer;
  color: #333;
}
</style>

<body>

<!-- 🧭 Topic Navigation Bar -->
<div class="topic-nav">
  <a href="#nlp">Natural Language Processing</a> |
  <a href="#cv">Computer Vision</a> |
  <a href="#rl">Reinforcement Learning</a> |
  <a href="#it">Information Theory</a>
</div>

<p>
As a researcher, I have had the opportunity to work across computer vision, natural language processing, machine learning, deep learning, reinforcement learning, and information theory. Below, I categorize my publications by topic.
</p>

<!-- 🧠 NLP SECTION -->
<h2 id="nlp">Natural Language Processing</h2>

<div class="pub-card">
  <div class="pub-title">
    <b>[EACL Findings 2023]</b> 
    <a href="https://aclanthology.org/2023.findings-eacl.134/" target="_blank">PriMeSRL-Eval: A Practical Quality Metric for Semantic Role Labeling Systems Evaluation</a>
  </div>
  <div class="pub-authors">
    Ishan Jindal, Alexandre Rademaker, Khoi-Nguyen Tran, Huaiyu Zhu, Hiroshi Kanayama, Marina Danilevsky, Yunyao Li
  </div>
  <div class="pub-links">
    <a href="https://aclanthology.org/2023.findings-eacl.134/" target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
    <a href="https://github.com/UniversalPropositions/PriMeSRL-Eval" target="_blank"><i class="fa-solid fa-code"></i>Code</a>
    <a href="https://universalpropositions.github.io/" target="_blank"><i class="fa-solid fa-brain"></i>Project</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-title">
    <b>[NAACL 2022]</b> 
    <a href="https://aclanthology.org/2022.naacl-main.411/" target="_blank">Label Definitions Improve Semantic Role Labeling</a>
  </div>
  <div class="pub-authors">
    Li Zhang, Ishan Jindal, Yunyao Li
  </div>
  <div class="pub-links">
    <a href="https://aclanthology.org/2022.naacl-main.411/" target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
    <a href="https://github.com/System-T/LabelAwareSRL" target="_blank"><i class="fa-solid fa-code"></i>Code</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-title">
    <b>[LREC 2022]</b> 
    <a href="http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.181.pdf" target="_blank">Universal Proposition Bank 2.0.</a>
  </div>
  <div class="pub-authors">
    Ishan Jindal, Alexandre Rademaker, Michał Ulewicz, Linh Ha, Huyen Nguyen, Khoi-Nguyen Tran, Huaiyu Zhu, Yunyao Li
  </div>
  <div class="pub-links">
    <a href="http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.181.pdf"  target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
    <a href="https://github.com/UniversalPropositions"  target="_blank"><i class="fa-solid fa-code"></i>Code</a>
    <a href="https://universalpropositions.github.io/" target="_blank"><i class="fa-solid fa-brain"></i>Project</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-title">
    <b>[NAACL, SUKI 2022]</b> 
    <a href="https://suki-workshop.github.io/assets/paper/3.pdf" target="_blank">Is Semantic-aware BERT more Linguistically Aware? A Case Study on Natural Language Inference.</a>
  </div>
  <div class="pub-authors">
    Ling Liu, Ishan Jindal, Yunyao Li
  </div>
  <div class="pub-links">
    <a href="https://suki-workshop.github.io/assets/paper/3.pdf" target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
    <a href="https://github.com/System-T/LingBert" target="_blank"><i class="fa-solid fa-code"></i>Code</a>
  </div>
</div>
  
<div class="pub-card">
  <div class="pub-title">
    <b>[EMNLP Findings 2021]</b> 
    <a href="https://aclanthology.org/2020.findings-emnlp.279/" target="_blank">CLAR: A Cross-Lingual Argument Regularizer for Semantic Role Labeling.</a>
  </div>
  <div class="pub-authors">
    Ishan Jindal, Yunyao Li, Siddhartha Brahma, Huaiyu Zhu
  </div>
  <div class="pub-links">
    <a href="https://aclanthology.org/2020.findings-emnlp.279/" target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
  </div>
</div>
  
<div class="pub-card">
  <div class="pub-title">
    <b>[Preprint 2020]</b> 
    <a href="https://arxiv.org/abs/2011.14459" target="_blank">Improved Semantic Role Labeling using Parameterized Neighborhood Memory Adaptation.</a>
  </div>
  <div class="pub-authors">
    Ishan Jindal, Ranit Aharonov, Siddhartha Brahma, Huaiyu Zhu, Yunyao Li
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2011.14459" target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
  </div>
</div>


<!-- 🖼️ Computer Vision Section -->
<h2 id="cv">Computer Vision</h2>

<div class="pub-card">
  <div class="pub-title">
    <b>[CVPRW 2019]</b> 
    <a href="https://openaccess.thecvf.com/content_CVPRW_2019/papers/Deep%20Vision%20Workshop/Jindal_A_Nonlinear_Noise-aware_Quasi-clustering_Approach_to_Learning_Deep_CNNs_from_Noisy_Labels_CVPRW_2019_paper.pdf" target="_blank">
      A Nonlinear, Noise-aware, Quasi-clustering Approach to Learning Deep CNNs from Noisy Labels
    </a>
  </div>
  <div class="pub-authors">
    Ishan Jindal, Matthew Nokleby, Daniel Pressel, Xuewen Chen
  </div>
  <div class="pub-links">
    <a href="https://openaccess.thecvf.com/content_CVPRW_2019/papers/Deep%20Vision%20Workshop/Jindal_A_Nonlinear_Noise-aware_Quasi-clustering_Approach_to_Learning_Deep_CNNs_from_Noisy_Labels_CVPRW_2019_paper.pdf" target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
  </div>
</div>

<!-- 🔁 Reinforcement Learning -->
<h2 id="rl">Reinforcement Learning</h2>

<div class="pub-card">
  <div class="pub-title">
    <b>[IEEE Big Data 2018]</b> 
    <a href="https://ieeexplore.ieee.org/abstract/document/8622481" target="_blank">Optimizing Taxi Carpool Policies via Reinforcement Learning and Spatio-temporal Mining</a>
  </div>
  <div class="pub-authors">
    Ishan Jindal, Zhiwei Tony Qin, Xuewen Chen, Matthew Nokleby, Jieping Ye
  </div>
  <div class="pub-links">
    <a href="https://ieeexplore.ieee.org/abstract/document/8622481" target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
  </div>
</div>

<!-- 📡 Information Theory -->
<h2 id="it">Information Theory</h2>

<div class="pub-card">
  <div class="pub-title">
    <b>[ICASSP 2019]</b> 
    <a href="https://ieeexplore.ieee.org/abstract/document/8683804" target="_blank">Tensor Matched Kronecker-Structured Subspace Detection for Missing Information</a>
  </div>
  <div class="pub-authors">
    Ishan Jindal, Matthew Nokleby
  </div>
  <div class="pub-links">
    <a href="https://ieeexplore.ieee.org/abstract/document/8683804" target="_blank"><i class="fa-solid fa-file-pdf"></i>PDF</a>
  </div>
</div>

<a href="#top" style="display:block;text-align:right;margin-top:20px;">↑ Back to Top</a>

</body>
