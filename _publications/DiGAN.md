---
title: "DiGAN Breakthrough: Advancing Diabetic Data Analysis with Innovative GAN-Based Imbalance Correction Techniques"
collection: publications
permalink: /publication/DiGAN
excerpt: 'Breakthrough in Diabetes Data Analysis: DiGAN represents a breakthrough approach in the field of medical diagnostics, especially in diabetes classification.'
date: 2024-04-01
venue: 'Computer Methods and Programs in Biomedicine Update'
type: "Journal"
paperurl: 'https://doi.org/10.1016/j.cmpbup.2024.100152'
citation: 'P. Zhao, X. Liu, Z. Yue et al., DiGAN Breakthrough: Advancing diabetic data analysis with innovative GAN-based imbalance correction techniques, Computer Methods and Programs in Biomedicine Update (2024), doi: https://doi.org/10.1016/j.cmpbup.2024.100152.'
---

<style>
.pub-hero { background: linear-gradient(135deg, #fdf6ee 0%, #fce8d5 100%); border-radius: 16px; padding: 2em 2.2em; margin-bottom: 1.5em; border: 1.5px solid #f0d4c0; box-shadow: 0 4px 20px rgba(200,120,80,0.08); }
.pub-meta-row { display: flex; flex-wrap: wrap; gap: 8px; margin: 0.8em 0 1em; }
.pub-chip { display: inline-flex; align-items: center; gap: 5px; background: rgba(255,255,255,0.8); border: 1px solid rgba(192,97,58,0.25); border-radius: 20px; padding: 3px 12px; font-size: 0.82em; color: #7a5c4e; }
.pub-chip.highlight { background: #c0613a; color: white; border-color: #c0613a; }
.section-card { background: #fff; border-radius: 14px; padding: 1.8em 2em; margin-bottom: 1.2em; border: 1.5px solid #f0e0d4; box-shadow: 0 2px 10px rgba(200,120,80,0.05); }
.section-card h3 { font-size: 1em; font-weight: 700; color: #c0613a; margin: 0 0 0.8em 0; }
.abstract-text { font-size: 0.95em; line-height: 1.9; color: #4a3528; margin: 0; }
.highlight-box { background: #fdf0e8; border-left: 3px solid #c0613a; border-radius: 0 10px 10px 0; padding: 0.9em 1.2em; margin-top: 1em; font-size: 0.88em; color: #7a3020; font-weight: 600; }
.bibtex-block { background: #fdf6ee; border-radius: 10px; padding: 1.2em 1.4em; font-family: 'Courier New', monospace; font-size: 0.82em; line-height: 1.7; color: #3d2b1f; overflow-x: auto; border: 1px solid #f0d4c0; margin: 0; }
.copy-btn { position: absolute; top: 10px; right: 10px; background: #c0613a; color: white; border: none; border-radius: 8px; padding: 4px 12px; font-size: 0.75em; cursor: pointer; font-weight: 700; transition: background 0.2s; }
.copy-btn:hover { background: #a04f2e; }
.link-btn { display: inline-flex; align-items: center; gap: 6px; padding: 9px 20px; border-radius: 25px; font-size: 0.85em; font-weight: 700; text-decoration: none; transition: all 0.2s; margin-right: 8px; margin-bottom: 8px; }
.btn-primary { background: #c0613a; color: white; box-shadow: 0 3px 12px rgba(192,97,58,0.3); }
.btn-primary:hover { background: #a04f2e; transform: translateY(-2px); color: white; text-decoration: none; }
.btn-secondary { background: white; color: #7a5c4e; border: 1.5px solid #e0c8bc; }
.btn-secondary:hover { background: #fdf6ee; transform: translateY(-2px); color: #3d2b1f; text-decoration: none; }
.related-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 12px; }
.related-card { background: #fdf9f5; border-radius: 12px; padding: 14px 16px; border: 1.5px solid #f0e0d4; text-decoration: none; transition: all 0.2s; display: block; }
.related-card:hover { transform: translateY(-3px); box-shadow: 0 6px 18px rgba(192,97,58,0.1); border-color: #e0a888; text-decoration: none; }
.related-year { font-size: 0.72em; font-weight: 700; color: #c0613a; background: #fdf0e8; padding: 2px 8px; border-radius: 10px; display: inline-block; margin-bottom: 6px; }
.related-title { font-size: 0.88em; font-weight: 700; color: #3d2b1f; line-height: 1.4; margin-bottom: 4px; }
.related-venue { font-size: 0.78em; color: #a08070; font-style: italic; }
</style>

<div class="pub-hero">
<div class="pub-meta-row">
  <span class="pub-chip highlight">📄 Journal Article</span>
  <span class="pub-chip">📅 April 2024</span>
  <span class="pub-chip">🏛 Computer Methods and Programs in Biomedicine Update</span>
</div>
<div>
  <a href="https://www.sciencedirect.com/science/article/pii/S2666990024000193?via%3Dihub" target="_blank" class="link-btn btn-primary">🔗 View on ScienceDirect</a>
  <a href="https://doi.org/10.1016/j.cmpbup.2024.100152" target="_blank" class="link-btn btn-secondary">📎 DOI Link</a>
</div>
</div>

<div class="section-card">
<h3>📝 Abstract</h3>
<p class="abstract-text">DiGAN represents a breakthrough approach in the field of medical diagnostics, especially in diabetes classification. Clinical diabetic datasets are frequently characterized by severe class imbalance, where minority classes represent critical high-risk patient groups. Standard oversampling techniques often fail to generate sufficiently realistic synthetic samples for complex clinical feature spaces. DiGAN employs a Generative Adversarial Network architecture specifically designed for diabetic data distributions, incorporating domain knowledge into the discriminator to ensure physiological plausibility of generated samples. The augmented datasets consistently improve classifier performance, achieving significant gains in minority class recall and AUC compared to existing baselines.</p>
<div class="highlight-box">🔬 Key Contribution: DiGAN is the first GAN-based framework tailored specifically for diabetic clinical data imbalance correction, with clinically validated synthetic sample generation.</div>
</div>

<div class="section-card">
<h3>📋 BibTeX Citation</h3>
<div style="position:relative;">
<pre class="bibtex-block" id="bib-digan">{% raw %}@article{zhao2024digan,
  title     = {{DiGAN} Breakthrough: Advancing Diabetic Data 
               Analysis with Innovative {GAN}-Based Imbalance 
               Correction Techniques},
  author    = {Zhao, Puyang and Liu, X. and Yue, Z. and others},
  journal   = {Computer Methods and Programs in 
               Biomedicine Update},
  year      = {2024},
  month     = {apr},
  doi       = {10.1016/j.cmpbup.2024.100152},
  url       = {https://doi.org/10.1016/j.cmpbup.2024.100152},
  publisher = {Elsevier}
}{% endraw %}</pre>
<button class="copy-btn" onclick="copyBib('bib-digan',this)">📋 Copy</button>
</div>
</div>

<div class="section-card">
<h3>🔗 Related Publications</h3>
<div class="related-grid">
  <a href="/publication/vaping-heart-rate" class="related-card">
    <span class="related-year">2025</span>
    <div class="related-title">Applied Statistical Methods for Identifying Features of Heart Rate Associated with Nicotine Vaping</div>
    <div class="related-venue">American Journal of Drug and Alcohol Abuse</div>
  </a>
  <a href="/publication/LSTM_BITCOIN" class="related-card">
    <span class="related-year">2022</span>
    <div class="related-title">An Attention-based LSTM Framework for Detection of Bitcoin Scams</div>
    <div class="related-venue">IEEE HDIS · Tianjin 🏆 Best Paper Nom.</div>
  </a>
  <a href="/publication/CENN" class="related-card">
    <span class="related-year">2024</span>
    <div class="related-title">CENN: Capsule-Enhanced Neural Network with Innovative Metrics for Robust SER</div>
    <div class="related-venue">Knowledge-Based Systems</div>
  </a>
</div>
</div>

<script>
function copyBib(id, btn) {
  var text = document.getElementById(id).innerText;
  navigator.clipboard.writeText(text).then(function() {
    btn.innerText = '✅ Copied!';
    setTimeout(function(){ btn.innerText = '📋 Copy'; }, 2000);
  });
}
</script>
