# 大型语言模型在可控多属性多目标分子优化中的应用

发布时间：2025年05月29日

`LLM应用

理由：这篇论文专注于将指令微调的大型语言模型应用于分子优化任务，特别是在药物设计中的多属性优化。它展示了LLM在特定实际应用中的有效性，属于LLM应用类别。` `药物设计` `分子优化`

> Large Language Models for Controllable Multi-property Multi-objective Molecule Optimization

# 摘要

> 在药物设计的实际应用中，分子优化需要在保持已有达标特性的基础上，精准提升多个分子特性至药理学意义水平。然而，现有计算方法和指令微调的LLMs未能有效捕捉这种细致的、特定属性优化目标，限制了其实际应用价值。为解决这一难题，我们推出了C-MuMOInstruct——首个专注于多属性优化、具备明确属性特定目标的指令微调数据集。基于此数据集，我们开发了GeLLMO-Cs系列指令微调LLMs，能够实现精准的属性特定优化。在涵盖5个在分布和5个分布外任务的实验中，GeLLMO-Cs表现显著优于现有强基线模型，成功提升幅度高达126%。尤为值得一提的是，GeLLMO-Cs在新型优化任务和未见指令上展现了卓越的零样本泛化能力。这一成果为构建支持现实场景中多样化、特定属性优化的基础LLM奠定了重要基础。C-MuMOInstruct数据集和代码已开源，可通过https://github.com/ninglab/GeLLMO-C获取。

> In real-world drug design, molecule optimization requires selectively improving multiple molecular properties up to pharmaceutically relevant levels, while maintaining others that already meet such criteria. However, existing computational approaches and instruction-tuned LLMs fail to capture such nuanced property-specific objectives, limiting their practical applicability. To address this, we introduce C-MuMOInstruct, the first instruction-tuning dataset focused on multi-property optimization with explicit, property-specific objectives. Leveraging C-MuMOInstruct, we develop GeLLMO-Cs, a series of instruction-tuned LLMs that can perform targeted property-specific optimization. Our experiments across 5 in-distribution and 5 out-of-distribution tasks show that GeLLMO-Cs consistently outperform strong baselines, achieving up to 126% higher success rate. Notably, GeLLMO-Cs exhibit impressive 0-shot generalization to novel optimization tasks and unseen instructions. This offers a step toward a foundational LLM to support realistic, diverse optimizations with property-specific objectives. C-MuMOInstruct and code are accessible through https://github.com/ninglab/GeLLMO-C.

[Arxiv](https://arxiv.org/abs/2505.23987)