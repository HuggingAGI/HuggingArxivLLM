# SimpleQA Verified：衡量参数化知识的可靠事实性基准

发布时间：2025年09月09日

`LLM应用` `基础理论`

> SimpleQA Verified: A Reliable Factuality Benchmark to Measure Parametric Knowledge

# 摘要

> 我们推出SimpleQA Verified——一个基于OpenAI SimpleQA构建的1000提示基准测试集，专门用于评估大型语言模型（LLM）的短文本事实性表现。该基准测试针对OpenAI原版本的核心缺陷进行了改进，例如标签质量差、主题失衡和问题重复等问题。SimpleQA Verified通过严格的多阶段过滤流程构建而成，包括去重、主题平衡和来源核验，以此生成更可靠且更具挑战性的评估集，同时还优化了自动评分器的提示设计。在这一新基准测试中，Gemini 2.5 Pro以55.6的F1分数刷新了当前最佳性能，超越了包括GPT-5在内的其他前沿模型。这项研究为学术界提供了一个更高精度的工具，助力追踪参数化模型在事实性方面的真实进展，并有效减少幻觉现象。相关基准数据集、评估代码及排行榜已开放获取：https://www.kaggle.com/benchmarks/deepmind/simpleqa-verified。

> We introduce SimpleQA Verified, a 1,000-prompt benchmark for evaluating Large Language Model (LLM) short-form factuality based on OpenAI's SimpleQA. It addresses critical limitations in OpenAI's benchmark, including noisy and incorrect labels, topical biases, and question redundancy. SimpleQA Verified was created through a rigorous multi-stage filtering process involving de-duplication, topic balancing, and source reconciliation to produce a more reliable and challenging evaluation set, alongside improvements in the autorater prompt. On this new benchmark, Gemini 2.5 Pro achieves a state-of-the-art F1-score of 55.6, outperforming other frontier models, including GPT-5. This work provides the research community with a higher-fidelity tool to track genuine progress in parametric model factuality and to mitigate hallucinations. The benchmark dataset, evaluation code, and leaderboard are available at: https://www.kaggle.com/benchmarks/deepmind/simpleqa-verified.

[Arxiv](https://arxiv.org/abs/2509.07968)