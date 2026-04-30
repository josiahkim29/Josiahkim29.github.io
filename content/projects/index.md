---
title: Projects
date: 2025-07-29
---

<style>
.proj-card { transition: transform 0.28s ease, box-shadow 0.28s ease; }
.proj-card:hover { transform: translateY(-8px); }
.proj-card-blue:hover  { box-shadow: 0 16px 40px rgba(59,130,246,0.28); }
.proj-card-teal:hover  { box-shadow: 0 16px 40px rgba(16,185,129,0.28); }
.proj-card-purple:hover{ box-shadow: 0 16px 40px rgba(139,92,246,0.25); }
.proj-card-orange:hover{ box-shadow: 0 16px 40px rgba(249,115,22,0.25); }
.proj-card-rose:hover  { box-shadow: 0 16px 40px rgba(244,63,94,0.25); }
.proj-btn { display:inline-block; font-size:0.8rem; font-weight:700; padding:0.4rem 1rem; border-radius:20px; text-decoration:none; transition: opacity 0.2s; }
.proj-btn:hover { opacity:0.82; }
</style>

<!-- ═══════════════ HERO BANNER ═══════════════ -->
<div style="position:relative; border-radius:20px; overflow:hidden; margin:0 0 4rem; min-height:300px;">
  <img src="/images/ai-projects.jpg" alt="AI and machine learning"
       style="position:absolute; inset:0; width:100%; height:100%; object-fit:cover; object-position:center;" />
  <div style="position:absolute; inset:0; background:linear-gradient(135deg, rgba(10,22,40,0.88) 0%, rgba(10,22,40,0.55) 100%);"></div>
  <div style="position:relative; z-index:1; padding:3.5rem 3rem;">
    <p style="font-size:0.8rem; font-weight:700; color:#67e8f9; text-transform:uppercase; letter-spacing:0.14em; margin:0 0 0.75rem;">Research · Engineering · Innovation</p>
    <h1 style="font-size:2.5rem; font-weight:800; line-height:1.15; color:white; margin:0 0 1rem; max-width:580px;">Building at the frontier of AI and data science.</h1>
    <p style="font-size:1.05rem; color:#cbd5e1; line-height:1.8; max-width:560px; margin:0;">A selection of projects spanning machine learning, recommender systems, ecological modelling, and the open-source tools that power modern AI research.</p>
  </div>
</div>

<!-- ═══════════════ ORIGINAL PROJECTS ═══════════════ -->
<h2 style="font-size:1.6rem; font-weight:700; margin:0 0 1.75rem; padding-top:0.5rem;">Research &amp; Engineering Projects</h2>

