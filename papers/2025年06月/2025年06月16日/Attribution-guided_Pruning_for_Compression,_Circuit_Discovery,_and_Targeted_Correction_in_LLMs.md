# 基于归因的剪枝在大型语言模型中的压缩、电路发现与定向修正

发布时间：2025年06月16日

`LLM理论` `人工智能`

> Attribution-guided Pruning for Compression, Circuit Discovery, and Targeted Correction in LLMs

# 摘要

> 大型语言模型（LLMs）作为当代人工智能应用的核心，却因庞大的参数量在资源受限环境中面临部署难题。近期研究表明，可解释性人工智能（XAI）中的归因方法不仅能提升模型透明度，还能通过去除与推理无关的组件实现模型压缩。本文采用层相关传播（LRP）技术，开展归因引导下的LLMs剪枝研究。虽然LRP在视觉模型的结构化剪枝中已初显成效，我们将其拓展至LLMs的非结构化剪枝，并证实其能在几乎不影响性能的前提下大幅缩减模型规模。我们的方法特别擅长提取任务相关“电路”——这些子图可表征核心功能（如间接目标识别）。在此基础上，我们开发了一种模型校正技术，通过移除导致不良行为（如毒性输出）的电路来优化模型表现。最终，我们将这些技术整合为一个统一框架，并通过在Llama和OPT模型上的广泛实验，展示了其在压缩、电路发现和模型校正方面的效果与局限，彰显了其提升模型效率与安全性的潜力。我们的代码已开源，地址为https://github.com/erfanhatefi/SparC3。

> Large Language Models (LLMs) are central to many contemporary AI applications, yet their extensive parameter counts pose significant challenges for deployment in memory- and compute-constrained environments. Recent works in eXplainable AI (XAI), particularly on attribution methods, suggest that interpretability can also enable model compression by identifying and removing components irrelevant to inference. In this paper, we leverage Layer-wise Relevance Propagation (LRP) to perform attribution-guided pruning of LLMs. While LRP has shown promise in structured pruning for vision models, we extend it to unstructured pruning in LLMs and demonstrate that it can substantially reduce model size with minimal performance loss. Our method is especially effective in extracting task-relevant subgraphs -- so-called ``circuits'' -- which can represent core functions (e.g., indirect object identification). Building on this, we introduce a technique for model correction, by selectively removing circuits responsible for spurious behaviors (e.g., toxic outputs). All in all, we gather these techniques as a uniform holistic framework and showcase its effectiveness and limitations through extensive experiments for compression, circuit discovery and model correction on Llama and OPT models, highlighting its potential for improving both model efficiency and safety. Our code is publicly available at https://github.com/erfanhatefi/SparC3.

[Arxiv](https://arxiv.org/abs/2506.13727)