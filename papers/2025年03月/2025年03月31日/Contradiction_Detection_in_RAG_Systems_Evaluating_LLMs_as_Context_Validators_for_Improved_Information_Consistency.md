# # 摘要
RAG系统中的矛盾检测：评估LLMs作为上下文验证器，提升信息一致性。

发布时间：2025年03月31日

`RAG`

> Contradiction Detection in RAG Systems: Evaluating LLMs as Context Validators for Improved Information Consistency

# 摘要

> 检索增强生成（RAG）系统为大型语言模型（LLMs）注入了强大的信息更新能力。然而，在新闻等快速发展的领域中，RAG系统的信息检索过程有时会揭示包含矛盾信息的文档。这些矛盾信息会对LLMs的性能产生重大影响，导致输出结果不一致或出现错误。本研究从两个角度应对这一关键挑战。首先，我们提出了一种新颖的数据生成框架，用于模拟RAG系统检索阶段可能出现的各种矛盾类型。其次，我们评估了不同LLMs作为上下文验证器的能力，考察它们在检索到的文档集中识别矛盾信息的能力。实验结果表明，即使是当前最先进的LLMs，上下文验证仍是一项极具挑战性的任务，且在不同类型的矛盾面前，模型表现差异显著。总体而言，模型规模越大，矛盾检测能力越强，但不同提示策略在不同任务和模型架构中的有效性参差不齐。我们发现，链式思维提示策略在某些模型上显著提升了性能，而在另一些模型上却可能适得其反，这凸显了该任务的复杂性以及在RAG系统中开发更稳健的上下文验证方法的必要性。

> Retrieval Augmented Generation (RAG) systems have emerged as a powerful method for enhancing large language models (LLMs) with up-to-date information. However, the retrieval step in RAG can sometimes surface documents containing contradictory information, particularly in rapidly evolving domains such as news. These contradictions can significantly impact the performance of LLMs, leading to inconsistent or erroneous outputs. This study addresses this critical challenge in two ways. First, we present a novel data generation framework to simulate different types of contradictions that may occur in the retrieval stage of a RAG system. Second, we evaluate the robustness of different LLMs in performing as context validators, assessing their ability to detect contradictory information within retrieved document sets. Our experimental results reveal that context validation remains a challenging task even for state-of-the-art LLMs, with performance varying significantly across different types of contradictions. While larger models generally perform better at contradiction detection, the effectiveness of different prompting strategies varies across tasks and model architectures. We find that chain-of-thought prompting shows notable improvements for some models but may hinder performance in others, highlighting the complexity of the task and the need for more robust approaches to context validation in RAG systems.

[Arxiv](https://arxiv.org/abs/2504.00180)