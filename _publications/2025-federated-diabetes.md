---
title: "Weighted Federated Learning with Encryption for Diabetes Classification"
collection: publications
category: conferences
permalink: /publications/2025-federated-diabetes
excerpt: 'A privacy-preserving federated learning framework with weighted aggregation and encryption for secure diabetes classification across distributed clinical sites.'
date: 2025-03-01
venue: 'IEEE CPS, AIxMHC, Taiwan'
paperurl: 'https://ieeexplore.ieee.org/'
citation: 'Zhao, P., Yue, Z., Liu, X., &amp; Wu, J. (2025). Weighted Federated Learning with Encryption for Diabetes Classification. <i>IEEE CPS, AIxMHC</i>, Taiwan.'
---

<style>
.pub-hero { background: linear-gradient(135deg, #eef4fd 0%, #d5e5fc 100%); border-radius: 16px; padding: 2em 2.2em; margin-bottom: 2em; border: 1.5px solid #c0d4f0; box-shadow: 0 4px 20px rgba(80,120,200,0.08); }
.pub-meta-row { display: flex; flex-wrap: wrap; gap: 8px; margin: 0.8em 0 1em; }
.pub-chip { display: inline-flex; align-items: center; gap: 5px; background: rgba(255,255,255,0.8); border: 1px solid rgba(58,90,192,0.25); border-radius: 20px; padding: 3px 12px; font-size: 0.82em; color: #3a5a8a; }
.pub-chip.highlight { background: #1565c0; color: white; border-color: #1565c0; }
.pub-chip.accepted { background: #e8f5e9; color: #2e7d32; border-color: #a5d6a7; }
.section-card { background: #fff; border-radius: 14px; padding: 1.8em 2em; margin-bottom: 1.2em; border: 1.5px solid #e0eaf4; box-shadow: 0 2px 10px rgba(80,120,200,0.05); }
.section-card h3 { font-size: 1em; font-weight: 700; color: #1565c0; margin: 0 0 0.8em 0; }
.abstract-text { font-size: 0.95em; line-height: 1.9; color: #1a2a3a; margin: 0; }
.bibtex-block { background: #f0f4fd; border-radius: 10px; padding: 1.2em 1.4em; font-family: 'Courier New', monospace; font-size: 0.82em; line-height: 1.7; color: #1a2a3a; overflow-x: auto; border: 1px solid #c0d4f0; }
.copy-btn { position: absolute; top: 10px; right: 10px; background: #1565c0; color: white; border: none; border-radius: 8px; padding: 4px 12px; font-size: 0.75em; cursor: pointer; font-weight: 700; }
.link-btn { display: inline-flex; align-items: center; gap: 6px; padding: 9px 20px; border-radius: 25px; font-size: 0.85em; font-weight: 700; text-decoration: none; transition: all 0.2s; margin-right: 8px; margin-bottom: 8px; }
.btn-primary { background: #1565c0; color: white; box-shadow: 0 3px 12px rgba(21,101,192,0.3); }
.btn-primary:hover { background: #0d47a1; transform: translateY(-2px); color: white; text-decoration: none; }
.btn-secondary { background: white; color: #3a5a8a; border: 1.5px solid #c0d4f0; }
.btn-secondary:hover { background: #f0f4fd; transform: translateY(-2px); color: #1a2a3a; text-decoration: none; }
.related-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 12px; }
.related-card { background: #f8faff; border-radius: 12px; padding: 14px 16px; border: 1.5px solid #e0eaf4; text-decoration: none; transition: all 0.2s; display: block; }
.related-card:hover { transform: translateY(-3px); box-shadow: 0 6px 18px rgba(80,120,200,0.1); text-decoration: none; }
.related-year { font-size: 0.72em; font-weight: 700; color: #1565c0; background: #e8f0fd; padding: 2px 8px; border-radius: 10px; display: inline-block; margin-bottom: 6px; }
.related-title { font-size: 0.88em; font-weight: 700; color: #1a2a3a; line-height: 1.4; margin-bottom: 4px; }
.related-venue { font-size: 0.78em; color: #6080a0; font-style: italic; }
</style>

<div class="pub-hero">
<div class="pub-meta-row">
  <span class="pub-chip highlight">🏛 Conference Paper</span>
  <span class="pub-chip accepted">✅ Accepted</span>
  <span class="pub-chip">📅 2025</span>
  <span class="pub-chip">📍 Taiwan</span>
</div>
<div>
  <a href="https://ieeexplore.ieee.org/" target="_blank" class="link-btn btn-primary">🔗 IEEE Xplore</a>
  <a href="mailto:puyang.zhao@rice.edu?subject=PDF Request: Federated Diabetes Paper" class="link-btn btn-secondary">📧 Request PDF</a>
</div>
</div>

<div class="section-card">
<h3>📝 Abstract</h3>
<p class="abstract-text">
<strong>Background:</strong> Diabetes classification using machine learning requires large, diverse datasets, yet patient privacy regulations and institutional data governance policies often prevent direct data sharing across clinical sites. Federated learning offers a promising framework for collaborative model training without centralizing sensitive data.<br><br>
<strong>Objectives:</strong> We propose a Weighted Federated Learning framework with Encryption (WFLE) for diabetes classification that addresses heterogeneity across federated sites while ensuring strong privacy guarantees through encryption protocols.<br><br>
<strong>Methods:</strong> The WFLE framework introduces a performance-based weighting scheme for model aggregation that down-weights contributions from sites with lower data quality or smaller sample sizes. Homomorphic encryption is integrated into the aggregation protocol to prevent inference attacks on model updates. The framework is evaluated on simulated federated scenarios derived from public diabetic datasets.<br><br>
<strong>Results:</strong> WFLE achieves superior diabetes classification performance compared to standard FedAvg under heterogeneous data distributions, while maintaining strong privacy guarantees. The weighted aggregation scheme significantly reduces the impact of low-quality site contributions.<br><br>
<strong>Conclusions:</strong> Privacy-preserving federated learning with intelligent weighting enables effective multi-site diabetes classification without compromising patient privacy, representing a practical framework for real-world clinical deployment.
</p>
</div>

<div class="section-card">
<h3>📋 BibTeX Citation</h3>
<div style="position:relative;">
<pre class="bibtex-block" id="bib7">@inproceedings{zhao2025federated,
  title     = {Weighted Federated Learning with Encryption 
               for Diabetes Classification},
  author    = {Zhao, Puyang and Yue, Z. and Liu, X. and Wu, J.},
  booktitle = {Proceedings of IEEE CPS, AIxMHC},
  year      = {2025},
  address   = {Taiwan},
  publisher = {IEEE}
}</pre>
<button class="copy-btn" onclick="copyBib('bib7',this)">📋 Copy</button>
</div>
</div>

<div class="section-card">
<h3>🔗 Related Publications</h3>
<div class="related-grid">
  <a href="/publications/2024-digan-diabetes" class="related-card">
    <span class="related-year">2024</span>
    <div class="related-title">DiGAN Breakthrough: Advancing Diabetic Data Analysis with GAN-Based Imbalance Correction</div>
    <div class="related-venue">Computer Methods and Programs in Biomedicine Update</div>
  </a>
  <a href="/publications/2025-heart-rate-vaping" class="related-card">
    <span class="related-year">2025</span>
    <div class="related-title">Applied Statistical Methods for Identifying Features of Heart Rate Associated with Nicotine Vaping</div>
    <div class="related-venue">American Journal of Drug and Alcohol Abuse</div>
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
