# KARPA：一种无需训练就能将知识图谱用作大型语言模型推理路径聚合参考的方法

发布时间：2024年12月30日

`LLM应用` `知识图谱` `问答系统`

> KARPA: A Training-free Method of Adapting Knowledge Graph as References for Large Language Model's Reasoning Path Aggregation

# 摘要

> 大型语言模型（LLMs）在各类任务中表现出众，然而却常受幻觉及知识时效性的影响。将知识图谱（KGs）用作外部知识源已成可行之策，可现有的基于LLM的知识图谱问答（KGQA）方法，要么受限于在知识图谱上的逐步决策，制约了LLM的全局规划与推理能力，要么需要针对特定知识图谱进行微调或预训练。为应对这些挑战，我们提出了知识图谱辅助推理路径聚合（KARPA）这一全新框架，借助LLM的全局规划能力实现高效准确的知识图谱推理。KARPA的运作分为三步：凭借LLM的全局规划能力预先规划关系路径，通过嵌入模型匹配语义相关路径，对这些路径进行推理从而生成答案。与现有的KGQA方法不同，KARPA无需逐步遍历，无需额外训练，且适用于各种LLM架构。大量实验结果显示，KARPA在KGQA任务中达到了领先水平，兼具高效与准确。我们的代码将在Github上公布。

> Large language models (LLMs) demonstrate exceptional performance across a variety of tasks, yet they are often affected by hallucinations and the timeliness of knowledge. Leveraging knowledge graphs (KGs) as external knowledge sources has emerged as a viable solution, but existing methods for LLM-based knowledge graph question answering (KGQA) are often limited by step-by-step decision-making on KGs, restricting the global planning and reasoning capabilities of LLMs, or they require fine-tuning or pre-training on specific KGs. To address these challenges, we propose Knowledge graph Assisted Reasoning Path Aggregation (KARPA), a novel framework that harnesses the global planning abilities of LLMs for efficient and accurate KG reasoning. KARPA operates in three steps: pre-planning relation paths using the LLM's global planning capabilities, matching semantically relevant paths via an embedding model, and reasoning over these paths to generate answers. Unlike existing KGQA methods, KARPA avoids stepwise traversal, requires no additional training, and is adaptable to various LLM architectures. Extensive experimental results show that KARPA achieves state-of-the-art performance in KGQA tasks, delivering both high efficiency and accuracy. Our code will be available on Github.

[Arxiv](https://arxiv.org/abs/2412.20995)