# HyDRA：面向可验证知识图谱的混合驱动推理架构

发布时间：2025年07月21日

`LLM应用

摘要中提到，HyDRA架构结合神经符号AI，利用大型语言模型（LLMs）生成过程来自动化构建知识图谱，并通过设计合同（DbC）来控制生成过程。这属于LLM的应用层面，因为论文的重点在于如何利用LLMs来提升KG的构建和验证，而不是探讨LLMs的内在机制或理论。` `知识图谱`

> HyDRA: A Hybrid-Driven Reasoning Architecture for Verifiable Knowledge Graphs

# 摘要

> 符号知识（如知识图谱 KGs）与神经网络生成能力的协同作用是推动神经符号 AI 发展的核心。然而，自动化构建 KG 的过程中面临诸多挑战，如输出可靠性、一致性和可验证性问题，这些问题可能导致数据孤岛或概念混淆。为了解决这些问题，我们提出了 HyDRA，一种专为可验证 KG 自动化设计的混合驱动推理架构。通过一组协作的神经符号代理，HyDRA 根据能力问题 (CQs) 构建本体图，并指导从任意文档中提取三元组生成 KG。我们的方法采用设计合同 (DbC) 原理，利用可验证合同控制大型语言模型 (LLMs) 的生成过程。为了验证方法效果，我们提出了一个评估框架，通过【数学公式】SymbolicAI【数学公式】的符号验证来评估 KG 的功能性正确性。这项工作为提升自动 KG 构建的可靠性及评估方法提供了新的视角。代码已公开。


> The synergy between symbolic knowledge, often represented by Knowledge Graphs (KGs), and the generative capabilities of neural networks is central to advancing neurosymbolic AI. A primary bottleneck in realizing this potential is the difficulty of automating KG construction, which faces challenges related to output reliability, consistency, and verifiability. These issues can manifest as structural inconsistencies within the generated graphs, such as the formation of disconnected $\textit{isolated islands}$ of data or the inaccurate conflation of abstract classes with specific instances. To address these challenges, we propose HyDRA, a $\textbf{Hy}$brid-$\textbf{D}$riven $\textbf{R}$easoning $\textbf{A}$rchitecture designed for verifiable KG automation. Given a domain or an initial set of documents, HyDRA first constructs an ontology via a panel of collaborative neurosymbolic agents. These agents collaboratively agree on a set of competency questions (CQs) that define the scope and requirements the ontology must be able to answer. Given these CQs, we build an ontology graph that subsequently guides the automated extraction of triplets for KG generation from arbitrary documents. Inspired by design-by-contracts (DbC) principles, our method leverages verifiable contracts as the primary control mechanism to steer the generative process of Large Language Models (LLMs). To verify the output of our approach, we extend beyond standard benchmarks and propose an evaluation framework that assesses the functional correctness of the resulting KG by leveraging symbolic verifications as described by the neurosymbolic AI framework, $\textit{SymbolicAI}$. This work contributes a hybrid-driven architecture for improving the reliability of automated KG construction and the exploration of evaluation methods for measuring the functional integrity of its output. The code is publicly available.

[Arxiv](https://arxiv.org/abs/2507.15917)