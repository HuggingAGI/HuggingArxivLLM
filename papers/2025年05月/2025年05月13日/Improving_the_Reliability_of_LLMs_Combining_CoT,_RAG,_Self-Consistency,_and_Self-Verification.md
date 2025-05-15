# 提升大型语言模型可靠性：融合CoT、RAG、自我一致性和自我验证

发布时间：2025年05月13日

`LLM应用` `生成技术`

> Improving the Reliability of LLMs: Combining CoT, RAG, Self-Consistency, and Self-Verification

# 摘要

> 大型语言模型（LLMs）生成自信但错误或不相关信息的幻觉现象依然存在，这依然是其在复杂开放任务应用中的主要障碍。思维链（CoT）提示法作为一种通过引导模型完成中间步骤来提升多步推理能力的方法，已显示出潜力。然而，仅靠CoT无法完全解决幻觉问题。本研究探讨了结合CoT与增强生成式检索（RAG），以及采用自我一致性和自我验证策略，能否减少幻觉并提升事实准确性。通过在推理过程中引入外部知识源，并使模型能够验证或修正自身输出，我们旨在生成更准确连贯的回应。本文对基线LLMs与CoT、CoT+RAG、自我一致性及自我验证技术进行了对比评估。结果显示，每种方法均具有效性，其中最稳健的方案能在保持流利性和推理深度的同时，显著减少幻觉。

> Hallucination, where large language models (LLMs) generate confident but incorrect or irrelevant information, remains a key limitation in their application to complex, open-ended tasks. Chain-of-thought (CoT) prompting has emerged as a promising method for improving multistep reasoning by guiding models through intermediate steps. However, CoT alone does not fully address the hallucination problem. In this work, we investigate how combining CoT with retrieval-augmented generation (RAG), as well as applying self-consistency and self-verification strategies, can reduce hallucinations and improve factual accuracy. By incorporating external knowledge sources during reasoning and enabling models to verify or revise their own outputs, we aim to generate more accurate and coherent responses. We present a comparative evaluation of baseline LLMs against CoT, CoT+RAG, self-consistency, and self-verification techniques. Our results highlight the effectiveness of each method and identify the most robust approach for minimizing hallucinations while preserving fluency and reasoning depth.

[Arxiv](https://arxiv.org/abs/2505.09031)