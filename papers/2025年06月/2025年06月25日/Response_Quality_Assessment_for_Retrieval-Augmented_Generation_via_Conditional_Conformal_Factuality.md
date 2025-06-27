# 通过条件符合事实性方法评估检索增强生成的响应质量

发布时间：2025年06月25日

`RAG` `问答系统` `信息检索`

> Response Quality Assessment for Retrieval-Augmented Generation via Conditional Conformal Factuality

# 摘要

> 目前对检索增强生成（RAG）的研究主要关注提升整体问答准确性，却忽视了生成响应中子声明的质量。现有提升RAG可信度的方法，如自动评估指标，要么缺乏概率保证，要么依赖真实答案。为解决这些问题，我们提出了Conformal-RAG，一个受符合性预测（CP）启发的创新框架。该框架利用CP和RAG机制的内部信息，为响应质量提供统计保证，确保在多个子领域上的覆盖，无需人工标注，适用于复杂场景。与现有方法相比，Conformal-RAG不仅为子声明质量提供统计保证，还保留了高达60%的高质量子声明，可靠性无虞。实验表明，Conformal-RAG在保持可靠性的同时，显著提升了响应质量。

> Existing research on Retrieval-Augmented Generation (RAG) primarily focuses on improving overall question-answering accuracy, often overlooking the quality of sub-claims within generated responses. Recent methods that attempt to improve RAG trustworthiness, such as through auto-evaluation metrics, lack probabilistic guarantees or require ground truth answers. To address these limitations, we propose Conformal-RAG, a novel framework inspired by recent applications of conformal prediction (CP) on large language models (LLMs). Conformal-RAG leverages CP and internal information from the RAG mechanism to offer statistical guarantees on response quality. It ensures group-conditional coverage spanning multiple sub-domains without requiring manual labelling of conformal sets, making it suitable for complex RAG applications. Compared to existing RAG auto-evaluation methods, Conformal-RAG offers statistical guarantees on the quality of refined sub-claims, ensuring response reliability without the need for ground truth answers. Additionally, our experiments demonstrate that by leveraging information from the RAG system, Conformal-RAG retains up to 60\% more high-quality sub-claims from the response compared to direct applications of CP to LLMs, while maintaining the same reliability guarantee.

[Arxiv](https://arxiv.org/abs/2506.20978)