# Awesome Spatial VLMs with stars

<div align="center">
  <h1> Awesome Spatial VLMs </h1>
  <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome Badge" style="vertical-align: middle;"> </a> <a href="https://github.com/DishengLL/Awesome-Spatial-VLMs/commits/main/"> <img src="https://img.shields.io/github/last-commit/DishengLL/Awesome-Spatial-VLMs" alt="GitHub Last Commit" style="vertical-align: middle;"></a>
</div>

<!-- <h1 align="center" style="font-size: 1.7rem">
  🚀 Awesome Spatial VLMs
  <a href="https://github.com/sindresorhus/awesome">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome Badge" style="vertical-align: middle;">
  </a>
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/commits/main/">
    <img src="https://img.shields.io/github/last-commit/vulab-AI/Awesome-Spatial-VLMs" alt="GitHub Last Commit" style="vertical-align: middle;">
  </a>
</h1> -->

<!-- 
  <p align="center">
    <a href="https://scholar.google.com/citations?user=xlIBwREAAAAJ&hl=en">Disheng Liu</a>,
    <a href="https://jiagengliu02.github.io/">Tuo Liang</a>,
    <a href="https://scholar.google.com/citations?user=oV8sqb0AAAAJ&hl=zh-CN">Zhe Hu</a>,
    <a href="https://scholar.google.com/citations?user=7CLFLX0AAAAJ&hl=en">Jierui Peng</a>,
    <a href="https://yiren-lu.com/">Yiren Lu</a>,
    <a href="https://sites.google.com/view/homepage-of-yi-xu">Yi Xu</a>,
    <a href="https://www1.ece.neu.edu/~yunfu/">Yun Fu</a>,
    <a href="https://yin-yu.github.io/">Yu Yin</a>
  </p> -->

> A curated hub for Spatial Intelligence in Vision-Language Models.\
> Actively maintained—watch for updates, benchmark your VLM with our evaluation code, and consider starring 🌟 and sharing if helpful.

