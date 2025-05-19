# 构建和平报告的自动化态势感知框架：基于RAG的方法

发布时间：2025年05月14日

`RAG` `人道主义`

> Towards Automated Situation Awareness: A RAG-Based Framework for Peacebuilding Reports

# 摘要

> 及时准确的情况感知对人道主义响应、冲突监测和早期预警至关重要。然而，传统的人工分析海量异质数据源往往导致延迟，影响干预效果。本文提出了一种动态检索增强生成（RAG）系统，通过整合新闻、冲突数据库和经济指标等多源实时数据，自动生成情况感知报告。系统根据需求构建特定查询的知识库，确保及时、精准的见解。

为确保报告质量，我们设计了三级评估框架：第一级运用NLP指标评估连贯性和准确性；第二级由专家验证报告的相关性和完整性；第三级借助LLM进行深度评估，确保结果的鲁棒性。实测表明，该系统能高效生成高质量报告，减轻人工负担，加速决策。我们已通过GitHub公开代码和工具，助力研究和实践。

> Timely and accurate situation awareness is vital for decision-making in humanitarian response, conflict monitoring, and early warning and early action. However, the manual analysis of vast and heterogeneous data sources often results in delays, limiting the effectiveness of interventions. This paper introduces a dynamic Retrieval-Augmented Generation (RAG) system that autonomously generates situation awareness reports by integrating real-time data from diverse sources, including news articles, conflict event databases, and economic indicators. Our system constructs query-specific knowledge bases on demand, ensuring timely, relevant, and accurate insights.
  To ensure the quality of generated reports, we propose a three-level evaluation framework that combines semantic similarity metrics, factual consistency checks, and expert feedback. The first level employs automated NLP metrics to assess coherence and factual accuracy. The second level involves human expert evaluation to verify the relevance and completeness of the reports. The third level utilizes LLM-as-a-Judge, where large language models provide an additional layer of assessment to ensure robustness. The system is tested across multiple real-world scenarios, demonstrating its effectiveness in producing coherent, insightful, and actionable reports. By automating report generation, our approach reduces the burden on human analysts and accelerates decision-making processes. To promote reproducibility and further research, we openly share our code and evaluation tools with the community via GitHub.

[Arxiv](https://arxiv.org/abs/2505.10586)