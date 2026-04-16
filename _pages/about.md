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
.news-date { flex-shrink: 0; font-size: 0.72em; font-weight: 600; color: #c0613a; width: 58px; }
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

<div class="warm-section-title"><span>§</span> News</div>
<ul class="news-list" id="newsList">
<li class="news-item"><span class="news-date">Apr 2026</span><p class="news-text">Presenting at <strong>ICLR 2026</strong> in Vienna — see you there!<span class="news-tag tag-talk">Talk</span></p></li>
<li class="news-item"><span class="news-date">Mar 2026</span><p class="news-text">New paper accepted at <em>Biomedical Signal Processing and Control</em>: "Pre-attentive Speech Signal Processing with Adaptive Routing for Emotion Recognition".<span class="news-tag tag-paper">Paper</span></p></li>
<li class="news-item"><span class="news-date">Feb 2026</span><p class="news-text">Paper published in <em>The American Journal of Drug and Alcohol Abuse</em> on heart rate features associated with nicotine vaping.<span class="news-tag tag-paper">Paper</span></p></li>
<li class="news-item"><span class="news-date">Jan 2026</span><p class="news-text">Joined the <strong>Program Committee</strong> for AAAI 2026 Workshop on AI for Health.<span class="news-tag tag-service">Service</span></p></li>
<li class="news-item"><span class="news-date">Dec 2025</span><p class="news-text">Conference paper on <em>Weighted Federated Learning with Encryption for Diabetes Classification</em> accepted at <strong>IEEE CPS AIxMHC</strong> (Taiwan).<span class="news-tag tag-paper">Paper</span></p></li>
<li class="news-item"><span class="news-date">Sep 2025</span><p class="news-text">Paper published in <em>Knowledge-Based Systems</em>: CENN — Capsule-Enhanced Neural Network for Robust Speech Emotion Recognition.<span class="news-tag tag-paper">Paper</span></p></li>
<li class="news-item"><span class="news-date">Jul 2024</span><p class="news-text">Started Postdoctoral Associate position at <strong>Rice University</strong>, working with Dr. Hanjie Chen.<span class="news-tag tag-misc">New Role</span></p></li>
</ul>

<div class="warm-section-title"><span>§</span> Research Interests</div>
<div class="research-grid" id="researchGrid">
<div class="r-card"><span class="r-card-icon">⌚</span><div class="r-card-title">Wearable Devices</div><div class="r-card-desc">Physiological signal analysis, heart rate monitoring in relation to nicotine vaping events.</div></div>
<div class="r-card"><span class="r-card-icon">🗣</span><div class="r-card-title">Speech Emotion Recognition</div><div class="r-card-desc">Capsule networks and fusion models for robust emotion recognition in clinical settings.</div></div>
<div class="r-card"><span class="r-card-icon">📊</span><div class="r-card-title">Longitudinal &amp; EMA Data</div><div class="r-card-desc">Statistical methods for ecological momentary assessment in behavioral health research.</div></div>
<div class="r-card"><span class="r-card-icon">🩺</span><div class="r-card-title">Clinical Machine Learning</div><div class="r-card-desc">GAN-based methods, federated learning, and deep learning for diabetes classification.</div></div>
<div class="r-card"><span class="r-card-icon">🌿</span><div class="r-card-title">Environmental Modeling</div><div class="r-card-desc">dPL-SPARROW framework combining neural networks with watershed models.</div></div>
<div class="r-card"><span class="r-card-icon">🚬</span><div class="r-card-title">Tobacco &amp; E-cigarette</div><div class="r-card-desc">Vaping behavior patterns and tobacco control in public health research.</div></div>
</div>

<div class="warm-section-title"><span>§</span> Education</div>
<div class="edu-timeline">
<div class="edu-item"><div class="edu-period">2024 – Present</div><div><p class="edu-degree">Postdoctoral Associate in Computer Science</p><p class="edu-school">Rice University, Houston, TX</p><p class="edu-advisor">Advisor: Dr. Hanjie Chen</p></div></div>
<div class="edu-item"><div class="edu-period">Ph.D.</div><div><p class="edu-degree">Biostatistics</p><p class="edu-school">UTHealth Houston</p><p class="edu-advisor">Advisors: Dr. James Yang · Dr. Anne Buu · Dr. Theresa Tran</p></div></div>
<div class="edu-item"><div class="edu-period">M.Sc.</div><div><p class="edu-degree">Mathematics and Statistics</p><p class="edu-school">University of Melbourne, Australia</p><p class="edu-advisor">Advisor: Dr. Howard Bondell</p></div></div>
<div class="edu-item"><div class="edu-period">B.Sc.</div><div><p class="edu-degree">Statistics</p><p class="edu-school">Hong Kong Baptist University</p><p class="edu-advisor">Advisor: Dr. Jingjing Wu</p></div></div>
</div>

<div class="warm-section-title"><span>§</span> Publications</div>
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
    document.querySelectorAll('.r-card, .edu-item, .pub-card, .news-item').forEach(function(el){
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