<div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(300px, 1fr)); gap:1.75rem; margin-bottom:4rem;">

  <!-- DL4Ecology -->
  <div class="proj-card proj-card-teal"
       style="background:linear-gradient(135deg,#f0fdf4,#dcfce7); border-top:4px solid #10b981; border-radius:16px; padding:2rem; box-shadow:0 3px 12px rgba(16,185,129,0.12);">
    <div style="font-size:2.2rem; margin-bottom:1rem;">🌿</div>
    <h3 style="font-size:1.1rem; font-weight:700; margin:0 0 0.4rem;">Deep Learning for Ecology</h3>
    <p style="font-size:0.82rem; color:#065f46; font-weight:600; margin:0 0 0.85rem;">AIMS South Africa · 2024</p>
    <p style="font-size:0.88rem; color:#374151; line-height:1.75; margin:0 0 1.25rem;">Applying deep learning models to ecological classification and species detection tasks. Explores convolutional and transformer-based architectures for biodiversity monitoring across African ecosystems.</p>
    <div style="display:flex; flex-wrap:wrap; gap:0.4rem; margin-bottom:1.25rem;">
      <span style="font-size:0.72rem; font-weight:600; background:#bbf7d0; color:#065f46; padding:0.2rem 0.55rem; border-radius:10px;">Python</span>
      <span style="font-size:0.72rem; font-weight:600; background:#bbf7d0; color:#065f46; padding:0.2rem 0.55rem; border-radius:10px;">PyTorch</span>
      <span style="font-size:0.72rem; font-weight:600; background:#bbf7d0; color:#065f46; padding:0.2rem 0.55rem; border-radius:10px;">Computer Vision</span>
      <span style="font-size:0.72rem; font-weight:600; background:#bbf7d0; color:#065f46; padding:0.2rem 0.55rem; border-radius:10px;">Ecology</span>
    </div>
  </div>

  <!-- ML at Scale / RecommenderSystem -->
  <div class="proj-card proj-card-blue"
       style="background:linear-gradient(135deg,#eff6ff,#dbeafe); border-top:4px solid #3b82f6; border-radius:16px; padding:2rem; box-shadow:0 3px 12px rgba(59,130,246,0.12);">
    <div style="font-size:2.2rem; margin-bottom:1rem;">🎬</div>
    <h3 style="font-size:1.1rem; font-weight:700; margin:0 0 0.4rem;">Movie Recommender System — ML at Scale</h3>
    <p style="font-size:0.82rem; color:#1e40af; font-weight:600; margin:0 0 0.85rem;">AIMS South Africa · 2024</p>
    <p style="font-size:0.88rem; color:#374151; line-height:1.75; margin:0 0 1.25rem;">A scalable movie recommender system using Alternating Least Squares (ALS) matrix factorisation, capable of delivering personalised recommendations from both implicit and explicit user feedback at scale.</p>
    <div style="display:flex; flex-wrap:wrap; gap:0.4rem; margin-bottom:1.25rem;">
      <span style="font-size:0.72rem; font-weight:600; background:#bfdbfe; color:#1e40af; padding:0.2rem 0.55rem; border-radius:10px;">Python</span>
      <span style="font-size:0.72rem; font-weight:600; background:#bfdbfe; color:#1e40af; padding:0.2rem 0.55rem; border-radius:10px;">PySpark</span>
      <span style="font-size:0.72rem; font-weight:600; background:#bfdbfe; color:#1e40af; padding:0.2rem 0.55rem; border-radius:10px;">ALS</span>
      <span style="font-size:0.72rem; font-weight:600; background:#bfdbfe; color:#1e40af; padding:0.2rem 0.55rem; border-radius:10px;">Collaborative Filtering</span>
    </div>
    <a class="proj-btn" href="https://github.com/josiahkim29/mlAatScale" target="_blank"
       style="background:#3b82f6; color:white;">View on GitHub →</a>
  </div>

</div>

<!-- ═══════════════ TOOLS & FRAMEWORKS ═══════════════ -->
<h2 style="font-size:1.6rem; font-weight:700; margin:0 0 0.6rem; padding-top:1rem; border-top:2px solid #f3f4f6;">Tools &amp; Frameworks</h2>
<p style="font-size:0.95rem; color:#6b7280; margin:0 0 1.75rem;">Open-source libraries at the core of my research and engineering stack.</p>

