# MIRAGE：面向增强生成的检索评测指标密集型评测基准

发布时间：2025年04月23日

`RAG` `问答系统`

> MIRAGE: A Metric-Intensive Benchmark for Retrieval-Augmented Generation Evaluation

# 摘要

> 检索增强生成（RAG）作为一种有效方法，通过整合外部知识显著提升了大型语言模型的生成能力。然而，由于检索与生成组件之间复杂的相互作用，对RAG系统的评估仍面临挑战。这一局限性导致了缺乏能够支持详细、特定组件评估的基准测试。在此工作中，我们推出了MIRAGE，一个专为RAG评估设计的问题回答数据集。MIRAGE包含7,560个精选实例，映射到37,800个检索池条目，从而能够高效且精准地评估检索和生成任务。我们还引入了新型评估指标，旨在衡量RAG的适应性，涵盖噪声易感性、上下文可接受性、上下文不敏感性和上下文误解等多个维度。通过在各种检索器-LLM配置上的全面实验，我们为模型对的最优配对以及RAG系统内部的复杂动态提供了新的见解。该数据集和评估代码公开可用，支持在不同研究环境中无缝集成与定制ootnote{MIRAGE代码和数据可在https://github.com/nlpai-lab/MIRAGE获取。}。

> Retrieval-Augmented Generation (RAG) has gained prominence as an effective method for enhancing the generative capabilities of Large Language Models (LLMs) through the incorporation of external knowledge. However, the evaluation of RAG systems remains a challenge, due to the intricate interplay between retrieval and generation components. This limitation has resulted in a scarcity of benchmarks that facilitate a detailed, component-specific assessment. In this work, we present MIRAGE, a Question Answering dataset specifically designed for RAG evaluation. MIRAGE consists of 7,560 curated instances mapped to a retrieval pool of 37,800 entries, enabling an efficient and precise evaluation of both retrieval and generation tasks. We also introduce novel evaluation metrics aimed at measuring RAG adaptability, encompassing dimensions such as noise vulnerability, context acceptability, context insensitivity, and context misinterpretation. Through comprehensive experiments across various retriever-LLM configurations, we provide new insights into the optimal alignment of model pairs and the nuanced dynamics within RAG systems. The dataset and evaluation code are publicly available, allowing for seamless integration and customization in diverse research settings\footnote{The MIRAGE code and data are available at https://github.com/nlpai-lab/MIRAGE.

[Arxiv](https://arxiv.org/abs/2504.17137)