# 解码流程：CauseMotion 助力长对话情感因果关系分析

发布时间：2025年01月01日

`RAG

理由：这篇论文提出了一个基于检索增强生成（RAG）和多模态融合的长序列情感因果推理框架，即CauseMotion。RAG是论文的核心技术之一，用于增强大规模语言模型在长序列情感因果推理中的表现。因此，这篇论文应归类为RAG。` `情感分析` `因果推理`

> Decoding the Flow: CauseMotion for Emotional Causality Analysis in Long-form Conversations

# 摘要

> # 摘要
长序列因果推理致力于揭示长时间序列数据中的因果关系，但复杂依赖性和因果链验证的挑战使其进展受阻。针对大规模语言模型（如GPT-4）在长对话中捕捉复杂情感因果关系的不足，我们提出了CauseMotion——一个基于检索增强生成（RAG）和多模态融合的长序列情感因果推理框架。与传统方法仅依赖文本不同，CauseMotion通过融合音频特征（如声音情感、情感强度和语速）来丰富语义表示。结合RAG与滑动窗口机制，它能够高效检索并利用上下文相关的对话片段，从而推断跨越多个对话轮次的复杂情感因果链。为验证其效果，我们构建了首个专注于长序列情感因果推理的基准数据集，包含超过70轮对话。实验表明，基于RAG的多模态集成方法显著提升了大规模语言模型的情感理解深度和因果推理能力。集成CauseMotion的GLM-4在因果准确性上比原始模型提升了8.7%，并超越GPT-4o 1.2%。此外，在公开的DiaASQ数据集上，CauseMotion-GLM-4在准确性、F1分数和因果推理准确性上均达到了业界领先水平。

> Long-sequence causal reasoning seeks to uncover causal relationships within extended time series data but is hindered by complex dependencies and the challenges of validating causal links. To address the limitations of large-scale language models (e.g., GPT-4) in capturing intricate emotional causality within extended dialogues, we propose CauseMotion, a long-sequence emotional causal reasoning framework grounded in Retrieval-Augmented Generation (RAG) and multimodal fusion. Unlike conventional methods relying only on textual information, CauseMotion enriches semantic representations by incorporating audio-derived features-vocal emotion, emotional intensity, and speech rate-into textual modalities. By integrating RAG with a sliding window mechanism, it effectively retrieves and leverages contextually relevant dialogue segments, thus enabling the inference of complex emotional causal chains spanning multiple conversational turns. To evaluate its effectiveness, we constructed the first benchmark dataset dedicated to long-sequence emotional causal reasoning, featuring dialogues with over 70 turns. Experimental results demonstrate that the proposed RAG-based multimodal integrated approach, the efficacy of substantially enhances both the depth of emotional understanding and the causal inference capabilities of large-scale language models. A GLM-4 integrated with CauseMotion achieves an 8.7% improvement in causal accuracy over the original model and surpasses GPT-4o by 1.2%. Additionally, on the publicly available DiaASQ dataset, CauseMotion-GLM-4 achieves state-of-the-art results in accuracy, F1 score, and causal reasoning accuracy.

[Arxiv](https://arxiv.org/abs/2501.00778)