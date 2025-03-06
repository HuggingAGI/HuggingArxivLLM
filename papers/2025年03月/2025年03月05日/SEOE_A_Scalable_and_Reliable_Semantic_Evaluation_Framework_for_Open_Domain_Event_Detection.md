# SEOE：面向开放领域事件检测的可扩展、可靠的语义评估框架

发布时间：2025年03月05日

`LLM应用` `信息抽取`

> SEOE: A Scalable and Reliable Semantic Evaluation Framework for Open Domain Event Detection

# 摘要

> 开放领域事件检测（ODED）的自动评估是一项极具挑战性的任务，因为其输出标签种类繁多且来自各种领域。现有评估方法通常基于有限标签和领域覆盖范围的基准，使用token级别匹配规则进行评估。然而，这种框架存在两大问题：(1) 有限基准缺乏真实世界代表性，难以准确反映方法性能；(2) 传统指标无法捕捉语义相似性。

为解决这些问题，我们提出了开放领域事件检测语义级评估框架（SEOE）。该框架通过构建更具代表性的评估基准和引入语义评估指标，实现更可靠的评估。具体来说，我们构建了一个包含7个领域564种事件类型的可扩展基准，并采用成本效益高的补充标注策略确保其代表性。同时，我们利用大型语言模型（LLMs）作为自动评估代理，计算语义F1分数，并通过细粒度语义相似标签定义增强评估可靠性。

实验结果验证了基准的代表性和语义评估指标的可靠性。通过对现有ODED方法的全面评估和预测错误模式的分析，我们揭示了多个有价值的见解。


> Automatic evaluation for Open Domain Event Detection (ODED) is a highly challenging task, because ODED is characterized by a vast diversity of un-constrained output labels from various domains. Nearly all existing evaluation methods for ODED usually first construct evaluation benchmarks with limited labels and domain coverage, and then evaluate ODED methods using metrics based on token-level label matching rules. However, this kind of evaluation framework faces two issues: (1) The limited evaluation benchmarks lack representatives of the real world, making it difficult to accurately reflect the performance of various ODED methods in real-world scenarios; (2) Evaluation metrics based on token-level matching rules fail to capture semantic similarity between predictions and golden labels. To address these two problems above, we propose a scalable and reliable Semantic-level Evaluation framework for Open domain Event detection (SEOE) by constructing a more representative evaluation benchmark and introducing a semantic evaluation metric. Specifically, our proposed framework first constructs a scalable evaluation benchmark that currently includes 564 event types covering 7 major domains, with a cost-effective supplementary annotation strategy to ensure the benchmark's representativeness. The strategy also allows for the supplement of new event types and domains in the future. Then, the proposed SEOE leverages large language models (LLMs) as automatic evaluation agents to compute a semantic F1-score, incorporating fine-grained definitions of semantically similar labels to enhance the reliability of the evaluation. Extensive experiments validate the representatives of the benchmark and the reliability of the semantic evaluation metric. Existing ODED methods are thoroughly evaluated, and the error patterns of predictions are analyzed, revealing several insightful findings.

[Arxiv](https://arxiv.org/abs/2503.03303)