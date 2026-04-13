# 🎓 Professional Service

<style>
#service-section details {
  margin-bottom: 1em;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  border: 1px solid #e8e8e8;
  transition: box-shadow 0.3s;
}
#service-section details:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}
#service-section details[open] {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}

#service-section summary {
  padding: 0.9em 1.2em;
  cursor: pointer;
  font-size: 1.1em;
  font-weight: 600;
  color: #1a1a1a;
  background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
  user-select: none;
  display: flex;
  align-items: center;
  gap: 0.5em;
  list-style: none;
  transition: background 0.2s;
}
#service-section summary::-webkit-details-marker { display: none; }
#service-section summary::before {
  content: "▶";
  font-size: 0.7em;
  color: #1565C0;
  transition: transform 0.25s;
  display: inline-block;
}
#service-section details[open] > summary::before {
  transform: rotate(90deg);
}
#service-section summary:hover {
  background: linear-gradient(135deg, #bbdefb 0%, #90caf9 100%);
}

#service-section .service-content {
  padding: 1.2em 1.5em;
  background: #fff;
}

#service-section .reviewer-category {
  margin-bottom: 1em;
}
#service-section .reviewer-category:last-child {
  margin-bottom: 0;
}
#service-section .reviewer-label {
  font-weight: 600;
  font-size: 0.92em;
  color: #555;
  margin-bottom: 0.6em;
  display: flex;
  align-items: center;
  gap: 0.4em;
}
#service-section .venue-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5em;
}
#service-section .venue-badge {
  display: inline-block;
  padding: 4px 12px;
  font-size: 0.82em;
  font-weight: 600;
  border-radius: 6px;
  background: linear-gradient(135deg, #1976D2, #1565C0);
  color: #fff;
  transition: all 0.15s;
  cursor: default;
  box-shadow: 0 2px 6px rgba(25, 118, 210, 0.2);
}
#service-section .venue-badge:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 10px rgba(25, 118, 210, 0.35);
}
#service-section .venue-badge.journal {
  background: linear-gradient(135deg, #7B1FA2, #6A1B9A);
  box-shadow: 0 2px 6px rgba(123, 31, 162, 0.2);
}
#service-section .venue-badge.journal:hover {
  box-shadow: 0 4px 10px rgba(123, 31, 162, 0.35);
}
#service-section .venue-badge.ai {
  background: linear-gradient(135deg, #E91E63, #C2185B);
  box-shadow: 0 2px 6px rgba(233, 30, 99, 0.2);
}
#service-section .venue-badge.ai:hover {
  box-shadow: 0 4px 10px rgba(233, 30, 99, 0.35);
}
</style>

<div id="service-section">

<details open>
<summary>🎓 Professional Service</summary>
<div class="service-content">

<div class="reviewer-category">
  <div class="reviewer-label">🤖 AI / Machine Learning</div>
  <div class="venue-badges">
    <span class="venue-badge ai">NeurIPS</span>
    <span class="venue-badge ai">ICML</span>
    <span class="venue-badge ai">ICLR</span>
    <span class="venue-badge ai">AAAI</span>
  </div>
</div>

<div class="reviewer-category">
  <div class="reviewer-label">👁️ Computer Vision & Multimodal</div>
  <div class="venue-badges">
    <span class="venue-badge">CVPR</span>
    <span class="venue-badge">ICCV</span>
    <span class="venue-badge">ECCV</span>
    <span class="venue-badge">ICCV Workshop</span>
    <span class="venue-badge">NeurIPS Workshop</span>
  </div>
</div>

<div class="reviewer-category">
  <div class="reviewer-label">📰 Journals</div>
  <div class="venue-badges">
    <span class="venue-badge journal">IJCV</span>
    <span class="venue-badge journal">TIP</span>
    <span class="venue-badge journal">TMM</span>
    <span class="venue-badge journal">TNNLS</span>
    <span class="venue-badge journal">TCSVT</span>
    <span class="venue-badge journal">PR</span>
  </div>
</div>

</div>
</details>

</div>
