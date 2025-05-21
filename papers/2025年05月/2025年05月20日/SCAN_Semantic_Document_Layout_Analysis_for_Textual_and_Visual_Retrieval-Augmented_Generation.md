# SCAN: 基于语义文档布局分析的文本与视觉检索增强生成

发布时间：2025年05月20日

`RAG` `文档分析`

> SCAN: Semantic Document Layout Analysis for Textual and Visual Retrieval-Augmented Generation

# 摘要

> 随着大型语言模型 (LLMs) 和视觉语言模型 (VLMs) 的广泛应用，用于检索增强生成 (RAG) 和视觉 RAG 等应用的丰富文档分析技术正受到广泛关注。尽管 recent research indicates that using VLMs can achieve better RAG performance, 但处理丰富文档仍然面临挑战，因为单页包含大量信息。在本文中，我们提出了 SCAN（	extbf{S}emanti	extbf{C} Document Layout 	extbf{AN}alysis），这是一种新颖的方法，旨在提升与视觉丰富文档协同工作的文本和视觉检索增强生成 (RAG) 系统的性能。它是一种适用于 VLM 的方法，能够以适当的语义粒度识别文档组件，平衡上下文保留与处理效率。SCAN 采用了一种粗粒度的语义方法，将文档划分为覆盖连续组件的连贯区域。我们通过使用复杂的标注数据集对目标检测模型进行微调来训练 SCAN 模型。我们在英语和日语数据集上的实验结果表明，应用 SCAN 可以将端到端文本 RAG 性能提升高达 9.0%，并将视觉 RAG 性能提升高达 6.4%，超越了传统方法甚至商业文档处理解决方案的性能。

> With the increasing adoption of Large Language Models (LLMs) and Vision-Language Models (VLMs), rich document analysis technologies for applications like Retrieval-Augmented Generation (RAG) and visual RAG are gaining significant attention. Recent research indicates that using VLMs can achieve better RAG performance, but processing rich documents still remains a challenge since a single page contains large amounts of information. In this paper, we present SCAN (\textbf{S}emanti\textbf{C} Document Layout \textbf{AN}alysis), a novel approach enhancing both textual and visual Retrieval-Augmented Generation (RAG) systems working with visually rich documents. It is a VLM-friendly approach that identifies document components with appropriate semantic granularity, balancing context preservation with processing efficiency. SCAN uses a coarse-grained semantic approach that divides documents into coherent regions covering continuous components. We trained the SCAN model by fine-tuning object detection models with sophisticated annotation datasets. Our experimental results across English and Japanese datasets demonstrate that applying SCAN improves end-to-end textual RAG performance by up to 9.0\% and visual RAG performance by up to 6.4\%, outperforming conventional approaches and even commercial document processing solutions.

[Arxiv](https://arxiv.org/abs/2505.14381)