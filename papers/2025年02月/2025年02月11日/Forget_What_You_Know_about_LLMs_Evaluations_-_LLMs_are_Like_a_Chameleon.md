# 关于 LLM 评估，忘掉你所知的一切——它们就像变色龙一样。

发布时间：2025年02月11日

`LLM理论` `机器学习`

> Forget What You Know about LLMs Evaluations - LLMs are Like a Chameleon

# 摘要

> 大型语言模型（LLMs）在公共基准测试中表现优异，但这些高分可能掩盖了它们对数据集特定表面线索的过度依赖，而非真正理解语言。我们推出Chameleon基准过拟合检测器（C-BOD），一个元评估框架，通过参数化变换系统性地扭曲基准提示，并检测LLMs的过拟合情况。通过在保持输入语义内容和标签的同时重新表述输入，C-BOD揭示了模型性能是否由记忆模式驱动。在使用26个领先的LLMs评估MMLU基准时，我们的方法在适度扰动下显示出平均性能下降2.15%，其中20个模型表现出统计上显著的差异。值得注意的是，基线准确率更高的模型在扰动下表现出更大的性能差异，而较大的LLMs往往对重新表述更敏感，表明这两种情况都可能过度依赖固定提示模式。相比之下，Llama家族和基线准确率较低的模型显示出微不足道的性能下降，表明它们对浅层线索的依赖减少。此外，C-BOD的无数据集和无模型偏见设计使其易于集成到训练管道中，以促进更强大的语言理解。我们的发现挑战了社区仅关注排行榜分数的做法，强调在LLM评估中优先考虑弹性和泛化能力。

> Large language models (LLMs) often appear to excel on public benchmarks, but these high scores may mask an overreliance on dataset-specific surface cues rather than true language understanding. We introduce the Chameleon Benchmark Overfit Detector (C-BOD), a meta-evaluation framework that systematically distorts benchmark prompts via a parametric transformation and detects overfitting of LLMs. By rephrasing inputs while preserving their semantic content and labels, C-BOD exposes whether a model's performance is driven by memorized patterns. Evaluated on the MMLU benchmark using 26 leading LLMs, our method reveals an average performance degradation of 2.15% under modest perturbations, with 20 out of 26 models exhibiting statistically significant differences. Notably, models with higher baseline accuracy exhibit larger performance differences under perturbation, and larger LLMs tend to be more sensitive to rephrasings indicating that both cases may overrely on fixed prompt patterns. In contrast, the Llama family and models with lower baseline accuracy show insignificant degradation, suggesting reduced dependency on superficial cues. Moreover, C-BOD's dataset- and model-agnostic design allows easy integration into training pipelines to promote more robust language understanding. Our findings challenge the community to look beyond leaderboard scores and prioritize resilience and generalization in LLM evaluation.

[Arxiv](https://arxiv.org/abs/2502.07445)