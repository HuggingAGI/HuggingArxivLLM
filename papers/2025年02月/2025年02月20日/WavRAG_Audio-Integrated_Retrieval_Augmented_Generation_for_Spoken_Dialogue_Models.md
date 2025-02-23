# WavRAG：面向语音对话模型的音频增强生成方法

发布时间：2025年02月20日

`RAG` `语音处理` `音频技术`

> WavRAG: Audio-Integrated Retrieval Augmented Generation for Spoken Dialogue Models

# 摘要

> 检索增强生成（RAG）因其赋予大型语言模型（LLMs）整合外部知识的能力而备受青睐。然而，现有RAG框架主要针对文本型LLMs，依赖自动语音识别（ASR）处理语音输入，导致音频信息丢失、转录错误风险增加以及计算开销上升。因此，我们推出了WavRAG——首个支持原生端到端音频处理的检索增强生成框架。WavRAG具备两大核心优势：1）绕过ASR，直接对原始音频进行嵌入和检索处理；2）将音频与文本整合到统一的知识表示中。具体而言，我们提出了WavRetriever，以便从文本-音频混合知识库中实现检索，并通过整合链式推理进一步增强语音对话模型的上下文能力。与最先进的ASR-文本RAG流水线相比，WavRAG在实现相当检索性能的同时，速度提升了10倍。此外，WavRAG独特的文本-音频混合检索能力将RAG的边界扩展到了音频模态。

> Retrieval Augmented Generation (RAG) has gained widespread adoption owing to its capacity to empower large language models (LLMs) to integrate external knowledge. However, existing RAG frameworks are primarily designed for text-based LLMs and rely on Automatic Speech Recognition to process speech input, which discards crucial audio information, risks transcription errors, and increases computational overhead. Therefore, we introduce WavRAG, the first retrieval augmented generation framework with native, end-to-end audio support. WavRAG offers two key features: 1) Bypassing ASR, WavRAG directly processes raw audio for both embedding and retrieval. 2) WavRAG integrates audio and text into a unified knowledge representation. Specifically, we propose the WavRetriever to facilitate the retrieval from a text-audio hybrid knowledge base, and further enhance the in-context capabilities of spoken dialogue models through the integration of chain-of-thought reasoning. In comparison to state-of-the-art ASR-Text RAG pipelines, WavRAG achieves comparable retrieval performance while delivering a 10x acceleration. Furthermore, WavRAG's unique text-audio hybrid retrieval capability extends the boundaries of RAG to the audio modality.

[Arxiv](https://arxiv.org/abs/2502.14727)