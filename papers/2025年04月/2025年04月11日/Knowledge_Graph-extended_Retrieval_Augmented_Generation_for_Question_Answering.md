# 知识图谱增强生成式问答

发布时间：2025年04月11日

`RAG` `问答系统`

> Knowledge Graph-extended Retrieval Augmented Generation for Question Answering

# 摘要

> 大型语言模型（LLMs）和知识图谱（KGs）为实现稳健且可解释的问题回答（QA）提供了一种有前景的方法。虽然LLMs在自然语言理解方面表现出色，但它们存在知识缺口和幻觉问题。KGs提供了结构化的知识，但缺乏自然语言交互能力。理想情况下，一个AI系统应该既能够应对缺失的事实，又易于沟通。本文提出了一种无需训练即可集成LLMs和KGs的系统，确保在不同KG之间具有良好的适应性，且只需少量人工干预。该方法可以被归类为一种特定形式的知识图谱增强检索生成（RAG），因此被命名为知识图谱扩展的检索增强生成（KG-RAG）。它包含一个问答分解模块，以增强多跳信息检索和答案的可解释性。通过使用In-Context Learning（ICL）和Chain-of-Thought（CoT）提示，它生成显式的推理链，单独处理以提高真实性和准确性。在MetaQA基准上的实验表明，与基于LLM和KG的基线方法相比，该方法在多跳问题上的准确率有所提高，尽管在单跳性能上有所妥协。这些发现表明，KG-RAG有望通过将无结构的语言理解与结构化的知识检索相结合，提高QA的透明度。

> Large Language Models (LLMs) and Knowledge Graphs (KGs) offer a promising approach to robust and explainable Question Answering (QA). While LLMs excel at natural language understanding, they suffer from knowledge gaps and hallucinations. KGs provide structured knowledge but lack natural language interaction. Ideally, an AI system should be both robust to missing facts as well as easy to communicate with. This paper proposes such a system that integrates LLMs and KGs without requiring training, ensuring adaptability across different KGs with minimal human effort. The resulting approach can be classified as a specific form of a Retrieval Augmented Generation (RAG) with a KG, thus, it is dubbed Knowledge Graph-extended Retrieval Augmented Generation (KG-RAG). It includes a question decomposition module to enhance multi-hop information retrieval and answer explainability. Using In-Context Learning (ICL) and Chain-of-Thought (CoT) prompting, it generates explicit reasoning chains processed separately to improve truthfulness. Experiments on the MetaQA benchmark show increased accuracy for multi-hop questions, though with a slight trade-off in single-hop performance compared to LLM with KG baselines. These findings demonstrate KG-RAG's potential to improve transparency in QA by bridging unstructured language understanding with structured knowledge retrieval.

[Arxiv](https://arxiv.org/abs/2504.08893)