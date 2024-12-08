# RAGDiffusion：借助外部知识同化生成逼真的布料

发布时间：2024年11月29日

`RAG` `图像生成`

> RAGDiffusion: Faithful Cloth Generation via External Knowledge Assimilation

# 摘要

> 标准服装资产的生成，需要从多样的现实情境中提取服装信息，创建出在清晰背景上展示的正面平铺服装图像。然而，由于生成图像有着高度标准化的采样分布和精确的结构要求，这带来了极大的挑战。现有的模型空间感知能力有限，在这种高规格的生成任务中常常出现结构幻觉。为解决此问题，我们提出了一种新颖的检索增强生成（RAG）框架，名为 RAGDiffusion，通过吸纳来自 LLM 和数据库的外部知识，来增强结构的确定性并减少幻觉。RAGDiffusion 包含两个核心流程：（1）基于检索的结构聚合，运用对比学习和结构局部线性嵌入（SLLE）来推导全局结构和空间地标，提供软硬两种指导以消除结构的不确定性；（2）全方位的忠实服装生成，引入了三级对齐，确保扩散过程中的结构、图案和解码组件的保真度。在具有挑战性的现实世界数据集上开展的大量实验表明，RAGDiffusion 合成了结构和细节都忠实的服装资产，性能显著提升，这是在高规格忠实生成中使用 RAG 来应对内在幻觉和提高保真度的开创性尝试。

> Standard clothing asset generation involves creating forward-facing flat-lay garment images displayed on a clear background by extracting clothing information from diverse real-world contexts, which presents significant challenges due to highly standardized sampling distributions and precise structural requirements in the generated images. Existing models have limited spatial perception and often exhibit structural hallucinations in this high-specification generative task. To address this issue, we propose a novel Retrieval-Augmented Generation (RAG) framework, termed RAGDiffusion, to enhance structure determinacy and mitigate hallucinations by assimilating external knowledge from LLM and databases. RAGDiffusion consists of two core processes: (1) Retrieval-based structure aggregation, which employs contrastive learning and a Structure Locally Linear Embedding (SLLE) to derive global structure and spatial landmarks, providing both soft and hard guidance to counteract structural ambiguities; and (2) Omni-level faithful garment generation, which introduces a three-level alignment that ensures fidelity in structural, pattern, and decoding components within the diffusing. Extensive experiments on challenging real-world datasets demonstrate that RAGDiffusion synthesizes structurally and detail-faithful clothing assets with significant performance improvements, representing a pioneering effort in high-specification faithful generation with RAG to confront intrinsic hallucinations and enhance fidelity.

[Arxiv](https://arxiv.org/abs/2411.19528)