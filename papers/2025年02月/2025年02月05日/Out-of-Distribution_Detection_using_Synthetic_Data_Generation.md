# 基于合成数据生成的分布外检测

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要讨论了利用大型语言模型（LLMs）的生成能力来生成高质量的合成OOD代理，以解决OOD检测中的挑战。该方法在多个文本分类任务和LLM开发与部署中的分类任务上进行了验证。因此，这篇论文属于LLM应用的范畴，因为它探讨了如何将LLMs应用于具体的任务和问题解决中。` `机器学习`

> Out-of-Distribution Detection using Synthetic Data Generation

# 摘要

> 区分分布内和分布外（OOD）输入是分类系统可靠部署的关键。然而，OOD数据通常难以获取，这给OOD检测带来了巨大挑战。本文提出了一种利用大型语言模型（LLMs）生成能力的方法，无需依赖外部OOD数据源，即可生成高质量的合成OOD代理。我们在毒性检测、情感分类等经典文本分类任务，以及LLM开发和部署中的分类任务（如RLHF奖励模型训练和未对齐生成检测）上验证了该方法的有效性。在九个InD-OOD数据集对和多种模型规模上的实验表明，该方法显著降低了误报率（某些情况下甚至为零），同时在分布内任务上保持了高准确率，远超基线方法。

> Distinguishing in- and out-of-distribution (OOD) inputs is crucial for reliable deployment of classification systems. However, OOD data is typically unavailable or difficult to collect, posing a significant challenge for accurate OOD detection. In this work, we present a method that harnesses the generative capabilities of Large Language Models (LLMs) to create high-quality synthetic OOD proxies, eliminating the dependency on any external OOD data source. We study the efficacy of our method on classical text classification tasks such as toxicity detection and sentiment classification as well as classification tasks arising in LLM development and deployment, such as training a reward model for RLHF and detecting misaligned generations. Extensive experiments on nine InD-OOD dataset pairs and various model sizes show that our approach dramatically lowers false positive rates (achieving a perfect zero in some cases) while maintaining high accuracy on in-distribution tasks, outperforming baseline methods by a significant margin.

[Arxiv](https://arxiv.org/abs/2502.03323)