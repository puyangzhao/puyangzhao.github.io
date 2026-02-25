---
title: "An Attention-Based Long Short-Term Memory Framework for Detection of Bitcoin Scams"
collection: publications
category: conferences
permalink: /publications/2022-bitcoin-scams
excerpt: 'An attention-enhanced LSTM framework for detecting Bitcoin scam transactions on blockchain networks. Best Paper Nomination at IEEE HDIS 2022.'
date: 2022-08-01
venue: 'IEEE HDIS, Tianjin'
paperurl: 'https://ieeexplore.ieee.org/'
citation: 'Zhao, P., Tian, W., Xiao, L., Liu, X., &amp; Wu, J. (2022). An Attention-Based Long Short-Term Memory Framework for Detection of Bitcoin Scams. <i>IEEE HDIS</i>, Tianjin.'
---

<style>
.pub-hero { background: linear-gradient(135deg, #fff8e1 0%, #ffecb3 100%); border-radius: 16px; padding: 2em 2.2em; margin-bottom: 2em; border: 1.5px solid #ffe082; box-shadow: 0 4px 20px rgba(200,160,40,0.1); }
.pub-meta-row { display: flex; flex-wrap: wrap; gap: 8px; margin: 0.8em 0 1em; }
.pub-chip { display: inline-flex; align-items: center; gap: 5px; background: rgba(255,255,255,0.8); border: 1px solid rgba(180,120,0,0.25); border-radius: 20px; padding: 3px 12px; font-size: 0.82em; color: #7a5a00; }
.pub-chip.highlight { background: #e65100; color: white; border-color: #e65100; }
.pub-chip.award { background: #f57f17; color: white; border-color: #f57f17; }
.section-card { background: #fff; border-radius: 14px; padding: 1.8em 2em; margin-bottom: 1.2em; border: 1.5px solid #ffe082; box-shadow: 0 2px 10px rgba(200,160,40,0.06); }
.section-card h3 { font-size: 1em; font-weight: 700; color: #e65100; margin: 0 0 0.8em 0; }
.abstract-text { font-size: 0.95em; line-height: 1.9; color: #3a2a00; margin: 0; }
.bibtex-block { background: #fffde7; border-radius: 10px; padding: 1.2em 1.4em; font-family: 'Courier New', monospace; font-size: 0.82em; line-height: 1.7; color: #3a2a00; overflow-x: auto; border: 1px solid #ffe082; }
.copy-btn { position: absolute; top: 10px; right: 10px; background: #e65100; color: white; border: none; border-radius: 8px; padding: 4px 12px; font-size: 0.75em; cursor: pointer; font-weight: 700; }
.link-btn { display: inline-flex; align-items: center; gap: 6px; padding: 9px 20px; border-radius: 25px; font-size: 0.85em; font-weight: 700; text-decoration: none; transition: all 0.2s; margin-right: 8px; margin-bottom: 8px; }
.btn-primary { background: #e65100; color: white; box-shadow: 0 3px 12px rgba(230,81,0,0.3); }
.btn-primary:hover { background: #bf360c; transform: translateY(-2px); color: white; text-decoration: none; }
.btn-secondary { background: white; color: #7a5a00; border: 1.5px solid #ffe082; }
.btn-secondary:hover { background: #fffde7; transform: translateY(-2px); color: #3a2a00; text-decoration: none; }
.award-banner { background: linear-gradient(135deg, #f57f17, #e65100); border-radius: 12px; padding: 1em 1.4em; margin-bottom: 1.2em; color: white; display: flex; align-items: center; gap: 12px; font-weight: 700; }
.related-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 12px; }
.related-card { background: #fffde7; border-radius: 12px; padding: 14px 16px; border: 1.5px solid #ffe082; text-decoration: none; transition: all 0.2s; display: block; }
.related-card:hover { transform: translateY(-3px); box-shadow: 0 6px 18px rgba(200,160,40,0.15); text-decoration: none; }
.related-year { font-size: 0.72em; font-weight: 700; color: #e65100; background: #fff8e1; padding: 2px 8px; border-radius: 10px; display: inline-block; margin-bottom: 6px; }
.related-title { font-size: 0.88em; font-weight: 700; color: #3a2a00; line-height: 1.4; margin-bottom: 4px; }
.related-venue { font-size: 0.78em; color: #a08040; font-style: italic; }
</style>

<div class="award-banner">
  <span style="font-size:1.6em;">🏆</span>
  <div>
    <div style="font-size:1em;">Best Paper Nomination</div>
    <div style="font-size:0.82em;opacity:0.9;font-weight:400;">IEEE HDIS 2022, Tianjin, China</div>
  </div>
</div>

<div class="pub-hero">
<div class="pub-meta-row">
  <span class="pub-chip highlight">🏛 Conference Paper</span>
  <span class="pub-chip award">🏆 Best Paper Nom.</span>
  <span class="pub-chip">📅 2022</span>
  <span class="pub-chip">📍 Tianjin, China</span>
</div>
<div>
  <a href="https://ieeexplore.ieee.org/" target="_blank" class="link-btn btn-primary">🔗 IEEE Xplore</a>
  <a href="mailto:puyang.zhao@rice.edu?subject=PDF Request: Bitcoin Scams Paper" class="link-btn btn-secondary">📧 Request PDF</a>
</div>
</div>

<div class="section-card">
<h3>📝 Abstract</h3>
<p class="abstract-text">
<strong>Background:</strong> The rapid growth of cryptocurrency markets has been accompanied by a proliferation of blockchain-based scams that cause significant financial harm. Automated detection of scam transactions on the Bitcoin network requires methods capable of capturing complex temporal and structural patterns in transaction data.<br><br>
<strong>Objectives:</strong> We propose an Attention-Based LSTM (AB-LSTM) framework for detecting Bitcoin scam addresses and transactions, leveraging temporal modeling and attention mechanisms to identify suspicious behavioral patterns.<br><br>
<strong>Methods:</strong> Transaction features are extracted from the Bitcoin blockchain and structured as time series sequences. An LSTM network with an integrated attention mechanism is trained to classify addresses as scam or legitimate based on transaction history patterns. The attention mechanism enables the model to focus on the most discriminative temporal segments of transaction behavior.<br><br>
<strong>Results:</strong> The AB-LSTM framework achieves high detection accuracy on a labeled Bitcoin scam dataset, outperforming baseline LSTM and classical machine learning approaches. The attention weights provide interpretable insights into which transaction patterns are most indicative of scam behavior.<br><br>
<strong>Conclusions:</strong> Attention-enhanced LSTM effectively captures the temporal dynamics of Bitcoin scam transactions, providing an interpretable and accurate tool for blockchain fraud detection.
</p>
</div>

<div class="section-card">
<h3>📋 BibTeX Citation</h3>
<div style="position:relative;">
<pre class="bibtex-block" id="bib8">@inproceedings{zhao2022bitcoin,
  title     = {An Attention-Based Long Short-Term Memory 
               Framework for Detection of Bitcoin Scams},
  author    = {Zhao, Puyang and Tian, W. and Xiao, L. 
               and Liu, X. and Wu, J.},
  booktitle = {Proceedings of IEEE HDIS},
  year      = {2022},
  address   = {Tianjin, China},
  publisher = {IEEE},
  note      = {Best Paper Nomination}
}</pre>
<button class="copy-btn" onclick="copyBib('bib8',this)">📋 Copy</button>
</div>
</div>

<div class="section-card">
<h3>🔗 Related Publications</h3>
<div class="related-grid">
  <a href="/publications/2022-solar-power" class="related-card">
    <span class="related-year">2022</span>
    <div class="related-title">Research on Prediction of Solar Power via Statistical and Machine Learning Methods</div>
    <div class="related-venue">IOP Conference Series, Tokyo</div>
  </a>
  <a href="/publications/2025-federated-diabetes" class="related-card">
    <span class="related-year">2025</span>
    <div class="related-title">Weighted Federated Learning with Encryption for Diabetes Classification</div>
    <div class="related-venue">IEEE CPS, AIxMHC</div>
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