This repository is the official, community-maintained resource for our survey paper:  **Spatial Intelligence in Vision-Language Models: A Comprehensive Survey**.\
We host an official website for streamlined navigation and well-organized resources: 👉 [Website 🔗](https://dishengll.github.io/Awesome-Spatial-VLMs/)

<p align="center">
  <a href="./website.png">
    <img src="./website.png" alt="Cover Image" width="88%">
  </a>
</p>

<p align="center">
<a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.176231405.57942913/v2">
  <img src="https://img.shields.io/badge/TechRxiv-Preprint-00629B?style=flat&logo=ieee&logoColor=white" alt="TechRxiv"></a>&nbsp;
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/Spatial_VLM_survey.pdf"><img src="https://img.shields.io/badge/Paper-PDF-0066CC?style=flat&logo=adobeacrobatreader&logoColor=white" alt="Paper PDF"></a>&nbsp;
  <a href="https://huggingface.co/datasets/LLDDSS/Awesome_Spatial_VQA_Benchmarks"><img src="https://img.shields.io/badge/Evaluated-Dataset-yellow?style=flat&logo=huggingface&logoColor=yellow" alt="Evaluated Data"></a>&nbsp;
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/evaluation/README.md"><img src="https://img.shields.io/badge/Evaluation-Code-black?style=flat&logo=github&logoColor=black" alt="Evaluation Code"></a>
  <br/>
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/data_benchmark/Dataset_SVQA.md"><img src="https://img.shields.io/badge/Training-24%20datasets-teal?style=flat"alt="Training - 24 datasets"></a>&nbsp;
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/data_benchmark/Benchmark_SVQA.md"><img src="https://img.shields.io/badge/Evaluation-54%20benchmarks-orange?style=flat" alt="Evaluation - 54 benchmarks"></a>&nbsp;
</p>

🤝 This repository will be continuously updated, and we warmly invite contributions. **If you have a paper, dataset, or model to add, please submit a pull request or open an issue for discussion.**

## Table of Contents

* [Table of Contents](#table-of-contents)
* [Overview](#overview)
* [🚀 Awesome Papers](#-awesome-papers)
  * [Training-Free Prompting](#training-free-prompting)
  * [Model-Centric Enhancements](#model-centric-enhancements)
  * [Explicit 2D Information Injection](#explicit-2d-information-injection)
  * [3D Information Enhancement](#3d-information-enhancement)
  * [Data-Centric Spatial Enhancement](#data-centric-spatial-enhancement)
* [📚 Datasets and Benchmarks](#-datasets-and-benchmarks)
  * [Spatially-Oriented Training Corpora](#spatially-oriented-training-corpora)
  * [Evaluation Benchmarks](#evaluation-benchmarks)
* [🏆 Spatial VLM Leaderboard & Evaluation Toolkit](#-spatial-vlm-leaderboard--evaluation-toolkit)
  * [🏅 Main Leaderboard](#-main-leaderboard)
  * [🧑‍🔬 How to Evaluate Your Model](#-how-to-evaluate-your-model)
* [Citation](#citation)

## Overview

This repository uses the framework from our survey paper to systematically organize the field of Spatial Intelligence in VLMs.

* **The “What”: A Cognitive Hierarchy** 🧩\
  We define spatial intelligence as a 3-level hierarchy, and group tasks, datasets, and benchmarks by required capability:\
  **L1** *Perception* of intrinsic 3D attributes (e.g., size, orientation) → **L2** relational *Understanding* → **L3** *Extrapolation* (e.g., hidden-state inference, future prediction).
* **The “How”: A Taxonomy of Methods** 🚀\
  Methods are organized into five families, giving you a clear map of the current landscape. See details in [🚀 Awesome Papers](#-awesome-papers).
* **Where We Are: Evaluation Results and Toolkit** 🏆\
  See how current models perform!
  * **Standardized Leaderboard:** We report results for **37+ VLMs** across all L1/L2/L3 tasks.
  * **Open Evaluation Toolkit:** Reproduce our protocols and **evaluate your own models** under the same settings.

<div align='center'><img src="./samples/outline.jpg"  alt="Overview Diagram" width="95%"/></div>

  <!-- - **L1: Spatial Perception:** Recognizing individual objects and their intrinsic 3D attributes (e.g., size, orientation, 3D segmentation).
  - **L2: Spatial Understanding:** Reasoning about the extrinsic, relational properties among multiple objects (e.g., "the dog to the left of the cat").
  - **L3: Spatial Extrapolation:** Inferring hidden states, predicting future configurations, or reasoning from a situated perspective (e.g., mental rotation, pathfinding). -->

## 🚀 Awesome Papers

### Training-Free Prompting

<a id="textual-prompting-methods"></a>

<details>
  <summary><b>Textual Prompting Methods</b></summary>

* \[CoRR2025] SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2502.13143) [\[code\]](https://github.com/qizekun/SoFar) ⭐ 247 | 🐛 12 | 🌐 Python | 📅 2025-06-30;

* \[CVPR2024] Compositional Chain-of-Thought Prompting for Large Multimodal Models (*University of California, Berkeley*) [\[paper\]](https://arxiv.org/pdf/2311.17076) [\[code\]](https://github.com/chancharikmitra/CCoT) ⭐ 142 | 🐛 0 | 🌐 Python | 📅 2024-06-20;

* \[EMNLP2024] Reasoning Paths with Reference Objects Elicit Quantitative Spatial Reasoning in Large Vision-Language Models (*University of Toronto*) [\[paper\]](https://arxiv.org/abs/2409.09788) [\[code\]](https://github.com/andrewliao11/Q-Spatial-Bench-code) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-10-30;

* \[NeurIPS2024] SpatialPIN: Enhancing Spatial Reasoning Capabilities of Vision-Language Models through Prompting and Interacting 3D Priors (*University of Oxford*) [\[paper\]](https://arxiv.org/pdf/2403.13438) [\[code\]](https://github.com/dannymcy/zeroshot_task_hallucination_code) ⭐ 11 | 🐛 1 | 📅 2025-01-05;

* \[CoRR2023] Enhancing the Spatial Awareness Capability of Multi-Modal Large Language Model (*Peking University*) [\[paper\]](https://arxiv.org/pdf/2310.20357);

</details>

<a id="visual-prompting-methods"></a>

<details>
  <summary><b>Visual Prompting Methods</b></summary>

* \[arXiv2023] Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V (*Microsoft Research, Redmond*) [\[paper\]](https://arxiv.org/pdf/2310.11441) [\[code\]](https://github.com/microsoft/SoM) ⭐ 1,551 | 🐛 22 | 🌐 Python | 📅 2024-08-19;

* \[NeurIPS2023] Fine-Grained Visual Prompting (*Nanjing University of Science and Technology*) [\[paper\]](https://arxiv.org/pdf/2306.04356) [\[code\]](https://github.com/ylingfeng/FGVP) ⭐ 57 | 🐛 1 | 🌐 Python | 📅 2024-02-01;

* \[arXiv2024] I Know About “Up”! Enhancing Spatial Reasoning in Visual Language Models Through 3D Reconstruction (*Guangdong Polytechnic Normal University*) [\[paper\]](https://arxiv.org/pdf/2407.14133);

  <!-- New paper, excluded in survey -->

* \[arXiv2026] Think3D: Thinking with Space for Spatial Reasoning (*Dalian University of Technology*) [\[paper\]](https://arxiv.org/pdf/2601.13029) [\[code\]](https://github.com/zhangzaibin/spagent) ⭐ 214 | 🐛 49 | 🌐 Python | 📅 2026-08-09 [\[checkpoint\]](https://huggingface.co/jialianjie/SPAgent-4B);
* \[NeurIPS2025] Mindjourney: Test-time scaling with world models for spatial reasoning (*UMass Amherst*) [\[paper\]](https://arxiv.org/pdf/2507.12508) [\[code\]](https://github.com/UMass-Embodied-AGI/MindJourney) ⭐ 151 | 🐛 2 | 🌐 Python | 📅 2025-11-04;
* \[NeurIPS2025] See\&Trek: Training-Free Spatial Prompting for Multimodal Large Language Model (*HKUST(GZ)*) [\[paper\]](https://arxiv.org/pdf/2509.16087) [\[code\]](https://github.com/Hoantrbl/SeeTrek?tab=readme-ov-file) ⭐ 118 | 🐛 1 | 🌐 Python | 📅 2025-12-22;
* \[arXiv2025] Abstract 3D Perception for Spatial Intelligence in Vision-Language Models (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2511.10946)
* \[CVPR2025] Coarse Correspondences Boost Spatial-Temporal Reasoning in Multimodal Language Model (*University of Washington*) [\[paper\]](https://arxiv.org/pdf/2408.00754);
* \[Neurocomputing2025] 3DAxisPrompt: Promoting the 3d grounding and reasoning in gpt-4o (*Shanghai AI Lab*) [\[paper\]](https://arxiv.org/pdf/2503.13185);

</details>

<a id="hybrid-prompting"></a>

<details>
  <summary><b>Hybrid Prompting</b></summary>
  - [arXiv2024] Image-of-Thought Prompting for Visual Reasoning Refinement in Multimodal Large Language Models (_Westlake University_) [[paper]](https://arxiv.org/pdf/2405.13872);

* \[NeurIPS2024] Visual SKETCHPAD: Sketching as a visual chain of thought for multimodal language models (*University of Washington*) [\[paper\]](https://arxiv.org/pdf/2406.09403) [\[code\]](https://github.com/Yushi-Hu/VisualSketchpad) ⭐ 288 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2025-08-05;
* \[CVPR2025] SeeGround: See and Ground for Zero-Shot Open-Vocabulary 3D Visual Grounding (*HKUST(GZ)*) [\[paper\]](https://arxiv.org/pdf/2412.04383) [\[code\]](https://github.com/iris0329/SeeGround) ⭐ 223 | 🐛 1 | 🌐 Python | 📅 2025-04-21;
* \[arXiv2026] CoV: Chain-of-View Prompting for Spatial Reasoning (*Zhejiang University*) [\[paper\]](https://arxiv.org/pdf/2601.05172) [\[code\]](https://github.com/ziplab/CoV?tab=readme-ov-file) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2026-04-07;
* \[COLING2025] Scaffolding coordinates to promote vision-language coordination in large multi-modal models (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2402.12058) [\[code\]](https://github.com/THUNLP-MT/Scaffold) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2024-12-16;
* \[NeurIPS2024] Mind's Eye of LLMs: Visualization-of-Thought Elicits Spatial Reasoning in Large Language Models (*Microsoft Research*) [\[paper\]](https://phttps://arxiv.org/pdf/2405.13872roceedings.neurips.cc/paper_files/paper/2024/file/a45296e83b19f656392e0130d9e53cb1-Paper-Conference.pdf) [\[code\]](https://github.com/microsoft/visualization-of-thought/) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2024-10-23;
* \[arXiv2025] SpatialPrompting: Keyframe-driven Zero-Shot Spatial Reasoning with Off-the-Shelf Multimodal Large Language Models (*Toyota Central R\&D Labs*) [\[paper\]](https://arxiv.org/pdf/2505.04911v1);

</details>

***

### Model-Centric Enhancements

<a id="advanced-training-strategies"></a>

<details>
  <summary><b>Advanced Training Strategies</b></summary>

* \[arXiv2023] What Makes for Good Visual Tokenizers for Large Language Models (*National University of Singapore 2ARC Lab*) [\[paper\]](https://arxiv.org/pdf/2305.12223) [\[code\]](https://github.com/TencentARC/GVT) ⭐ 59 | 🐛 5 | 🌐 Python | 📅 2023-06-27 [\[checkpoint\]](https://github.com/TencentARC/GVT/tree/master/gvt) ⭐ 59 | 🐛 5 | 🌐 Python | 📅 2023-06-27;

* \[arXiv2025] SpatialCoT: Advancing Spatial Reasoning through Coordinate Alignment and Chain-of-Thought for Embodied Task Planning (*Huawei Noah's Ark Lab*) [\[paper\]](https://arxiv.org/pdf/2501.10074);

  <!-- New paper, excluded in survey -->

* \[arXiv2025] Enhancing Spatial Reasoning through Visual and Textual Thinking (*Zhejiang University*) [\[paper\]](https://arxiv.org/pdf/2507.20529);

  <!-- New paper, excluded in survey -->

* \[arXiv2025] MetaSpatial: Reinforcing 3D Spatial Reasoning in VLMs for the Metaverse (*Northwestern University*) [\[paper\]](https://arxiv.org/pdf/2503.18470) [\[code\]](https://github.com/PzySeere/MetaSpatial) ⭐ 321 | 🐛 1 | 🌐 Python | 📅 2025-05-05;

* \[arXiv2025] SpaceR: Reinforcing MLLMs in Video Spatial Reasoning (*Peking University*) [\[paper\]](https://arxiv.org/pdf/2504.01805v2) [\[code\]](https://github.com/OuyangKun10/SpaceR?tab=readme-ov-file) ⭐ 111 | 🐛 8 | 🌐 Python | 📅 2025-07-09 [\[checkpoint\]](https://huggingface.co/RUBBISHLIKE/SpaceR);

* \[arXiv2025] SpatialLadder: Progressive Training for Spatial Reasoning in Vision-Language Models (*Zhejiang University*) [\[paper\]](https://arxiv.org/pdf/2510.08531) [\[code\]](https://github.com/zju-real/SpatialLadder) ⭐ 99 | 🐛 0 | 🌐 Python | 📅 2026-06-09 [\[checkpoint\]](https://huggingface.co/hongxingli/SpatialLadder-3B);

* \[arXiv2025] ViLaSR: Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing (*Institute of Automation, Chinese Academy of Sciences*) [\[paper\]](https://arxiv.org/abs/2506.09965) [\[code\]](https://github.com/AntResearchNLP/ViLaSR) ⭐ 98 | 🐛 4 | 🌐 Python | 📅 2025-07-27 [\[checkpoint\]](https://huggingface.co/inclusionAI/ViLaSR/tree/main);

* \[arXiv2025] Embodied-R: Collaborative Framework for Activating Embodied Spatial Reasoning in Foundation Models via Reinforcement Learning (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2504.12680) [\[code\]](https://github.com/EmbodiedCity/Embodied-R.code) ⭐ 95 | 🐛 0 | 🌐 Python | 📅 2026-08-07 [\[checkpoint\]](https://huggingface.co/EmbodiedCity/Embodied-R);

* \[arXiv2025] M2-Reasoning: Empowering MLLMs with Unified General and Spatial Reasoning (*Inclusion AI, Ant Group*) [\[paper\]](https://arxiv.org/pdf/2507.08306) [\[code\]](https://github.com/inclusionAI/M2-Reasoning) ⭐ 47 | 🐛 5 | 🌐 Python | 📅 2025-07-17 [\[checkpoint\]](https://huggingface.co/inclusionAI/M2-Reasoning);

* \[arXiv2025] Improved Visual-Spatial Reasoning via R1-Zero-Like Training (*Shanghai Jiao Tong University*) [\[paper\]](https://arxiv.org/pdf/2504.00883) [\[code\]](https://github.com/zhijie-group/R1-Zero-VSI) ⭐ 42 | 🐛 4 | 📅 2025-06-09

* \[arXiv2025] SpaceTools: Tool-Augmented Spatial Reasoning via Double Interactive RL (*Umich*) [\[paper\]](https://arxiv.org/pdf/2512.04069)

* \[arXiv2025] SVQA-R1: Reinforcing Spatial Reasoning in MLLMs via View-Consistent Reward Optimization (*Stony Brook University*) [\[paper\]](https://arxiv.org/pdf/2506.01371);

  <!-- New paper, excluded in survey -->

* \[arXiv2025] SpatialThinker: Reinforcing 3D Reasoning in Multimodal LLMs via Spatial Rewards (*University of Oxford*) [\[paper\]](https://arxiv.org/pdf/2511.07403) [\[code\]](https://github.com/hunarbatra/SpatialThinker) ⭐ 42 | 🐛 2 | 🌐 Python | 📅 2026-01-28 [\[checkpoint\]](https://huggingface.co/collections/OX-PIXL/spatialthinker);
  <!-- ![RL-based](https://img.shields.io/badge/RL--based-blue?) -->

  <!-- New paper, excluded in survey -->

* \[arXiv2025] Think with 3D: Geometric Imagination Grounded Spatial Reasoning from Limited Views (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2510.18632) [\[code\]](https://github.com/zhangquanchen/3DThinker) ⭐ 245 | 🐛 0 | 🌐 Python | 📅 2026-05-07
  <!-- ![RL-based](https://img.shields.io/badge/RL--based-blue?) -->

  <!-- New paper, excluded in survey -->

* \[arXiv2025] SpaceMind: Camera-Guided Modality Fusion for Spatial Reasoning in Vision-Language Models (*Huawei*) [\[paper\]](https://arxiv.org/pdf/2511.23075)

  <!-- New paper, excluded in survey -->

* \[arXiv2025] DepthLM: Metric Depth From Vision Language Models (*Meta*) [\[paper\]](https://arxiv.org/pdf/2509.25413#page=4.00) [\[code\]](https://github.com/facebookresearch/DepthLM_Official) ⭐ 368 | 🐛 1 | 🌐 Python | 📅 2026-06-01 [\[checkpoint\]](https://huggingface.co/facebook/DepthLM)

* \[ICLR2025] Ross: Reconstructive Visual Instruction Tuning (*Institute of Automation, Chinese Academy of Sciences*) [\[paper\]](https://arxiv.org/pdf/2410.09575) [\[code\]](https://github.com/haochen-wang409/ross) ⭐ 135 | 🐛 3 | 🌐 Python | 📅 2025-04-09 [\[checkpoint\]](https://huggingface.co/HaochenWang/ross-qwen2-7b);

* \[ICML2025] Imagine while Reasoning in Space: Multimodal Visualization-of-Thought (*Microsoft Research*) [\[paper\]](https://arxiv.org/pdf/2501.07542) [\[code\]](https://github.com/chengzu-li/MVoT) ⭐ 78 | 🐛 1 | 🌐 Python | 📅 2025-04-12;

* \[ICLR2025] Locality Alignment Improves Vision-Language Models (*Stanford University*) [\[paper\]](https://arxiv.org/pdf/2410.11087) [\[code\]](https://github.com/iancovert/locality-alignment/?tab=readme-ov-file) ⭐ 55 | 🐛 3 | 🌐 Python | 📅 2025-01-17;

* \[CVPR2025] Perception Tokens Enhance Visual Reasoning in Multimodal Language Models (*University of Washington*) [\[paper\]](https://arxiv.org/pdf/2412.03548v1) [\[code\]](https://github.com/mahtabbigverdi/Aurora-perception) ⭐ 50 | 🐛 9 | 🌐 Python | 📅 2026-02-18 [\[checkpoint\]](https://drive.google.com/file/d/1r7WYQWYA6VDpzfxPIHP1zEUgBYQmwNIj/view);

* \[NeurIPS2025] SpatialReasoner: Towards Explicit and Generalizable 3D Spatial Reasoning, (*Johns Hopkins University*) [\[paper\]](https://arxiv.org/pdf/2504.20024) [\[code\]](https://github.com/johnson111788/SpatialReasoner) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2026-04-05 [\[checkpoint\]](https://huggingface.co/collections/ccvl/spatialreasoner-68114caec81774edbf1781d3);

* \[ICLR2025] Language-Image Models with 3D Understanding (Cube-LLM) (*UT Austin*) [\[paper\]](https://arxiv.org/pdf/2405.03685);

* \[NeurIPS2025] Fine-Grained Preference Optimization Improves Spatial Reasoning in VLMs (*UIUC*) [\[paper\]](https://arxiv.org/pdf/2506.21656);

  <!-- New paper, excluded in survey -->

* \[AAAI2026] SIFThinker: Spatially-Aware Image Focus for Visual Reasoning (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2508.06259) [\[code\]](https://github.com/zhangquanchen/SIFThinker?tab=readme-ov-file) ⭐ 23 | 🐛 0 | 📅 2025-12-02;
  <!-- ![RL-based](https://img.shields.io/badge/RL--based-blue?) -->
  </details>

<a id="architectural-enhancements"></a>

<details>
  <summary><b>Architectural Enhancements</b></summary>

* \[NeurIPS2024] Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLM (*New York University*) [\[paper\]](https://arxiv.org/pdf/2406.16860) [\[code\]](https://github.com/cambrian-mllm/cambrian) ⭐ 2,014 | 🐛 48 | 🌐 Python | 📅 2025-11-07 [\[checkpoint\]](https://huggingface.co/collections/nyu-visionx/cambrian-1-models-666fa7116d5420e514b0f23c);

* \[CVPR2024] Honeybee: Locality Enhanced Projector for Multimodal LLM (*Kakao Brain*) [\[paper\]](https://arxiv.org/pdf/2312.06742) [\[code\]](https://github.com/khanrc/honeybee) ⭐ 470 | 🐛 1 | 🌐 Python | 📅 2024-05-10 [\[checkpoint\]](https://github.com/khanrc/honeybee) ⭐ 470 | 🐛 1 | 🌐 Python | 📅 2024-05-10;

* \[ECCV2024] Contrastive Region Guidance: Improving Grounding in Vision-Language Models without Training (*UNC*) [\[paper\]](https://arxiv.org/pdf/2403.02325) [\[code\]](https://github.com/meetdavidwan/crg) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2024-03-04 [\[checkpoint\]](https://github.com/meetdavidwan/crg) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2024-03-04;

* \[EMNLP2024] To Preserve or To Compress: An In-Depth Study of Connector Selection in Multimodal Large Language Models (*Digital Twin Institute, Eastern Institute of Technology, China*) [\[paper\]](https://arxiv.org/pdf/2410.06765v1) [\[code\]](https://github.com/EIT-NLP/Connector-Selection-for-MLLM) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2024-12-13;

  <!-- New paper, excluded in survey -->

* \[arXiv2025] Cambrian-S: Towards Spatial Supersensing in Video (*New York University*) [\[paper\]](https://arxiv.org/pdf/2511.04670) [\[code\]](https://github.com/cambrian-mllm/cambrian-s) ⭐ 565 | 🐛 1 | 🌐 Python | 📅 2026-04-03 [\[checkpoint\]](https://huggingface.co/collections/nyu-visionx/cambrian-s-models);

* \[ICML2025] Why is Spatial Reasoning Hard for VLMs? An Attention Mechanism Perspective on Focus Areas (*City University of Hong Kong*) [\[paper\]](https://arxiv.org/pdf/2503.01773) [\[code\]](https://github.com/shiqichen17/AdaptVis) ⭐ 76 | 🐛 5 | 🌐 Python | 📅 2025-05-02 [\[checkpoint\]](https://github.com/shiqichen17/AdaptVis) ⭐ 76 | 🐛 5 | 🌐 Python | 📅 2025-05-02;

</details>

<a id="encoder-level-improvements"></a>

<details>
  <summary><b>Encoder-Level Improvements</b></summary>

* \[NeurIPS2024] Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLM (*New York University*) [\[paper\]](https://arxiv.org/pdf/2406.16860) [\[code\]](https://github.com/cambrian-mllm/cambrian) ⭐ 2,014 | 🐛 48 | 🌐 Python | 📅 2025-11-07 [\[checkpoint\]](https://huggingface.co/collections/nyu-visionx/cambrian-1-models-666fa7116d5420e514b0f23c);

* \[ICML2024] Prismatic VLMs: Investigating the Design Space of Visually-Conditioned Language Models (*Stanford University*) [\[paper\]](https://arxiv.org/pdf/2402.07865) [\[code\]](https://github.com/TRI-ML/prismatic-vlms?tab=readme-ov-file#pretrained-models) ⭐ 1,008 | 🐛 21 | 🌐 Python | 📅 2024-07-04 [\[checkpoint\]](https://github.com/TRI-ML/prismatic-vlms) ⭐ 1,008 | 🐛 21 | 🌐 Python | 📅 2024-07-04;

* \[arXiv2025] Introducing Visual Perception Token into Multimodal Large Language Model (*National University of Singapore*) [\[paper\]](https://arxiv.org/pdf/2502.17425) [\[code\]](https://github.com/yu-rp/VisualPerceptionToken?tab=readme-ov-file) ⭐ 136 | 🐛 13 | 🌐 Python | 📅 2025-03-22 [\[checkpoint\]](https://huggingface.co/collections/rp-yu/vpt-models-67b6afdc8679a05a2876f07a);

  <!-- New paper, excluded in survey -->

* \[ICLR2025] Eagle 2: Building Post-Training Data Strategies from Scratch for Frontier Vision-Language Models (*NVIDIA*) [\[paper\]](https://arxiv.org/pdf/2501.14818) [\[code\]](https://github.com/NVlabs/EAGLE?tab=readme-ov-file) ⭐ 3,402 | 🐛 62 | 🌐 Python | 📅 2026-06-24 [\[checkpoint\]](https://huggingface.co/nvidia/Eagle2.5-8B);

* \[arXiv2025] G2VLM: Geometry Grounded Vision Language Model with Unified 3D Reconstruction and Spatial Reasoning (*Shanghai AI Lab*) [\[paper\]](https://arxiv.org/pdf/2511.21688) [\[code\]](https://github.com/InternRobotics/G2VLM) ⭐ 349 | 🐛 11 | 🌐 Python | 📅 2026-04-18 [\[checkpoint\]](https://huggingface.co/InternRobotics/G2VLM-2B-MoT)

* \[CVPR2025] SpatialCLIP: Learning 3D-aware Image Representations from Spatially Discriminative Language (*Zhejiang University*) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_SpatialCLIP_Learning_3D-aware_Image_Representations_from_Spatially_Discriminative_Language_CVPR_2025_paper.pdf) [\[code\]](https://github.com/SpatialVision/Spatial-CLIP) ⭐ 56 | 🐛 1 | 🌐 Python | 📅 2025-12-09;

* \[CVPR2025] SpatialLLM: A Compound 3D-Informed Design towards Spatially-Intelligent Large Multimodal Models (*Johns Hopkins University*) [\[paper\]](https://arxiv.org/pdf/2505.00788) [\[code\]](https://3d-spatial-reasoning.github.io/spatial-llm/#public);

* \[CVPR2025] Argus: A Compact and Versatile Foundation Model for Vision (*University of Illinois Urbana-Champaign*) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhuang_Argus_A_Compact_and_Versatile_Foundation_Model_for_Vision_CVPR_2025_paper.pdf);

* \[IJCAI2025] Incorporating Visual Experts to Resolve the Information Loss in Multimodal Large Language Models (*Huawei*) [\[paper\]](https://arxiv.org/pdf/2401.03105);

</details>

***

### Explicit 2D Information Injection

<a id="object-region-guidance"></a>

<details>
  <summary><b>Object Region Guidance</b></summary>

* \[ECCVWorkshops2024] GPT4RoI: Instruction Tuning Large Language Model on Region-of-Interest (*The University of Hong Kong*) [\[paper\]](https://arxiv.org/pdf/2307.03601) [\[code\]](https://github.com/jshilong/GPT4RoI?tab=readme-ov-file) ⭐ 555 | 🐛 30 | 🌐 Python | 📅 2025-06-03 [\[checkpoint\]](https://huggingface.co/shilongz/GPT4RoI-7B-delta-V0);

* \[CVPR2024] VCoder: Versatile Vision Encoders for Multimodal Large Language Models (*Georgia Tech*) [\[paper\]](https://arxiv.org/pdf/2312.14233) [\[code\]](https://github.com/SHI-Labs/VCoder) ⭐ 280 | 🐛 5 | 🌐 Python | 📅 2024-04-17 [\[checkpoint\]](https://huggingface.co/models?search=vcoder);

* \[EMNLP2022] PEVL: Position-enhanced Pre-training and Prompt Tuning for Vision-language Models (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2205.11169) [\[code\]](https://github.com/thunlp/PEVL) ⭐ 49 | 🐛 7 | 🌐 Python | 📅 2022-11-10 [\[checkpoint\]](https://github.com/thunlp/PEVL) ⭐ 49 | 🐛 7 | 🌐 Python | 📅 2022-11-10;

* \[ICLR2024] CoVLM: Composing Visual Entities and Relationships in Large Language Models Via Communicative Decoding (*UMass Amherst*) [\[paper\]](https://arxiv.org/abs/2311.03354) [\[code\]](https://github.com/UMass-Embodied-AGI/CoVLM?tab=readme-ov-file) ⭐ 46 | 🐛 1 | 🌐 Python | 📅 2025-06-09 [\[checkpoint\]](https://github.com/UMass-Embodied-AGI/CoVLM?tab=readme-ov-file) ⭐ 46 | 🐛 1 | 🌐 Python | 📅 2025-06-09;

* \[CoRR2023] Position-Enhanced Visual Instruction Tuning for Multimodal Large Language Models (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2308.13437) [\[code\]](https://github.com/PVIT-official/PVIT?tab=readme-ov-file#pvit-weights) ⭐ 37 | 🐛 2 | 🌐 Python | 📅 2023-09-19 [\[checkpoint\]](https://huggingface.co/PVIT/pvit);

* \[CVPR2024] RegionGPT: Towards Region Understanding Vision Language Model (*Nvidia*) [\[paper\]](https://arxiv.org/pdf/2403.02330);

* \[CVPR2024] Learning to Localize Objects Improves Spatial Reasoning in Visual-LLMs (*Meta*) [\[paper\]](https://arxiv.org/pdf/2404.07449);

* \[arXiv2025] Lyrics: Boosting Fine-grained Language-Vision Alignment and Comprehension via Semantic-aware Visual Objects (*International Digital Economy Academy*) [\[paper\]](https://arxiv.org/pdf/2312.05278);

* \[CVPR2025] Argus: A Compact and Versatile Foundation Model for Vision (*University of Illinois Urbana-Champaign*) [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhuang_Argus_A_Compact_and_Versatile_Foundation_Model_for_Vision_CVPR_2025_paper.pdf);

</details>

<a id="explicit-spatial-relationship"></a>

<details>
  <summary><b>Explicit Spatial Relationship</b></summary>

* \[ACL2023] Incorporating Structured Representations into Pretrained Vision & Language Models Using Scene Graphs (*Tel-Aviv University*) [\[paper\]](https://arxiv.org/pdf/2305.06343) [\[code\]](https://github.com/AlonMendelson/SGVL) ⭐ 17 | 🐛 4 | 🌐 Python | 📅 2023-12-13 [\[checkpoint\]](https://drive.google.com/file/d/13jzpcLgGalO3hkiqVwziNAlCEZD90ENN/view);

* \[arXiv2025] Object-centric Binding in Contrastive Language-Image Pretraining (*Meta*) [\[paper\]](https://arxiv.org/pdf/2502.14113);

* \[arXiv2025] Seeing Beyond the Scene: Enhancing Vision-Language Models with Interactional Reasoning (*South China University of Technology*) [\[paper\]](https://arxiv.org/pdf/2505.09118);

* \[arXiv2025] LLaVA-SG: Leveraging Scene Graphs as Visual Semantic Expression in Vision-Language Models (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2408.16224);

</details>

***

### 3D Information Enhancement

<a id="explicit-3d-geometric-representations"></a>

<details>
  <summary><b>Explicit 3D Geometric Representations</b></summary>

* \[NeurIPS2023] 3D-LLM: Injecting the 3D World into Large Language Models (*UCLA*) [\[paper\]](https://arxiv.org/pdf/2307.12981) [\[code\]](https://github.com/UMass-Embodied-AGI/3D-LLM) ⭐ 1,209 | 🐛 31 | 🌐 Python | 📅 2024-06-06;

* \[NeurIPS2025] SD-VLM: Spatial Measuring and Understanding with Depth-Encoded Vision-Language Models (*Zhejiang University*) [\[paper\]](https://arxiv.org/pdf/2509.17664) [\[code\]](https://github.com/cpystan/SD-VLM) ⭐ 441 | 🐛 6 | 🌐 Python | 📅 2026-06-05 [\[checkpoint\]](https://huggingface.co/cpystan/SD-VLM-7B);

* \[ICRA2025] SpatialBot: Precise Spatial Understanding with Vision Language Models (*Shanghai Jiao Tong University*) [\[paper\]](https://arxiv.org/pdf/2406.13642) [\[code\]](https://github.com/BAAI-DCAI/SpatialBot) ⭐ 348 | 🐛 5 | 🌐 Python | 📅 2026-07-26 [\[checkpoint\]](https://huggingface.co/RussRobin/SpatialBot-3B);

* \[NeurIPS2024] SpatialRGPT: Grounded Spatial Reasoning in Vision-Language Models (*UC San Diego*) [\[paper\]](https://arxiv.org/pdf/2406.01584) [\[code\]](https://github.com/AnjieCheng/SpatialRGPT) ⭐ 337 | 🐛 26 | 🌐 Python | 📅 2024-12-14 [\[checkpoint\]](https://huggingface.co/collections/a8cheng/spatialrgpt-grounded-spatial-reasoning-in-vlms-66fef10465966adc81819723);

* \[CVPR2024] LL3DA: Visual Interactive Instruction Tuning for Omni-3D Understanding, Reasoning, and Planning (*Fudan University*) [\[paper\]](https://arxiv.org/pdf/2311.18651) [\[code\]](https://github.com/Open3DA/LL3DA) ⭐ 320 | 🐛 19 | 🌐 Python | 📅 2024-07-17;

* \[CVPR2024] VCoder: Versatile Vision Encoders for Multimodal Large Language Models (*Georgia Tech*) [\[paper\]](https://arxiv.org/pdf/2312.14233) [\[code\]](https://github.com/SHI-Labs/VCoder) ⭐ 280 | 🐛 5 | 🌐 Python | 📅 2024-04-17 [\[checkpoint\]](https://huggingface.co/models?search=vcoder);

* \[NeurIPS2025] RoboRefer: Towards Spatial Referring with Reasoning in Vision-Language Models for Robotics (*Beihang University*) [\[paper\]](https://arxiv.org/pdf/2506.04308) [\[code\]](https://github.com/Zhoues/RoboRefer) ⭐ 266 | 🐛 16 | 🌐 Python | 📅 2025-12-16 [\[checkpoint\]](https://huggingface.co/collections/Zhoues/roborefer-and-refspatial-6857c97848fab02271310b89);

* \[CVPR2022] ScanQA: 3D Question Answering for Spatial Scene Understanding (*Kyoto University*) [\[paper\]](https://arxiv.org/pdf/2112.10482) [\[code\]](https://github.com/ATR-DBI/ScanQA) ⭐ 163 | 🐛 11 | 🌐 Python | 📅 2023-08-23;

* \[CVPR2025] 3D-LLaVA: Towards Generalist 3D LMMs with Omni Superpoint Transformer (*The University of Adelaide*) [\[paper\]](https://arxiv.org/pdf/2501.01163) [\[code\]](https://github.com/djiajunustc/3D-LLaVA?tab=readme-ov-file) ⭐ 101 | 🐛 11 | 🌐 Python | 📅 2025-05-26 [\[checkpoint\]](https://huggingface.co/djiajunustc/3D-LLaVA-7B-LoRA);

* \[CVPR2025] LSceneLLM: Enhancing Large 3D Scene Understanding Using Adaptive Visual Preferences (*South China University of Technology*) [\[paper\]](https://arxiv.org/pdf/2412.01292) [\[code\]](https://github.com/Hoyyyaard/LSceneLLM) ⭐ 74 | 🐛 1 | 🌐 C++ | 📅 2025-03-29 [\[checkpoint\]](https://huggingface.co/Hoyard/LSceneLLM);

* \[CVPR2024] Situational Awareness Matters in 3D Vision Language Reasoning (*UIUC*) [\[paper\]](https://arxiv.org/pdf/2406.07544) [\[code\]](https://github.com/YunzeMan/Situation3D) ⭐ 44 | 🐛 5 | 🌐 Python | 📅 2024-12-09;

* \[NeurIPS2025] SSR: Enhancing Depth Perception in Vision-Language Models via Rationale-Guided Spatial Reasoning (*Westlake University*) [\[paper\]](https://arxiv.org/pdf/2505.12448) [\[code\]](https://github.com/yliu-cs/SSR) ⭐ 40 | 🐛 1 | 🌐 CSS | 📅 2025-10-14 [\[checkpoint\]](https://huggingface.co/collections/yliu-cs/ssr-682d44496b64e4edd94092bb);

* \[ICCVW2025] SmolRGPT: Efficient Spatial Reasoning for Warehouse Environments with 600M Parameters (*Universit de Moncton*) [\[paper\]](https://arxiv.org/pdf/2509.15490) [\[code\]](https://github.com/abtraore/SmolRGPT) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-04-02 [\[checkpoint\]](https://huggingface.co/collections/Abdrah/smolrgpt-checkpoints-6893bad56127440ef250486e);

* \[ECCV2024] SegPoint: Segment Any Point Cloud via Large Language Model (*Nanyang Technological University*) [\[paper\]](https://arxiv.org/pdf/2407.13761) [\[code\]](https://github.com/heshuting555/);

* \[arXiv2025] Spatial 3D-LLM: Progressive Spatial Awareness for Advanced 3D Vision-Language Understanding (*Beijing Digital Native Digital City Research Center*) [\[paper\]](https://openreview.net/pdf?id=JzLcKWtGnl);

  <!-- New paper, excluded in survey -->

* \[NeurIPS2025] SPATIALLM: Training Large Language Models for Structured Indoor Modeling (*Manycore Tech Inc.*) [\[paper\]](https://arxiv.org/pdf/2506.07491) [\[code\]](https://github.com/manycore-research/SpatialLM) ⭐ 4,705 | 🐛 5 | 🌐 Python | 📅 2026-06-26 [\[checkpoint\]](https://huggingface.co/manycore-research/SpatialLM1.1-Qwen-0.5B)

  <!-- New paper, excluded in survey -->

* \[Arxiv2025] 3D Aware Region Prompted Vision Language Model (*UC San Diego*) [\[paper\]](https://arxiv.org/pdf/2509.13317);
  <!-- leveraging depth for training a position embedding -->
  </details>

<a id="implicit-3d-from-egocentric-views"></a>

<details>
  <summary><b>Implicit 3D from Egocentric Views</b></summary>

* \[arXiv2025] Spatial-MLLM: Boosting MLLM Capabilities in Visual-based Spatial Intelligence (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2505.23747) [\[code\]](https://github.com/diankun-wu/Spatial-MLLM) ⭐ 482 | 🐛 8 | 🌐 Python | 📅 2026-02-05;

* \[arXiv2025] VLM-3R: Vision-Language Models Augmented with Instruction-Aligned 3D Reconstruction (*UT Austin*) [\[paper\]](https://arxiv.org/pdf/2505.20279) [\[code\]](https://github.com/VITA-Group/VLM-3R) ⭐ 439 | 🐛 10 | 🌐 Python | 📅 2026-07-15;

  <!-- New paper, excluded in survey -->

* \[arXiv2025] Vision-Language Memory for Spatial Reasoning (*University at Buffalo*) [\[paper\]](https://arxiv.org/pdf/2511.20644)

* \[ICCV2025] SplatTalk: 3D VQA with Gaussian Splatting (*Georgia Institute of Technology*) [\[paper\]](https://arxiv.org/pdf/2503.06271) [\[code\]](https://splat-talk.github.io/);

  <!-- New paper, excluded in survey -->

* \[NeurIPS2025] Learning from Videos for 3D World: Enhancing MLLMs with 3D Vision Geometry Priors (*CUHK*) [\[paper\]](https://arxiv.org/pdf/2505.24625#page=3.50) [\[code\]](https://github.com/LaVi-Lab/VG-LLM) ⭐ 254 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2025-11-28

  <!-- New paper, excluded in survey -->

* \[NeurIPS2025] 3DRS: MLLMs Need 3D-Aware Representation Supervision for Scene Understanding (*HKU*) [\[paper\]](https://arxiv.org/pdf/2506.01946) [\[code\]](https://github.com/Visual-AI/3DRS) ⭐ 160 | 🐛 4 | 🌐 Python | 📅 2025-12-09 [\[checkpoint\]](https://huggingface.co/OliverHuang1998/3DRS)

  <!-- New paper, excluded in survey -->

* \[arXiv2026] Spa3R: Predictive Spatial Field Modeling for 3D Visual Reasoning (*Huazhong University of Science & Technology*) [\[paper\]](https://arxiv.org/pdf/2602.21186) [\[code\]](https://github.com/hustvl/Spa3R) ⭐ 52 | 🐛 0 | 🌐 Python | 📅 2026-03-25 [\[checkpoint\]](https://huggingface.co/hustvl/Spa3-VLM)

</details>

<a id="scene-level-information--ego-centric"></a>

<details>
  <summary><b>Scene-level Information + Ego-centric</b></summary>

* \[arXiv2025] GPT4Scene: Understand 3D Scenes from Videos with Vision-Language Models (*The University of Hong Kong*) [\[paper\]](https://arxiv.org/pdf/2501.01428) [\[code\]](https://github.com/Qi-Zhangyang/GPT4Scene-and-VLN-R1) ⭐ 532 | 🐛 19 | 🌐 Python | 📅 2026-03-02 [\[checkpoint\]](https://huggingface.co/alexzyqi/GPT4Scene-qwen2vl_full_sft_mark_32_3D_img512);

* \[ICML2024] An Embodied Generalist Agent in 3D World (*Beijing Institute for General Artificial Intelligence (BIGAI)*) [\[paper\]](https://arxiv.org/pdf/2311.12871) [\[code\]](https://github.com/embodied-generalist/embodied-generalist) ⭐ 488 | 🐛 0 | 🌐 Python | 📅 2025-04-20 [\[checkpoint\]](https://huggingface.co/datasets/huangjy-pku/LEO_data/tree/main);

* \[NeurIPS2024] Chat-Scene: Bridging 3D Scene and Large Language Models with Object Identifiers (*Zhejiang University*) [\[paper\]](https://arxiv.org/pdf/2312.08168) [\[code\]](https://github.com/ZzZZCHS/Chat-Scene) ⭐ 216 | 🐛 12 | 🌐 Python | 📅 2026-04-12;

* \[CVPR2023] 3D Concept Learning and Reasoning from Multi-View Images (*UCLA*) [\[paper\]](https://arxiv.org/pdf/2303.11327) [\[code\]](https://github.com/evelinehong/3D-CLR-Official) ⭐ 85 | 🐛 0 | 🌐 Python | 📅 2024-01-20;

* \[ECCV2024] ScanReason: Empowering 3D Visual Grounding with Reasoning Capabilities (*The University of Hong Kong*) [\[paper\]](https://arxiv.org/pdf/2407.01525) [\[code\]](https://github.com/ZCMax/ScanReason) ⭐ 85 | 🐛 7 | 🌐 Python | 📅 2024-10-10;

  <!-- New paper, excluded in survey -->

* \[ICCV2025] MM-Spatial: Exploring 3D Spatial Understanding in Multimodal LLMs (*Apple*) [\[paper\]](https://arxiv.org/pdf/2503.13111) [\[code\]](https://github.com/apple/ml-cubifyanything) ⭐ 438 | 🐛 23 | 🌐 Python | 📅 2025-11-03;

* \[ICCV2025] LLaVA-3D: A Simple yet Effective Pathway to Empowering LMMs with 3D Capabilities (*The University of Hong Kong*) [\[paper\]](https://arxiv.org/pdf/2409.18125) [\[code\]](https://github.com/ZCMax/LLaVA-3D) ⭐ 388 | 🐛 26 | 🌐 Python | 📅 2025-10-21 [\[checkpoint\]](https://huggingface.co/ChaimZhu/LLaVA-3D-7B);

* \[CVPR2025] Inst3D-LMM: Instance-Aware 3D Scene Understanding with Multi-modal Instruction Tuning (*Zhejiang University*) [\[paper\]](https://arxiv.org/pdf/2503.00513) [\[code\]](https://github.com/hanxunyu/Inst3D-LMM) ⭐ 134 | 🐛 4 | 🌐 Python | 📅 2026-01-30;

* \[ICCV2025] Robin3D: Improving 3D Large Language Model via Robust Instruction Tuning (*University of Illinois Chicago*) [\[paper\]](https://arxiv.org/pdf/2410.00255) [\[code\]](https://github.com/WeitaiKang/Robin3D?tab=readme-ov-file) ⭐ 71 | 🐛 4 | 🌐 Python | 📅 2025-10-19 [\[checkpoint\]](https://drive.google.com/drive/folders/14Si8bdWI3N5NEeVDLhmAlxilWPl0f_Wp?usp=sharing);

* \[CVPR2025] DSPNet: Dual-vision Scene Perception for Robust 3D Question Answering (*Sun Yat-sen University*) [\[paper\]](https://arxiv.org/pdf/2503.03190) [\[code\]](https://github.com/LZ-CH/DSPNet) ⭐ 28 | 🐛 4 | 🌐 Python | 📅 2025-04-18 [\[checkpoint\]](https://github.com/LZ-CH/DSPNet) ⭐ 28 | 🐛 4 | 🌐 Python | 📅 2025-04-18;

* \[arXiv2025] Beyond Flatlands: Unlocking Spatial Intelligence by Decoupling 3D Reasoning from Numerical Regression (*Beijing Institute of Technology*) [\[paper\]](https://arxiv.org/pdf/2511.11239)

* \[WACV2025] Scene-LLM: Extending Language Model for 3D Visual Understanding and Reasoning (*Brown University*) [\[paper\]](https://arxiv.org/pdf/2403.11401);

</details>

***

### Data-Centric Spatial Enhancement

<a id="manifesting-spatial-relations-in-2d-images"></a>

<details>
  <summary><b>Manifesting Spatial Relations in 2D Images</b></summary>

* \[ICLR2024] KOSMOS-2: Grounding Multimodal Large Language Models to the World (*Microsoft Research*) [\[paper\]](https://arxiv.org/pdf/2306.14824) [\[code\]](https://github.com/microsoft/unilm/tree/master/kosmos-2) ⭐ 22,187 | 🐛 684 | 🌐 Python | 📅 2026-01-23 [\[checkpoint\]](https://huggingface.co/microsoft/kosmos-2-patch14-224);

* \[ECCV2024] The All-Seeing Project V2: Towards General Relation Comprehension of the Open World (*Shanghai AI Laboratory*) [\[paper\]](https://arxiv.org/pdf/2402.19474) [\[code\]](https://github.com/OpenGVLab/all-seeing?tab=readme-ov-file) ⭐ 506 | 🐛 15 | 🌐 Python | 📅 2024-08-09 [\[checkpoint\]](https://huggingface.co/OpenGVLab/ASMv2);

* \[CVPR2022] Pseudo-Q: Generating Pseudo Language Queries for Visual Grounding (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2203.08481) [\[code\]](https://github.com/LeapLabTHU/Pseudo-Q?tab=readme-ov-file) ⭐ 153 | 🐛 0 | 🌐 Python | 📅 2024-07-13;

* \[arXiv2023] Position-Enhanced Visual Instruction Tuning for Multimodal Large Language Models (*Tsinghua University*) [\[paper\]](https://arxiv.org/pdf/2308.13437) [\[code\]](https://github.com/PVIT-official/PVIT) ⭐ 37 | 🐛 2 | 🌐 Python | 📅 2023-09-19 [\[checkpoint\]](https://huggingface.co/PVIT/pvit);

* \[arXiv2025] SpaRE: Enhancing Spatial Reasoning in Vision-Language Models with Synthetic Data (*University of Waterloo*) [\[paper\]](https://arxiv.org/pdf/2504.20648);

  <!-- New paper, excluded in survey -->

* \[arXiv2025] Scaling Spatial Intelligence with Multimodal Foundation  (*SenseTime Research*) [\[paper\]](https://arxiv.org/pdf/2511.13719) [\[code\]](https://github.com/OpenSenseNova/SenseNova-SI) ⭐ 294 | 🐛 1 | 🌐 Python | 📅 2026-05-14 [\[checkpoint\]](https://huggingface.co/collections/sensenova/sensenova-si);

* \[NeurIPS2025] Stitch and Tell: A Structured Multimodal Data Augmentation Method for Spatial Understanding (*Beijing Institute of Technology*) [\[paper\]](https://www.arxiv.org/pdf/2512.06769);

</details>

<a id="manifesting-spatial-priors-in-3d-and-synthetic-worlds"></a>

<details>
  <summary><b>Manifesting Spatial Priors in 3D and Synthetic Worlds</b></summary>

* \[CVPR2024] SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities (*Google DeepMind*) [\[paper\]](https://arxiv.org/pdf/2401.12168) [\[code\]](https://spatial-vlm.github.io/#community-implementation) [\[checkpoint\]](https://github.com/remyxai/VQASynth?tab=readme-ov-file#models-trained-using-vqasynth-) ⭐ 586 | 🐛 3 | 🌐 Python | 📅 2026-08-13;

* \[arXiv2025] Multi-SpatialMLLM: Multi-Frame Spatial Understanding with MultiModal Large Language Models (*Meta FAIR*) [\[paper\]](https://arxiv.org/pdf/2505.17015) [\[code\]](https://github.com/facebookresearch/Multi-SpatialMLLM?tab=readme-ov-file#-model-training) ⭐ 178 | 🐛 2 | 🌐 Python | 📅 2026-02-25;

* \[NeurIPS2024] Multi-modal Situated Reasoning in 3D Scenes (*BIGAI*) [\[paper\]](https://arxiv.org/pdf/2409.02389) [\[code\]](https://github.com/MSR3D/MSR3D) ⭐ 77 | 🐛 1 | 🌐 Python | 📅 2025-12-02;

* \[arXiv2025] Sparkle: Mastering Basic Spatial Capabilities in Vision Language Models Elicits Generalization to Spatial Reasoning (*Massachusetts Institute of Technology*) [\[paper\]](https://arxiv.org/pdf/2410.16162);

  <!-- New paper, excluded in survey -->

* \[arXiv2025] SCoT: Teaching 3D-LLMs to Think Spatially with Million-scale CoT Annotations (*Anonymous*) [\[paper\]](https://openreview.net/pdf?id=5Tph6wFMOm);

  <!-- New paper, excluded in survey -->

* \[arXiv2025] Scaling Spatial Reasoning in MLLMs through Programmatic Data Synthesis (*Harbin Institute of Technology*) [\[paper\]](https://arxiv.org/pdf/2512.16237#page=7.00) [\[code\]](https://github.com/AI9Stars/SPRITE) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2026-01-20;

  <!-- New paper, excluded in survey -->

* \[arXiv2025] Visual Spatial Tuning (*The University of Hong Kong*) [\[paper\]](https://arxiv.org/pdf/2511.05491) [\[code\]](https://github.com/Yangr116/VST) ⭐ 201 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-03-25 [\[checkpoint\]](https://huggingfgace.co/collections/rayruiyang/vst);

  <!-- New paper, excluded in survey -->

* \[ICML2025] Orient Anything: Learning Robust Object Orientation Estimation from Rendering 3D Models (*Zhejiang University*) [\[paper\]](https://arxiv.org/pdf/2412.18605) [\[code\]](https://github.com/SpatialVision/Orient-Anything?tab=readme-ov-file) ⭐ 392 | 🐛 13 | 🌐 Python | 📅 2026-02-06 [\[checkpoint\]](https://huggingface.co/Viglong/Orient-Anything/blob/main/croplargeEX2/dino_weight.pt);

* \[CVPR2025] RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics (*NVIDIA*) [\[paper\]](https://arxiv.org/pdf/2411.16537) [\[code\]](https://github.com/NVlabs/RoboSpatial) ⭐ 149 | 🐛 0 | 🌐 Python | 📅 2026-06-17;

* \[WACV2025] LLaVA-SpaceSGG: Visual Instruct Tuning for Open-vocabulary Scene Graph Generation with Enhanced Spatial Relations (*City University of Hong Kong*) [\[paper\]](https://arxiv.org/pdf/2412.06322) [\[code\]](https://github.com/Endlinc/LLaVA-SpaceSGG?tab=readme-ov-file) ⭐ 30 | 🐛 3 | 🌐 Python | 📅 2025-01-27 [\[checkpoint\]](https://huggingface.co/wumengyangok/LLaVA-SpaceSGG/tree/main);

* \[NeurIPS2025] Actial: Activate Spatial Reasoning Ability of Multimodal Large Language Models (*Nanjing University*) [\[paper\]](https://openreview.net/pdf?id=jquTBzt3Av) [\[code\]](https://github.com/warmsnow-sh/Actial) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-01-26 [\[checkpoint\]](https://huggingface.co/Osilly/Acital-Qwen-2.5VL-7B);

* \[arXiv2025] INTERNSPATIAL: A COMPREHENSIVE DATASET FOR SPATIAL REASONING IN VISION-LANGUAGE MODELS (*Shanghai AI Laboratory*) [\[paper\]](https://arxiv.org/pdf/2506.18385)

* \[ICLR2025] SPARTUN3D: Situated Spatial Understanding of 3D World in Large Language Models (*Michigan State University & UC Davis*) [\[paper\]](https://arxiv.org/pdf/2410.03878);

</details>

## 📚 Datasets and Benchmarks

> A comprehensive list of datasets for training and evaluation.

### Spatially-Oriented Training Corpora

<p align="left">
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/data_benchmark/Dataset_SVQA.md">
    <img src="https://img.shields.io/badge/Training Data-Collection-green?style=flat&logo=mdbook&logoColor=white" alt="Dataset"> 
  </a>
</p>

### Evaluation Benchmarks

<p align="left">
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/data_benchmark/Benchmark_SVQA.md">
    <img src="https://img.shields.io/badge/Benchmark-Collection-green?style=flat&logo=mdbook&logoColor=white" alt="Benchmark">
  </a>
</p>

## 🏆 Spatial VLM Leaderboard & Evaluation Toolkit

### 🏅 Main Leaderboard

The table below presents the main results from our survey, comparing [38 VLMs](evaluation/README.md#model-details-and-original-repositories) across [9 benchmarks](#evaluated-benchmarks). Scores are QA Accuracy (%). Benchmarks are grouped by our Cognitive Hierarchy.

<div align='center'><img src="./samples/leaderboard.jpg"  alt="Leaderboard" width="100%"/></div>

We invite the community to benchmark new models using our suite. Please to add your model's results!

### 🧑‍🔬 How to Evaluate Your Model

1. **Selected Benchmarks for the Leaderboard**\
   We collect existing spatial benchmarks used in the literature and standardize their usage for evaluation in the hugging face repo<a href="https://huggingface.co/datasets/LLDDSS/Awesome_Spatial_VQA_Benchmarks"><img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="Hugging Face" width="20"/></a>.\
   The table below summarizes the key datasets used to benchmark spatial VLMs on our leaderboard.\ <a id="evaluated-benchmarks"></a>
    <table>
      <tr>
        <th>Dataset Name</th>
        <th>Description</th>
        <th>Link</th>
      </tr>
      <tr>
        <td>EgoOrientBench</td>
        <td>Egocentric spatial understanding benchmark</td>
        <td rowspan="10"><a href="https://huggingface.co/datasets/LLDDSS/Awesome_Spatial_VQA_Benchmarks"><img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="Hugging Face Link" width="20"/> Link</a></td>
      </tr>
      <tr><td>GeoMeter(real)</td><td>A depth-aware spatial reasoning benchmark</td></tr>
      <tr><td>SEED-Bench (Spatial section)</td><td>Subset focusing on spatial relations</td></tr>
      <tr><td>What’s Up</td><td>Spatial relation in visual grounding</td></tr>
      <tr><td>CV-Bench</td><td>Visual-center spatial benchmark</td></tr>
      <tr><td>SRBench</td><td>The extrapolation of spatial benchmark</td></tr>
      <tr><td>MindCube</td><td>The extrapolation of spatial benchmark</td></tr>
      <tr><td>OmniSpatial</td><td>Comprehensive spatial reasoning dataset</td></tr>
      <tr><td>RealWorldQA</td><td>Comprehensive spatial reasoning dataset</td></tr>
    </table>

2. **Evaluation Toolkit**\
   To facilitate fair and reproducible evaluation on these benchmarks, we provide a dedicated evaluation toolkit. The related code is available in [`evaluation/README.md`](evaluation/README.md).\
   It supports running experiments with:

   * [Commercial VLMs](evaluation/Commercial_General/README.md) (*e.g.,* GPT, Gemini)
   * [General-purpose VLMs](evaluation/Commercial_General/README.md) (*e.g.,* Qwen2.5, LLava1.5, LLava\_Next, LLava\_Onevision)
   * Specialized Spatial VLMs:\
     (1) [Train-Free Promptings](evaluation/Train_Free_Promptings/README.md)\
     (2) [Model-Centric Enhancement](evaluation/Model_Centric/README.md)\
     (3) [Explicit 2D Information Injection](evaluation/2D_Information/README.md)\
     (4) [3D Spatial Information Enhancement](evaluation/3D_Information/README.md)\
     (5) [Data-Centric Spatial Enhancement](evaluation/Data_Centric/README.md)

   Follow the instructions there to plug in your own model and report results under the same protocol as our leaderboard.

***

## Citation

If you find this survey or repository useful for your research, please cite our paper:

```
 @article{Liu_2025,
  title={Spatial Intelligence in Vision-Language Models: A Comprehensive Survey},
  url={http://dx.doi.org/10.36227/techrxiv.176231405.57942913/v2},
  DOI={10.36227/techrxiv.176231405.57942913/v2},
  publisher={Institute of Electrical and Electronics Engineers (IEEE)},
  author={Liu, Disheng and Liang, Tuo and Hu, Zhe and Peng, Jierui and Lu, Yiren and Xu, Yi and Fu, Yun and Yin, Yu},
  year={2025},
  month=nov }
```

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
