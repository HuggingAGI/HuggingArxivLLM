# 将时序图学习融入基于LLM的时序知识图谱模型

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要讨论了如何将大型语言模型（LLMs）应用于时间知识图谱预测（TKGF）任务中，提出了一个名为TGL-LLM的框架，通过时间图学习和混合图标记化方法来增强LLMs对时间和结构信息的理解。论文的核心在于如何利用LLMs来解决具体的应用问题（即时间知识图谱预测），因此应归类为LLM应用。` `知识图谱` `时间序列分析`

> Integrate Temporal Graph Learning into LLM-based Temporal Knowledge Graph Model

# 摘要

> # 时间知识图谱预测（TKGF）旨在通过历史事件预测未来。近年来，大型语言模型（LLMs）展现出强大的能力，激发了其在时间知识图谱（TKGs）推理中的应用研究热潮。现有基于LLM的方法虽然整合了历史事实或静态图表示，但对时间模式的建模不足以及图与语言之间的跨模态对齐效果不佳，限制了LLMs对TKGs中时间和结构信息的全面理解。为此，我们提出了TGL-LLM框架，将时间图学习融入基于LLM的时间知识图谱模型。具体而言，我们通过时间图学习捕捉时间和关系模式，生成历史图嵌入，并设计了混合图标记化方法，充分建模LLMs中的时间模式。此外，我们采用两阶段训练范式，在高质量多样化数据上微调LLMs，以实现图与语言的更好对齐。在三个真实数据集上的实验表明，我们的方法显著优于现有最先进（SOTA）方法。

> Temporal Knowledge Graph Forecasting (TKGF) aims to predict future events based on the observed events in history. Recently, Large Language Models (LLMs) have exhibited remarkable capabilities, generating significant research interest in their application for reasoning over temporal knowledge graphs (TKGs). Existing LLM-based methods have integrated retrieved historical facts or static graph representations into LLMs. Despite the notable performance of LLM-based methods, they are limited by the insufficient modeling of temporal patterns and ineffective cross-modal alignment between graph and language, hindering the ability of LLMs to fully grasp the temporal and structural information in TKGs. To tackle these issues, we propose a novel framework TGL-LLM to integrate temporal graph learning into LLM-based temporal knowledge graph model. Specifically, we introduce temporal graph learning to capture the temporal and relational patterns and obtain the historical graph embedding. Furthermore, we design a hybrid graph tokenization to sufficiently model the temporal patterns within LLMs. To achieve better alignment between graph and language, we employ a two-stage training paradigm to finetune LLMs on high-quality and diverse data, thereby resulting in better performance. Extensive experiments on three real-world datasets show that our approach outperforms a range of state-of-the-art (SOTA) methods.

[Arxiv](https://arxiv.org/abs/2501.11911)