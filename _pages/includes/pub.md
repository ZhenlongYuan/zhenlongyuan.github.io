# 📝 Selected Publications

For a complete list of publications, please visit my [Google Scholar profile](https://scholar.google.co.jp/citations?user=zii-mcAAAAAJ&hl=zh-CN)

**Note:** * denotes equal contribution

<style>
#pub-section details {
  margin-bottom: 1em;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  border: 1px solid #e8e8e8;
  transition: box-shadow 0.3s;
}
#pub-section details:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}
#pub-section details[open] {
  box-shadow: 0 4px 16px rgba(0,0,0,0.10);
}

#pub-section summary {
  padding: 0.9em 1.2em;
  cursor: pointer;
  font-size: 1.1em;
  font-weight: 600;
  color: #1a1a1a;
  background: linear-gradient(135deg, #fef5ff 0%, #f5eef8 100%);
  user-select: none;
  display: flex;
  align-items: center;
  gap: 0.5em;
  list-style: none;
  transition: background 0.2s;
}
#pub-section summary::-webkit-details-marker { display: none; }
#pub-section summary::before {
  content: "▶";
  font-size: 0.7em;
  color: #9C27B0;
  transition: transform 0.25s;
  display: inline-block;
}
#pub-section details[open] > summary::before {
  transform: rotate(90deg);
}
#pub-section summary:hover {
  background: linear-gradient(135deg, #f5eef8 0%, #ece0f0 100%);
}

#pub-section .badge-count {
  font-size: 0.75em;
  font-weight: 500;
  color: #fff;
  background: #9C27B0;
  padding: 2px 9px;
  border-radius: 12px;
  margin-left: auto;
}

