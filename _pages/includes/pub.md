# 📝 Selected Publications

For a complete list of publications, please visit my [Google Scholar profile](https://scholar.google.co.jp/citations?user=zii-mcAAAAAJ&hl=zh-CN)

<details>
<summary>📈 <strong>View Citation Trend</strong></summary>
<div align="center" style="padding: 1em;">
  <img src="https://raw.githubusercontent.com/ZhenlongYuan/ZhenlongYuan.github.io/google-scholar-stats/citation_trend.svg" alt="Citation Trend" style="max-width: 100%; height: auto;">
</div>
</details>

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

.paper-box-text a {
  color: #1a1a1a;
  font-weight: 600;
  font-size: 1.05em;
  text-decoration: none;
  transition: all 0.2s;
}
.paper-box-text a:hover {
  color: #d44000;
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
  color: #d44000;
}

/* Tag pills */
.paper-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-top: 6px;
}
.paper-tag {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  padding: 3px 10px;
  font-size: 0.78em;
  font-weight: 500;
  border-radius: 20px;
  transition: all 0.2s;
  cursor: default;
  white-space: nowrap;
}
.paper-tag:hover {
  transform: translateY(-1px);
}
.paper-tag.tool { background: linear-gradient(135deg, #e3f2fd, #bbdefb); color: #1565c0; }
.paper-tag.rl { background: linear-gradient(135deg, #f3e5f5, #e1bee7); color: #7b1fa2; }
.paper-tag.vision { background: linear-gradient(135deg, #e8f5e9, #c8e6c9); color: #2e7d32; }
.paper-tag.driving { background: linear-gradient(135deg, #fff3e0, #ffe0b2); color: #e65100; }
.paper-tag.reasoning { background: linear-gradient(135deg, #e0f7fa, #b2ebf2); color: #00838f; }
.paper-tag.diffusion { background: linear-gradient(135deg, #fce4ec, #f48fb1); color: #880e4f; }
.paper-tag.mvs { background: linear-gradient(135deg, #f1f8e9, #dcedc8); color: #558b2f; }
</style>

<div id="pub-section">

<!-- ====== Vision-Language Models & VLA ====== -->
<details open>
<summary>🤖 Vision-Language Models & VLA <span class="badge-count">3</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">ICLR 2026</div><img src='images/VideoSTAR.png' alt="Video-STAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video-STAR: Reinforcing Zero-shot Video Understanding with Tools](https://arxiv.org/abs/2510.08480)
<span class="paper-tags">
  <span class="paper-tag tool">🔧 Tool-Using Agent</span>
  <span class="paper-tag rl">🔄 Multi-turn Agentic RL</span>
</span>
**Yuan Z.**, Qu X., Qian, C., Chen, R., Tang, J., Sun L., Chu X., Zhang D., Wang Y., Cai Y., Li S.

[[Paper]](https://arxiv.org/abs/2510.08480) [[Code]](https://github.com/AMAP-ML/Video-STAR)

Video-STAR proposes a novel framework that reinforces zero-shot video understanding through tool-use agents with multi-turn reasoning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">ICLR 2026</div><img src='images/AutoDrive-R2.png' alt="AutoDrive-R²" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoDrive-R²: Incentivizing Reasoning and Self-Reflection Capacity for VLA Model in Autonomous Driving](https://arxiv.org/abs/2509.01944v1)
<span class="paper-tags">
  <span class="paper-tag reasoning">⚡ Multimodal Reasoning</span>
  <span class="paper-tag driving">🚗 Autonomous Driving</span>
</span>
**Featured by** [AutoDrive Heart (自动驾驶之心)](https://mp.weixin.qq.com/s/7y0-CMAkls16iumNK3mlXg)
**Yuan Z.**, Tang, J., Luo, J., Chen, R., Qian, C., Sun, L., Cai Y., Zhang D., Li, S.

[[Paper]](https://arxiv.org/abs/2509.01944v1) [[Code]](https://github.com/AMAP-ML/AutoDrive-R2)

AutoDrive-R² introduces a reasoning and self-reflection framework for Vision-Language-Action models in autonomous driving scenarios.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-preprint">Preprint</div><img src='images/Reasoning-VLA.png' alt="Reasoning-VLA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning-VLA: A Fast and General Vision-Language-Action Reasoning Model for Autonomous Driving](https://arxiv.org/abs/2511.19912)
<span class="paper-tags">
  <span class="paper-tag driving">🚗 Autonomous Driving</span>
  <span class="paper-tag reasoning">⚡ Fast VLA</span>
</span>
Zhang D.\*, **Yuan Z.\***, Chen Z., Liao C., Chen Y., Shen F., Zhou Q., Chua T.

[[Paper]](https://arxiv.org/abs/2511.19912)

Reasoning-VLA presents a fast and general VLA reasoning model optimized for real-time autonomous driving applications.

</div>
</div>

</details>

<!-- ====== Diffusion Models ====== -->
<details open>
<summary>✨ Diffusion Models <span class="badge-count">1</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">CVPR 2026</div><img src='images/Q1.png' alt="ADE-CoT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ADE-CoT: ...](https://openreview.net/forum?id=id747ZRjaL)
<span class="paper-tags">
  <span class="paper-tag diffusion">✨ Diffusion Model</span>
  <span class="paper-tag reasoning">⚡ Chain-of-Thought</span>
</span>
**Yuan Z.**, et al.

[[Paper]](https://openreview.net/forum?id=id747ZRjaL)

</div>
</div>

</details>

<!-- ====== 3D Vision ====== -->
<details open>
<summary>📐 3D Vision <span class="badge-count">6</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">TCSVT 2025</div><img src='images/DVP-MVS++.png' alt="DVP-MVS++" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DVP-MVS++: Synergize Depth-Normal-Edge and Harmonized Visibility Prior for Multi-View Stereo](https://arxiv.org/abs/2506.13215)
<span class="paper-tags">
  <span class="paper-tag mvs">📷 Multi-View Stereo</span>
  <span class="paper-tag vision">👁️ 3D Reconstruction</span>
</span>
**Yuan Z.**, Zhang, D., Li, Z., Qian, C., Chen, J., Chen, Y., Chen K., Mao T., Li Z., Jiang H., Wang, Z.

[[Paper]](https://arxiv.org/abs/2506.13215)

DVP-MVS++ advances multi-view stereo through synergistic depth-normal-edge and visibility prior modeling.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">TCSVT 2025</div><img src='images/SED-MVS.png' alt="SED-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SED-MVS: Segmentation-Driven and Edge-Aligned Deformation Multi-View Stereo with Depth Restoration and Occlusion Constraint](https://ieeexplore.ieee.org/document/11016951)
<span class="paper-tags">
  <span class="paper-tag mvs">📷 Segmentation-Driven</span>
  <span class="paper-tag vision">👁️ Depth Estimation</span>
</span>
**Yuan Z.**, Yang, Z., Cai, Y., Wu, K., Liu, M., Zhang, D., Jiang H, Li Z., Wang, Z.

[[Paper]](https://ieeexplore.ieee.org/document/11016951)

SED-MVS introduces segmentation-driven and edge-aligned deformation for robust multi-view stereo with depth restoration.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2025</div><img src='images/DVP-MVS.png' alt="DVP-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DVP-MVS: Synergize Depth-Edge and Visibility Prior for Multi-View Stereo](https://ojs.aaai.org/index.php/AAAI/article/view/33056)
<span class="paper-tags">
  <span class="paper-tag mvs">📷 Visibility Prior</span>
  <span class="paper-tag vision">👁️ 3D Vision</span>
</span>
**Yuan Z.**, Luo, J., Shen, F., Li, Z., Liu, C., Mao, T., Wang, Z.

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33056) [[Code]](https://github.com/ZhenlongYuan/DVP-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2025</div><img src='images/MSP-MVS2.png' alt="MSP-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MSP-MVS: Multi-granularity segmentation prior guided multi-view stereo](https://ojs.aaai.org/index.php/AAAI/article/view/33057)
<span class="paper-tags">
  <span class="paper-tag mvs">📷 Segmentation Prior</span>
  <span class="paper-tag vision">👁️ Multi-View</span>
</span>
**Yuan Z.**, Liu, C., Shen, F., Li, Z., Luo, J., Mao, T., Wang, Z.

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33057) [[Code]](https://github.com/ZhenlongYuan/MSP-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2024</div><img src='images/SD-MVS.png' alt="SD-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SD-MVS: Segmentation-driven deformation multi-view stereo with spherical refinement and em optimization](https://ojs.aaai.org/index.php/AAAI/article/view/28512)
<span class="paper-tags">
  <span class="paper-tag mvs">📷 Spherical Refinement</span>
  <span class="paper-tag vision">👁️ EM Optimization</span>
</span>
**Yuan Z.**, Cao, J., Li, Z., Jiang, H., Wang, Z.

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/28512) [[Code]](https://github.com/ZhenlongYuan/SD-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">PR 2024</div><img src='images/TSAR-MVS.png' alt="TSAR-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TSAR-MVS: Textureless-aware segmentation and correlative refinement guided multi-view stereo](https://www.sciencedirect.com/science/article/pii/S0031320324003169)
<span class="paper-tags">
  <span class="paper-tag mvs">📷 Textureless-Aware</span>
  <span class="paper-tag vision">👁️ 3D Reconstruction</span>
</span>
**Yuan Z.**, Cao, J., Wang, Z., Li, Z.

[[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320324003169) [[Code]](https://github.com/ZhenlongYuan/TSAR-MVS)

</div>
</div>

</details>

</div>
