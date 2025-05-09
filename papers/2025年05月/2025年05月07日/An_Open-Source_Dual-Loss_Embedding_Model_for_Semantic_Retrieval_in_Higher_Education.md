# 面向高等教育的开源双损失嵌入模型，用于语义检索

发布时间：2025年05月07日

`LLM应用

理由：这篇论文讨论了大型语言模型在多语言嵌入反转攻击中的安全性问题，属于LLM在实际应用中的安全性和潜在风险，因此归类为LLM应用。` `知识图谱`

> An Open-Source Dual-Loss Embedding Model for Semantic Retrieval in Higher Education

# 摘要

> <翻译失败>

> Recent advances in AI have catalyzed the adoption of intelligent educational tools, yet many semantic retrieval systems remain ill-suited to the unique linguistic and structural characteristics of academic content. This study presents two open-source embedding models fine-tuned for educational question answering, particularly in the context of course syllabi. A synthetic dataset of 3,197 sentence pairs, spanning synonymous terminology, paraphrased questions, and implicit-explicit mappings, was constructed through a combination of manual curation and large language model (LLM)-assisted generation. Two training strategies were evaluated: (1) a baseline model fine-tuned using MultipleNegativesRankingLoss (MNRL), and (2) a dual-loss model that combines MNRL with CosineSimilarityLoss to improve both semantic ranking and similarity calibration. Evaluations were conducted on 28 university course syllabi using a fixed set of natural language questions categorized into course, faculty, and teaching assistant information. Results demonstrate that both fine-tuned models outperform strong open-source baselines, including all-MiniLM-L6-v2 and multi-qa-MiniLM-L6-cos-v1, and that the dual-loss model narrows the performance gap with high-performing proprietary embeddings such as OpenAI's text-embedding-3 series. This work contributes reusable, domain-aligned embedding models and provides a replicable framework for educational semantic retrieval, supporting downstream applications such as academic chatbots, retrieval-augmented generation (RAG) systems, and learning management system (LMS) integrations.

[Arxiv](https://arxiv.org/abs/2505.04916)