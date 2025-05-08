# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月02日

`LLM应用

摘要中提到的研究将大型语言模型（LLMs）应用于图相关问题，提出了一种新的框架SDM-InstructGLM，用于在不依赖图神经网络（GNNs）的情况下处理图数据。这属于LLMs在特定任务中的应用，因此归类为LLM应用。` `图数据科学`

> Scalability Matters: Overcoming Challenges in InstructGLM with Similarity-Degree-Based Sampling

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域表现卓越，但在图相关问题上的应用仍显不足，主要受限于可扩展性问题和缺乏专门的图结构处理机制。目前，主流方法是将LLMs与图神经网络（GNNs）结合，通常将GNNs作为特征编码器或辅助组件。然而，直接在LLMs中编码图结构的研究尚不充分，尤其在大规模图中，token限制成为有效表示的瓶颈。为解决这一难题，我们提出了SDM-InstructGLM——一个全新的基于指令微调的图语言模型（InstructGLM）框架，无需依赖GNNs即可实现高效扩展。我们的方法创新性地引入了基于相似度和度中心性的偏差随机游走机制，通过选择性采样和编码图信息，确保了LLM中自适应的结构化表示。这种方法不仅显著提升了token效率，还有效缓解了随机采样带来的信息损失，同时在节点分类和链接预测等图任务中表现出色。此外，我们的研究证明了仅使用LLM进行图处理的可行性，成功实现了可扩展且可解释的图语言模型（GLMs），并通过基于指令的微调进一步优化。这项工作为无GNN的图学习方法开辟了新道路，充分利用LLMs作为独立的图推理模型。我们的源代码现已开源，欢迎访问GitHub获取。


> Large Language Models (LLMs) have demonstrated strong capabilities in various natural language processing tasks; however, their application to graph-related problems remains limited, primarily due to scalability constraints and the absence of dedicated mechanisms for processing graph structures. Existing approaches predominantly integrate LLMs with Graph Neural Networks (GNNs), using GNNs as feature encoders or auxiliary components. However, directly encoding graph structures within LLMs has been underexplored, particularly in the context of large-scale graphs where token limitations hinder effective representation. To address these challenges, we propose SDM-InstructGLM, a novel instruction-tuned Graph Language Model (InstructGLM) framework that enhances scalability and efficiency without relying on GNNs. Our method introduces a similarity-degree-based biased random walk mechanism, which selectively samples and encodes graph information based on node-feature similarity and degree centrality, ensuring an adaptive and structured representation within the LLM. This approach significantly improves token efficiency, mitigates information loss due to random sampling, and enhances performance on graph-based tasks such as node classification and link prediction. Furthermore, our results demonstrate the feasibility of LLM-only graph processing, enabling scalable and interpretable Graph Language Models (GLMs) optimized through instruction-based fine-tuning. This work paves the way for GNN-free approaches to graph learning, leveraging LLMs as standalone graph reasoning models. Our source code is available on GitHub.

[Arxiv](https://arxiv.org/abs/2505.03799)