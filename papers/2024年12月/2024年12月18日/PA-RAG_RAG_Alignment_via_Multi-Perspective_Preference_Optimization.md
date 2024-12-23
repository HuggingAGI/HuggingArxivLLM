# PA-RAG：借助多视角偏好优化达成 RAG 对齐

发布时间：2024年12月18日

`RAG` `语言模型` `问答系统`

> PA-RAG: RAG Alignment via Multi-Perspective Preference Optimization

# 摘要

> 检索增强生成（RAG）的出现减轻了大型语言模型（LLMs）生成内容过时和产生幻觉等问题，不过仍存在诸多局限。当通用的 LLM 充当 RAG 生成器时，往往存在响应信息不充分、响应稳健性差以及引用质量不佳的情况。以往解决这些限制的方法，不管是在生成响应之外添加额外步骤，还是通过监督微调（SFT）优化生成器，都未能完全契合 RAG 的要求。所以，在保持端到端 LLM 形式的同时，从多个偏好角度优化 RAG 生成器仍是一项挑战。为了填补这一空缺，我们提出了用于检索增强生成的多视角偏好对齐（PA-RAG），这是一种全面优化 RAG 系统生成器以满足 RAG 要求的方法。具体而言，我们在不同的提示文档质量场景下，从生成器中采样不同质量的响应，构建高质量的指令微调数据和多视角偏好数据。接着，我们使用 SFT 和直接偏好优化（DPO）来优化生成器。在三个 LLM 的四个问答数据集上开展的大量实验表明，PA-RAG 能够显著提升 RAG 生成器的性能。我们的代码和数据集可在 https://github.com/wujwyi/PA-RAG 获取。

> The emergence of Retrieval-augmented generation (RAG) has alleviated the issues of outdated and hallucinatory content in the generation of large language models (LLMs), yet it still reveals numerous limitations. When a general-purpose LLM serves as the RAG generator, it often suffers from inadequate response informativeness, response robustness, and citation quality. Past approaches to tackle these limitations, either by incorporating additional steps beyond generating responses or optimizing the generator through supervised fine-tuning (SFT), still failed to align with the RAG requirement thoroughly. Consequently, optimizing the RAG generator from multiple preference perspectives while maintaining its end-to-end LLM form remains a challenge. To bridge this gap, we propose Multiple Perspective Preference Alignment for Retrieval-Augmented Generation (PA-RAG), a method for optimizing the generator of RAG systems to align with RAG requirements comprehensively. Specifically, we construct high-quality instruction fine-tuning data and multi-perspective preference data by sampling varied quality responses from the generator across different prompt documents quality scenarios. Subsequently, we optimize the generator using SFT and Direct Preference Optimization (DPO). Extensive experiments conducted on four question-answer datasets across three LLMs demonstrate that PA-RAG can significantly enhance the performance of RAG generators. Our code and datasets are available at https://github.com/wujwyi/PA-RAG.

[Arxiv](https://arxiv.org/abs/2412.14510)