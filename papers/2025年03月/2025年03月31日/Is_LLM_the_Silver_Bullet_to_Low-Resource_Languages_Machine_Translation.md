# # LLM 是否是低资源语言机器翻译的终极解决方案？

发布时间：2025年03月31日

`LLM应用`

> Is LLM the Silver Bullet to Low-Resource Languages Machine Translation?

# 摘要

> 低资源语言 (LRLs) 在自然语言处理领域面临诸多挑战，主要由于其语言资源匮乏且在标准数据集中代表性不足。尽管大型语言模型 (LLMs) 和神经机器翻译 (NMT) 的最新进展显著提升了高资源语言的翻译能力，但 LRLs 的性能差距依然显著，尤其在隐私敏感和资源受限的场景中影响深远。本文通过 FLORES-200 等基准测试系统评估了当前 LLMs 在 200 种语言上的局限性。我们还探索了新闻文章和双语词典等替代数据来源，并展示了如何通过知识蒸馏从大型预训练模型中显著提升小型 LRL 翻译质量。此外，我们深入研究了多种微调策略，发现增量增强能有效缩小小型 LLMs 的性能差距。

> Low-Resource Languages (LRLs) present significant challenges in natural language processing due to their limited linguistic resources and underrepresentation in standard datasets. While recent advancements in Large Language Models (LLMs) and Neural Machine Translation (NMT) have substantially improved translation capabilities for high-resource languages, performance disparities persist for LRLs, particularly impacting privacy-sensitive and resource-constrained scenarios. This paper systematically evaluates the limitations of current LLMs across 200 languages using benchmarks such as FLORES-200. We also explore alternative data sources, including news articles and bilingual dictionaries, and demonstrate how knowledge distillation from large pre-trained models can significantly improve smaller LRL translations. Additionally, we investigate various fine-tuning strategies, revealing that incremental enhancements markedly reduce performance gaps on smaller LLMs.

[Arxiv](https://arxiv.org/abs/2503.24102)