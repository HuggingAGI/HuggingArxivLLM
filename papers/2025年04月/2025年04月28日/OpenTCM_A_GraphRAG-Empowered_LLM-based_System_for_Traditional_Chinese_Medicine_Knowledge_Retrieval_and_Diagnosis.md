# OpenTCM：基于GraphRAG和大语言模型的中医药知识检索与诊断系统

发布时间：2025年04月28日

`RAG` `知识图谱`

> OpenTCM: A GraphRAG-Empowered LLM-based System for Traditional Chinese Medicine Knowledge Retrieval and Diagnosis

# 摘要

> 中医（TCM）作为古代医学智慧的宝库，在现代医疗领域依然发挥着重要作用。然而，由于中医文献的复杂性与广度，如何将其与现代人工智能技术相结合，实现现代化与广泛应用，成为亟待解决的挑战。这些挑战包括对古典中文文本的精准解读，以及对中医概念间复杂语义关系的建模。本文提出 OpenTCM 系统，通过结合中医知识图谱与基于图的检索增强生成（GraphRAG），为这一难题提供了创新解决方案。

首先，我们从中国医学经典数据库中精选了 68 本妇科著作，提取了超过 373 万个古典中文字符。这一过程得到了中医与妇科领域专家的鼎力支持。随后，借助定制提示与中文大型语言模型（如 DeepSeek 和 Kimi），我们构建了一个包含 48,000 多个实体及 152,000 多个关系的多关系知识图谱，确保了语义理解的高保真度。

最终，我们将 OpenTCM 系统与该知识图谱无缝集成，实现了无需模型微调的高保真成分知识检索与诊断问答功能。实验结果表明，我们的提示设计与模型选择显著提升了知识图谱的质量，达到了 98.55% 的精确度与 99.55% 的 F1 分数。在实际应用中，OpenTCM 在成分信息检索与诊断问答任务中分别获得了 4.5 和 3.8 的平均专家评分，超越了现有最优解决方案，为中医的现代化应用开辟了新的可能性。

> Traditional Chinese Medicine (TCM) represents a rich repository of ancient medical knowledge that continues to play an important role in modern healthcare. Due to the complexity and breadth of the TCM literature, the integration of AI technologies is critical for its modernization and broader accessibility. However, this integration poses considerable challenges, including the interpretation of obscure classical Chinese texts and the modeling of intricate semantic relationships among TCM concepts. In this paper, we develop OpenTCM, an LLM-based system that combines a domain-specific TCM knowledge graph and Graph-based Retrieval-Augmented Generation (GraphRAG). First, we extract more than 3.73 million classical Chinese characters from 68 gynecological books in the Chinese Medical Classics Database, with the help of TCM and gynecology experts. Second, we construct a comprehensive multi-relational knowledge graph comprising more than 48,000 entities and 152,000 interrelationships, using customized prompts and Chinese-oriented LLMs such as DeepSeek and Kimi to ensure high-fidelity semantic understanding. Last, we integrate OpenTCM with this knowledge graph, enabling high-fidelity ingredient knowledge retrieval and diagnostic question-answering without model fine-tuning. Experimental evaluations demonstrate that our prompt design and model selection significantly improve knowledge graph quality, achieving a precision of 98. 55% and an F1 score of 99. 55%. In addition, OpenTCM achieves mean expert scores of 4.5 in ingredient information retrieval and 3.8 in diagnostic question-answering tasks, outperforming state-of-the-art solutions in real-world TCM use cases.

[Arxiv](https://arxiv.org/abs/2504.20118)