<div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(270px, 1fr)); gap:1.5rem;">

  <!-- PyTorch -->
  <div class="proj-card proj-card-orange"
       style="background:linear-gradient(135deg,#fff7ed,#fed7aa); border-top:4px solid #f97316; border-radius:16px; padding:1.75rem; box-shadow:0 3px 12px rgba(249,115,22,0.12);">
    <div style="font-size:2rem; margin-bottom:0.85rem;">🔥</div>
    <h3 style="font-size:1rem; font-weight:700; margin:0 0 0.35rem;">PyTorch</h3>
    <p style="font-size:0.88rem; color:#374151; line-height:1.7; margin:0 0 1rem;">Python deep learning framework used across research projects — from computer vision models to weather prediction experiments with strong GPU acceleration.</p>
    <div style="display:flex; flex-wrap:wrap; gap:0.4rem; margin-bottom:1rem;">
      <span style="font-size:0.72rem; font-weight:600; background:#fed7aa; color:#9a3412; padding:0.2rem 0.55rem; border-radius:10px;">Deep Learning</span>
      <span style="font-size:0.72rem; font-weight:600; background:#fed7aa; color:#9a3412; padding:0.2rem 0.55rem; border-radius:10px;">GPU</span>
      <span style="font-size:0.72rem; font-weight:600; background:#fed7aa; color:#9a3412; padding:0.2rem 0.55rem; border-radius:10px;">Tensors</span>
    </div>
    <a class="proj-btn" href="https://github.com/pytorch/pytorch" target="_blank"
       style="background:#f97316; color:white;">GitHub →</a>
  </div>

  <!-- Pandas -->
  <div class="proj-card proj-card-purple"
       style="background:linear-gradient(135deg,#faf5ff,#ede9fe); border-top:4px solid #8b5cf6; border-radius:16px; padding:1.75rem; box-shadow:0 3px 12px rgba(139,92,246,0.12);">
    <div style="font-size:2rem; margin-bottom:0.85rem;">🐼</div>
    <h3 style="font-size:1rem; font-weight:700; margin:0 0 0.35rem;">Pandas</h3>
    <p style="font-size:0.88rem; color:#374151; line-height:1.7; margin:0 0 1rem;">Flexible and powerful data analysis and manipulation library for Python. The foundation of every data pipeline and exploratory analysis in my workflow.</p>
    <div style="display:flex; flex-wrap:wrap; gap:0.4rem; margin-bottom:1rem;">
      <span style="font-size:0.72rem; font-weight:600; background:#ddd6fe; color:#5b21b6; padding:0.2rem 0.55rem; border-radius:10px;">Data Analysis</span>
      <span style="font-size:0.72rem; font-weight:600; background:#ddd6fe; color:#5b21b6; padding:0.2rem 0.55rem; border-radius:10px;">DataFrames</span>
      <span style="font-size:0.72rem; font-weight:600; background:#ddd6fe; color:#5b21b6; padding:0.2rem 0.55rem; border-radius:10px;">Python</span>
    </div>
    <a class="proj-btn" href="https://github.com/pandas-dev/pandas" target="_blank"
       style="background:#8b5cf6; color:white;">GitHub →</a>
  </div>

  <!-- scikit-learn -->
  <div class="proj-card proj-card-rose"
       style="background:linear-gradient(135deg,#fff1f2,#ffe4e6); border-top:4px solid #f43f5e; border-radius:16px; padding:1.75rem; box-shadow:0 3px 12px rgba(244,63,94,0.12);">
    <div style="font-size:2rem; margin-bottom:0.85rem;">⚙️</div>
    <h3 style="font-size:1rem; font-weight:700; margin:0 0 0.35rem;">scikit-learn</h3>
    <p style="font-size:0.88rem; color:#374151; line-height:1.7; margin:0 0 1rem;">Python machine learning library built on SciPy. Used for classical ML pipelines, model evaluation, and benchmarking alongside deep learning approaches.</p>
    <div style="display:flex; flex-wrap:wrap; gap:0.4rem; margin-bottom:1rem;">
      <span style="font-size:0.72rem; font-weight:600; background:#fecdd3; color:#9f1239; padding:0.2rem 0.55rem; border-radius:10px;">ML Pipelines</span>
      <span style="font-size:0.72rem; font-weight:600; background:#fecdd3; color:#9f1239; padding:0.2rem 0.55rem; border-radius:10px;">Classification</span>
      <span style="font-size:0.72rem; font-weight:600; background:#fecdd3; color:#9f1239; padding:0.2rem 0.55rem; border-radius:10px;">Evaluation</span>
    </div>
    <a class="proj-btn" href="https://github.com/scikit-learn/scikit-learn" target="_blank"
       style="background:#f43f5e; color:white;">GitHub →</a>
  </div>

</div>
