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

.badge-impact, .badge-ccf {
  display: inline-block;
  padding: 4px 8px;
  border-radius: 3px;
  font-size: 0.75em;
  font-weight: 500;
}
.badge-q1 {
  background: #FFD700;
  color: #333;
}
.badge-ccf-a {
  background: #E91E63;
  color: white;
}
.badge-ccf-b {
  background: #FF9800;
  color: white;
}

.paper-box-text strong {
  color: #9C27B0;
}
.paper-box-text img[src*="shields.io"] {
  vertical-align: middle;
  margin-left: 4px;
}

.research-tags {
  display: inline-flex;
  gap: 4px;
  margin-left: 8px;
  vertical-align: middle;
}
.research-tag {
  display: inline-block;
  padding: 2px 6px;
  font-size: 0.7em;
  font-weight: 500;
  border-radius: 3px;
  background: rgba(118, 75, 162, 0.1);
  color: #764ba2;
  border: 1px solid rgba(118, 75, 162, 0.2);
  white-space: nowrap;
}

.citation-badge {
  display: inline-flex;
  align-items: center;
  gap: 3px;
  padding: 2px 6px;
  font-size: 0.7em;
  font-weight: 500;
  border-radius: 4px;
  background: #4285f4;
  color: white;
  margin-left: 6px;
  vertical-align: middle;
}
</style>

<div id="pub-section">

