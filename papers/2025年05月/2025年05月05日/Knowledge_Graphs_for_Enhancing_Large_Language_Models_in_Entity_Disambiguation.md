# # 知识图谱助力提升大型语言模型的实体消歧效果

发布时间：2025年05月05日

`LLM应用` `知识图谱`

> Knowledge Graphs for Enhancing Large Language Models in Entity Disambiguation

# 摘要

> 大型语言模型（LLMs）的最新进展使其成为解决自然语言处理任务的突出方案。它们无需训练特定任务模型，即可通过零样本或少样本方式处理问题。然而，LLMs也面临幻觉、特定领域知识过时或缺失等挑战。重新训练模型解决这些问题耗时且昂贵。为应对这些挑战，我们提出使用知识图谱（KGs）作为结构化的外部信息源来增强LLMs。本研究中，我们利用KGs来提升零样本实体消歧（ED）任务的效果。具体而言，我们借助KG中实体类别的层次化表示逐步缩小候选范围，并通过实体描述丰富输入提示，从而补充事实知识。实验结果表明，该方法不仅优于未增强和仅基于描述增强的LLMs，还比任务特定模型更具适应性。此外，我们还进行了错误分析，并探讨了KG的语义表达能力对ED性能的影响。

> Recent advances in Large Language Models (LLMs) have positioned them as a prominent solution for Natural Language Processing tasks. Notably, they can approach these problems in a zero or few-shot manner, thereby eliminating the need for training or fine-tuning task-specific models. However, LLMs face some challenges, including hallucination and the presence of outdated knowledge or missing information from specific domains in the training data. These problems cannot be easily solved by retraining the models with new data as it is a time-consuming and expensive process. To mitigate these issues, Knowledge Graphs (KGs) have been proposed as a structured external source of information to enrich LLMs. With this idea, in this work we use KGs to enhance LLMs for zero-shot Entity Disambiguation (ED). For that purpose, we leverage the hierarchical representation of the entities' classes in a KG to gradually prune the candidate space as well as the entities' descriptions to enrich the input prompt with additional factual knowledge. Our evaluation on popular ED datasets shows that the proposed method outperforms non-enhanced and description-only enhanced LLMs, and has a higher degree of adaptability than task-specific models. Furthermore, we conduct an error analysis and discuss the impact of the leveraged KG's semantic expressivity on the ED performance.

[Arxiv](https://arxiv.org/abs/2505.02737)