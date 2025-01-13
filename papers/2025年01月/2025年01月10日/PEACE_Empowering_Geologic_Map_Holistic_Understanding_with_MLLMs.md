# PEACE：利用多模态大语言模型（MLLMs）提升地质地图的全面理解

发布时间：2025年01月10日

`Agent

理由：这篇论文主要介绍了一个名为GeoMap-Agent的智能代理，该代理专门设计用于地质图理解。论文详细描述了GeoMap-Agent的三大模块（分层信息提取、领域知识注入和提示增强问答），并展示了其在GeoMap-Bench基准测试上的优异表现。由于论文的核心内容是开发和应用一个智能代理来解决特定领域的问题，因此将其分类为Agent。` `地质学` `灾害预警`

> PEACE: Empowering Geologic Map Holistic Understanding with MLLMs

# 摘要

> # 摘要
地质图是地质科学中的核心图表，揭示了地球地下和地表的构造与组成。这些地图在灾害预警、资源勘探和土木工程等领域至关重要。然而，当前的多模态大型语言模型（MLLMs）在地质图理解上表现欠佳，主要原因是地图制图综合的复杂性，如高分辨率地图处理、多组件管理及领域知识需求。为此，我们创建了首个地质图理解基准GeoMap-Bench，全面评估MLLMs的提取、引用、推理和分析能力。为填补这一空白，我们推出了GeoMap-Agent，首个专为地质图理解设计的智能代理，包含分层信息提取（HIE）、领域知识注入（DKI）和提示增强问答（PEQA）三大模块。借鉴人类科学家的跨学科合作模式，AI专家组作为顾问，利用多样化工具池深入分析问题。实验表明，GeoMap-Agent在GeoMap-Bench上获得0.811的高分，远超GPT-4o的0.369。我们的研究通过MLLMs赋能地质图整体理解（PEACE），为地质学中的AI应用开辟了新路径，显著提升了地质调查的效率和精度。

> Geologic map, as a fundamental diagram in geology science, provides critical insights into the structure and composition of Earth's subsurface and surface. These maps are indispensable in various fields, including disaster detection, resource exploration, and civil engineering. Despite their significance, current Multimodal Large Language Models (MLLMs) often fall short in geologic map understanding. This gap is primarily due to the challenging nature of cartographic generalization, which involves handling high-resolution map, managing multiple associated components, and requiring domain-specific knowledge. To quantify this gap, we construct GeoMap-Bench, the first-ever benchmark for evaluating MLLMs in geologic map understanding, which assesses the full-scale abilities in extracting, referring, grounding, reasoning, and analyzing. To bridge this gap, we introduce GeoMap-Agent, the inaugural agent designed for geologic map understanding, which features three modules: Hierarchical Information Extraction (HIE), Domain Knowledge Injection (DKI), and Prompt-enhanced Question Answering (PEQA). Inspired by the interdisciplinary collaboration among human scientists, an AI expert group acts as consultants, utilizing a diverse tool pool to comprehensively analyze questions. Through comprehensive experiments, GeoMap-Agent achieves an overall score of 0.811 on GeoMap-Bench, significantly outperforming 0.369 of GPT-4o. Our work, emPowering gEologic mAp holistiC undErstanding (PEACE) with MLLMs, paves the way for advanced AI applications in geology, enhancing the efficiency and accuracy of geological investigations.

[Arxiv](https://arxiv.org/abs/2501.06184)