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
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;600;700&family=Lora:ital,wght@0,400;0,600;1,400&display=swap');

.page__content { font-family: 'Nunito', sans-serif; }

.hero-banner {
  background: linear-gradient(135deg, #fdf6ee 0%, #fce8d5 50%, #f9ddd0 100%);
  border-radius: 20px;
  padding: 2.8em 2.5em 2.2em;
  margin-bottom: 2.5em;
  position: relative;
  overflow: hidden;
  box-shadow: 0 4px 24px rgba(200,120,80,0.08);
  animation: fadeSlideDown 0.7s ease both;
}
.hero-banner::before {
  content: '';
  position: absolute;
  top: -60px; right: -60px;
  width: 220px; height: 220px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(220,140,100,0.18) 0%, transparent 70%);
}
.hero-greeting { font-family: 'Lora', serif; font-size: 2.2em; font-weight: 600; color: #3d2b1f; margin: 0 0 0.3em 0; line-height: 1.2; }
.hero-greeting span { color: #c0613a; }
.hero-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 1.2em; }
.hero-pill { display: inline-flex; align-items: center; gap: 5px; background: rgba(255,255,255,0.7); border: 1px solid rgba(192,97,58,0.2); border-radius: 20px; padding: 3px 12px; font-size: 0.85em; color: #7a5c4e; }
.hero-bio { font-size: 0.97em; line-height: 1.9; color: #4a3528; max-width: 680px; margin: 0; position: relative; z-index: 1; }
.hero-bio strong { color: #c0613a; }

.warm-section-title { font-family: 'Lora', serif; font-size: 1.35em; font-weight: 600; color: #3d2b1f; margin: 2.2em 0 1em 0; display: flex; align-items: center; gap: 10px; }
.warm-section-title::after { content: ''; flex: 1; height: 2px; background: linear-gradient(to right, rgba(192,97,58,0.35), transparent); border-radius: 2px; margin-left: 6px; }

.research-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 14px; margin-bottom: 0.5em; }
.r-card { background: #fff; border-radius: 14px; padding: 18px 16px; border: 1.5px solid #f0e0d4; box-shadow: 0 2px 10px rgba(200,120,80,0.06); transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease, opacity 0.5s ease; opacity: 0; transform: translateY(20px); }
.r-card.visible { opacity: 1; transform: translateY(0); }
.r-card:hover { transform: translateY(-4px) scale(1.01) !important; box-shadow: 0 8px 24px rgba(192,97,58,0.13) !important; border-color: #e0a888 !important; }
.r-card-icon { font-size: 1.6em; margin-bottom: 8px; display: block; }
.r-card-title { font-weight: 700; font-size: 0.88em; color: #c0613a; margin-bottom: 5px; }
.r-card-desc { font-size: 0.82em; color: #7a6055; line-height: 1.65; }

.edu-timeline { position: relative; padding-left: 28px; margin: 0.5em 0 1em; }
.edu-timeline::before { content: ''; position: absolute; left: 8px; top: 8px; bottom: 8px; width: 2px; background: linear-gradient(to bottom, #c0613a, #f0c8b0); border-radius: 2px; }
.edu-item { position: relative; margin-bottom: 1.2em; background: #fff; border-radius: 14px; padding: 14px 18px; border: 1.5px solid #f0e0d4; box-shadow: 0 2px 8px rgba(200,120,80,0.05); transition: box-shadow 0.25s, transform 0.25s, opacity 0.5s ease; opacity: 0; transform: translateX(-16px); }
.edu-item.visible { opacity: 1; transform: translateX(0); }
.edu-item:hover { box-shadow: 0 6px 20px rgba(192,97,58,0.1) !important; transform: translateX(4px) !important; }
.edu-item::before { content: ''; position: absolute; left: -23px; top: 18px; width: 12px; height: 12px; border-radius: 50%; background: #c0613a; border: 3px solid #fdf6ee; box-shadow: 0 0 0 2px #c0613a; }
.edu-period { display: inline-block; background: #fdf0e8; color: #c0613a; font-size: 0.75em; font-weight: 700; padding: 2px 10px; border-radius: 20px; margin-bottom: 6px; letter-spacing: 0.04em; }
.edu-degree { font-weight: 700; color: #3d2b1f; font-size: 0.97em; margin: 0; }
.edu-school { color: #7a5c4e; font-size: 0.88em; margin: 2px 0 0 0; }
.edu-advisor { color: #a08070; font-size: 0.82em; font-style: italic; margin: 2px 0 0 0; }

.pub-tabs { display: flex; gap: 8px; margin-bottom: 1.2em; flex-wrap: wrap; }
.pub-tab { padding: 6px 18px; border-radius: 20px; border: 1.5px solid #e0c8bc; background: transparent; font-family: 'Nunito', sans-serif; font-size: 0.82em; font-weight: 700; color: #a08070; cursor: pointer; transition: all 0.2s ease; }
.pub-tab.active, .pub-tab:hover { background: #c0613a; border-color: #c0613a; color: white; box-shadow: 0 3px 10px rgba(192,97,58,0.25); transform: translateY(-1px); }
.pub-card { background: #fff; border-radius: 14px; padding: 16px 20px; margin-bottom: 10px; border: 1.5px solid #f0e0d4; box-shadow: 0 2px 8px rgba(200,120,80,0.05); display: grid; grid-template-columns: 42px 1fr auto; gap: 14px; align-items: start; transition: transform 0.2s, box-shadow 0.2s, opacity 0.45s ease; opacity: 0; transform: translateY(12px); }
.pub-card.visible { opacity: 1; transform: translateY(0); }
.pub-card:hover { transform: translateY(-3px) !important; box-shadow: 0 6px 20px rgba(192,97,58,0.1) !important; }
.pub-yr { font-size: 0.75em; font-weight: 700; color: #c0613a; background: #fdf0e8; border-radius: 8px; padding: 4px 6px; text-align: center; line-height: 1.3; }
.pub-t { font-weight: 700; font-size: 0.93em; color: #3d2b1f; margin: 0 0 4px 0; line-height: 1.45; }
.pub-a { font-size: 0.82em; color: #9a7060; margin: 0 0 3px 0; }
.pub-a b { color: #c0613a; }
.pub-v { font-size: 0.8em; color: #b09080; font-style: italic; margin: 0; }
.pub-badge { font-size: 0.68em; font-weight: 700; padding: 3px 9px; border-radius: 20px; white-space: nowrap; align-self: flex-start; letter-spacing: 0.04em; }
.bj { background: #e8f5e9; color: #2e7d32; border: 1px solid #c8e6c9; }
.bc { background: #e3f2fd; color: #1565c0; border: 1px solid #bbdefb; }
.bb { background: #fff8e1; color: #e65100; border: 1px solid #ffe082; }

.contact-box { background: linear-gradient(135deg, #fdf6ee 0%, #fce8d5 100%); border-radius: 18px; padding: 2em 2.2em; border: 1.5px solid #f0d4c0; box-shadow: 0 4px 20px rgba(200,120,80,0.08); margin-top: 0.5em; }
.contact-tagline { font-family: 'Lora', serif; font-size: 1.1em; color: #3d2b1f; margin: 0 0 1em 0; font-style: italic; }
.contact-email-btn { display: inline-flex; align-items: center; gap: 8px; background: #c0613a; color: white; padding: 10px 22px; border-radius: 25px; font-size: 0.9em; font-weight: 700; text-decoration: none; box-shadow: 0 4px 14px rgba(192,97,58,0.3); transition: transform 0.2s, box-shadow 0.2s; }
.contact-email-btn:hover { transform: translateY(-2px); box-shadow: 0 6px 20px rgba(192,97,58,0.4); color: white; text-decoration: none; }
.social-links { display: flex; gap: 8px; flex-wrap: wrap; margin-top: 0.8em; }
.s-link { display: inline-flex; align-items: center; gap: 5px; padding: 6px 14px; border-radius: 20px; border: 1.5px solid #e0c8bc; background: white; font-size: 0.78em; font-weight: 600; color: #7a5c4e; text-decoration: none; transition: all 0.2s ease; }
.s-link:hover { background: #c0613a; color: white; border-color: #c0613a; transform: translateY(-2px); box-shadow: 0 4px 12px rgba(192,97,58,0.2); text-decoration: none; }

.photo-strip { display: flex; gap: 10px; overflow-x: auto; margin: 1.5em 0 0.5em; padding-bottom: 6px; }
.photo-strip img { height: 72px; border-radius: 10px; object-fit: cover; flex-shrink: 0; transition: transform 0.2s, box-shadow 0.2s; border: 2px solid #f0e0d4; }
.photo-strip img:hover { transform: scale(1.08) translateY(-3px); box-shadow: 0 6px 16px rgba(192,97,58,0.18); }

@keyframes fadeSlideDown { from { opacity: 0; transform: translateY(-18px); } to { opacity: 1; transform: translateY(0); } }
</style>

<div class="hero-banner">
<div class="hero-greeting">Hi, I'm <span>Puyang</span> 👋</div>
<div class="hero-pills">
<span class="hero-pill">🎓 Postdoctoral Associate</span>
<span class="hero-pill">🏛 Rice University</span>
<span class="hero-pill">📍 Houston, TX</span>
<span class="hero-pill">she/her</span>
</div>
<p class="hero-bio">I am currently a <strong>Postdoctoral Associate</strong> at Rice University, working with Dr. Hanjie Chen. I earned my Ph.D. in Biostatistics from UTHealth Houston (Dr. James Yang, Dr. Anne Buu, Dr. Theresa Tran). I received my M.Sc. from the University of Melbourne (Dr. Howard Bondell) and my B.Sc. from Hong Kong Baptist University (Dr. Jingjing Wu). My work sits at the intersection of <strong>biostatistics</strong>, <strong>machine learning</strong>, and clinical applications.</p>
</div>

<div class="warm-section-title">🔬 Research Interests</div>
<div class="research-grid" id="researchGrid">
<div class="r-card"><span class="r-card-icon">⌚</span><div class="r-card-title">Wearable Devices</div><div class="r-card-desc">Physiological signal analysis, heart rate monitoring in relation to nicotine vaping events.</div></div>
<div class="r-card"><span class="r-card-icon">🗣</span><div class="r-card-title">Speech Emotion Recognition</div><div class="r-card-desc">Capsule networks and fusion models for robust emotion recognition in clinical settings.</div></div>
<div class="r-card"><span class="r-card-icon">📊</span><div class="r-card-title">Longitudinal &amp; EMA Data</div><div class="r-card-desc">Statistical methods for ecological momentary assessment in behavioral health research.</div></div>
<div class="r-card"><span class="r-card-icon">🩺</span><div class="r-card-title">Clinical Machine Learning</div><div class="r-card-desc">GAN-based methods, federated learning, and deep learning for diabetes classification.</div></div>
<div class="r-card"><span class="r-card-icon">🌿</span><div class="r-card-title">Environmental Modeling</div><div class="r-card-desc">dPL-SPARROW framework combining neural networks with watershed models.</div></div>
<div class="r-card"><span class="r-card-icon">🚬</span><div class="r-card-title">Tobacco &amp; E-cigarette</div><div class="r-card-desc">Vaping behavior patterns and tobacco control in public health research.</div></div>
</div>

<div class="warm-section-title">🎓 Education</div>
<div class="edu-timeline">
<div class="edu-item"><span class="edu-period">2024 – Present</span><p class="edu-degree">Postdoctoral Associate</p><p class="edu-school">Rice University, Houston, TX</p><p class="edu-advisor">Advisor: Dr. Hanjie Chen</p></div>
<div class="edu-item"><span class="edu-period">Ph.D.</span><p class="edu-degree">Biostatistics</p><p class="edu-school">UTHealth Houston</p><p class="edu-advisor">Advisors: Dr. James Yang · Dr. Anne Buu · Dr. Theresa Tran</p></div>
<div class="edu-item"><span class="edu-period">M.Sc.</span><p class="edu-degree">Mathematics and Statistics</p><p class="edu-school">University of Melbourne, Australia</p><p class="edu-advisor">Advisor: Dr. Howard Bondell</p></div>
<div class="edu-item"><span class="edu-period">B.Sc.</span><p class="edu-degree">Statistics</p><p class="edu-school">Hong Kong Baptist University</p><p class="edu-advisor">Advisor: Dr. Jingjing Wu</p></div>
</div>

<div class="warm-section-title">📚 Publications</div>
<div class="pub-tabs">
<button class="pub-tab active" onclick="filterPubs('all',this)">All</button>
<button class="pub-tab" onclick="filterPubs('j',this)">Journal Articles</button>
<button class="pub-tab" onclick="filterPubs('c',this)">Conference</button>
</div>
<div id="pubContainer">
<div class="pub-card" data-type="j"><div class="pub-yr">2025</div><div><p class="pub-t">Applied Statistical Methods for Identifying Features of Heart Rate Associated with Nicotine Vaping</p><p class="pub-a"><b>Zhao P.</b>, Yang J., Buu A.</p><p class="pub-v">The American Journal of Drug and Alcohol Abuse, Feb 2025</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2025</div><div><p class="pub-t">Reproducible and Generalizable Speech Emotion Recognition via an Intelligent Fusion Network</p><p class="pub-a">Zhang H., <b>Zhao P.*</b>, Tang G., Li Z., Yuan Z.</p><p class="pub-v">Biomedical Signal Processing and Control, May 2025</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2025</div><div><p class="pub-t">Pre-attentive Speech Signal Processing with Adaptive Routing for Emotion Recognition</p><p class="pub-a">Zhang H., Pang Z., <b>Zhao P.</b>, Tang G., Shen L., Wang G.</p><p class="pub-v">Biomedical Signal Processing and Control, 2025</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2025</div><div><p class="pub-t">Sparse Temporal-Aware Capsule Network for Robust Speech Emotion Recognition</p><p class="pub-a">Zhang H.*, Huang H., <b>Zhao P.</b>, Yu Z.</p><p class="pub-v">Engineering Applications of Artificial Intelligence, 2025</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2024</div><div><p class="pub-t">CENN: Capsule-Enhanced Neural Network with Innovative Metrics for Robust Speech Emotion Recognition</p><p class="pub-a">Zhang H.*, Huang H., <b>Zhao P.</b>, Zhu X., Yu Z.</p><p class="pub-v">Knowledge-Based Systems, Sep 2024</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="j"><div class="pub-yr">2024</div><div><p class="pub-t">DiGAN Breakthrough: Advancing Diabetic Data Analysis with Innovative GAN-Based Imbalance Correction</p><p class="pub-a"><b>Zhao P.</b>, Liu X., Yue Z., Zhao Q., Liu X., Deng Y., Wu J.*</p><p class="pub-v">Computer Methods and Programs in Biomedicine Update, 2024</p></div><span class="pub-badge bj">Journal</span></div>
<div class="pub-card" data-type="c"><div class="pub-yr">2025</div><div><p class="pub-t">Weighted Federated Learning with Encryption for Diabetes Classification</p><p class="pub-a"><b>Zhao P.</b>, Yue Z., Liu X., Wu J.</p><p class="pub-v">IEEE CPS, AIxMHC · Taiwan, 2025 · Accepted</p></div><span class="pub-badge bc">Conference</span></div>
<div class="pub-card" data-type="c"><div class="pub-yr">2022</div><div><p class="pub-t">An Attention-Based LSTM Framework for Detection of Bitcoin Scams</p><p class="pub-a"><b>Zhao P.</b>, Tian W., Xiao L., Liu X., Wu J.</p><p class="pub-v">IEEE HDIS · Tianjin, 2022</p></div><span class="pub-badge bb">🏆 Best Paper Nom.</span></div>
<div class="pub-card" data-type="c"><div class="pub-yr">2022</div><div><p class="pub-t">Prediction of Solar Power via Statistical and Machine Learning Methods</p><p class="pub-a"><b>Zhao P.</b>, Tian W.</p><p class="pub-v">IOP Conference Series · Tokyo, 2022</p></div><span class="pub-badge bc">Conference</span></div>
</div>

<div class="warm-section-title">📬 Let's Connect</div>
<div class="contact-box">
<p class="contact-tagline">"Open to collaboration &amp; research discussions!"</p>
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

<p style="font-size:0.78em;color:#b09080;margin-top:1.5em;"><em>Last updated: February 2026</em></p>

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
    document.querySelectorAll('.r-card, .edu-item, .pub-card').forEach(function(el, i){
      el.style.transitionDelay = (i % 6 * 0.08) + 's';
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
    var idx = 0;
    document.querySelectorAll('.pub-card').forEach(function(card){
      if(type === 'all' || card.dataset.type === type){
        card.style.display = 'grid';
        card.classList.remove('visible');
        card.style.transitionDelay = (idx * 0.07) + 's';
        idx++;
        setTimeout(function(c){ c.classList.add('visible'); }, 30, card);
      } else {
        card.style.display = 'none';
      }
    });
  };
})();
</script>
