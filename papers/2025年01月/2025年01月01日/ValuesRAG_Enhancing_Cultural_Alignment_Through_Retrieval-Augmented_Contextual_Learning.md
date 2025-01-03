# ValuesRAG: 利用检索增强的上下文学习优化文化对齐

发布时间：2025年01月01日

`RAG

理由：该论文提出了一个名为ValuesRAG的创新框架，结合了检索增强生成（RAG）与上下文学习，旨在解决大型语言模型（LLMs）中的文化价值观对齐问题。论文的核心方法是通过检索增强生成技术动态整合文化和人口统计知识，这与RAG技术的应用密切相关。因此，该论文应被分类为RAG。` `文化研究` `人工智能`

> ValuesRAG: Enhancing Cultural Alignment Through Retrieval-Augmented Contextual Learning

# 摘要

> # 摘要
大型语言模型（LLMs）中的文化价值观对齐面临重大挑战，因其容易从训练数据中继承西方中心偏见，导致跨文化场景中的表述失真和公平性问题。现有方法如角色分配和少样本学习，因过度依赖预训练知识、缺乏扩展性且难以捕捉文化细节，往往难以实现可靠的文化对齐。为此，我们提出ValuesRAG，一个创新框架，结合检索增强生成（RAG）与上下文学习，动态整合文化和人口统计知识。基于世界价值观调查（WVS）数据集，ValuesRAG首先为个体生成价值观摘要，随后精选多个代表性区域数据集作为测试集，根据人口特征检索相关摘要，并通过重排序选出前k个最相关摘要。ValuesRAG在主要实验和仅提供摘要的消融研究中均显著优于基线方法，展现了其在推动文化对齐AI系统和提升AI应用包容性方面的巨大潜力。

> Cultural values alignment in Large Language Models (LLMs) is a critical challenge due to their tendency to embed Western-centric biases from training data, leading to misrepresentations and fairness issues in cross-cultural contexts. Recent approaches, such as role-assignment and few-shot learning, often struggle with reliable cultural alignment as they heavily rely on pre-trained knowledge, lack scalability, and fail to capture nuanced cultural values effectively. To address these issues, we propose ValuesRAG, a novel and effective framework that applies Retrieval-Augmented Generation (RAG) with in-context learning to integrate cultural and demographic knowledge dynamically during text generation. Leveraging the World Values Survey (WVS) dataset, ValuesRAG first generates summaries of values for each individual. Subsequently, we curated several representative regional datasets to serve as test datasets and retrieve relevant summaries of values based on demographic features, followed by a reranking step to select the top-k relevant summaries. ValuesRAG consistently outperforms baseline methods, both in the main experiment and in the ablation study where only the values summary was provided, highlighting ValuesRAG's potential to foster culturally aligned AI systems and enhance the inclusivity of AI-driven applications.

[Arxiv](https://arxiv.org/abs/2501.01031)