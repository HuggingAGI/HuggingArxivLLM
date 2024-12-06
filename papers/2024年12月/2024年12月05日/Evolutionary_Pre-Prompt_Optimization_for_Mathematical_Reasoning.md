# 用于数学推理的进化式预提示优化

发布时间：2024年12月05日

`LLM应用` `人工智能`

> Evolutionary Pre-Prompt Optimization for Mathematical Reasoning

# 摘要

> 近期的研究进展表明，大型语言模型（LLMs）在获得少量特定任务的示例后，能够展现出非凡的能力，甚至能应对复杂的推理任务。尤其是少样本学习与思维链（CoT）方法相结合，对引导模型得出更具逻辑性的结论至关重要。本文探究了为设计有效的 CoT 预提示而进行的示例选择优化，指出优化算法的选择（通常倾向于如进化计算之类的基于比较的方法）能显著提升效果和可行性。具体来说，由于有限的探索性和过度拟合的优化，进化预提示优化（EPPO）相比朴素的少样本方法，在 GSM8k 和 MathQA 等基准数据集上的精确匹配分数上提升超过 10 个绝对点。这些成果在各种情境下都保持一致，并且与自我一致性（SC）集成时会进一步增强。

> Recent advancements have highlighted that large language models (LLMs), when given a small set of task-specific examples, demonstrate remarkable proficiency, a capability that extends to complex reasoning tasks. In particular, the combination of few-shot learning with the chain-of-thought (CoT) approach has been pivotal in steering models towards more logically consistent conclusions. This paper explores the optimization of example selection for designing effective CoT pre-prompts and shows that the choice of the optimization algorithm, typically in favor of comparison-based methods such as evolutionary computation, significantly enhances efficacy and feasibility. Specifically, thanks to a limited exploitative and overfitted optimization, Evolutionary Pre-Prompt Optimization (EPPO) brings an improvement over the naive few-shot approach exceeding 10 absolute points in exact match scores on benchmark datasets such as GSM8k and MathQA. These gains are consistent across various contexts and are further amplified when integrated with self-consistency (SC)

[Arxiv](https://arxiv.org/abs/2412.04291)