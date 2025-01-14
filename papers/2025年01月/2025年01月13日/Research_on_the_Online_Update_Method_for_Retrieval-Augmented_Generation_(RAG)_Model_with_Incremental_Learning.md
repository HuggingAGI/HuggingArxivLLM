# 增量学习下检索增强生成（RAG）模型的在线更新方法研究

发布时间：2025年01月13日

`RAG

理由：这篇论文摘要主要讨论了基于检索增强生成（RAG）模型的在线更新方法，并详细介绍了其创新机制，如动态记忆、分层索引、多层门控机制等。这些内容与RAG模型的核心技术和应用密切相关，因此将其分类为RAG是合适的。` `信息技术` `语言模型`

> Research on the Online Update Method for Retrieval-Augmented Generation (RAG) Model with Incremental Learning

# 摘要

> 在信息技术迅猛发展和数据量激增的背景下，语言模型面临着实时更新和适应新知识的巨大挑战。本研究提出了一种基于检索增强生成（RAG）模型的在线更新方法，并引入了多项创新机制。首先，利用动态记忆捕捉新兴数据样本，并通过可调的知识蒸馏策略逐步整合到核心模型中。其次，检索模块采用分层索引和多层门控机制，确保检索内容更加精准。最后，生成阶段为不同类型输入构建多阶段网络结构，并通过交叉注意力匹配和筛选中间表示，实现新旧知识的有效融合与迭代更新。实验表明，该方法在知识保留和推理准确性上优于现有主流模型。

> In the contemporary context of rapid advancements in information technology and the exponential growth of data volume, language models are confronted with significant challenges in effectively navigating the dynamic and ever-evolving information landscape to update and adapt to novel knowledge in real time. In this work, an online update method is proposed, which is based on the existing Retrieval Enhanced Generation (RAG) model with multiple innovation mechanisms. Firstly, the dynamic memory is used to capture the emerging data samples, and then gradually integrate them into the core model through a tunable knowledge distillation strategy. At the same time, hierarchical indexing and multi-layer gating mechanism are introduced into the retrieval module to ensure that the retrieved content is more targeted and accurate. Finally, a multi-stage network structure is established for different types of inputs in the generation stage, and cross-attention matching and screening are carried out on the intermediate representations of each stage to ensure the effective integration and iterative update of new and old knowledge. Experimental results show that the proposed method is better than the existing mainstream comparison models in terms of knowledge retention and inference accuracy.

[Arxiv](https://arxiv.org/abs/2501.07063)