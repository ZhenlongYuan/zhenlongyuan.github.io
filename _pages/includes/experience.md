# 💼 Professional Experience

<style>
#work-section details {
  margin-bottom: 1em;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  border: 1px solid #e8e8e8;
  transition: box-shadow 0.3s;
}
#work-section details:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}
#work-section details[open] {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}

#work-section summary {
  padding: 0.9em 1.2em;
  cursor: pointer;
  font-size: 1.1em;
  font-weight: 600;
  color: #1a1a1a;
  background: linear-gradient(135deg, #fff8f0 0%, #fff3e6 100%);
  user-select: none;
  display: flex;
  align-items: center;
  gap: 0.5em;
  list-style: none;
  transition: background 0.2s;
}
#work-section summary::-webkit-details-marker { display: none; }
#work-section summary::before {
  content: "▶";
  font-size: 0.7em;
  color: #FF9800;
  transition: transform 0.25s;
  display: inline-block;
}
#work-section details[open] > summary::before {
  transform: rotate(90deg);
}
#work-section summary:hover {
  background: linear-gradient(135deg, #fff3e6 0%, #ffe8cc 100%);
}

#work-section .exp-item {
  padding: 1.2em 1.5em;
  border-bottom: 1px solid #f0f0f0;
  transition: background 0.15s;
}
#work-section .exp-item:last-child { border-bottom: none; }
#work-section .exp-item:hover { background: #fffcf8; }

#work-section .company-header {
  display: flex;
  align-items: center;
  gap: 15px;
  margin-bottom: 0.5em;
}
#work-section .company-header img {
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
#work-section .company-name {
  font-size: 1.1em;
  font-weight: 600;
  color: #1a1a1a;
  margin: 0;
}
#work-section .position-info {
  color: #555;
  font-size: 0.95em;
  margin: 0.3em 0;
  font-style: italic;
}
#work-section .location {
  color: #666;
  font-size: 0.9em;
  margin: 0;
}

#work-section .exp-details {
  margin-top: 0.8em;
  padding-left: 0;
  list-style-type: none;
}
#work-section .exp-details > li {
  margin-bottom: 0.5em;
  line-height: 1.7;
  color: #444;
  padding-left: 1.2em;
  position: relative;
}
#work-section .exp-details > li::before {
  content: "•";
  color: #FF9800;
  font-weight: bold;
  position: absolute;
  left: 0;
}

#work-section a {
  color: #2196F3;
  text-decoration: none;
  transition: color 0.2s;
}
#work-section a:hover {
  color: #1976D2;
  text-decoration: underline;
}
</style>

<div id="work-section">

<details open>
<summary>💼 Industry Experience</summary>

<div class="exp-item">
<div class="company-header">
  <img src="/images/DreamX.png" alt="DreamX Logo" width="60"/>
  <div>
    <p class="company-name">DreamX Team, Alibaba</p>
    <p class="position-info">Research Intern</p>
    <p class="location">📍 Beijing · Jun 2025 - Jan 2026</p>
  </div>
</div>
<ul class="exp-details">
  <li>Research focus: Vision-Language Models (VLM), Foundation Models, Agentic AI</li>
  <li>Contributed to <a href="https://github.com/AMAP-ML/DreamX-World">DreamX-World</a>: A General-Purpose Interactive World Model</li>
</ul>
</div>

<div class="exp-item">
<div class="company-header">
  <img src="/images/Meituan.png" alt="Meituan Logo" width="60"/>
  <div>
    <p class="company-name">LongCat Team, Meituan</p>
    <p class="position-info">Research Intern</p>
    <p class="location">📍 Beijing · Jan 2026 - Present</p>
  </div>
</div>
<ul class="exp-details">
  <li>Developed <a href="https://arxiv.org/abs/2510.08480">Video-STAR</a>: Reinforcing zero-shot video understanding with tools</li>
  <li>Developed <a href="https://arxiv.org/abs/2509.01944v1">AutoDrive-R²</a>: Incentivizing reasoning and self-reflection for VLA in autonomous driving</li>
  <li>Developed <a href="https://arxiv.org/abs/2511.19912">Reasoning-VLA</a>: A fast and general VLA reasoning model for autonomous driving</li>
</ul>
</div>

</details>

</div>
