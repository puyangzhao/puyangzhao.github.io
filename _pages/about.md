---
permalink: /
title: ""
author_profile: true
classes: wide
redirect_from: 
  - /about/
  - /about.html
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Lora:ital,wght@0,400;0,600;1,400&display=swap');

.page__content { font-family: 'Inter', sans-serif; font-size: 0.92em; color: #2d2d2d; }

/* Hero */
.hero-banner { border-left: 3px solid #c0613a; padding: 1.1em 1.4em; margin-bottom: 1.8em; background: #fafafa; }
.hero-greeting { font-family: 'Lora', serif; font-size: 1.45em; font-weight: 600; color: #1a1a1a; margin: 0 0 0.45em 0; }
.hero-greeting span { color: #c0613a; }
.hero-pills { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 0.9em; }
.hero-pill { font-size: 0.75em; color: #555; background: #f0f0f0; border-radius: 3px; padding: 2px 8px; }
.hero-bio { font-size: 0.88em; line-height: 1.75; color: #333; margin: 0; }
.hero-bio strong { color: #c0613a; font-weight: 600; }

/* Section titles */
.warm-section-title { font-family: 'Lora', serif; font-size: 1.0em; font-weight: 600; color: #1a1a1a; margin: 1.8em 0 0.7em 0; padding-bottom: 0.3em; border-bottom: 1.5px solid #e8e8e8; display: block; letter-spacing: 0.01em; }
.warm-section-title span { color: #c0613a; margin-right: 6px; }

/* Research interests */
.research-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap: 8px; margin-bottom: 0.5em; }
.r-card { background: #fff; border-radius: 4px; padding: 10px 12px; border: 1px solid #e8e8e8; transition: border-color 0.2s, opacity 0.4s ease; opacity: 0; }
.r-card.visible { opacity: 1; }
.r-card:hover { border-color: #c0613a; }
.r-card-icon { font-size: 1.1em; margin-bottom: 4px; display: block; }
.r-card-title { font-weight: 600; font-size: 0.8em; color: #1a1a1a; margin-bottom: 3px; }
.r-card-desc { font-size: 0.76em; color: #666; line-height: 1.55; }

/* Education */
.edu-timeline { margin: 0.4em 0 1em; }
.edu-item { display: grid; grid-template-columns: 90px 1fr; gap: 12px; padding: 7px 0; border-bottom: 1px solid #f0f0f0; opacity: 0; transition: opacity 0.4s ease; }
.edu-item.visible { opacity: 1; }
.edu-item:last-child { border-bottom: none; }
.edu-period { font-size: 0.75em; font-weight: 600; color: #c0613a; padding-top: 2px; }
.edu-degree { font-weight: 600; color: #1a1a1a; font-size: 0.85em; margin: 0; }
.edu-school { color: #444; font-size: 0.8em; margin: 1px 0 0 0; }
.edu-advisor { color: #888; font-size: 0.75em; font-style: italic; margin: 1px 0 0 0; }

/* Publications */
.pub-tabs { display: flex; gap: 6px; margin-bottom: 0.9em; flex-wrap: wrap; }
.pub-tab { padding: 3px 12px; border-radius: 3px; border: 1px solid #ddd; background: transparent; font-family: 'Inter', sans-serif; font-size: 0.76em; font-weight: 500; color: #666; cursor: pointer; transition: all 0.15s ease; }
.pub-tab.active, .pub-tab:hover { background: #c0613a; border-color: #c0613a; color: white; }
.pub-card { padding: 9px 0; margin-bottom: 0; border-bottom: 1px solid #f0f0f0; display: grid; grid-template-columns: 36px 1fr auto; gap: 10px; align-items: start; transition: opacity 0.4s ease; opacity: 0; }
.pub-card.visible { opacity: 1; }
.pub-card:last-child { border-bottom: none; }
.pub-yr { font-size: 0.7em; font-weight: 600; color: #c0613a; text-align: center; padding-top: 2px; }
.pub-t { font-weight: 500; font-size: 0.84em; color: #1a1a1a; margin: 0 0 3px 0; line-height: 1.4; }
.pub-a { font-size: 0.76em; color: #666; margin: 0 0 2px 0; }
.pub-a b { color: #333; font-weight: 600; }
.pub-v { font-size: 0.74em; color: #999; font-style: italic; margin: 0; }
.pub-badge { font-size: 0.63em; font-weight: 600; padding: 2px 7px; border-radius: 3px; white-space: nowrap; align-self: flex-start; margin-top: 2px; }
.bj { background: #edf7ee; color: #2e7d32; border: 1px solid #c8e6c9; }
.bc { background: #e8f1fb; color: #1565c0; border: 1px solid #bbdefb; }
.bb { background: #fdf6e3; color: #b45309; border: 1px solid #fde68a; }

/* Contact */
.contact-box { background: #fafafa; border: 1px solid #e8e8e8; border-left: 3px solid #c0613a; padding: 1.1em 1.4em; margin-top: 0.5em; }
.contact-tagline { font-family: 'Lora', serif; font-size: 0.9em; color: #444; margin: 0 0 0.8em 0; font-style: italic; }
.contact-email-btn { display: inline-flex; align-items: center; gap: 6px; background: #c0613a; color: white; padding: 6px 16px; border-radius: 3px; font-size: 0.8em; font-weight: 500; text-decoration: none; transition: background 0.2s; }
.contact-email-btn:hover { background: #a04f2e; color: white; text-decoration: none; }
.social-links { display: flex; gap: 6px; flex-wrap: wrap; margin-top: 0.7em; }
.s-link { display: inline-flex; align-items: center; gap: 4px; padding: 4px 10px; border-radius: 3px; border: 1px solid #ddd; background: white; font-size: 0.74em; font-weight: 500; color: #555; text-decoration: none; transition: all 0.15s ease; }
.s-link:hover { background: #c0613a; color: white; border-color: #c0613a; text-decoration: none; }

/* Photo strip */
.photo-strip { display: flex; gap: 8px; overflow-x: auto; margin: 1.2em 0 0.4em; padding-bottom: 4px; }
.photo-strip img { height: 58px; border-radius: 4px; object-fit: cover; flex-shrink: 0; border: 1px solid #e8e8e8; transition: opacity 0.2s; }
.photo-strip img:hover { opacity: 0.85; }

/* News */
.news-list { list-style: none; padding: 0; margin: 0.4em 0 1em; }
.news-item { display: flex; gap: 12px; align-items: baseline; padding: 6px 0; border-bottom: 1px solid #f0f0f0; transition: opacity 0.4s ease; opacity: 0; }
.news-item.visible { opacity: 1; }
.news-item:last-child { border-bottom: none; }
.news-date { flex-shrink: 0; font-size: 0.72em; font-weight: 600; color: #c0613a; width: 82px; }
.news-text { font-size: 0.83em; color: #333; line-height: 1.55; margin: 0; }
.news-text a { color: #c0613a; text-decoration: none; font-weight: 500; }
.news-text a:hover { text-decoration: underline; }
.news-tag { display: inline-block; font-size: 0.65em; font-weight: 600; padding: 1px 6px; border-radius: 3px; margin-left: 5px; vertical-align: middle; }
.tag-paper { background: #edf7ee; color: #2e7d32; border: 1px solid #c8e6c9; }
.tag-award { background: #fdf6e3; color: #b45309; border: 1px solid #fde68a; }
.tag-talk { background: #e8f1fb; color: #1565c0; border: 1px solid #bbdefb; }
.tag-service { background: #f5f0fa; color: #6a1b9a; border: 1px solid #e1bee7; }
.tag-misc { background: #f5f5f5; color: #555; border: 1px solid #ddd; }
</style>

<div class="hero-banner">
<div class="hero-greeting">Puyang Zhao</div>
<div class="hero-pills">
<span class="hero-pill">Postdoctoral Associate · Rice University</span>
<span class="hero-pill">Houston, TX</span>
<span class="hero-pill">she/her</span>
</div>
<p class="hero-bio">I am a <strong>Postdoctoral Associate</strong> at Rice University, working with Dr. Hanjie Chen. I earned my Ph.D. in Biostatistics from UTHealth Houston (advisors: Dr. James Yang, Dr. Anne Buu, Dr. Theresa Tran), M.Sc. from the University of Melbourne (Dr. Howard Bondell), and B.Sc. from Hong Kong Baptist University (Dr. Jingjing Wu). My work sits at the intersection of <strong>biostatistics</strong>, <strong>machine learning</strong>, and clinical applications.</p>
</div>

<section class="news-section">
  <div class="warm-section-title"><span>§</span> News</div>

  <div class="news-carousel-wrap">
    <button class="news-nav prev" id="newsPrev" aria-label="Scroll left">‹</button>

    <div class="news-carousel" id="newsCarousel">

      <article class="news-card">
        <div class="news-card-date">Apr 23, 2026</div>
        <div class="news-card-text">
          Invited to present at <strong>CAPE Day 2026</strong> (Texas Children's Hospital, April 23) on the Poverty Simulator intervention in health professions education.
        </div>
        <span class="news-chip news-chip-talk">🎤 Talk</span>
      </article>

      <article class="news-card">
        <div class="news-card-date">Apr 8, 2026</div>
        <div class="news-card-text">
          Paper accepted at <strong>IEEE EIT 2026</strong>: “Comparative Analysis of Shallow and Deep Learning Methods for Diabetes Prediction Using the Pima Indians Dataset”.
        </div>
        <span class="news-chip news-chip-paper">📄 Paper</span>
      </article>

      <article class="news-card">
        <div class="news-card-date">Mar 15, 2026</div>
        <div class="news-card-text">
          Oral presentation accepted at the <strong>30th Annual Conference of the International Association</strong>: “Promoting Structural Awareness and Empathy: Evaluation of a Poverty Simulation Intervention in Health Professions Education”.
        </div>
        <span class="news-chip news-chip-talk">🎤 Talk</span>
      </article>

      <article class="news-card">
        <div class="news-card-date">Feb 9, 2026</div>
        <div class="news-card-text">
          Joined <strong>Rice University</strong> as a Postdoctoral Associate in Computer Science, working with Dr. Hanjie Chen.
        </div>
        <span class="news-chip news-chip-misc">💼 New Role</span>
      </article>

      <article class="news-card">
        <div class="news-card-date">Dec 12, 2025</div>
        <div class="news-card-text">
          Awarded <strong>Ph.D. in Biostatistics</strong> (minor: Health Economics) from UTHealth Houston.
        </div>
        <span class="news-chip news-chip-award">🎓 Milestone</span>
      </article>

      <article class="news-card">
        <div class="news-card-date">Nov 29, 2025</div>
        <div class="news-card-text">
          Paper accepted in <em>Biomedical Signal Processing and Control</em>: “Demography-Aware Personalized Federated Learning for Fair, Private, and Efficient Clinical Risk Prediction”.
        </div>
        <span class="news-chip news-chip-paper">📄 Paper</span>
      </article>

      <article class="news-card">
        <div class="news-card-date">Oct 1, 2025</div>
        <div class="news-card-text">
          Paper accepted in <em>Biomedical Signal Processing and Control</em>: “Pre-attentive Speech Signal Processing with Adaptive Routing for Emotion Recognition”.
        </div>
        <span class="news-chip news-chip-paper">📄 Paper</span>
      </article>

      <article class="news-card">
        <div class="news-card-date">Jul 11, 2025</div>
        <div class="news-card-text">
          Paper accepted at <strong>IEEE AIxMHC 2025</strong> (Taiwan): “Weighted Federated Learning with Encryption for Diabetes Classification”.
        </div>
        <span class="news-chip news-chip-paper">📄 Paper</span>
      </article>

      <article class="news-card">
        <div class="news-card-date">Dec 10, 2024</div>
        <div class="news-card-text">
          Paper accepted in <em>The American Journal of Drug and Alcohol Abuse</em>: “Applied Statistical Methods for Identifying Features of Heart Rate Associated with Nicotine Vaping”.
        </div>
        <span class="news-chip news-chip-paper">📄 Paper</span>
      </article>

    </div>

    <button class="news-nav next" id="newsNext" aria-label="Scroll right">›</button>
  </div>
</section>

<style>
  .news-section{
    margin: 0.8em 0 1.6em;
  }

  .news-carousel-wrap{
    position: relative;
    display: flex;
    align-items: center;
  }

  .news-carousel{
    display: flex;
    gap: 16px;
    overflow-x: auto;
    scroll-snap-type: x mandatory;
    scroll-behavior: smooth;
    -webkit-overflow-scrolling: touch;
    width: 100%;
    padding: 8px 6px 16px;
    scrollbar-width: none;
    cursor: grab;
  }

  .news-carousel::-webkit-scrollbar{
    display: none;
  }

  .news-carousel:active{
    cursor: grabbing;
  }

  .news-card{
    flex: 0 0 340px;
    scroll-snap-align: start;
    background: linear-gradient(180deg, #fffdfb 0%, #fff8f2 100%);
    border: 1px solid #eadfd2;
    border-radius: 18px;
    padding: 16px 16px 14px;
    box-shadow: 0 6px 20px rgba(93, 67, 42, 0.08);
    transition: transform 0.22s ease, box-shadow 0.22s ease, border-color 0.22s ease, opacity 0.4s ease;
    min-height: 198px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    opacity: 0;
  }

  .news-card.visible{
    opacity: 1;
  }

  .news-card:hover{
    transform: translateY(-3px);
    box-shadow: 0 12px 28px rgba(93, 67, 42, 0.12);
    border-color: #dcc8b3;
  }

  .news-card-date{
    display: inline-flex;
    align-items: center;
    width: fit-content;
    font-size: 0.78em;
    font-weight: 600;
    color: #9a7a60;
    background: #f7eee6;
    border: 1px solid #efe1d5;
    border-radius: 999px;
    padding: 5px 10px;
    margin-bottom: 12px;
  }

  .news-card-text{
    color: #3d342d;
    font-size: 0.84em;
    line-height: 1.65;
    margin-bottom: 14px;
  }

  .news-card-text strong{
    color: #2f241c;
  }

  .news-card-text em{
    color: #4a3a31;
    font-style: italic;
  }

  .news-chip{
    display: inline-flex;
    align-items: center;
    gap: 0.35rem;
    width: fit-content;
    font-size: 0.68em;
    font-weight: 600;
    padding: 5px 10px;
    border-radius: 999px;
    letter-spacing: 0.12px;
  }

  .news-chip-paper{
    background: #edf7ee;
    color: #2e7d32;
    border: 1px solid #c8e6c9;
  }

  .news-chip-talk{
    background: #e8f1fb;
    color: #1565c0;
    border: 1px solid #bbdefb;
  }

  .news-chip-award{
    background: #fdf6e3;
    color: #b45309;
    border: 1px solid #fde68a;
  }

  .news-chip-misc{
    background: #f5f5f5;
    color: #555;
    border: 1px solid #ddd;
  }

  .news-nav{
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    z-index: 3;
    width: 40px;
    height: 40px;
    border: none;
    border-radius: 50%;
    background: rgba(255, 250, 245, 0.95);
    color: #6f533e;
    box-shadow: 0 6px 16px rgba(70, 50, 35, 0.14);
    font-size: 1.7rem;
    line-height: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    transition: all 0.2s ease;
  }

  .news-nav:hover{
    background: #fff;
    transform: translateY(-50%) scale(1.05);
  }

  .news-nav:disabled{
    opacity: 0.3;
    cursor: not-allowed;
    transform: translateY(-50%);
  }

  .news-nav.prev{
    left: -8px;
  }

  .news-nav.next{
    right: -8px;
  }

  .news-carousel-wrap::before,
  .news-carousel-wrap::after{
    content: "";
    position: absolute;
    top: 0;
    bottom: 0;
    width: 34px;
    z-index: 2;
    pointer-events: none;
  }

  .news-carousel-wrap::before{
    left: 0;
    background: linear-gradient(to right, rgba(255,255,255,0.94), rgba(255,255,255,0));
  }

  .news-carousel-wrap::after{
    right: 0;
    background: linear-gradient(to left, rgba(255,255,255,0.94), rgba(255,255,255,0));
  }

  @media (max-width: 900px){
    .news-card{
      flex: 0 0 300px;
      min-height: 208px;
    }
  }

  @media (max-width: 640px){
    .news-card{
      flex: 0 0 86%;
      min-height: auto;
    }

    .news-nav{
      width: 36px;
      height: 36px;
      font-size: 1.45rem;
    }

    .news-carousel-wrap::before,
    .news-carousel-wrap::after{
      width: 16px;
    }
  }
</style>

<script>
(function () {
  const carousel = document.getElementById('newsCarousel');
  const prevBtn = document.getElementById('newsPrev');
  const nextBtn = document.getElementById('newsNext');

  if (!carousel || !prevBtn || !nextBtn) return;

  function getScrollAmount() {
    const card = carousel.querySelector('.news-card');
    if (!card) return 300;
    return card.offsetWidth + 16;
  }

  function updateButtons() {
    const maxScrollLeft = carousel.scrollWidth - carousel.clientWidth;
    prevBtn.disabled = carousel.scrollLeft <= 5;
    nextBtn.disabled = carousel.scrollLeft >= maxScrollLeft - 5;
  }

  prevBtn.addEventListener('click', () => {
    carousel.scrollBy({ left: -getScrollAmount(), behavior: 'smooth' });
  });

  nextBtn.addEventListener('click', () => {
    carousel.scrollBy({ left: getScrollAmount(), behavior: 'smooth' });
  });

  carousel.addEventListener('scroll', updateButtons);
  window.addEventListener('resize', updateButtons);

  let isDown = false;
  let startX = 0;
  let scrollLeft = 0;

  carousel.addEventListener('mousedown', (e) => {
    isDown = true;
    startX = e.pageX - carousel.offsetLeft;
    scrollLeft = carousel.scrollLeft;
  });

  carousel.addEventListener('mouseleave', () => {
    isDown = false;
  });

  carousel.addEventListener('mouseup', () => {
    isDown = false;
  });

  carousel.addEventListener('mousemove', (e) => {
    if (!isDown) return;
    e.preventDefault();
    const x = e.pageX - carousel.offsetLeft;
    const walk = (x - startX) * 1.15;
    carousel.scrollLeft = scrollLeft - walk;
  });

  updateButtons();
})();
</script>
<div class="warm-section-title"><span>§</span> Education</div>
<div class="edu-timeline">
<div class="edu-item"><div class="edu-period">2026 – Present</div><div><p class="edu-degree">Postdoctoral Associate in Computer Science</p><p class="edu-school">Rice University, Houston, TX</p><p class="edu-advisor">Advisor: Dr. Hanjie Chen</p></div></div>
<div class="edu-item"><div class="edu-period">2025 · Ph.D.</div><div><p class="edu-degree">Biostatistics (minor: Health Economics)</p><p class="edu-school">UTHealth Houston</p><p class="edu-advisor">Advisors: Dr. James Yang · Dr. Anne Buu · Dr. Theresa Tran</p></div></div>
<div class="edu-item"><div class="edu-period">M.Sc.</div><div><p class="edu-degree">Mathematics and Statistics</p><p class="edu-school">University of Melbourne, Australia</p><p class="edu-advisor">Advisor: Dr. Howard Bondell</p></div></div>
<div class="edu-item"><div class="edu-period">B.Sc.</div><div><p class="edu-degree">Statistics</p><p class="edu-school">Hong Kong Baptist University</p><p class="edu-advisor">Advisor: Dr. Jingjing Wu</p></div></div>
</div>

<div class="warm-section-title"><span>§</span> Publications</div>
<div class="pub-tabs">
<button class="pub-tab active" onclick="filterPubs('all',this)">All</button>
<button class="pub-tab" onclick="filterPubs('j',this)">Journal Articles</button>
<button class="pub-tab" onclick="filterPubs('c',this)">Conference</button>
</div>
<style>
  #pubContainer{
    display:flex;
    flex-direction:column;
    gap:14px;
    margin-top:12px;
    font-family: "Inter", "Segoe UI", Arial, sans-serif;
  }

  .pub-card{
    display:grid;
    grid-template-columns:90px 1fr auto;
    gap:16px;
    align-items:start;
    padding:16px 18px;
    border:1px solid #e8e8e8;
    border-radius:16px;
    background:#fff;
    box-shadow:0 2px 10px rgba(0,0,0,0.04);
    transition:transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
  }

  .pub-card:hover{
    transform:translateY(-2px);
    box-shadow:0 8px 22px rgba(0,0,0,0.08);
    border-color:#d8d8d8;
  }

  .pub-yr{
    font-size:0.95rem;
    font-weight:700;
    color:#4b5563;
    white-space:nowrap;
    padding-top:2px;
  }

  .pub-t{
    margin:0 0 8px 0;
    font-size:1.02rem;
    font-weight:700;
    line-height:1.45;
    color:#111827;
  }

  .pub-a{
    margin:0 0 6px 0;
    font-size:0.95rem;
    line-height:1.5;
    color:#374151;
  }

  .pub-v{
    margin:0;
    font-size:0.92rem;
    line-height:1.5;
    color:#6b7280;
    font-style:italic;
  }

  .pub-badge{
    align-self:start;
    display:inline-flex;
    align-items:center;
    gap:6px;
    font-size:0.82rem;
    font-weight:700;
    padding:7px 12px;
    border-radius:999px;
    white-space:nowrap;
    letter-spacing:0.2px;
  }

  .bj{
    background:#eaf2ff;
    color:#1d4ed8;
  }

  .bc{
    background:#ecfdf5;
    color:#047857;
  }

  .bb{
    background:#fff7ed;
    color:#c2410c;
  }

  @media (max-width: 760px){
    .pub-card{
      grid-template-columns:1fr;
      gap:10px;
    }

    .pub-badge{
      justify-self:start;
    }
  }
</style>

<div id="pubContainer">
<div class="pub-card" data-type="j"><div class="pub-yr">2026</div><div><p class="pub-t">Demography-Aware Personalized Federated Learning for Fair, Private, and Efficient Clinical Risk Prediction</p><p class="pub-a"><b>Zhao P.</b>, Yue Z., Mi N., Zhang H.</p><p class="pub-v">Biomedical Signal Processing and Control 114, 109312</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2026</div><div><p class="pub-t">Pre-attentive Speech Signal Processing with Adaptive Routing for Emotion Recognition</p><p class="pub-a">Zhang H., Pang Z., <b>Zhao P.</b>, Tang G., Shen L., Wang G.</p><p class="pub-v">Biomedical Signal Processing and Control 112, 108782</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2025</div><div><p class="pub-t">Applied Statistical Methods for Identifying Features of Heart Rate Associated with Nicotine Vaping</p><p class="pub-a"><b>Zhao P.</b>, Yang J., Buu A.</p><p class="pub-v">The American Journal of Drug and Alcohol Abuse 51(2), 165–172</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2025</div><div><p class="pub-t">Reproducible and Generalizable Speech Emotion Recognition via an Intelligent Fusion Network</p><p class="pub-a">Zhang H., <b>Zhao P.</b>, Tang G., Li Z., Yuan Z.</p><p class="pub-v">Biomedical Signal Processing and Control 109, 107996</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2025</div><div><p class="pub-t">Sparse Temporal-Aware Capsule Network for Robust Speech Emotion Recognition</p><p class="pub-a">Zhang H., Huang H., <b>Zhao P.</b>, Yu Z.</p><p class="pub-v">Engineering Applications of Artificial Intelligence 144, 110060</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2024</div><div><p class="pub-t">CENN: Capsule-Enhanced Neural Network with Innovative Metrics for Robust Speech Emotion Recognition</p><p class="pub-a">Zhang H., Huang H., <b>Zhao P.</b>, Zhu X., Yu Z.</p><p class="pub-v">Knowledge-Based Systems 304, 112499</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2024</div><div><p class="pub-t">DiGAN Breakthrough: Advancing Diabetic Data Analysis with Innovative GAN-Based Imbalance Correction</p><p class="pub-a"><b>Zhao P.</b>, Liu X., Yue Z., Zhao Q., Liu X., Deng Y., Wu J.</p><p class="pub-v">Computer Methods and Programs in Biomedicine Update 5, 100152</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="c"><div class="pub-yr">2026</div><div><p class="pub-t">Promoting Structural Awareness and Empathy: Evaluation of a Poverty Simulation Intervention in Health Professions Education</p><p class="pub-a"><b>Zhao P.</b>, Carapucci T., Alford J., Kodakandla M.</p><p class="pub-v">30th Annual Conference of the International Association · 2026</p></div><span class="pub-badge bc">Conference</span></div>
<div class="pub-card" data-type="c"><div class="pub-yr">2025</div><div><p class="pub-t">Weighted Federated Learning with Encryption for Diabetes Classification</p><p class="pub-a"><b>Zhao P.</b>, Yue Z., Liu X., Wu J.</p><p class="pub-v">IEEE AIxMHC · Taiwan, 2025</p></div><span class="pub-badge bc">Conference</span></div>
<div class="pub-card" data-type="c"><div class="pub-yr">2022</div><div><p class="pub-t">An Attention-Based LSTM Framework for Detection of Bitcoin Scams</p><p class="pub-a"><b>Zhao P.</b>, Tian W., Xiao L., Liu X., Wu J.</p><p class="pub-v">IEEE HDIS · Tianjin, 2022</p></div><span class="pub-badge bb">🏆 Best Paper Nom.</span></div>
<div class="pub-card" data-type="c"><div class="pub-yr">2022</div><div><p class="pub-t">Prediction of Solar Power via Statistical and Machine Learning Methods</p><p class="pub-a"><b>Zhao P.</b>, Tian W.</p><p class="pub-v">IOP Conference Series: Earth and Environmental Science 1046(1), 012006 · Tokyo, 2022</p></div><span class="pub-badge bc">Conference</span></div>
</div>

<div class="warm-section-title"><span>§</span> Contact</div>
<div class="contact-box">
<p class="contact-tagline">Open to collaboration and research discussions.</p>
<a href="mailto:Puyang.Zhao@rice.edu" class="contact-email-btn">✉ Puyang.Zhao@rice.edu</a>
<div class="social-links">
<a href="https://scholar.google.com/citations?user=UeUkeiIAAAAJ" target="_blank" class="s-link">📖 Scholar</a>
<a href="https://github.com/puyangzhao" target="_blank" class="s-link">⌥ GitHub</a>
<a href="https://www.linkedin.com/in/puyang-zhao-24343b191/" target="_blank" class="s-link">🔗 LinkedIn</a>
<a href="https://orcid.org/0009-0002-8660-4835" target="_blank" class="s-link">◎ ORCID</a>
<a href="https://www.researchgate.net/profile/Puyang-Zhao" target="_blank" class="s-link">🔬 ResearchGate</a>
</div>
</div>

<div style="width:270px;height:270px;overflow:hidden;position:relative;margin:2em 0 1em;">
<script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=clIdEPFSxTObYL5YCT6KPfejmqi13_-8ETks5Uwv8eQ"></script>
</div>

<div class="photo-strip">
<img src="images/tianjin.jpg" alt="Tianjin">
<img src="images/uth.png" alt="UTH">
<img src="images/uth2.jpg" alt="UTH2">
<img src="images/melb.jpg" alt="Melbourne">
<img src="images/uic.jpg" alt="UIC">
<img src="images/stat.jpg" alt="Statistics">
<img src="images/hkbu.png" alt="HKBU">
<img src="images/rice.png" alt="Rice">
</div>

<p style="font-size:0.75em;color:#aaa;margin-top:1.5em;"><em>Last updated: April 2026</em></p>

<script>
(function(){
  var observer = new IntersectionObserver(function(entries){
    entries.forEach(function(entry){
      if(entry.isIntersecting){
        entry.target.classList.add('visible');
        observer.unobserve(entry.target);
      }
    });
  }, {threshold: 0.1, rootMargin: '0px 0px -30px 0px'});

  function init(){
    document.querySelectorAll('.r-card, .edu-item, .pub-card, .news-card').forEach(function(el){
      observer.observe(el);
    });
  }

  if(document.readyState === 'loading'){
    document.addEventListener('DOMContentLoaded', init);
  } else {
    init();
  }

  window.filterPubs = function(type, btn){
    document.querySelectorAll('.pub-tab').forEach(function(b){ b.classList.remove('active'); });
    btn.classList.add('active');
    document.querySelectorAll('.pub-card').forEach(function(card){
      if(type === 'all' || card.dataset.type === type){
        card.style.display = 'grid';
        setTimeout(function(c){ c.classList.add('visible'); }, 30, card);
      } else {
        card.style.display = 'none';
      }
    });
  };
})();
</script>
