# Reward Model Interpretability via Optimal and Pessimal Tokens
利用最优与最劣标记，提升奖励模型的可解释性

发布时间：2025年06月08日

`LLM应用` `人工智能`

> Reward Model Interpretability via Optimal and Pessimal Tokens

# 摘要

> 奖励建模已成为将大型语言模型与人类价值观对齐的关键环节。尽管大量研究关注于利用奖励模型微调生成模型，但奖励模型本身——通过将提示-响应对转化为标量奖励直接编码人类价值判断——仍然相对研究较少。我们提出了一种通过全面分析奖励模型在整个词汇空间中的响应来提升奖励模型可解释性的新方法。通过考察不同奖励模型对价值观导向提示的所有可能单令牌响应的评分，我们发现了几个引人注目的现象：(i) 在相似目标上训练的模型之间存在显著差异，(ii) 模型在编码高分与低分令牌时存在系统性不对称，(iii) 对提示框架的显著敏感性，这种敏感性与人类认知偏见相呼应，以及(iv) 对更频繁令牌的过度重视。我们在十种近期开源奖励模型上展示了这些效果，这些模型参数数量和架构各不相同。我们的研究结果挑战了关于奖励模型互换性的假设，以及它们作为复杂且依赖上下文的人类价值观代理的适用性。我们发现这些模型可能对某些身份群体存在令人担忧的偏见，这些偏见可能是无害性训练的意外后果——这些偏差可能通过已部署到数百万用户的下游大型语言模型传播开来。

> Reward modeling has emerged as a crucial component in aligning large language models with human values. Significant attention has focused on using reward models as a means for fine-tuning generative models. However, the reward models themselves -- which directly encode human value judgments by turning prompt-response pairs into scalar rewards -- remain relatively understudied. We present a novel approach to reward model interpretability through exhaustive analysis of their responses across their entire vocabulary space. By examining how different reward models score every possible single-token response to value-laden prompts, we uncover several striking findings: (i) substantial heterogeneity between models trained on similar objectives, (ii) systematic asymmetries in how models encode high- vs low-scoring tokens, (iii) significant sensitivity to prompt framing that mirrors human cognitive biases, and (iv) overvaluation of more frequent tokens. We demonstrate these effects across ten recent open-source reward models of varying parameter counts and architectures. Our results challenge assumptions about the interchangeability of reward models, as well as their suitability as proxies of complex and context-dependent human values. We find that these models can encode concerning biases toward certain identity groups, which may emerge as unintended consequences of harmlessness training -- distortions that risk propagating through the downstream large language models now deployed to millions.

[Arxiv](https://arxiv.org/abs/2506.07326)