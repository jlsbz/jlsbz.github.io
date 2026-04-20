---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-section { margin-bottom: 35px; }
  .cv-title { font-size: 22px; font-weight: bold; border-bottom: 2px solid #538F79; padding-bottom: 6px; margin-bottom: 15px; color: #222; }
  .cv-item { margin-bottom: 12px; line-height: 1.6; }
  .cv-label { font-weight: bold; min-width: 110px; display: inline-block; color: #333; }
  .pub-entry { margin-bottom: 10px; line-height: 1.5; }
  .pub-title { font-weight: 600; }
  .pub-me { color: #000; font-weight: bold; border-bottom: 1.5px solid #333; }
  .pub-conf { color: #006699; font-weight: 500; }
</style>

<div class="cv-section">
  <div class="cv-title">Personal Information</div>
  <div class="cv-item"><span class="cv-label">Name:</span> Ning Yang</div>
  <div class="cv-item"><span class="cv-label">Phone:</span> 15201952982</div>
  <div class="cv-item"><span class="cv-label">Email:</span> yn937391832@sjtu.edu.cn</div>
  <div class="cv-item"><span class="cv-label">Website:</span> <a href="https://jlsbz.github.io/">https://jlsbz.github.io/</a></div>
</div>

<div class="cv-section">
  <div class="cv-title">Education</div>
  <div class="cv-item">
    <span class="cv-label">Ph.D in computer science and technology:</span> Shanghai Jiao Tong University (SJTU), 2021.09 – Present<br>
    &nbsp;&nbsp;&nbsp;&nbsp; Intelligent Memory & Processor Architecture & Computing Lab, Advisor: Li Jiang
  </div>
  <div class="cv-item">
    <span class="cv-label">B.S. in computer science and technology:</span> Shanghai Jiao Tong University (SJTU), 2017.09 – 2021.06<br>
    &nbsp;&nbsp;&nbsp;&nbsp; Zhiyuan Honors Program
  </div>
</div>

<div class="cv-section">
  <div class="cv-title">Research Interests</div>
  <div class="cv-item">
    • Model Quantization & Compression<br>
    • Memory-efficient execution and dataflow optimization<br>
    • Mixture-of-Experts (MoE) inference and scheduling<br>
    • Hardware–software co-design for LLM deployment<br>
  </div>
</div>

<div class="cv-section">
  <div class="cv-title">Publications</div>

<!-- Ning Yang 为第一作者的论文 -->
<div class="pub-entry">
    <span class="pub-title">NICE: Deep Neural Network Acceleration via Hardware-Friendly Index Assisted Compression</span><br>
    <span class="pub-me">Ning Yang</span>, Fangxin Liu, Zongwu Wang, Haomin Li, Hongbo Zhao, Xinran Liang, Li Jiang, Haibing Guan<br>
    <span class="pub-conf">TACO 2026 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Rethinking variable-length encoding: Exploiting bit sparsity for parallel decoding in LLM accelerators</span><br>
    <span class="pub-me">Ning Yang</span>, Fangxin Liu, Junjie Wang, Chenyang Guan, Zongwu Wang, Junping Zhao, Li Jiang, Haibing Guan<br>
    <span class="pub-conf">TACO 2026 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">PISA: Efficient Precision-Slice Framework for LLMs with Adaptive Numerical Type</span><br>
    <span class="pub-me">Ning Yang</span>, Zongwu Wang, Qingxiao Sun, Liqiang Lu, Fangxin Liu<br>
    <span class="pub-conf">DAC 2025 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">DASH: Input-Aware Dynamic Layer Skipping for Efficient LLM Inference with Markov Decision Policies</span><br>
    <span class="pub-me">Ning Yang</span>, Fangxin Liu, Junjie Wang, Tao Yang, Kan Liu, Haibing Guan, Li Jiang<br>
    <span class="pub-conf">arXiv 2025 (Preprint)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Searchq: Search-based fine-grained quantization for data-free model compression</span><br>
    <span class="pub-me">Ning Yang</span>, Fangxin Liu, Zongwu Wang, Junping Zhao, Li Jiang<br>
    <span class="pub-conf">TCAS-AI 2024</span>
</div>

<!-- Ning Yang 为第二作者（含共同第一作者）的论文 -->
<div class="pub-entry">
    <span class="pub-title">STEP: Adaptive Spatio-Temporal Expert Prefetching for Low-Latency and Memory-Efficient MoE Inference (Accepted!)</span><br>
    <span class="pub-me">Fangxin Liu=</span>, <b>Ning Yang=</b>, Zongwu Wang, Chenyang Guan, Haomin Li, Yu Feng, Liqiang Lu, Xiang Li, Siran Yang, Jiamang Wang, Lin Qu, Li Jiang, Haibing Guan<br>
    <span class="pub-conf">ISCA 2026 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">EARTH: An Efficient MoE Accelerator with Entropy-Aware Speculative Prefetch and Result Reuse</span><br>
    <span class="pub-me">Fangxin Liu=</span>, <b>Ning Yang=</b>, Jingkui Yang, Zongwu Wang, Chenyang Guan, Yu Feng, Li Jiang, Haibing Guan<br>
    <span class="pub-conf">ASPLOS 2026 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">BLOOM: Bit-Slice Framework for DNN Acceleration with Mixed-Precision</span><br>
    <span class="pub-me">Fangxin Liu=</span>, <b>Ning Yang=</b>, Zongwu Wang, Xuanpeng Zhu, Haidong Yao, Xiankui Xiong, Li Jiang, Haibing Guan<br>
    <span class="pub-conf">DAC 2025 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Ops: Outlier-aware precision-slice framework for llm acceleration</span><br>
    <span class="pub-me">Fangxin Liu=</span>, <b>Ning Yang=</b>, Zongwu Wang, Xuanpeng Zhu, Haidong Yao, Xiankui Xiong, Qi Sun, Li Jiang<br>
    <span class="pub-conf">DATE 2025 (CCF-B)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">EOS: An Energy-Oriented Attack Framework for Spiking Neural Networks</span><br>
    <span class="pub-me">Ning Yang=</span>, Fangxin Liu=, Zongwu Wang, Haomin Li, Zhuoran Song, Songwen Pei, Li Jiang<br>
    <span class="pub-conf">DAC 2024 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Inspire: Accelerating deep neural networks via hardware-friendly index-pair encoding</span><br>
    <span class="pub-me">Fangxin Liu=</span>, <b>Ning Yang=</b>, Zhiyan Song, Zongwu Wang, Haomin Li, Shiyuan Huang, Zhuoran Song, Songwen Pei, Li Jiang<br>
    <span class="pub-conf">DAC 2024 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Spark: Scalable and precision-aware acceleration of neural networks via efficient encoding</span><br>
    <span class="pub-me">Fangxin Liu=</span>, <b>Ning Yang=</b>, Haomin Li, Zongwu Wang, Zhuoran Song, Songwen Pei, Li Jiang<br>
    <span class="pub-conf">HPCA 2024 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">T-BUS: Taming bipartite unstructured sparsity for energy-efficient DNN acceleration</span><br>
    <span class="pub-me">Ning Yang=</span>, Fangxin Liu=, Zongwu Wang, Zhiyan Song, Tao Yang, Li Jiang<br>
    <span class="pub-conf">ICCD 2024 (CCF-B)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Holes: Boosting large language models efficiency with hardware-friendly lossless encoding</span><br>
    <span class="pub-me">Fangxin Liu=</span>, <b>Ning Yang=</b>, Zhiyan Song, Zongwu Wang, Li Jiang<br>
    <span class="pub-conf">ICCD 2024 (CCF-B)</span>
</div>

<!-- Ning Yang 为其他位置的论文 -->
<div class="pub-entry">
    <span class="pub-title">Aster: Adaptive dynamic layer-skipping for efficient transformer inference via markov decision process</span><br>
    <span class="pub-me">Fangxin Liu</span>, Junjie Wang, <b>Ning Yang</b>, Zongwu Wang, Junping Zhao, Li Jiang, Haibing Guan<br>
    <span class="pub-conf">ACM MM 2025 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">TAIL: Exploiting temporal asynchronous execution for efficient spiking neural networks with inter-layer parallelism</span><br>
    <span class="pub-me">Haomin Li</span>, Fangxin Liu, Zongwu Wang, Dongxu Lyu, Shiyuan Huang, <b>Ning Yang</b>, Qi Sun, Zhuoran Song, Li Jiang<br>
    <span class="pub-conf">DATE 2025 (CCF-B)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">LCD: Advancing Extreme Low-Bit Clustering for Large Language Models via Knowledge Distillation</span><br>
    <span class="pub-me">Fangxin Liu</span>, <b>Ning Yang</b>, Junping Zhao, Tao Yang, Haibing Guan, Li Jiang<br>
    <span class="pub-conf">arXiv 2025 (Preprint)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Irregular Sparsity-Enabled Search-in-Memory Engine for Accelerating Spiking Neural Networks</span><br>
    <span class="pub-me">Fangxin Liu</span>, Zongwu Wang, <b>Ning Yang</b>, Haomin Li, Tao Yang, Haibing Guan, Li Jiang<br>
    <span class="pub-conf">APPT 2025</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Paap-hd: Pim-assisted approximation for efficient hyper-dimensional computing</span><br>
    <span class="pub-me">Fangxin Liu</span>, Haomin Li, <b>Ning Yang</b>, Yichi Chen, Zongwu Wang, Tao Yang, Li Jiang<br>
    <span class="pub-conf">ASPDAC 2024 (CCF-B)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Teas: Exploiting spiking activity for temporal-wise adaptive spiking neural networks</span><br>
    <span class="pub-me">Fangxin Liu</span>, Haomin Li, <b>Ning Yang</b>, Zongwu Wang, Tao Yang, Li Jiang<br>
    <span class="pub-conf">ASPDAC 2024 (CCF-B)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Compass: Sram-based computing-in-memory snn accelerator with adaptive spike speculation</span><br>
    <span class="pub-me">Zongwu Wang</span>, Fangxin Liu, <b>Ning Yang</b>, Shiyuan Huang, Haomin Li, Li Jiang<br>
    <span class="pub-conf">MICRO 2024 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Exploiting temporal-unrolled parallelism for energy-efficient snn acceleration</span><br>
    <span class="pub-me">Fangxin Liu</span>, Zongwu Wang, Wenbo Zhao, <b>Ning Yang</b>, Yongbiao Chen, Shiyuan Huang, Haomin Li, Tao Yang, Songwen Pei, Xiaoyao Liang, others<br>
    <span class="pub-conf">TPDS 2024 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">STCO: Enhancing Training Efficiency via Structured Sparse Tensor Compilation Optimization</span><br>
    <span class="pub-me">Shiyuan Huang</span>, Fangxin Liu, Tian Li, Zongwu Wang, <b>Ning Yang</b>, Haomin Li, Li Jiang<br>
    <span class="pub-conf">TODAES 2024 (CCF-B)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">SpMMPlu-Pro: An enhanced compiler plug-in for efficient SpMM and sparsity propagation algorithm</span><br>
    <span class="pub-me">Shiyuan Huang</span>, Fangxin Liu, Tao Yang, Zongwu Wang, <b>Ning Yang</b>, Li Jiang<br>
    <span class="pub-conf">TCAD 2024 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">Attack and Defense: Enhancing Robustness of Binary Hyper-Dimensional Computing</span><br>
    <span class="pub-me">Haomin Li</span>, Fangxin Liu, Zongwu Wang, <b>Ning Yang</b>, Shiyuan Huang, Xiaoyao Liang, Haibing Guan, Li Jiang<br>
    <span class="pub-conf">TACO 2024 (CCF-A)</span>
</div>

<div class="pub-entry">
    <span class="pub-title">PSQ: An automatic search framework for data-free quantization on pim-based architecture</span><br>
    <span class="pub-me">Fangxin Liu</span>, <b>Ning Yang</b>, Li Jiang<br>
    <span class="pub-conf">ICCD 2023 (CCF-B)</span>
</div>

<div class="cv-section">
  <div class="cv-title">Projects & Experiences</div>
  <div class="cv-item">• <b>Xiaomi</b>: On-Device Large Model Low-Bit Quantization</div>
  <div class="cv-item">• <b>Huawei</b>: Optimization Scheme Analysis of Cold/Hot Aware Scheduling Based on "Query instead of Calculation"</div>
  <div class="cv-item">• <b>ZTE</b>: High-Efficiency Quantization & Compression Platform for Multi-Model Adaptation</div>
  <div class="cv-item">• <b>Huawei</b>: Low-Power Optical Communication Operators Based on Computing-in-Memory</div>
</div>

<div class="cv-section">
  <div class="cv-title">Awards & Honors</div>
  <div class="cv-item">• National Scholarship, 2024</div>
  <div class="cv-item">• Best Paper Poster Award, 3rd CCF China Computer Systems Conference (CCS), 2024</div>
  <div class="cv-item">• First Prize, 2nd Open Source Competition for Integrated Chips & Chiplet Technology, 2024</div>
</div>

<div class="cv-section">
  <div class="cv-title">Academic Services</div>
  <div class="cv-item">Reviewer for DAC, TACO, TC, ACL, etc.</div>
</div>