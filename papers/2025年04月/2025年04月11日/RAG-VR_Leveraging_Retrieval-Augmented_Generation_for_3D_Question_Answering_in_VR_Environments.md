# RAG-VR: 基于检索增强生成的VR环境三维问答系统

发布时间：2025年04月11日

`RAG` `虚拟现实` `问答系统`

> RAG-VR: Leveraging Retrieval-Augmented Generation for 3D Question Answering in VR Environments

# 摘要

> 大型语言模型（LLMs）的最新进展为虚拟现实（VR）中的情境理解开辟了新可能。然而，VR场景往往高度本地化且个性化，这对通用型LLMs的效果构成了限制。为解决这一难题，我们推出了RAG-VR——首个专为VR设计的三维问答系统，通过检索增强生成（RAG）技术，将LLM与本地知识库中的外部知识相结合，显著提升回答质量。RAG-VR内置了一个专门提取虚拟环境及用户状态综合信息的流水线，以确保生成精准回答。为了实现高效检索，RAG-VR将检索任务分流至附近的边缘服务器，并仅在检索过程中调用关键信息。此外，我们对检索器进行了优化训练，使其能够有效区分与问题相关、不相关以及难以辨别的信息。实验证明，与传统基线系统相比，RAG-VR的回答准确率提升了17.9%-41.8%，端到端延迟降低了34.5%-47.3%。

> Recent advances in large language models (LLMs) provide new opportunities for context understanding in virtual reality (VR). However, VR contexts are often highly localized and personalized, limiting the effectiveness of general-purpose LLMs. To address this challenge, we present RAG-VR, the first 3D question-answering system for VR that incorporates retrieval-augmented generation (RAG), which augments an LLM with external knowledge retrieved from a localized knowledge database to improve the answer quality. RAG-VR includes a pipeline for extracting comprehensive knowledge about virtual environments and user conditions for accurate answer generation. To ensure efficient retrieval, RAG-VR offloads the retrieval process to a nearby edge server and uses only essential information during retrieval. Moreover, we train the retriever to effectively distinguish among relevant, irrelevant, and hard-to-differentiate information in relation to questions. RAG-VR improves answer accuracy by 17.9%-41.8% and reduces end-to-end latency by 34.5%-47.3% compared with two baseline systems.

[Arxiv](https://arxiv.org/abs/2504.08256)