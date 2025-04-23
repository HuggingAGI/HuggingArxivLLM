# DyFo: 一种零训练动态聚焦视觉搜索，助力提升大模型在细粒度视觉理解中的表现。

发布时间：2025年04月21日

`LLM应用` `计算机视觉` `人工智能`

> DyFo: A Training-Free Dynamic Focus Visual Search for Enhancing LMMs in Fine-Grained Visual Understanding

# 摘要

> 人类在杂乱环境中轻松定位目标物体的能力，源于一种名为视觉搜索的认知机制，它能高效过滤无关信息，聚焦于任务相关区域。受此启发，我们提出了一种无需训练的动态聚焦视觉搜索方法——Dyfo（Dynamic Focus），旨在提升大规模多模态模型（LMMs）的细粒度视觉理解能力。与现有方法不同，Dyfo无需额外模块或数据收集，而是通过LMMs与视觉专家的双向交互，利用蒙特卡洛树搜索（MCTS）算法模拟人类-like的注意力调整。这使LMMs能够专注于关键视觉区域，同时过滤无关内容，而无需因词汇扩展或集成专用定位模块而引入额外训练。实验结果表明，Dyfo显著提升了LMMs的细粒度视觉理解能力，并减少了幻觉问题，在固定和动态分辨率模型上均实现了更优性能。代码可在https://github.com/PKU-ICST-MIPL/DyFo_CVPR2025获取

> Humans can effortlessly locate desired objects in cluttered environments, relying on a cognitive mechanism known as visual search to efficiently filter out irrelevant information and focus on task-related regions. Inspired by this process, we propose Dyfo (Dynamic Focus), a training-free dynamic focusing visual search method that enhances fine-grained visual understanding in large multimodal models (LMMs). Unlike existing approaches which require additional modules or data collection, Dyfo leverages a bidirectional interaction between LMMs and visual experts, using a Monte Carlo Tree Search (MCTS) algorithm to simulate human-like focus adjustments. This enables LMMs to focus on key visual regions while filtering out irrelevant content, without introducing additional training caused by vocabulary expansion or the integration of specialized localization modules. Experimental results demonstrate that Dyfo significantly improves fine-grained visual understanding and reduces hallucination issues in LMMs, achieving superior performance across both fixed and dynamic resolution models. The code is available at https://github.com/PKU-ICST-MIPL/DyFo_CVPR2025

[Arxiv](https://arxiv.org/abs/2504.14920)