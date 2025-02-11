# # 透明NLP：利用RAG与LLM对齐技术实现隐私保护问答

发布时间：2025年02月10日

`RAG` `隐私保护`

> Transparent NLP: Using RAG and LLM Alignment for Privacy Q&A

# 摘要

> 《通用数据保护条例》(GDPR)要求数据处理信息清晰、准确且易于获取。语言模型虽有潜力，但其概率性质使真实性和可理解性面临挑战。本文研究了结合对齐技术的先进检索增强生成(RAG)系统，以满足GDPR要求。我们使用隐私问答数据集，评估了集成类似可逆自回归推理(RAIN)对齐模块的RAG系统，以及我们的多维扩展MultiRAIN。通过优化准确性和可理解性，并采用21个指标（包括确定性和大型语言模型基线评估）进行评估。结果显示，配备对齐模块的RAG系统在大多数指标上优于基线系统，但尚未完全匹配人类回答。主成分分析揭示了指标间的复杂交互，强调了完善评估指标的必要性。这项研究为将先进自然语言处理系统整合到法律合规框架中奠定了基础。

> The transparency principle of the General Data Protection Regulation (GDPR) requires data processing information to be clear, precise, and accessible. While language models show promise in this context, their probabilistic nature complicates truthfulness and comprehensibility.
  This paper examines state-of-the-art Retrieval Augmented Generation (RAG) systems enhanced with alignment techniques to fulfill GDPR obligations. We evaluate RAG systems incorporating an alignment module like Rewindable Auto-regressive Inference (RAIN) and our proposed multidimensional extension, MultiRAIN, using a Privacy Q&A dataset. Responses are optimized for preciseness and comprehensibility and are assessed through 21 metrics, including deterministic and large language model-based evaluations.
  Our results show that RAG systems with an alignment module outperform baseline RAG systems on most metrics, though none fully match human answers. Principal component analysis of the results reveals complex interactions between metrics, highlighting the need to refine metrics. This study provides a foundation for integrating advanced natural language processing systems into legal compliance frameworks.

[Arxiv](https://arxiv.org/abs/2502.06652)