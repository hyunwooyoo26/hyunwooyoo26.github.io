---
layout: default
title: Home
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

<div class="profile-layout">

<aside class="sidebar">
  <img src="{{ '/assets/img/profile.jpg' | relative_url }}" class="profile-img" alt="Profile photo">

  <h1>Hyunwoo Yoo</h1>
  <p class="position">PhD Candidate at Drexel University</p>

  <nav class="links">
    <a href="mailto:hyunwooyoo26@email.com">Email</a>
    <a href="https://scholar.google.com/">Google Scholar</a>
    <a href="https://github.com/username">GitHub</a>
    <a href="https://linkedin.com/in/username">GitHub</a>
    <a href="https://linkedin.com/in/username">LinkedIn</a>
  </nav>
</aside>

<main class="content">

<section>
  <h2>About</h2>

  <p>
    Hi, I’m an PhD candidate at
    <a href="https://drexel.edu">Drexel University</a>, advised by Prof.
    <a href="https://drexel.edu/engineering/about/faculty-staff/R/rosen-gail/">Prof. Gail Rosen</a>. My research focuses on developing reliable and practical large language models 
    for biomedical and scientific applications. I am particularly interested in
    biomedical NLP, bioinformatics, multimodal learning, and trustworthy evaluation
    of language models in high-stakes domains.
  </p>



  <p>
  Previously, I worked as a machine learning software engineer at
  TmaxSoft and Hyperlounge, where I built
  applied NLP systems for document understanding, information retrieval,
  semantic search, OCR enhancement, chatbot improvement, business data crawling,
  and automatic summarization.
</p>

<p>
  My research interests lie in making large language models more
  <em>reliable</em>, <em>interpretable</em>, and <em>useful for biomedical and scientific discovery</em>:
</p>

<ul>
  <li>
    <strong>BioNLP and biomedical foundation models</strong> for clinical text,
    microbial metadata, antimicrobial resistance, and biomedical decision support.
  </li>
  <li>
    <strong>Trustworthy LLM evaluation</strong>, including counterfactual auditing,
    robustness analysis, demographic sensitivity, cultural bias, and medical-advice evaluation.
  </li>
  <li>
    <strong>Multimodal scientific AI</strong>, including text, speech, vision,
    sequence, and biological data for classification, retrieval, and generation.
  </li>
  <li>
    <strong>AI for scientific and drug discovery</strong>, including retrieval-augmented modeling,
    biological representation learning, protein and sequence analysis, and domain-informed architectures.
  </li>
</ul>
</section>

<section>
  <h2>Work Experience</h2>

  <div class="experience">
    <div>
      <strong>Hyperlounge</strong><br>
      Software Engineer, 
    </div>
    <div class="meta">
      2022.10 – 2023.02<br>
      Seoul, South Korea
    </div>
  </div>

  <div class="experience">
    <div>
      <strong>TmaxSoft</strong><br>
      Machine Learning Software Engineer, 
    </div>
    <div class="meta">
      2019.07 – 2022.10<br>
      Gyeonggi, South Korea
    </div>
  </div>
</section>

<section>
  <h2>Selected Publications</h2>

  <article class="paper">
    <h3>Cross-Modal Generative Augmentation for Multimodal Biological Classification</h3>
    <p><strong>H. Yoo</strong>, E. Soufleri, D. Ravikumar, and G. Rosen</p>
    <p class="venue">TMLR, 2026</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>CliniCAST: Benchmarking Acoustic Grounding and Text Dominance in Medical Triage</h3>
    <p>K. Kim*, <strong>H. Yoo*</strong>, J. Choi, G. Rosen, K. Kim, and B. Suh</p>
    <p class="venue">Findings of ACL, 2026</p>
    <p class="note">*Equal contribution</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>Visual Interference in Speech Evaluation: Cultural Asymmetry and Cross-Modal Bias in MLLMs</h3>
    <p>K. Kim*, <strong>H. Yoo*</strong>, J. Choi, G. Rosen, and B. Suh</p>
    <p class="venue">Findings of ACL, 2026</p>
    <p class="note">*Equal contribution</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>When Demographic Sensitivity Isn't What It Seems: Baseline-Aware Counterfactual Audits for Clinical NLP</h3>
    <p><strong>H. Yoo</strong></p>
    <p class="venue">BioNLP at ACL, 2026</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>Counterfactual Auditing of Cross-Cultural Variation in LLM-Generated Medical Advice</h3>
    <p><strong>H. Yoo</strong> and G. Rosen</p>
    <p class="venue">Stereacult at ACL, 2026</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>Interpretable Metadata-Based Microbial Risk Prediction Using Large Language Models</h3>
    <p><strong>H. Yoo</strong> and G. Rosen</p>
    <p class="venue">ACM BCB, 2025</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>Can Large Language Models Classify and Generate Antimicrobial Resistance Genes?</h3>
    <p><strong>H. Yoo</strong>, H. Shin, and G. Rosen</p>
    <p class="venue">BioNLP at ACL, 2025</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>Enhancing Antimicrobial Drug Resistance Classification by Integrating Sequence-Based and Text-Based Representations</h3>
    <p><strong>H. Yoo</strong>, B. Sokhansanj, and J. R. Brown</p>
    <p class="venue">BioNLP at ACL, 2025</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>Exploring Adversarial Robustness in Classification Tasks using DNA Language Models</h3>
    <p><strong>H. Yoo</strong>, H. Shin, K. Xu, and G. Rosen</p>
    <p class="venue">GenBio at ICML, 2025</p>
    <a class="button" href="#">Paper</a>
  </article>

  <article class="paper">
    <h3>Predicting Microbial Ontology and Pathogen Risk from Environmental Metadata with Large Language Models</h3>
    <p><strong>H. Yoo</strong> and G. Rosen</p>
    <p class="venue">GenBio at ICML, 2025</p>
    <a class="button" href="#">Paper</a>
  </article>
</section>

</main>

</div>
