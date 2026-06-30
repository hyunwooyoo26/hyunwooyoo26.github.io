---
layout: default
title: Home
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

<div class="profile-layout">

<aside class="sidebar">
  <img src="{{ '/assets/img/profile.jpg' | relative_url }}" class="profile-img" alt="Profile photo">

  <h1>Your Name</h1>
  <p class="position">PhD Student at University Name</p>

  <nav class="links">
    <a href="mailto:you@email.com">Email</a>
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
    Hi, I’m an incoming PhD student at
    <a href="#">University Name</a>, advised by Prof.
    <a href="#">Advisor Name</a>. My research focuses on making large language
    models more efficient and reliable.
  </p>

  <p>
    Previously, I worked as a research scientist at
    <a href="#">Company Name</a>, where I worked on applied LLM systems,
    information retrieval, and semantic parsing.
  </p>

  <p>
    My research interests lie in making large language models more
    <em>efficient</em> and <em>practical</em>:
  </p>

  <ul>
    <li><strong>Efficient training and inference</strong> methods for LLMs.</li>
    <li><strong>Real-world impact</strong>, including agents, retrieval, and scientific discovery.</li>
  </ul>
</section>

<section>
  <h2>Work Experience</h2>

  <div class="experience">
    <div>
      <strong> Research</strong><br>
      Research Intern
    </div>
    <div class="meta">
      2022.10 – 2023.02<br>
      Seoul, Korea
    </div>
  </div>

  <div class="experience">
    <div>
      <strong> Research</strong><br>
      Research Scientist
    </div>
    <div class="meta">
      2019.07 – 2022.10<br>
      Seongnam, Korea
    </div>
  </div>
</section>

<section>
  <h2>Publications</h2>

  <article class="paper">
    <h3>Paper Title: Dynamic Mixture Optimization of Instruction Tuning Collections</h3>
    <p><strong>Your Name</strong>, Coauthor A, Coauthor B</p>
    <p class="venue">ACL 2026 Findings</p>
    <a class="button" href="#">Paper</a>
  </article>
</section>

</main>

</div>
