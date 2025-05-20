# 探索针对大型语言模型的经济实惠、模型无关的解释生成方法

发布时间：2025年05月18日

`LLM理论` `人工智能` `机器学习`

> Towards Budget-Friendly Model-Agnostic Explanation Generation for Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在各领域广泛应用，解释其预测结果已成为重要课题。由于LLMs架构多样且部分模型闭源，模型不可知技术无需访问内部参数，展现出巨大潜力。然而，现有技术需频繁调用LLMs以获取足够样本，生成忠实解释，导致高昂成本。本文通过实证研究发现，通过采样预算友好的模型，可为大规模LLMs生成忠实解释。此外，此类代理解释在下游任务中表现优异。我们的分析为LLMs的模型不可知解释方法提供了新范式，通过整合预算友好型模型信息实现这一目标。

> With Large language models (LLMs) becoming increasingly prevalent in various applications, the need for interpreting their predictions has become a critical challenge. As LLMs vary in architecture and some are closed-sourced, model-agnostic techniques show great promise without requiring access to the model's internal parameters. However, existing model-agnostic techniques need to invoke LLMs many times to gain sufficient samples for generating faithful explanations, which leads to high economic costs. In this paper, we show that it is practical to generate faithful explanations for large-scale LLMs by sampling from some budget-friendly models through a series of empirical studies. Moreover, we show that such proxy explanations also perform well on downstream tasks. Our analysis provides a new paradigm of model-agnostic explanation methods for LLMs, by including information from budget-friendly models.

[Arxiv](https://arxiv.org/abs/2505.12509)