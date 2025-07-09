# KERAG_R：推荐系统中的知识增强生成方法

发布时间：2025年07月08日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在推荐系统中的应用，并提出了一种结合知识图谱和图检索增强生成（GraphRAG）的方法来解决领域知识缺失的问题。论文的重点在于将LLMs应用于推荐任务，并展示了该方法在实际数据集上的优越性能。因此，它属于LLM应用类别。` `推荐系统` `知识图谱`

> KERAG_R: Knowledge-Enhanced Retrieval-Augmented Generation for Recommendation

# 摘要

> 大型语言模型（LLMs）在推荐系统中表现出色，主要得益于其上下文学习和泛化能力。现有基于LLMs的推荐方法通过设计专门提示来利用其上下文能力，并使输出与人类偏好保持一致，从而提升推荐性能。然而，LLMs在推荐任务中的应用受到领域知识缺失的限制。具体来说，LLMs在预训练语料库中缺乏关于待推荐项目的相关知识，这可能导致不准确或幻觉化的推荐结果。此外，直接引入知识图谱信息会带来冗余和噪声信息，影响LLMs推理过程或超出其输入上下文长度限制，从而降低推荐性能。

为了解决领域知识缺失的问题，我们提出了一种名为知识增强检索增强生成推荐模型（KERAG_R）的新方法。具体而言，我们利用基于图检索增强生成（GraphRAG）的组件，将来自知识图谱（KG）的额外信息整合到指令中，使LLMs能够协同利用基于文本的用户交互和知识图谱中的推荐信号，从而更好地估计用户在推荐情境下的偏好。特别地，我们通过预训练一个图注意力网络（GAT）来选择与目标用户最相关的三元组，用于所使用的LLMs，从而增强LLMs性能，同时减少冗余和噪声信息。

我们在三个公开数据集上的大量实验表明，KERAG_R模型在推荐性能上显著优于现有的十种最先进推荐方法。

> Large Language Models (LLMs) have shown strong potential in recommender systems due to their contextual learning and generalisation capabilities. Existing LLM-based recommendation approaches typically formulate the recommendation task using specialised prompts designed to leverage their contextual abilities, and aligning their outputs closely with human preferences to yield an improved recommendation performance. However, the use of LLMs for recommendation tasks is limited by the absence of domain-specific knowledge. This lack of relevant relational knowledge about the items to be recommended in the LLM's pre-training corpus can lead to inaccuracies or hallucinations, resulting in incorrect or misleading recommendations. Moreover, directly using information from the knowledge graph introduces redundant and noisy information, which can affect the LLM's reasoning process or exceed its input context length, thereby reducing the performance of LLM-based recommendations. To address the lack of domain-specific knowledge, we propose a novel model called Knowledge-Enhanced Retrieval-Augmented Generation for Recommendation (KERAG_R). Specifically, we leverage a graph retrieval-augmented generation (GraphRAG) component to integrate additional information from a knowledge graph (KG) into instructions, enabling the LLM to collaboratively exploit recommendation signals from both text-based user interactions and the knowledge graph to better estimate the users' preferences in a recommendation context. In particular, we perform graph RAG by pre-training a graph attention network (GAT) to select the most relevant triple for the target users for the used LLM, thereby enhancing the LLM while reducing redundant and noisy information. Our extensive experiments on three public datasets show that our proposed KERAG_R model significantly outperforms ten existing state-of-the-art recommendation methods.

[Arxiv](https://arxiv.org/abs/2507.05863)