# 基于部分知识提示的大型语言模型在未见实体问题中的回答研究

发布时间：2025年08月02日

`RAG` `知识图谱` `问答系统`

> Prompting Large Language Models with Partial Knowledge for Answering Questions with Unseen Entities

# 摘要

> 检索增强生成（RAG）通过补充和替代大型语言模型（LLMs）中的参数化知识，展现了令人瞩目的性能。检索到的知识可分为显式答案证据、隐式答案线索以及不充分的答案背景，后者又细分为完全不相关和部分相关的信息。有效利用部分相关知识是RAG系统的关键挑战，尤其是在知识库检索不完整时。与传统观点不同，我们提出：大型语言模型可通过其自身嵌入的部分相关知识被“唤醒”。为全面研究此现象，我们从黄金推理路径中提取三元组及其变体，并移除包含答案的路径以构建部分相关知识。我们对大型语言模型的唤醒效应进行了理论分析，并在两个知识图谱问答（QA）数据集上通过实验验证了假设。此外，我们提出了一种新任务——未见实体KGQA，模拟了现实世界中因知识图谱不完整导致实体链接失败的挑战。基于唤醒机制的方法在实际应用中表现出色，超越了传统依赖嵌入相似性的方法，这些传统方法易返回噪声信息。


> Retrieval-Augmented Generation (RAG) shows impressive performance by supplementing and substituting parametric knowledge in Large Language Models (LLMs). Retrieved knowledge can be divided into three types: explicit answer evidence, implicit answer clue, and insufficient answer context which can be further categorized into totally irrelevant and partially relevant information. Effectively utilizing partially relevant knowledge remains a key challenge for RAG systems, especially in incomplete knowledge base retrieval. Contrary to the conventional view, we propose a new perspective: LLMs can be awakened via partially relevant knowledge already embedded in LLMs. To comprehensively investigate this phenomenon, the triplets located in the gold reasoning path and their variants are used to construct partially relevant knowledge by removing the path that contains the answer. We provide theoretical analysis of the awakening effect in LLMs and support our hypothesis with experiments on two Knowledge Graphs (KGs) Question Answering (QA) datasets. Furthermore, we present a new task, Unseen Entity KGQA, simulating real-world challenges where entity linking fails due to KG incompleteness. Our awakening-based approach demonstrates greater efficacy in practical applications, outperforms traditional methods that rely on embedding-based similarity which are prone to returning noisy information.

[Arxiv](https://arxiv.org/abs/2508.01290)