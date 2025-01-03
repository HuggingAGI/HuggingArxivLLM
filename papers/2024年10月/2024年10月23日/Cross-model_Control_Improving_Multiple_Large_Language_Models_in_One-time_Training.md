# 跨模型控制：一次性训练优化多个大型语言模型

发布时间：2024年10月23日

`LLM理论

理由：这篇论文主要讨论了如何通过跨模型控制（CMC）来优化多个大型语言模型（LLMs）的微调过程，并提出了一个轻量级的小型语言模型来调整LLMs的输出。论文的核心内容涉及LLMs的理论优化方法，特别是如何通过小型模型来影响和调整LLMs的行为。因此，这篇论文更适合归类为LLM理论。` `机器学习`

> Cross-model Control: Improving Multiple Large Language Models in One-time Training

# 摘要

> 随着不同参数规模和词汇量的大型语言模型（LLMs）数量不断增加，虽然它们展现出强大的性能，但也面临着一系列优化需求，如遵循指令或避免输出敏感信息。然而，如何将一个模型的微调成果复用到其他模型以降低训练成本，仍是一个难题。为此，我们提出了跨模型控制（CMC），通过一个轻量级的小型语言模型，在一次训练中同时优化多个LLMs。我们发现，不同模型在微调前后的logit偏移高度相似，基于这一发现，我们引入了一个极简参数的小型语言模型。通过与冻结的模板LLM联合训练，该小型模型能够调整LLMs输出的logits。为了使其适用于不同词汇量的模型，我们设计了一种名为PM-MinED的token映射策略。我们在指令微调和遗忘任务上进行了大量实验，验证了CMC的有效性。代码已开源：https://github.com/wujwyi/CMC。

> The number of large language models (LLMs) with varying parameter scales and vocabularies is increasing. While they deliver powerful performance, they also face a set of common optimization needs to meet specific requirements or standards, such as instruction following or avoiding the output of sensitive information from the real world. However, how to reuse the fine-tuning outcomes of one model to other models to reduce training costs remains a challenge. To bridge this gap, we introduce Cross-model Control (CMC), a method that improves multiple LLMs in one-time training with a portable tiny language model. Specifically, we have observed that the logit shift before and after fine-tuning is remarkably similar across different models. Based on this insight, we incorporate a tiny language model with a minimal number of parameters. By training alongside a frozen template LLM, the tiny model gains the capability to alter the logits output by the LLMs. To make this tiny language model applicable to models with different vocabularies, we propose a novel token mapping strategy named PM-MinED. We have conducted extensive experiments on instruction tuning and unlearning tasks, demonstrating the effectiveness of CMC. Our code is available at https://github.com/wujwyi/CMC.

[Arxiv](https://arxiv.org/abs/2410.17599)