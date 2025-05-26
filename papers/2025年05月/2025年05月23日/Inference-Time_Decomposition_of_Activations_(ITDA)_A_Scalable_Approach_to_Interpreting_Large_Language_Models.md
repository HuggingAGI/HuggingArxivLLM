# 推理时激活分解（ITDA）：一种用于解释大型语言模型的可扩展方法

发布时间：2025年05月23日

`LLM理论` `人工智能`

> Inference-Time Decomposition of Activations (ITDA): A Scalable Approach to Interpreting Large Language Models

# 摘要

> 稀疏自动编码器（SAEs）是将大型语言模型（LLM）激活分解为可解释潜在表示的流行方法。然而，由于其高昂的训练成本，大多数学术研究使用开源的 SAE，这些 SAE 仅适用于参数量不超过 270 亿的特定模型。此外，SAE 的潜在表示是从一组激活数据集中学习得到的，这意味着它们无法跨模型迁移。受相对表示相似性度量的启发，我们引入了推理时间激活分解（ITDA）模型，这是一种替代的激活分解方法。为了训练 ITDA，我们基于提示数据集贪婪地构建语言模型激活字典，选择那些在现有字典上匹配追踪效果最差的激活。与 SAE 相比，ITDAs 仅需 1% 的训练时间和 1% 的数据量。这使我们能够在单个消费级 GPU 上训练 Llama-3.1 70B 和 405B 的 ITDAs。ITDAs 在某些目标 LLM 上可达到与 SAE 相似的重建性能，但通常会带来性能损失。然而，ITDA 字典支持跨模型比较，且基于 ITDA 字典的简单 Jaccard 相似性指数优于现有的 CKA、SVCCA 以及相对表示相似性指标。ITDAs 为计算资源有限或需要跨模型比较的场景提供了一种经济的替代方案。代码可在 https://github.com/pleask/itda 获取。

> Sparse autoencoders (SAEs) are a popular method for decomposing Large Langage Models (LLM) activations into interpretable latents. However, due to their substantial training cost, most academic research uses open-source SAEs which are only available for a restricted set of models of up to 27B parameters. SAE latents are also learned from a dataset of activations, which means they do not transfer between models. Motivated by relative representation similarity measures, we introduce Inference-Time Decomposition of Activations (ITDA) models, an alternative method for decomposing language model activations. To train an ITDA, we greedily construct a dictionary of language model activations on a dataset of prompts, selecting those activations which were worst approximated by matching pursuit on the existing dictionary. ITDAs can be trained in just 1\% of the time required for SAEs, using 1\% of the data. This allowed us to train ITDAs on Llama-3.1 70B and 405B on a single consumer GPU. ITDAs can achieve similar reconstruction performance to SAEs on some target LLMs, but generally incur a performance penalty. However, ITDA dictionaries enable cross-model comparisons, and a simple Jaccard similarity index on ITDA dictionaries outperforms existing methods like CKA, SVCCA, and relative representation similarity metrics. ITDAs provide a cheap alternative to SAEs where computational resources are limited, or when cross model comparisons are necessary. Code available at https://github.com/pleask/itda.

[Arxiv](https://arxiv.org/abs/2505.17769)