<!-- ====== Vision-Language Models & VLA ====== -->
<details open>
<summary>🤖 Vision-Language Models & VLA <span class="badge-count">3</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">ICLR 2026</div><img src='images/VideoSTAR.png' alt="Video-STAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video-STAR: Reinforcing Zero-shot Video Understanding with Tools](https://arxiv.org/abs/2510.08480) <span class="research-tags"><span class="research-tag">Tool-Using Agent</span><span class="research-tag">Multi-turn RL</span></span> \\
ICLR | January 2026 \\
**Yuan Z.**, Qu X., Qian, C., Chen, R., Tang, J., Sun L., Chu X., Zhang D., Wang Y., Cai Y., Li S.

[[Paper]](https://arxiv.org/abs/2510.08480) [[Code]](https://github.com/AMAP-ML/Video-STAR)

Video-STAR proposes a novel framework that reinforces zero-shot video understanding through tool-use agents with multi-turn reasoning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">ICLR 2026</div><img src='images/AutoDrive-R2.png' alt="AutoDrive-R²" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoDrive-R²: Incentivizing Reasoning and Self-Reflection Capacity for VLA Model in Autonomous Driving](https://arxiv.org/abs/2509.01944v1) <span class="research-tags"><span class="research-tag">Autonomous Driving</span><span class="research-tag">Multimodal Reasoning</span></span> \\
ICLR | January 2026 \\
**Featured by** [AutoDrive Heart (自动驾驶之心)](https://mp.weixin.qq.com/s/7y0-CMAkls16iumNK3mlXg) \\
**Yuan Z.**, Tang, J., Luo, J., Chen, R., Qian, C., Sun, L., Cai Y., Zhang D., Li, S.

[[Paper]](https://arxiv.org/abs/2509.01944v1) [[Code]](https://github.com/AMAP-ML/AutoDrive-R2)

AutoDrive-R² introduces a reasoning and self-reflection framework for Vision-Language-Action models in autonomous driving scenarios.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-preprint">Preprint</div><img src='images/Reasoning-VLA.png' alt="Reasoning-VLA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning-VLA: A Fast and General Vision-Language-Action Reasoning Model for Autonomous Driving](https://arxiv.org/abs/2511.19912) <span class="research-tags"><span class="research-tag">Autonomous Driving</span><span class="research-tag">Fast VLA</span></span> \\
arXiv | November 2025 \\
Zhang D.\*, **Yuan Z.\***, Chen Z., Liao C., Chen Y., Shen F., Zhou Q., Chua T.

[[Paper]](https://arxiv.org/abs/2511.19912)

Reasoning-VLA presents a fast and general VLA reasoning model optimized for real-time autonomous driving applications.

</div>
</div>

</details>

<!-- ====== 3D Vision ====== -->
<details open>
<summary>📐 3D Vision <span class="badge-count">5</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">TCSVT 2025</div><img src='images/DVP-MVS++.png' alt="DVP-MVS++" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DVP-MVS++: Synergize Depth-Normal-Edge and Harmonized Visibility Prior for Multi-View Stereo](https://arxiv.org/abs/2506.13215) <span class="research-tags"><span class="research-tag">Multi-View Stereo</span><span class="research-tag">3D Reconstruction</span></span> \\
IEEE Transactions on Circuits and Systems for Video Technology | 2025 \\
**Yuan Z.**, Zhang, D., Li, Z., Qian, C., Chen, J., Chen, Y., Chen K., Mao T., Li Z., Jiang H., Wang, Z.

[[Paper]](https://arxiv.org/abs/2506.13215)

DVP-MVS++ advances multi-view stereo through synergistic depth-normal-edge and visibility prior modeling.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">TCSVT 2025</div><img src='images/SED-MVS.png' alt="SED-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SED-MVS: Segmentation-Driven and Edge-Aligned Deformation Multi-View Stereo with Depth Restoration and Occlusion Constraint](https://ieeexplore.ieee.org/document/11016951) <span class="research-tags"><span class="research-tag">Segmentation</span><span class="research-tag">Depth Estimation</span></span> \\
IEEE Transactions on Circuits and Systems for Video Technology | 2025 \\
**Yuan Z.**., Yang, Z., Cai, Y., Wu, K., Liu, M., Zhang, D., Jiang H, Li Z., Wang, Z.

[[Paper]](https://ieeexplore.ieee.org/document/11016951)

SED-MVS introduces segmentation-driven and edge-aligned deformation for robust multi-view stereo with depth restoration.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2025</div><img src='images/DVP-MVS.png' alt="DVP-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DVP-MVS: Synergize Depth-Edge and Visibility Prior for Multi-View Stereo](https://ojs.aaai.org/index.php/AAAI/article/view/33056) <span class="research-tags"><span class="research-tag">Visibility Prior</span><span class="research-tag">3D Vision</span></span> \\
AAAI Conference on Artificial Intelligence | 2025 \\
**Yuan Z.**., Luo, J., Shen, F., Li, Z., Liu, C., Mao, T., Wang, Z.

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33056) [[Code]](https://github.com/ZhenlongYuan/DVP-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2025</div><img src='images/MSP-MVS2.png' alt="MSP-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MSP-MVS: Multi-granularity segmentation prior guided multi-view stereo](https://ojs.aaai.org/index.php/AAAI/article/view/33057) <span class="research-tags"><span class="research-tag">Segmentation Prior</span><span class="research-tag">Multi-View</span></span> \\
AAAI Conference on Artificial Intelligence | 2025 \\
**Yuan Z.**, Liu, C., Shen, F., Li, Z., Luo, J., Mao, T., Wang, Z.

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33057) [[Code]](https://github.com/ZhenlongYuan/MSP-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2024</div><img src='images/SD-MVS.png' alt="SD-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SD-MVS: Segmentation-driven deformation multi-view stereo with spherical refinement and em optimization](https://ojs.aaai.org/index.php/AAAI/article/view/28512) <span class="research-tags"><span class="research-tag">Spherical Refinement</span><span class="research-tag">EM Optimization</span></span> \\
AAAI Conference on Artificial Intelligence | 2024 \\
**Yuan Z.**, Cao, J., Li, Z., Jiang, H., Wang, Z.

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/28512) [[Code]](https://github.com/ZhenlongYuan/SD-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">PR 2024</div><img src='images/TSAR-MVS.png' alt="TSAR-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TSAR-MVS: Textureless-aware segmentation and correlative refinement guided multi-view stereo](https://www.sciencedirect.com/science/article/pii/S0031320324003169) <span class="research-tags"><span class="research-tag">Textureless</span><span class="research-tag">Pattern Recognition</span></span> \\
Pattern Recognition | 2024 \\
**Yuan Z.**, Cao, J., Wang, Z., Li, Z.

[[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320324003169) [[Code]](https://github.com/ZhenlongYuan/TSAR-MVS)

</div>
</div>

</details>

<!-- ====== All Publications ====== -->
<details open>
<summary>📖 All Publications</summary>

- ``ICLR 2026`` [Video-STAR: Reinforcing Zero-shot Video Understanding with Tools.](https://arxiv.org/abs/2510.08480) **Z Yuan**, X Qu, C Qian, et al.
- ``ICLR 2026`` [AutoDrive-R2: Incentivizing Reasoning and Self-Reflection Capacity for VLA Model in Autonomous Driving.](https://arxiv.org/pdf/2509.01944) **Z Yuan**, J Tang, J Luo, et al.
- ``Preprint`` [What if Agents Could Imagine? Reinforcing Open-Vocabulary HOI Comprehension through Generation.]() **Z Yuan**, X Qu, J Tang, et al.
- ``Preprint`` [From Scale to Speed: Adaptive Test-Time Scaling for Image Editing.]() X Qu, **Z Yuan**, et al.
- ``Preprint`` [Recovering Degradations with Generative Model: A Consistency-aware Distillation Network for Infrared and Visible Image Fusion.]() H Yu, **Z Yuan**, Y Bai, et al.
- ``Preprint`` [Pure Vision Language Action (VLA) Models: A Comprehensive Survey.](https://arxiv.org/pdf/2509.19012) D Zhang, J Sun, C Hu, X Wu, **Z Yuan**, et al.
- ``Preprint`` [AT-Drive: Exploiting Adversarial Transfer for End-to-end Autonomous Driving.]() D Zhang, **Z Yuan**, K Huang, et al.
- ``Preprint`` [ADDI: A Simplified E2E Autonomous Driving Model with Distinct Experts and Implicit Interactions.]() D Zhang, **Z Yuan**, Chen Y., et al.
- ``IEEE JBHI 2025`` [EMPOWER: Evolutionary Medical Prompt Optimization With Reinforcement Learning.](https://arxiv.org/pdf/2508.17703) Y Chen, Y He, J Yang, D Zhang, **Z Yuan**, et al.
- ``IEEE TCSVT 2025`` [DVP-MVS++: Synergize Depth-Normal-Edge and Harmonized Visibility Prior for Multi-View Stereo.](https://arxiv.org/pdf/2506.13215) **Z Yuan**, D Zhang, Z Li, et al.
- ``NeurIPS 2025`` [InstructHOI: Context-Aware Instruction for Multi-Modal Reasoning in Human-Object Interaction Detection.]() J Luo, W Ren, Q Zheng, Y Zhang, **Z Yuan**, et al.
- ``IEEE TCSVT 2025`` [Learning multi-view stereo with geometry-aware prior.](https://ieeexplore.ieee.org/abstract/document/11029471) K Chen, **Z Yuan**, H Xiao, T Mao, et al.
- ``HCII 2025`` [MR-IntelliAssist: A World Cognition Agent Enabling Adaptive Human-AI Symbiosis in Industry 4.0.](https://link.springer.com/chapter/10.1007/978-3-031-93429-2_11), C Liu, **Z Yuan**, Y Wang, Y Yin, et al.
- ``IEEE TCSVT 2025`` [SED-MVS: Segmentation-Driven and Edge-Aligned Deformation Multi-View Stereo with Depth Restoration and Occlusion Constraint.](https://arxiv.org/pdf/2503.13721), **Z Yuan**, Z Yang, Y Cai, et al.
- ``AAAI 2025`` [Dual-level precision edges guided multi-view stereo with accurate planarization.](https://ojs.aaai.org/index.php/AAAI/article/view/32208/34363), K Chen, **Z Yuan**, T Mao, et al.
- ``AAAI 2025`` [Mapexpert: Online hd map construction with simple and efficient sparse map element expert.](https://ojs.aaai.org/index.php/AAAI/article/download/33616/35771), D Zhang, D Chen, P Zhi, Y Chen, **Z Yuan**, et al.
- ``AAAI 2025`` [DVP-MVS: Synergize depth-edge and visibility prior for multi-view stereo.](https://ojs.aaai.org/index.php/AAAI/article/view/33056/35211), **Z Yuan**, J Luo, F Shen, et al.
- ``AAAI 2025`` [MSP-MVS: Multi-granularity segmentation prior guided multi-view stereo.](https://ojs.aaai.org/index.php/AAAI/article/download/33057/35212), **Z Yuan**, C Liu, F Shen, et al.
- ``IEEE TCSVT 2025`` [Light4gs: Lightweight compact 4d gaussian splatting generation via context model.](https://arxiv.org/pdf/2503.13948?), M Liu, Q Yang, H Huang, W Huang, **Z Yuan**, et al.
- ``Preprint`` [Adaptive label correction for robust medical image segmentation with noisy labels.](https://arxiv.org/pdf/2503.12218), C Qian, K Han, J Ding, L Liu, C Lyu, **Z Yuan**, et al.
- ``Preprint`` [Dyncim: Dynamic curriculum for imbalanced multimodal learning.](https://arxiv.org/pdf/2503.06456), C Qian, K Han, J Wang, **Z Yuan**, et al.
- ``PR 2025`` [Nerf-based polarimetric multi-view stereo.](https://www.sciencedirect.com/science/article/pii/S0031320324007878), J Cao, **Z Yuan**, T Mao, et al.
- ``PR 2024`` [Tsar-mvs: Textureless-aware segmentation and correlative refinement guided multi-view stereo.](https://arxiv.org/pdf/2308.09990), **Z Yuan**, J Cao, Z Wang, et al.
- ``AAAI 2024`` [Sd-mvs: Segmentation-driven deformation multi-view stereo with spherical refinement and em optimization.](https://ojs.aaai.org/index.php/AAAI/article/view/28512/28998), **Z Yuan**, J Cao, Z Li, et al.

</details>

</div>
