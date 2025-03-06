# # 前言
前沿LLM能否胜任生物医学文本挖掘中的标注工作？分析挑战与探索解决方案

发布时间：2025年03月05日

`LLM应用` `生物医学` `文本挖掘`

> Can Frontier LLMs Replace Annotators in Biomedical Text Mining? Analyzing Challenges and Exploring Solutions

# 摘要

> 大型语言模型（LLMs）无需监督数据，即可通过上下文学习完成多种自然语言处理（NLP）任务。然而，在生物医学文本挖掘领域，LLMs的表现仍有待提升。通过对现有评估中的失败模式进行分析，我们总结出LLMs在生物医学语料库中面临的主要挑战：（1）难以从监督数据中提取数据集特有的隐含细节；（2）判别任务的格式要求限制了LLMs的推理能力，尤其对计算资源有限的模型影响更大；（3）难以遵循标注指南并匹配精确模式，这使其难以准确理解复杂的标注需求，而这对于生物医学标注至关重要。针对这些挑战，我们开发了专门的提示工程技巧，并设计了一个能从标注指南中动态提取指令的流水线。研究发现，前沿LLMs在几乎不依赖人工标注数据且无需微调的情况下，性能可与基于BERT的最先进模型相媲美。此外，通过在闭源LLM上进行模型蒸馏，我们证明了仅使用LLMs标注的合成数据训练的BERT模型也能达到实用水平。基于这些发现，我们进一步探讨了在生物医学文本挖掘中，以LLMs部分取代人工标注的可行性。

> Large language models (LLMs) can perform various natural language processing (NLP) tasks through in-context learning without relying on supervised data. However, multiple previous studies have reported suboptimal performance of LLMs in biological text mining. By analyzing failure patterns in these evaluations, we identified three primary challenges for LLMs in biomedical corpora: (1) LLMs fail to learn implicit dataset-specific nuances from supervised data, (2) The common formatting requirements of discriminative tasks limit the reasoning capabilities of LLMs particularly for LLMs that lack test-time compute, and (3) LLMs struggle to adhere to annotation guidelines and match exact schemas, which hinders their ability to understand detailed annotation requirements which is essential in biomedical annotation workflow. To address these challenges, we experimented with prompt engineering techniques targeted to the above issues, and developed a pipeline that dynamically extracts instructions from annotation guidelines. Our findings show that frontier LLMs can approach or surpass the performance of state-of-the-art (SOTA) BERT-based models with minimal reliance on manually annotated data and without fine-tuning. Furthermore, we performed model distillation on a closed-source LLM, demonstrating that a BERT model trained exclusively on synthetic data annotated by LLMs can also achieve a practical performance. Based on these results, we explored the feasibility of partially replacing manual annotation with LLMs in production scenarios for biomedical text mining.

[Arxiv](https://arxiv.org/abs/2503.03261)