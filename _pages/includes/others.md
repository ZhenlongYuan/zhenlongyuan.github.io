# 🎙️ Talks & Teaching

<style>
#talks-section details {
  margin-bottom: 1em;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  border: 1px solid #e8e8e8;
  transition: box-shadow 0.3s;
}
#talks-section details:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}
#talks-section details[open] {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}

#talks-section summary {
  padding: 0.9em 1.2em;
  cursor: pointer;
  font-size: 1.1em;
  font-weight: 600;
  color: #1a1a1a;
  background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
  user-select: none;
  display: flex;
  align-items: center;
  gap: 0.5em;
  list-style: none;
  transition: background 0.2s;
}
#talks-section summary::-webkit-details-marker { display: none; }
#talks-section summary::before {
  content: "▶";
  font-size: 0.7em;
  color: #4CAF50;
  transition: transform 0.25s;
  display: inline-block;
}
#talks-section details[open] > summary::before {
  transform: rotate(90deg);
}
#talks-section summary:hover {
  background: linear-gradient(135deg, #c8e6c9 0%, #a5d6a7 100%);
}

#talks-section .section-content {
  padding: 1.2em 1.5em;
  background: #fff;
}

/* Talks timeline */
#talks-section .talk-item {
  display: flex;
  gap: 1em;
  padding: 0.8em 0;
  border-bottom: 1px solid #f0f0f0;
}
#talks-section .talk-item:last-child { border-bottom: none; }
#talks-section .talk-date {
  flex-shrink: 0;
  font-size: 0.82em;
  font-weight: 600;
  color: #fff;
  background: #4CAF50;
  padding: 3px 10px;
  border-radius: 4px;
  height: fit-content;
  margin-top: 2px;
}
#talks-section .talk-text {
  color: #333;
  line-height: 1.6;
}
#talks-section .talk-text strong {
  color: #1a1a1a;
}
#talks-section .talk-venue {
  display: block;
  font-size: 0.88em;
  color: #666;
  margin-top: 2px;
}

/* Reviewer badges */
#talks-section .reviewer-category {
  margin-bottom: 1em;
}
#talks-section .reviewer-category:last-child {
  margin-bottom: 0;
}
#talks-section .reviewer-label {
  font-weight: 600;
  font-size: 0.92em;
  color: #555;
  margin-bottom: 0.6em;
  display: flex;
  align-items: center;
  gap: 0.4em;
}
#talks-section .venue-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5em;
}
#talks-section .venue-badge {
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
#talks-section .venue-badge:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 10px rgba(25, 118, 210, 0.35);
}
#talks-section .venue-badge.journal {
  background: linear-gradient(135deg, #7B1FA2, #6A1B9A);
  box-shadow: 0 2px 6px rgba(123, 31, 162, 0.2);
}
#talks-section .venue-badge.journal:hover {
  box-shadow: 0 4px 10px rgba(123, 31, 162, 0.35);
}
#talks-section .venue-badge.ai {
  background: linear-gradient(135deg, #E91E63, #C2185B);
  box-shadow: 0 2px 6px rgba(233, 30, 99, 0.2);
}
#talks-section .venue-badge.ai:hover {
  box-shadow: 0 4px 10px rgba(233, 30, 99, 0.35);
}
</style>

<div id="talks-section">

<details open>
<summary>🎙️ Invited Talks</summary>
<div class="section-content">

<div class="talk-item">
  <span class="talk-date">TBD</span>
  <div class="talk-text">
    <strong>Coming soon...</strong>
  </div>
</div>

</div>
</details>

</div>