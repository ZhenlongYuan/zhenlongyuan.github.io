# 🎓 Education

<style>
#education-section details {
  margin-bottom: 1em;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  border: 1px solid #e8e8e8;
  transition: box-shadow 0.3s;
}
#education-section details:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}
#education-section details[open] {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}
#education-section summary {
  padding: 0.9em 1.2em;
  cursor: pointer;
  font-size: 1.1em;
  font-weight: 600;
  color: #1a1a1a;
  background: linear-gradient(135deg, #f0faf0 0%, #e8f5e9 100%);
  user-select: none;
  display: flex;
  align-items: center;
  gap: 0.5em;
  list-style: none;
  transition: background 0.2s;
}
#education-section summary::-webkit-details-marker { display: none; }
#education-section summary::before {
  content: "▶";
  font-size: 0.7em;
  color: #4CAF50;
  transition: transform 0.25s;
  display: inline-block;
}
#education-section details[open] > summary::before {
  transform: rotate(90deg);
}
#education-section summary:hover {
  background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
}

#education-section .edu-item {
  padding: 1.2em 1.5em;
  border-bottom: 1px solid #f0f0f0;
  transition: background 0.15s;
}
#education-section .edu-item:last-child { border-bottom: none; }
#education-section .edu-item:hover { background: #fafff8; }

#education-section .school-header {
  display: flex;
  align-items: center;
  gap: 15px;
  margin-bottom: 0.5em;
}
#education-section .school-header img {
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
#education-section .school-name {
  font-size: 1.1em;
  font-weight: 600;
  color: #1a1a1a;
  margin: 0;
}
#education-section .degree-info {
  color: #555;
  font-size: 0.95em;
  margin: 0.3em 0;
  font-style: italic;
}
#education-section .location {
  color: #666;
  font-size: 0.9em;
  margin: 0;
}

#education-section .edu-details {
  margin-top: 0.8em;
  padding-left: 0;
  list-style-type: none;
}
#education-section .edu-details > li {
  margin-bottom: 0.5em;
  line-height: 1.7;
  color: #444;
  padding-left: 1.2em;
  position: relative;
}
#education-section .edu-details > li::before {
  content: "•";
  color: #4CAF50;
  font-weight: bold;
  position: absolute;
  left: 0;
}

#education-section a {
  color: #2196F3;
  text-decoration: none;
  transition: color 0.2s;
}
#education-section a:hover {
  color: #1976D2;
  text-decoration: underline;
}
</style>

<div id="education-section">

<details open>
<summary>🎓 Academic Background</summary>

<div class="edu-item">
<div class="school-header">
  <img src="/images/ICT.png" alt="ICT Logo" width="60"/>
  <div>
    <p class="school-name">Institute of Computing Technology, Chinese Academy of Sciences</p>
    <p class="degree-info">Ph.D. in Information and Communication Engineering</p>
    <p class="location">📍 Beijing · Graduated</p>
  </div>
</div>
<ul class="edu-details">
  <li>Research focus: Vision-Language Models, Large Language Models, Embodied Agents, Multimodal AI, 3D Vision</li>
  <li>Advised by <a href="http://english.ict.cas.cn/people/scien/bln/202303/t20230315_328238.html">Prof. Zhaoqi Wang</a></li>
  <li>Collaborated with <a href="https://scholar.google.com/citations?user=6WNtJa0AAAAJ&hl=en">Prof. Shuo Li</a>, <a href="https://vanoracai.github.io/">Prof. Yujun Cai</a>, and <a href="https://wangywust.github.io/">Prof. Yiwei Wang</a></li>
  <li>Published 20+ papers at top AI conferences including NeurIPS, ICLR, ICML, CVPR, ICCV, AAAI</li>
</ul>
</div>

</details>

</div>
