---
title: "Sparse Temporal-Aware Capsule Network for Robust Speech Emotion Recognition"
collection: publications
category: manuscripts
permalink: /publications/2025-capsule-ser
excerpt: 'A sparse temporal-aware capsule network architecture designed for robust speech emotion recognition across varying acoustic conditions.'
date: 2025-01-15
venue: 'Engineering Applications of Artificial Intelligence'
paperurl: 'https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence'
citation: 'Zhang, H.*, Huang, H., Zhao, P., &amp; Yu, Z. (2025). Sparse Temporal-Aware Capsule Network for Robust Speech Emotion Recognition. <i>Engineering Applications of Artificial Intelligence</i>.'
---

<style>
.pub-hero { background: linear-gradient(135deg, #fdf6ee 0%, #fce8d5 100%); border-radius: 16px; padding: 2em 2.2em; margin-bottom: 2em; border: 1.5px solid #f0d4c0; box-shadow: 0 4px 20px rgba(200,120,80,0.08); }
.pub-meta-row { display: flex; flex-wrap: wrap; gap: 8px; margin: 0.8em 0 1em; }
.pub-chip { display: inline-flex; align-items: center; gap: 5px; background: rgba(255,255,255,0.8); border: 1px solid rgba(192,97,58,0.25); border-radius: 20px; padding: 3px 12px; font-size: 0.82em; color: #7a5c4e; }
.pub-chip.highlight { background: #c0613a; color: white; border-color: #c0613a; }
.section-card { background: #fff; border-radius: 14px; padding: 1.8em 2em; margin-bottom: 1.2em; border: 1.5px solid #f0e0d4; box-shadow: 0 2px 10px rgba(200,120,80,0.05); }
.section-card h3 { font-size: 1em; font-weight: 700; color: #c0613a; margin: 0 0 0.8em 0; }
.abstract-text { font-size: 0.95em; line-height: 1.9; color: #4a3528; margin: 0; }
.bibtex-block { background: #fdf6ee; border-radius: 10px; padding: 1.2em 1.4em; font-family: 'Courier New', monospace; font-size: 0.82em; line-height: 1.7; color: #3d2b1f; overflow-x: auto; border: 1px solid #f0d4c0; }
.copy-btn { position: absolute; top: 10px; right: 10px; background: #c0613a; color: white; border: none; border-radius: 8px; padding: 4px 12px; font-size: 0.75em; cursor: pointer; font-weight: 700; transition: background 0.2s; }
.link-btn { display: inline-flex; align-items: center; gap: 6px; padding: 9px 20px; border-radius: 25px; font-size: 0.85em; font-weight: 700; text-decoration: none; transition: all 0.2s; margin-right: 8px; margin-bottom: 8px; }
.btn-primary { background: #c0613a; color: white; box-shadow: 0 3px 12px rgba(192,97,58,0.3); }
.btn-primary:hover { background: #a04f2e; transform: translateY(-2px); color: white; text-decoration: none; }
.btn-secondary { background: white; color: #7a5c4e; border: 1.5px solid #e0c8bc; }
.btn-secondary:hover { background: #fdf6ee; transform: translateY(-2px); color: #3d2b1f; text-decoration: none; }
.related-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 12px; }
.related-card { background: #fdf9f5; border-radius: 12px; padding: 14px 16px; border: 1.5px solid #f0e0d4; text-decoration: none; transition: all 0.2s; display: block; }
.related-card:hover { transform: translateY(-3px); box-shadow: 0 6px 18px rgba(192,97,58,0.1); text-decoration: none; }
.related-year { font-size: 0.72em; font-weight: 700; color: #c0613a; background: #fdf0e8; padding: 2px 8px; border-radius: 10px; display: inline-block; margin-bottom: 6px; }
.related-title { font-size: 0.88em; font-weight: 700; color: #3d2b1f; line-height: 1.4; margin-bottom: 4px; }
.related-venue { font-size: 0.78em; color: #a08070; font-style: italic; }
</style>

<div class="pub-hero">
<div class="pub-meta-row">
  <span class="pub-chip highlight">📄 Journal Article</span>
  <span class="pub-chip">📅 2025</span>
  <span class="pub-chip">🏛 Engineering Applications of AI</span>
</div>
<div>
  <a href="https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence" target="_blank" class="link-btn btn-primary">🔗 View Journal</a>
  <a href="mailto:puyang.zhao@rice.edu?subject=PDF Request: Capsule SER" class="link-btn btn-secondary">📧 Request PDF</a>
</div>
</div>

<div class="section-card">
<h3>📝 Abstract</h3>
<p class="abstract-text">
<strong>Background:</strong> Capsule networks offer promising properties for speech emotion recognition due to their ability to preserve spatial hierarchies and part-whole relationships in feature representations. However, existing capsule-based SER models struggle with temporal modeling and computational efficiency.<br><br>
<strong>Objectives:</strong> We propose a Sparse Temporal-Aware Capsule Network (STACN) that incorporates temporal awareness and sparsity constraints to improve robustness and efficiency in SER tasks.<br><br>
<strong>Methods:</strong> STACN introduces a temporal capsule routing mechanism that explicitly models the temporal dynamics of emotional speech. A sparsity regularization strategy is applied to capsule activations, encouraging the network to focus on the most emotionally salient time-frequency regions. The architecture is evaluated under both clean and noisy conditions.<br><br>
<strong>Results:</strong> STACN achieves superior performance compared to baseline capsule and non-capsule SER models, with particular gains in noisy and challenging conditions. The sparse activation pattern improves interpretability while maintaining high recognition accuracy.<br><br>
<strong>Conclusions:</strong> Incorporating temporal awareness and sparsity into capsule networks yields a robust SER architecture well-suited for real-world clinical deployment.
</p>
</div>

<div class="section-card">
<h3>📋 BibTeX Citation</h3>
<div style="position:relative;">
<pre class="bibtex-block" id="bib4">@article{zhang2025capsule,
  title     = {Sparse Temporal-Aware Capsule Network for Robust 
               Speech Emotion Recognition},
  author    = {Zhang, H. and Huang, H. and Zhao, Puyang and Yu, Z.},
  journal   = {Engineering Applications of Artificial Intelligence},
  year      = {2025},
  publisher = {Elsevier}
}</pre>
<button class="copy-btn" onclick="copyBib('bib4',this)">📋 Copy</button>
</div>
</div>

<div class="section-card">
<h3>🔗 Related Publications</h3>
<div class="related-grid">
  <a href="/publications/2025-fusion-ser" class="related-card">
    <span class="related-year">2025</span>
    <div class="related-title">Reproducible and Generalizable Speech Emotion Recognition via an Intelligent Fusion Network</div>
    <div class="related-venue">Biomedical Signal Processing and Control</div>
  </a>
  <a href="/publications/2024-cenn-ser" class="related-card">
    <span class="related-year">2024</span>
    <div class="related-title">CENN: Capsule-Enhanced Neural Network with Innovative Metrics for Robust SER</div>
    <div class="related-venue">Knowledge-Based Systems</div>
  </a>
  <a href="/publications/2025-adaptive-routing-ser" class="related-card">
    <span class="related-year">2025</span>
    <div class="related-title">Pre-attentive Speech Signal Processing with Adaptive Routing</div>
    <div class="related-venue">Biomedical Signal Processing and Control</div>
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
