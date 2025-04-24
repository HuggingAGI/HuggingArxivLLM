# 大型语言模型的多跳推理评测：以化学为中心的案例研究

发布时间：2025年04月23日

`LLM应用` `知识图谱`

> Evaluating Multi-Hop Reasoning in Large Language Models: A Chemistry-Centric Case Study

# 摘要

> 本研究推出了一项全新基准测试，结合精选数据集与标准化评估流程，专注于评估大型语言模型在化学领域的组合推理能力。我们开发并验证了一个全自动化的专业管道，经领域专家认证，为研究提供了有力支持。研究方法融合 OpenAI 推理模型与命名实体识别（NER）系统，从最新文献中提取化学实体，并借助外部知识库构建全面知识图谱。通过跨图谱生成多跳问题，我们全面评估了 LLM 在有无上下文增强环境下的表现。实验结果表明，即便是当前最先进的模型，面对多跳组合推理仍面临严峻挑战。研究凸显了为 LLM 增强文档检索的重要性，这一举措对提升模型性能具有显著推动作用。然而，即便在完美检索准确性与完整上下文支持下，推理错误依然存在，这进一步印证了组合推理的复杂性。本研究不仅揭示了现有 LLM 的性能基准与局限性，更推出了一种创新的数据生成管道，能够在跨领域场景下生成具有挑战性的推理数据集。这项工作全面深化了我们对计算语言学领域推理机制的理解。

> In this study, we introduced a new benchmark consisting of a curated dataset and a defined evaluation process to assess the compositional reasoning capabilities of large language models within the chemistry domain. We designed and validated a fully automated pipeline, verified by subject matter experts, to facilitate this task. Our approach integrates OpenAI reasoning models with named entity recognition (NER) systems to extract chemical entities from recent literature, which are then augmented with external knowledge bases to form a comprehensive knowledge graph. By generating multi-hop questions across these graphs, we assess LLM performance in both context-augmented and non-context augmented settings. Our experiments reveal that even state-of-the-art models face significant challenges in multi-hop compositional reasoning. The results reflect the importance of augmenting LLMs with document retrieval, which can have a substantial impact on improving their performance. However, even perfect retrieval accuracy with full context does not eliminate reasoning errors, underscoring the complexity of compositional reasoning. This work not only benchmarks and highlights the limitations of current LLMs but also presents a novel data generation pipeline capable of producing challenging reasoning datasets across various domains. Overall, this research advances our understanding of reasoning in computational linguistics.

[Arxiv](https://arxiv.org/abs/2504.16414)