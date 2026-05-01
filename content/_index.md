---
title: ""
date: 2025-07-29
type: landing

design:
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: "Just Show Up!!"
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        image:
          filename: hero-background.jpg
          filters:
            brightness: 0.9
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: ''
      text: |-
        <style>
        .home-stat-item { text-align:center; padding:0.5rem 1rem; }
        .home-nav-card { display:flex; flex-direction:column; text-decoration:none; border-radius:16px; padding:1.75rem; transition:transform 0.28s ease, box-shadow 0.28s ease; }
        .home-nav-card:hover { transform:translateY(-8px); }
        .home-nav-green:hover  { box-shadow:0 16px 40px rgba(16,185,129,0.28); }
        .home-nav-blue:hover   { box-shadow:0 16px 40px rgba(59,130,246,0.28); }
        .home-nav-purple:hover { box-shadow:0 16px 40px rgba(139,92,246,0.28); }
        .home-nav-orange:hover { box-shadow:0 16px 40px rgba(249,115,22,0.28); }
        .home-nav-rose:hover   { box-shadow:0 16px 40px rgba(244,63,94,0.28); }
        .home-pub-card { transition:transform 0.28s ease, box-shadow 0.28s ease; }
        .home-pub-card:hover { transform:translateY(-6px); box-shadow:0 14px 36px rgba(16,185,129,0.22); }
        </style>

        <!-- STATS BAND -->
        <div style="background:#0f172a; border-radius:16px; padding:2rem 2.5rem; margin-bottom:4rem;">
          <div style="display:flex; flex-wrap:wrap; gap:1.5rem; justify-content:space-around; align-items:center;">
            <div class="home-stat-item">
              <div style="font-size:1.1rem; font-weight:800; color:#10b981; line-height:1.2;">Google DeepMind Scholar</div>
              <div style="font-size:0.72rem; color:#94a3b8; text-transform:uppercase; letter-spacing:0.1em; margin-top:0.25rem;">2024 – 2025</div>
            </div>
            <div style="width:1px; height:2.5rem; background:#1e293b; flex-shrink:0;"></div>
            <div class="home-stat-item">
              <div style="font-size:1.1rem; font-weight:800; color:#10b981; line-height:1.2;">Cum Laude</div>
              <div style="font-size:0.72rem; color:#94a3b8; text-transform:uppercase; letter-spacing:0.1em; margin-top:0.25rem;">MSc AI for Science</div>
            </div>
            <div style="width:1px; height:2.5rem; background:#1e293b; flex-shrink:0;"></div>
            <div class="home-stat-item">
              <div style="font-size:2rem; font-weight:800; color:#10b981; line-height:1;">5+</div>
              <div style="font-size:0.72rem; color:#94a3b8; text-transform:uppercase; letter-spacing:0.1em; margin-top:0.25rem;">Years in Tech</div>
            </div>
            <div style="width:1px; height:2.5rem; background:#1e293b; flex-shrink:0;"></div>
            <div class="home-stat-item">
              <div style="font-size:2rem; font-weight:800; color:#10b981; line-height:1;">7</div>
              <div style="font-size:0.72rem; color:#94a3b8; text-transform:uppercase; letter-spacing:0.1em; margin-top:0.25rem;">Leadership Roles</div>
            </div>
            <div style="width:1px; height:2.5rem; background:#1e293b; flex-shrink:0;"></div>
            <div class="home-stat-item">
              <div style="font-size:2rem; font-weight:800; color:#10b981; line-height:1;">2</div>
              <div style="font-size:0.72rem; color:#94a3b8; text-transform:uppercase; letter-spacing:0.1em; margin-top:0.25rem;">Publications</div>
            </div>
          </div>
        </div>

        <!-- RESEARCH FOCUS -->
        <div style="display:flex; flex-wrap:wrap; align-items:center; gap:3rem; margin-bottom:5rem;">

          <div style="flex:1.1; min-width:270px;">
            <p style="font-size:0.8rem; font-weight:700; color:#10b981; text-transform:uppercase; letter-spacing:0.14em; margin:0 0 0.75rem;">AI · Climate · Africa</p>
            <h2 style="font-size:2.2rem; font-weight:800; line-height:1.2; margin:0 0 1.1rem;">Building the next generation of weather intelligence for Africa.</h2>
            <p style="font-size:1.02rem; color:#6b7280; line-height:1.8; margin:0 0 1.75rem;">My research sits at the intersection of machine learning and atmospheric science. My thesis, PiggyCast, introduces a stacking-based ensemble that outperforms individual frontier AI weather models — with gains that grow as forecast lead time increases.</p>
            <a href="/publications/" style="display:inline-block; background:#10b981; color:white; font-size:0.85rem; font-weight:700; padding:0.55rem 1.5rem; border-radius:20px; text-decoration:none;">Explore My Research →</a>
          </div>

          <div style="flex:1; min-width:270px;">
            <div class="home-pub-card" style="background:linear-gradient(135deg,#f0fdf4,#dcfce7); border-left:5px solid #10b981; border-radius:16px; padding:1.75rem; box-shadow:0 4px 16px rgba(16,185,129,0.14);">
              <div style="display:flex; gap:0.5rem; margin-bottom:0.9rem; flex-wrap:wrap;">
                <span style="font-size:0.7rem; font-weight:700; background:#10b981; color:white; padding:0.2rem 0.65rem; border-radius:20px;">Preprint · 2025</span>
                <span style="font-size:0.7rem; font-weight:700; background:#fef9c3; color:#854d0e; padding:0.2rem 0.65rem; border-radius:20px;">⭐ Featured</span>
              </div>
              <h3 style="font-size:1rem; font-weight:800; line-height:1.35; margin:0 0 0.6rem;">PiggyCast: Improving Weather Prediction through Stacking-Based Ensemble AI</h3>
              <p style="font-size:0.86rem; color:#374151; line-height:1.7; margin:0 0 1rem;">A stacking ensemble trained on frontier AIWP model outputs to predict ERA5 variables — achieving notable RMSE improvements that grow with forecast lead time.</p>
              <div style="display:flex; flex-wrap:wrap; gap:0.4rem; margin-bottom:1rem;">
                <span style="font-size:0.7rem; font-weight:600; background:#bbf7d0; color:#065f46; padding:0.18rem 0.55rem; border-radius:8px;">Ensemble Learning</span>
                <span style="font-size:0.7rem; font-weight:600; background:#bbf7d0; color:#065f46; padding:0.18rem 0.55rem; border-radius:8px;">Climate AI</span>
                <span style="font-size:0.7rem; font-weight:600; background:#bbf7d0; color:#065f46; padding:0.18rem 0.55rem; border-radius:8px;">WeatherBench 2</span>
              </div>
              <a href="/publication/preprint/" style="font-size:0.8rem; font-weight:700; color:#10b981; text-decoration:none;">Read Paper →</a>
            </div>
          </div>

        </div>

        <!-- EXPLORE SECTIONS -->
        <div style="margin-bottom:5rem;">
        <p style="font-size:0.8rem; font-weight:700; color:#10b981; text-transform:uppercase; letter-spacing:0.14em; margin:0 0 0.6rem;">Explore</p>
        <h2 style="font-size:1.8rem; font-weight:800; margin:0 0 1.75rem;">There is more to see.</h2>
        <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(190px, 1fr)); gap:1.25rem;">
        <a class="home-nav-card home-nav-blue" href="/experience/" style="background:linear-gradient(135deg,#eff6ff,#dbeafe); border-top:4px solid #3b82f6; box-shadow:0 3px 12px rgba(59,130,246,0.1);"><span style="font-size:2rem; display:block; margin-bottom:0.75rem;">💼</span><span style="font-size:1rem; font-weight:700; color:#1e3a5f; display:block; margin-bottom:0.4rem;">Experience</span><span style="font-size:0.82rem; color:#475569; line-height:1.6; display:block;">Work history, education, skills, and awards.</span><span style="font-size:0.78rem; font-weight:700; color:#3b82f6; display:block; margin-top:1rem;">View →</span></a>
        <a class="home-nav-card home-nav-green" href="/projects/" style="background:linear-gradient(135deg,#f0fdf4,#dcfce7); border-top:4px solid #10b981; box-shadow:0 3px 12px rgba(16,185,129,0.1);"><span style="font-size:2rem; display:block; margin-bottom:0.75rem;">🛠️</span><span style="font-size:1rem; font-weight:700; color:#134e4a; display:block; margin-bottom:0.4rem;">Projects</span><span style="font-size:0.82rem; color:#475569; line-height:1.6; display:block;">Research projects and open-source tools.</span><span style="font-size:0.78rem; font-weight:700; color:#10b981; display:block; margin-top:1rem;">View →</span></a>
        <a class="home-nav-card home-nav-purple" href="/publications/" style="background:linear-gradient(135deg,#faf5ff,#ede9fe); border-top:4px solid #8b5cf6; box-shadow:0 3px 12px rgba(139,92,246,0.1);"><span style="font-size:2rem; display:block; margin-bottom:0.75rem;">📄</span><span style="font-size:1rem; font-weight:700; color:#2d1b69; display:block; margin-bottom:0.4rem;">Publications</span><span style="font-size:0.82rem; color:#475569; line-height:1.6; display:block;">Papers on AI, climate, and education.</span><span style="font-size:0.78rem; font-weight:700; color:#8b5cf6; display:block; margin-top:1rem;">View →</span></a>
        <a class="home-nav-card home-nav-orange" href="/talks/" style="background:linear-gradient(135deg,#fff7ed,#fed7aa); border-top:4px solid #f97316; box-shadow:0 3px 12px rgba(249,115,22,0.1);"><span style="font-size:2rem; display:block; margin-bottom:0.75rem;">🎤</span><span style="font-size:1rem; font-weight:700; color:#3b1f00; display:block; margin-bottom:0.4rem;">Talks</span><span style="font-size:0.82rem; color:#475569; line-height:1.6; display:block;">Public talks, panels, and science communication.</span><span style="font-size:0.78rem; font-weight:700; color:#f97316; display:block; margin-top:1rem;">View →</span></a>
        <a class="home-nav-card home-nav-rose" href="/leadership/" style="background:linear-gradient(135deg,#fff1f2,#ffe4e6); border-top:4px solid #f43f5e; box-shadow:0 3px 12px rgba(244,63,94,0.1);"><span style="font-size:2rem; display:block; margin-bottom:0.75rem;">🤝</span><span style="font-size:1rem; font-weight:700; color:#2d1b1b; display:block; margin-bottom:0.4rem;">Leadership</span><span style="font-size:0.82rem; color:#475569; line-height:1.6; display:block;">Community roles, civic service, and governance.</span><span style="font-size:0.78rem; font-weight:700; color:#f43f5e; display:block; margin-top:1rem;">View →</span></a>
        </div>
        </div>

        <!-- CONNECT CTA -->
        <div style="background:linear-gradient(135deg,#0f172a,#1e3a5f); border-radius:20px; padding:3rem 2.5rem; text-align:center;">
          <p style="font-size:0.8rem; font-weight:700; color:#10b981; text-transform:uppercase; letter-spacing:0.14em; margin:0 0 0.75rem;">Let's Connect</p>
          <h2 style="font-size:1.9rem; font-weight:800; color:white; margin:0 0 0.85rem;">Collaborate. Discuss. Build.</h2>
          <p style="font-size:1rem; color:#94a3b8; line-height:1.8; max-width:520px; margin:0 auto 2rem;">Whether you want to discuss research, explore a collaboration, or invite me to speak — I would love to hear from you.</p>
          <div style="display:flex; flex-wrap:wrap; gap:1rem; justify-content:center;">
            <a href="mailto:josiah@aims.ac.za"
               style="display:inline-block; background:#10b981; color:white; font-size:0.88rem; font-weight:700; padding:0.65rem 1.75rem; border-radius:20px; text-decoration:none;">Email Me →</a>
            <a href="https://www.linkedin.com/in/josiah-kimani-2a059319b/" target="_blank"
               style="display:inline-block; background:white; color:#0f172a; font-size:0.88rem; font-weight:700; padding:0.65rem 1.75rem; border-radius:20px; text-decoration:none;">LinkedIn →</a>
          </div>
        </div>
    design:
      columns: '1'
---
