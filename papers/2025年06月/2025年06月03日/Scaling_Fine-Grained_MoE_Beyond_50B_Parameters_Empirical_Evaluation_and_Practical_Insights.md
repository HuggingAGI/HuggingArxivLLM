# 探索细粒度专家混合模型的扩展之路：超越500亿参数的实证评估与实用见解

发布时间：2025年06月03日

`LLM理论` `人工智能` `机器学习`

> Scaling Fine-Grained MoE Beyond 50B Parameters: Empirical Evaluation and Practical Insights

# 摘要

> 专家混合（MoE）架构已成为大型语言模型（LLMs）高效扩展的关键。采用更多但更小规模专家的细粒度MoE方法，在提升模型收敛性和质量方面展现出潜力。本研究提出了一套训练配方，并对细粒度MoE进行了全面的实证评估，直接对比其与标准MoE配置的扩展特性，涵盖总参数量高达560亿（170亿活跃参数）的模型。我们探讨了不同设置下的收敛速度、模型在下游基准测试中的性能以及实际训练考量。总体而言，在最大规模下，细粒度MoE在一组下游基准测试中实现了更低的验证损失和更高的准确率。这项研究为未来大规模模型开发中利用细粒度MoE提供了实证依据和实用见解。

> Mixture of Experts (MoE) architectures have emerged as pivotal for scaling Large Language Models (LLMs) efficiently. Fine-grained MoE approaches - utilizing more numerous, smaller experts - have demonstrated potential in improving model convergence and quality. This work proposes a set of training recipes and provides a comprehensive empirical evaluation of fine-grained MoE, directly comparing its scaling properties against standard MoE configurations for models with up to 56B total (17B active) parameters. We investigate convergence speed, model performance on downstream benchmarks, and practical training considerations across various setups. Overall, at the largest scale we show that fine-grained MoE achieves better validation loss and higher accuracy across a set of downstream benchmarks. This study offers empirical grounding and practical insights for leveraging fine-grained MoE in the development of future large-scale models.

[Arxiv](https://arxiv.org/abs/2506.02890)