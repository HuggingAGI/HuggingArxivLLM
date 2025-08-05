# # AnalogCoder-Pro：融合生成与优化，多模态大语言模型助力模拟电路设计 #

发布时间：2025年08月04日

`LLM应用` `电子设计自动化` `电路设计`

> AnalogCoder-Pro: Unifying Analog Circuit Generation and Optimization via Multi-modal LLMs

# 摘要

> 尽管模拟设计自动化领域取得了进展，模拟前端设计仍严重依赖专家直觉和迭代仿真，这凸显了在关键性能应用中实现全自动优化仍存在重大缺口。近期，大型语言模型（LLMs）的快速发展为模拟设计自动化带来了新的希望。然而，现有研究仍处于初级阶段，面向实际端到端解决方案的整体联合优化仍鲜有探索。我们提出了AnalogCoder-Pro，一个统一的多模态LLM框架，整合生成能力和优化技术，联合探索电路拓扑并优化器件尺寸，自动生成特定性能、全尺寸的电路网表。AnalogCoder-Pro采用拒绝采样方法，利用高质量合成电路数据对LLMs进行微调，并引入基于功能规范和波形图像的多模态诊断与修复工作流。通过利用LLMs解析生成的电路网表，AnalogCoder-Pro实现了关键设计参数的自动化提取和参数空间的构建，形成了同时生成拓扑结构和优化器件尺寸的端到端工作流。大量实验表明，这些正交方法显著提升了模拟电路设计的成功率并改善了电路性能。

> Despite advances in analog design automation, analog front-end design still heavily depends on expert intuition and iterative simulations, underscoring critical gaps in fully automated optimization for performance-critical applications. Recently, the rapid development of Large Language Models (LLMs) has brought new promise to analog design automation. However, existing work remains in its early stages, and holistic joint optimization for practical end-to-end solutions remains largely unexplored. We propose AnalogCoder-Pro, a unified multimodal LLM-based framework that integrates generative capabilities and optimization techniques to jointly explore circuit topologies and optimize device sizing, automatically generating performance-specific, fully sized schematic netlists. AnalogCoder-Pro employs rejection sampling for fine-tuning LLMs on high-quality synthesized circuit data and introduces a multimodal diagnosis and repair workflow based on functional specifications and waveform images. By leveraging LLMs to interpret generated circuit netlists, AnalogCoder-Pro automates the extraction of critical design parameters and the formulation of parameter spaces, establishing an end-to-end workflow for simultaneous topology generation and device sizing optimization. Extensive experiments demonstrate that these orthogonal approaches significantly improve the success rate of analog circuit design and enhance circuit performance.

[Arxiv](https://arxiv.org/abs/2508.02518)