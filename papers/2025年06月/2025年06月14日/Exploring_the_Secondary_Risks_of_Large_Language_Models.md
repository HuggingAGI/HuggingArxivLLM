# # 探索大型语言模型的次生风险

发布时间：2025年06月14日

`LLM理论` `模型安全` `评估框架`

> Exploring the Secondary Risks of Large Language Models

# 摘要

> 随着大型语言模型 (LLMs) 在关键应用和社会功能中的深度整合，确保其安全性和对齐性已成为重大挑战。以往研究主要关注越狱攻击，但对良性交互中悄然出现的非对抗性故障关注较少。我们提出次级风险 (secondary risks)，一类由良性提示引发的有害或误导性行为定义的新失败模式。这些风险源于模型的不完美泛化，常能规避标准安全机制。为实现系统性评估，我们引入冗长响应 (verbose response) 和推测性建议 (speculative advice) 两个风险原语，以捕捉核心失败模式。基于此，我们提出 SecLens，一个黑盒多目标搜索框架，通过优化任务相关性、风险激活和语言合理性，高效诱发次级风险行为。为支持可重复评估，我们发布 SecRiskBench 基准数据集，包含覆盖八类现实风险的 650 个提示。对 16 个流行模型的广泛评估表明，次级风险普遍且跨模型迁移，强调了改进安全机制以应对现实部署中良性但有害行为的迫切需求。

> Ensuring the safety and alignment of Large Language Models is a significant challenge with their growing integration into critical applications and societal functions. While prior research has primarily focused on jailbreak attacks, less attention has been given to non-adversarial failures that subtly emerge during benign interactions. We introduce secondary risks a novel class of failure modes marked by harmful or misleading behaviors during benign prompts. Unlike adversarial attacks, these risks stem from imperfect generalization and often evade standard safety mechanisms. To enable systematic evaluation, we introduce two risk primitives verbose response and speculative advice that capture the core failure patterns. Building on these definitions, we propose SecLens, a black-box, multi-objective search framework that efficiently elicits secondary risk behaviors by optimizing task relevance, risk activation, and linguistic plausibility. To support reproducible evaluation, we release SecRiskBench, a benchmark dataset of 650 prompts covering eight diverse real-world risk categories. Experimental results from extensive evaluations on 16 popular models demonstrate that secondary risks are widespread, transferable across models, and modality independent, emphasizing the urgent need for enhanced safety mechanisms to address benign yet harmful LLM behaviors in real-world deployments.

[Arxiv](https://arxiv.org/abs/2506.12382)