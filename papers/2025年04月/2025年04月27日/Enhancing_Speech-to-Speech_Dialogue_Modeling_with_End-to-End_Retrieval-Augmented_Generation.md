# 提升语音到语音对话建模：端到端检索增强生成方法

发布时间：2025年04月27日

`RAG` `语音技术` `知识图谱`

> Enhancing Speech-to-Speech Dialogue Modeling with End-to-End Retrieval-Augmented Generation

# 摘要

> 近年来，端到端语音到语音（S2S）对话系统因其优势吸引了越来越多的研究关注。相比传统级联系统，它们不仅延迟更低，还能更自然地整合非语言线索（如情感和说话人身份）。然而，这些端到端系统在整合外部知识方面面临挑战，而这一能力通常通过基于文本的大语言模型（LLMs）中的检索增强生成（RAG）来解决。核心困难在于语音输入与检索到的文本知识之间的模态差距，这阻碍了有效整合。为了解决这一问题，我们提出了一种新型的端到端RAG框架，该框架可以直接从语音查询中检索相关文本知识，无需通过ASR等技术进行中间的语音到文本转换。实验结果表明，我们的方法显著提升了端到端S2S对话系统的性能，同时实现了更高的检索效率。尽管整体性能仍落后于级联模型，但我们的框架为提升端到端S2S系统的知识整合能力提供了一个有希望的方向。我们将发布代码和数据集，以支持可重复性并促进该领域的进一步研究。

> In recent years, end-to-end speech-to-speech (S2S) dialogue systems have garnered increasing research attention due to their advantages over traditional cascaded systems, including achieving lower latency and more natural integration of nonverbal cues such as emotion and speaker identity. However, these end-to-end systems face key challenges, particularly in incorporating external knowledge, a capability commonly addressed by Retrieval-Augmented Generation (RAG) in text-based large language models (LLMs). The core difficulty lies in the modality gap between input speech and retrieved textual knowledge, which hinders effective integration. To address this issue, we propose a novel end-to-end RAG framework that directly retrieves relevant textual knowledge from speech queries, eliminating the need for intermediate speech-to-text conversion via techniques like ASR. Experimental results demonstrate that our method significantly improves the performance of end-to-end S2S dialogue systems while achieving higher retrieval efficiency. Although the overall performance still lags behind cascaded models, our framework offers a promising direction for enhancing knowledge integration in end-to-end S2S systems. We will release the code and dataset to support reproducibility and promote further research in this area.

[Arxiv](https://arxiv.org/abs/2505.00028)