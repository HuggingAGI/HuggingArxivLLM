# # SoS1：O1 和 R1 类似推理的 LLM 其实是平方和求解器

发布时间：2025年02月27日

`LLM应用`

> SoS1: O1 and R1-Like Reasoning LLMs are Sum-of-Square Solvers

# 摘要

> 大型语言模型（LLMs）在多样化任务中已展现出接近人类水平的能力，但其在严谨数学推理方面的表现仍有待突破。本研究聚焦于一个基础且具挑战性的问题：判断多变量多项式的非负性。这一问题与希尔伯特第十七问题紧密相关，在全局优化和多个应用领域中具有重要意义。我们精心打造了SoS-1K数据集，包含约1,000个多项式，并基于五个逐步提升难度的标准设计了专家级推理指令。实验结果表明，未经结构化指导的模型表现仅略优于随机猜测（50%），而高质量的推理指令则将准确率显著提升至81%。值得注意的是，我们的70亿参数模型SoS-7B仅需4小时微调，便在准确率上超越了6710亿参数的DeepSeek-V3和GPT-4o-mini，同时计算效率分别提升了1.8%和5%。本研究充分展现了LLMs在突破数学推理边界和解决NP难问题方面的巨大潜力。

> Large Language Models (LLMs) have achieved human-level proficiency across diverse tasks, but their ability to perform rigorous mathematical problem solving remains an open challenge. In this work, we investigate a fundamental yet computationally intractable problem: determining whether a given multivariate polynomial is nonnegative. This problem, closely related to Hilbert's Seventeenth Problem, plays a crucial role in global polynomial optimization and has applications in various fields. First, we introduce SoS-1K, a meticulously curated dataset of approximately 1,000 polynomials, along with expert-designed reasoning instructions based on five progressively challenging criteria. Evaluating multiple state-of-the-art LLMs, we find that without structured guidance, all models perform only slightly above the random guess baseline 50%. However, high-quality reasoning instructions significantly improve accuracy, boosting performance up to 81%. Furthermore, our 7B model, SoS-7B, fine-tuned on SoS-1K for just 4 hours, outperforms the 671B DeepSeek-V3 and GPT-4o-mini in accuracy while only requiring 1.8% and 5% of the computation time needed for letters, respectively. Our findings highlight the potential of LLMs to push the boundaries of mathematical reasoning and tackle NP-hard problems.

[Arxiv](https://arxiv.org/abs/2502.20545)