.paper-box {
  list-style-type: none;
  margin-bottom: 0;
  padding: 1.5em;
  border-bottom: 1px solid #f0f0f0;
  transition: background 0.15s;
}
.paper-box:last-child { border-bottom: none; }
.paper-box:hover { background: #fdfaff; }

.paper-box-image img {
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.paper-box-text {
  display: flex;
  flex-direction: column;
  gap: 6px;
}

.paper-box-text a {
  color: #1a1a1a;
  font-weight: 600;
  font-size: 1.05em;
  text-decoration: none;
  transition: all 0.2s;
}
.paper-box-text a:hover {
  color: #9C27B0;
  text-decoration: underline;
}

.badge-journal, .badge-conference, .badge-preprint {
  display: inline-block;
  padding: 4px 10px;
  border-radius: 4px;
  font-size: 0.85em;
  font-weight: 600;
  margin-right: 6px;
  margin-bottom: 8px;
}
.badge-journal {
  background: #9C27B0;
  color: white;
}
.badge-conference {
  background: #673AB7;
  color: white;
}
.badge-preprint {
  background: #FF5722;
  color: white;
}

.paper-box-text strong {
  color: #9C27B0;
}

/* Pill tags — matches about.md style */
.paper-pill {
  display: inline-block;
  padding: 2px 10px;
  margin: 2px 4px 2px 0;
  border-radius: 15px;
  font-size: 12px;
  font-weight: 500;
  white-space: nowrap;
}
.paper-pill-blue   { background-color: #e8f4f8; color: #0077b6; }
.paper-pill-orange { background-color: #fff3e0; color: #e65100; }
.paper-pill-purple { background-color: #f3e5f5; color: #7b1fa2; }
.paper-pill-green  { background-color: #e8f5e9; color: #2e7d32; }
.paper-pill-teal   { background-color: #e0f7fa; color: #00838f; }
.paper-pill-red    { background-color: #fce4ec; color: #880e4f; }

/* Consistent field spacing */
.paper-tags-line   { display: flex; flex-wrap: wrap; align-items: center; gap: 0; }
.paper-author-line { font-size: 0.9em; color: #444; }
.paper-links-line  { font-size: 0.88em; }
.paper-links-line a {
  margin-right: 0.8em;
  font-weight: 700;
  text-decoration: none;
  color: #1565C0;
  transition: color 0.2s;
}
.paper-links-line a:hover { color: #0D47A1; text-decoration: underline; }
.paper-abstract-line { font-size: 0.88em; color: #555; line-height: 1.6; }
</style>

<div id="pub-section">

<!-- ====== Technical Report ====== -->
<details open>
<summary>📄 Technical Report <span class="badge-count">1</span></summary>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-preprint">Tech Report 2026</div>
    <img src="images/longcat-next.png" alt="LongCat-Next" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2603.27538">LongCat-Next: Lexicalizing Modalities as Discrete Tokens</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-purple">Native Multimodal</span>
      <span class="paper-pill paper-pill-orange">Any-to-Any Generation</span>
      <span class="paper-pill paper-pill-blue">Foundation Model</span>
    </p>
    <p class="paper-author-line">Meituan LongCat Team</p>
    <p class="paper-links-line">
      <a href="https://arxiv.org/abs/2603.27538">[**[Paper]**]</a>
      <a href="https://github.com/meituan-longcat/LongCat-Next">[**[Code]**]</a>
    </p>
    <p class="paper-abstract-line">LongCat-Next is a native multimodal model (A3B) that unifies text, vision, and audio under a single autoregressive objective via discrete tokenization, achieving strong performance across multimodal benchmarks.</p>
  </div>
</div>

</details>

<!-- ====== Vision-Language Models & VLA ====== -->
<details open>
<summary>🤖 Vision-Language Models &amp; VLA <span class="badge-count">4</span></summary>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-preprint">Preprint</div>
    <img src="images/ImagineAgent.png" alt="What if Agents" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/0000.00000">What if Agents Could Imagine?</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-blue">Vision-Language</span>
      <span class="paper-pill paper-pill-purple">Open-Vocabulary HOI</span>
      <span class="paper-pill paper-pill-orange">Agentic Generation</span>
    </p>
    <p class="paper-author-line">Yuan Z., Qu X., Tang J., Chen R., Sun L., Yu H., Qian C., Chu X., Li S., Zhou Y.</p>
    <p class="paper-links-line">
      <a href="https://arxiv.org/abs/0000.00000">[**[Paper]**]</a>
    </p>
    <p class="paper-abstract-line">What if Agents Could Imagine? reinforces open-vocabulary Human-Object Interaction comprehension through generative modeling.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-conference">ICLR 2026</div>
    <img src="images/VideoSTAR.png" alt="Video-STAR" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2510.08480">Video-STAR: Reinforcing Zero-shot Video Understanding with Tools</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-blue">Tool-Using Agent</span>
      <span class="paper-pill paper-pill-purple">Multi-turn RL</span>
      <span class="paper-pill paper-pill-orange">Zero-shot Video</span>
    </p>
    <p class="paper-author-line"><strong>Yuan Z.</strong>, Qu X., Qian, C., Chen, R., Tang, J., Sun L., Chu X., Zhang D., Wang Y., Cai Y., Li S.</p>
    <p class="paper-links-line">
      <a href="https://arxiv.org/abs/2510.08480">[**[Paper]**]</a>
      <a href="https://github.com/AMAP-ML/Video-STAR">[**[Code]**]</a>
    </p>
    <p class="paper-abstract-line">Video-STAR proposes a novel framework that reinforces zero-shot video understanding through tool-use agents with multi-turn reasoning.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-conference">ICLR 2026</div>
    <img src="images/AutoDrive-R2.png" alt="AutoDrive-R²" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2509.01944v1">AutoDrive-R²: Incentivizing Reasoning and Self-Reflection Capacity for VLA Model in Autonomous Driving</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-blue">Multimodal Reasoning</span>
      <span class="paper-pill paper-pill-orange">Autonomous Driving</span>
      <span class="paper-pill paper-pill-purple">Vision-Language-Action</span>
    </p>
    <p class="paper-author-line"><strong>Featured by</strong> <a href="https://mp.weixin.qq.com/s/7y0-CMAkls16iumNK3mlXg">AutoDrive Heart (自动驾驶之心)</a></p>
    <p class="paper-author-line"><strong>Yuan Z.</strong>, Tang, J., Luo, J., Chen, R., Qian, C., Sun, L., Cai Y., Zhang D., Li, S.</p>
    <p class="paper-links-line">
      <a href="https://arxiv.org/abs/2509.01944v1">[**[Paper]**]</a>
      <a href="https://github.com/AMAP-ML/AutoDrive-R2">[**[Code]**]</a>
    </p>
    <p class="paper-abstract-line">AutoDrive-R² introduces a reasoning and self-reflection framework for Vision-Language-Action models in autonomous driving scenarios.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-preprint">Preprint</div>
    <img src="images/Reasoning-VLA.png" alt="Reasoning-VLA" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2511.19912">Reasoning-VLA: A Fast and General Vision-Language-Action Reasoning Model for Autonomous Driving</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-orange">Autonomous Driving</span>
      <span class="paper-pill paper-pill-blue">Fast VLA</span>
      <span class="paper-pill paper-pill-purple">Real-time Inference</span>
    </p>
    <p class="paper-author-line">Zhang D.*, <strong>Yuan Z.*</strong>, Chen Z., Liao C., Chen Y., Shen F., Zhou Q., Chua T.</p>
    <p class="paper-links-line">
      <a href="https://arxiv.org/abs/2511.19912">[**[Paper]**]</a>
    </p>
    <p class="paper-abstract-line">Reasoning-VLA presents a fast and general VLA reasoning model optimized for real-time autonomous driving applications.</p>
  </div>
</div>

</details>

<!-- ====== Generative Foundation Model ====== -->
<details open>
<summary>🎨 Generative Foundation Model <span class="badge-count">2</span></summary>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-conference">CVPR 2026</div>
    <img src="images/Q1.png" alt="ADE-CoT" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://openreview.net/forum?id=id747ZRjaL">ADE-CoT: Adaptive Diffusion Elicits Chain-of-Thought in Image Editing</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-red">Diffusion Model</span>
      <span class="paper-pill paper-pill-teal">Chain-of-Thought</span>
      <span class="paper-pill paper-pill-green">Image Editing</span>
    </p>
    <p class="paper-author-line">Qu X.*, <strong>Yuan Z.*</strong>, Tang J., Chen R., Tang D., Yu M., Sun L., Bai Y., Chu X., Gou G., Xiong G., Cai Y.</p>
    <p class="paper-links-line">
      <a href="https://openreview.net/forum?id=id747ZRjaL">[**[Paper]**]</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-preprint">Preprint</div>
    <img src="images/Degradation.png" alt="Recovering Degradations" width="100%">
  </div>
  <div class="paper-box-text">
    <p>Recovering Degradations with Generative Model: A Consistency-aware Distillation Network for Infrared and Visible Image Fusion</p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-green">Generation Model</span>
      <span class="paper-pill paper-pill-blue">Image Fusion</span>
      <span class="paper-pill paper-pill-orange">Infrared-Visible</span>
    </p>
    <p class="paper-author-line">Yu H.*, <strong>Yuan Z.*</strong>, Bai Y., Li J., Liu J., Li S., Sun L., Chu X.</p>
  </div>
</div>

</details>

<!-- ====== 3D Vision ====== -->
<details open>
<summary>📐 3D Vision <span class="badge-count">6</span></summary>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-journal">TCSVT 2025</div>
    <img src="images/DVP-MVS++.png" alt="DVP-MVS++" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://arxiv.org/abs/2506.13215">DVP-MVS++: Synergize Depth-Normal-Edge and Harmonized Visibility Prior for Multi-View Stereo</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-green">Multi-View Stereo</span>
      <span class="paper-pill paper-pill-blue">3D Reconstruction</span>
    </p>
    <p class="paper-author-line"><strong>Yuan Z.</strong>, Zhang, D., Li, Z., Qian, C., Chen, J., Chen, Y., Chen K., Mao T., Li Z., Jiang H., Wang, Z.</p>
    <p class="paper-links-line">
      <a href="https://arxiv.org/abs/2506.13215">[**[Paper]**]</a>
    </p>
    <p class="paper-abstract-line">DVP-MVS++ advances multi-view stereo through synergistic depth-normal-edge and visibility prior modeling.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-journal">TCSVT 2025</div>
    <img src="images/SED-MVS.png" alt="SED-MVS" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://ieeexplore.ieee.org/document/11016951">SED-MVS: Segmentation-Driven and Edge-Aligned Deformation Multi-View Stereo with Depth Restoration and Occlusion Constraint</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-green">Segmentation-Driven</span>
      <span class="paper-pill paper-pill-blue">Depth Estimation</span>
    </p>
    <p class="paper-author-line"><strong>Yuan Z.</strong>, Yang, Z., Cai, Y., Wu, K., Liu, M., Zhang, D., Jiang H, Li Z., Wang, Z.</p>
    <p class="paper-links-line">
      <a href="https://ieeexplore.ieee.org/document/11016951">[**[Paper]**]</a>
    </p>
    <p class="paper-abstract-line">SED-MVS introduces segmentation-driven and edge-aligned deformation for robust multi-view stereo with depth restoration.</p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-conference">AAAI 2025</div>
    <img src="images/DVP-MVS.png" alt="DVP-MVS" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://ojs.aaai.org/index.php/AAAI/article/view/33056">DVP-MVS: Synergize Depth-Edge and Visibility Prior for Multi-View Stereo</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-green">Visibility Prior</span>
      <span class="paper-pill paper-pill-blue">3D Vision</span>
    </p>
    <p class="paper-author-line"><strong>Yuan Z.</strong>, Luo, J., Shen, F., Li, Z., Liu, C., Mao, T., Wang, Z.</p>
    <p class="paper-links-line">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/33056">[**[Paper]**]</a>
      <a href="https://github.com/ZhenlongYuan/DVP-MVS">[**[Code]**]</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-conference">AAAI 2025</div>
    <img src="images/MSP-MVS2.png" alt="MSP-MVS" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://ojs.aaai.org/index.php/AAAI/article/view/33057">MSP-MVS: Multi-granularity segmentation prior guided multi-view stereo</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-green">Segmentation Prior</span>
      <span class="paper-pill paper-pill-blue">Multi-View</span>
    </p>
    <p class="paper-author-line"><strong>Yuan Z.</strong>, Liu, C., Shen, F., Li, Z., Luo, J., Mao, T., Wang, Z.</p>
    <p class="paper-links-line">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/33057">[**[Paper]**]</a>
      <a href="https://github.com/ZhenlongYuan/MSP-MVS">[**[Code]**]</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-conference">AAAI 2024</div>
    <img src="images/SD-MVS.png" alt="SD-MVS" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://ojs.aaai.org/index.php/AAAI/article/view/28512">SD-MVS: Segmentation-driven deformation multi-view stereo with spherical refinement and em optimization</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-green">Spherical Refinement</span>
      <span class="paper-pill paper-pill-blue">EM Optimization</span>
    </p>
    <p class="paper-author-line"><strong>Yuan Z.</strong>, Cao, J., Li, Z., Jiang, H., Wang, Z.</p>
    <p class="paper-links-line">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/28512">[**[Paper]**]</a>
      <a href="https://github.com/ZhenlongYuan/SD-MVS">[**[Code]**]</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge-journal">PR 2024</div>
    <img src="images/TSAR-MVS.png" alt="TSAR-MVS" width="100%">
  </div>
  <div class="paper-box-text">
    <p><a href="https://www.sciencedirect.com/science/article/pii/S0031320324003169">TSAR-MVS: Textureless-Aware Segmentation and Correlative Refinement Guided Multi-View Stereo</a></p>
    <p class="paper-tags-line">
      <span class="paper-pill paper-pill-green">Textureless-Aware</span>
      <span class="paper-pill paper-pill-blue">3D Vision</span>
    </p>
    <p class="paper-author-line"><strong>Yuan Z.</strong>, Cao, J., Wang, Z., Li, Z.</p>
    <p class="paper-links-line">
      <a href="https://www.sciencedirect.com/science/article/pii/S0031320324003169">[**[Paper]**]</a>
      <a href="https://github.com/ZhenlongYuan/TSAR-MVS">[**[Code]**]</a>
    </p>
  </div>
</div>

</details>

</div>
