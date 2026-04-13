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
</style>

<div id="pub-section">

<!-- ====== Technical Report ====== -->
<details open>
<summary>📄 Technical Report <span class="badge-count">1</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-preprint">Tech Report 2026</div><img src='images/longcat-next.png' alt="LongCat-Next" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LongCat-Next: Lexicalizing Modalities as Discrete Tokens](https://arxiv.org/abs/2603.27538) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#f3e5f5; color:#7b1fa2; border-radius:15px; font-size:12px;">Native Multimodal</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#fff3e0; color:#e65100; border-radius:15px; font-size:12px;">Any-to-Any Generation</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">Foundation Model</span> \\
Meituan LongCat Team

[**<strong>[Paper]</strong>**](https://arxiv.org/abs/2603.27538) [**<strong>[Code]</strong>**](https://github.com/meituan-longcat/LongCat-Next)

LongCat-Next is a native multimodal model (A3B) that unifies text, vision, and audio under a single autoregressive objective via discrete tokenization, achieving strong performance across multimodal benchmarks.

</div>
</div>

</details>

<!-- ====== Vision-Language Models & VLA ====== -->
<details open>
<summary>🤖 Vision-Language Models & VLA <span class="badge-count">4</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-preprint">Preprint</div><img src='images/ImagineAgent.png' alt="What if Agents" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[What if Agents Could Imagine? Reinforcing Open-Vocabulary HOI Comprehension through Generation](https://arxiv.org/abs/0000.00000) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">Vision-Language</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#f3e5f5; color:#7b1fa6; border-radius:15px; font-size:12px;">Open-Vocabulary HOI</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#fff3e0; color:#e65100; border-radius:15px; font-size:12px;">Agentic Generation</span> \\
**Yuan Z.**, Qu X., Tang J., Chen R., Sun L., Chen R., Yu H., Qian C., Chu X., Li S., Zhou Y.

[**<strong>[Paper]</strong>**](https://arxiv.org/abs/0000.00000)

What if Agents Could Imagine? reinforces open-vocabulary Human-Object Interaction comprehension through generative modeling.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">ICLR 2026</div><img src='images/VideoSTAR.png' alt="Video-STAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video-STAR: Reinforcing Zero-shot Video Understanding with Tools](https://arxiv.org/abs/2510.08480) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">Tool-Using Agent</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#f3e5f5; color:#7b1fa6; border-radius:15px; font-size:12px;">Multi-turn RL</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#fff3e0; color:#e65100; border-radius:15px; font-size:12px;">Zero-shot Video</span> \\
**Yuan Z.**, Qu X., Qian, C., Chen, R., Tang, J., Sun L., Chu X., Zhang D., Wang Y., Cai Y., Li S.

[**<strong>[Paper]</strong>**](https://arxiv.org/abs/2510.08480) [**<strong>[Code]</strong>**](https://github.com/AMAP-ML/Video-STAR)

Video-STAR proposes a novel framework that reinforces zero-shot video understanding through tool-use agents with multi-turn reasoning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">ICLR 2026</div><img src='images/AutoDrive-R2.png' alt="AutoDrive-R²" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoDrive-R²: Incentivizing Reasoning and Self-Reflection Capacity for VLA Model in Autonomous Driving](https://arxiv.org/abs/2509.01944v1) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">Multimodal Reasoning</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#fff3e0; color:#e65100; border-radius:15px; font-size:12px;">Autonomous Driving</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#f3e5f5; color:#7b1fa6; border-radius:15px; font-size:12px;">Vision-Language-Action</span> \\
**Featured by** [AutoDrive Heart (自动驾驶之心)](https://mp.weixin.qq.com/s/7y0-CMAkls16iumNK3mlXg) \\
**Yuan Z.**, Tang, J., Luo, J., Chen, R., Qian, C., Sun, L., Cai Y., Zhang D., Li, S.

[**<strong>[Paper]</strong>**](https://arxiv.org/abs/2509.01944v1) [**<strong>[Code]</strong>**](https://github.com/AMAP-ML/AutoDrive-R2)

AutoDrive-R² introduces a reasoning and self-reflection framework for Vision-Language-Action models in autonomous driving scenarios.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-preprint">Preprint</div><img src='images/Reasoning-VLA.png' alt="Reasoning-VLA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning-VLA: A Fast and General Vision-Language-Action Reasoning Model for Autonomous Driving](https://arxiv.org/abs/2511.19912) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#fff3e0; color:#e65100; border-radius:15px; font-size:12px;">Autonomous Driving</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">Fast VLA</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#f3e5f5; color:#7b1fa6; border-radius:15px; font-size:12px;">Real-time Inference</span> \\
Zhang D.\*, **Yuan Z.\***, Chen Z., Liao C., Chen Y., Shen F., Zhou Q., Chua T.

[**<strong>[Paper]</strong>**](https://arxiv.org/abs/2511.19912)

Reasoning-VLA presents a fast and general VLA reasoning model optimized for real-time autonomous driving applications.

</div>
</div>

</details>

<!-- ====== Generative Foundation Model ====== -->
<details open>
<summary>🎨 Generative Foundation Model <span class="badge-count">2</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">CVPR 2026</div><img src='images/Q1.png' alt="ADE-CoT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ADE-CoT: Adaptive Diffusion Elicits Chain-of-Thought in Image Editing](https://openreview.net/forum?id=id747ZRjaL) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#fce4ec; color:#880e4f; border-radius:15px; font-size:12px;">Diffusion Model</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e0f7fa; color:#00838f; border-radius:15px; font-size:12px;">Chain-of-Thought</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f5e9; color:#2e7d32; border-radius:15px; font-size:12px;">Image Editing</span> \\
Qu X.\*, **Yuan Z.\***, Tang J., Chen R., Tang D., Yu M., Sun L., Bai Y., Chu X., Gou G., Xiong G., Cai Y.

[**<strong>[Paper]</strong>**](https://openreview.net/forum?id=id747ZRjaL)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-preprint">Preprint</div><img src='images/Degradation.png' alt="Recovering Degradations" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Recovering Degradations with Generative Model: A Consistency-aware Distillation Network for Infrared and Visible Image Fusion <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f5e9; color:#2e7d32; border-radius:15px; font-size:12px;">Generation Model</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">Image Fusion</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#fff3e0; color:#e65100; border-radius:15px; font-size:12px;">Infrared-Visible</span> \\
Yu H.\*, **Yuan Z.\***, Bai Y., Li J., Liu J., Li S., Sun L., Chu X.

</div>
</div>

</details>

<!-- ====== 3D Vision ====== -->
<details open>
<summary>📐 3D Vision <span class="badge-count">6</span></summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">TCSVT 2025</div><img src='images/DVP-MVS++.png' alt="DVP-MVS++" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DVP-MVS++: Synergize Depth-Normal-Edge and Harmonized Visibility Prior for Multi-View Stereo](https://arxiv.org/abs/2506.13215) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f5e9; color:#2e7d32; border-radius:15px; font-size:12px;">Multi-View Stereo</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">3D Reconstruction</span> \\
**Yuan Z.**, Zhang, D., Li, Z., Qian, C., Chen, J., Chen, Y., Chen K., Mao T., Li Z., Jiang H., Wang, Z.

[**<strong>[Paper]</strong>**](https://arxiv.org/abs/2506.13215)

DVP-MVS++ advances multi-view stereo through synergistic depth-normal-edge and visibility prior modeling.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">TCSVT 2025</div><img src='images/SED-MVS.png' alt="SED-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SED-MVS: Segmentation-Driven and Edge-Aligned Deformation Multi-View Stereo with Depth Restoration and Occlusion Constraint](https://ieeexplore.ieee.org/document/11016951) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f5e9; color:#2e7d32; border-radius:15px; font-size:12px;">Segmentation-Driven</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">Depth Estimation</span> \\
**Yuan Z.**, Yang, Z., Cai, Y., Wu, K., Liu, M., Zhang, D., Jiang H, Li Z., Wang, Z.

[**<strong>[Paper]</strong>**](https://ieeexplore.ieee.org/document/11016951)

SED-MVS introduces segmentation-driven and edge-aligned deformation for robust multi-view stereo with depth restoration.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2025</div><img src='images/DVP-MVS.png' alt="DVP-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DVP-MVS: Synergize Depth-Edge and Visibility Prior for Multi-View Stereo](https://ojs.aaai.org/index.php/AAAI/article/view/33056) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f5e9; color:#2e7d32; border-radius:15px; font-size:12px;">Visibility Prior</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">3D Vision</span> \\
**Yuan Z.**, Luo, J., Shen, F., Li, Z., Liu, C., Mao, T., Wang, Z.

[**<strong>[Paper]</strong>**](https://ojs.aaai.org/index.php/AAAI/article/view/33056) [**<strong>[Code]</strong>**](https://github.com/ZhenlongYuan/DVP-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2025</div><img src='images/MSP-MVS2.png' alt="MSP-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MSP-MVS: Multi-granularity segmentation prior guided multi-view stereo](https://ojs.aaai.org/index.php/AAAI/article/view/33057) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f5e9; color:#2e7d32; border-radius:15px; font-size:12px;">Segmentation Prior</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">Multi-View</span> \\
**Yuan Z.**, Liu, C., Shen, F., Li, Z., Luo, J., Mao, T., Wang, Z.

[**<strong>[Paper]</strong>**](https://ojs.aaai.org/index.php/AAAI/article/view/33057) [**<strong>[Code]</strong>**](https://github.com/ZhenlongYuan/MSP-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-conference">AAAI 2024</div><img src='images/SD-MVS.png' alt="SD-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SD-MVS: Segmentation-driven deformation multi-view stereo with spherical refinement and em optimization](https://ojs.aaai.org/index.php/AAAI/article/view/28512) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f5e9; color:#2e7d32; border-radius:15px; font-size:12px;">Spherical Refinement</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">EM Optimization</span> \\
**Yuan Z.**, Cao, J., Li, Z., Jiang, H., Wang, Z.

[**<strong>[Paper]</strong>**](https://ojs.aaai.org/index.php/AAAI/article/view/28512) [**<strong>[Code]</strong>**](https://github.com/ZhenlongYuan/SD-MVS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge-journal">PR 2024</div><img src='images/TSAR-MVS.png' alt="TSAR-MVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TSAR-MVS: Textureless-Aware Segmentation and Correlative Refinement Guided Multi-View Stereo](https://www.sciencedirect.com/science/article/pii/S0031320324003169) <br>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f5e9; color:#2e7d32; border-radius:15px; font-size:12px;">Textureless-Aware</span>
<span style="display:inline-block; padding:2px 10px; margin:2px 4px 2px 0; background-color:#e8f4f8; color:#0077b6; border-radius:15px; font-size:12px;">3D Vision</span> \\
**Yuan Z.**, Cao, J., Wang, Z., Li, Z.

[**<strong>[Paper]</strong>**](https://www.sciencedirect.com/science/article/pii/S0031320324003169) [**<strong>[Code]</strong>**](https://github.com/ZhenlongYuan/TSAR-MVS)

</div>
</div>

</details>

</div>
