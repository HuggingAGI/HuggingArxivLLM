# 大型语言模型能预测司法判决的结果吗？

发布时间：2025年01月15日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在特定任务（阿拉伯语法律判决预测）中的应用，包括数据集的构建、模型的微调、评估框架的设计等。研究重点在于如何通过微调和提示工程来提升模型在特定任务中的性能，并公开了相关资源以支持未来的研究。这些内容都属于LLM在实际任务中的应用和优化，因此分类为“LLM应用”。`

> Can Large Language Models Predict the Outcome of Judicial Decisions?

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）的多个领域展现了卓越能力，但在低资源语言（如阿拉伯语）的法律判决预测（LJP）等特定任务中的应用仍待深入探索。本研究通过构建一个基于沙特商业法院判决的阿拉伯语LJP数据集，填补了这一空白。我们对LLaMA-3.2-3B和LLaMA-3.1-8B等开源LLMs进行了基准测试，涵盖零-shot、one-shot及QLoRA微调等多种配置。同时，我们采用了一个结合定量指标（如BLEU和ROUGE）与定性评估（如连贯性、法律语言和清晰度）的综合评估框架。结果显示，在特定任务中，经过微调的较小模型能够达到与大型模型相当的性能，同时显著提升了资源效率。此外，我们还探讨了提示工程和微调对模型输出的影响，揭示了性能变异性和指令敏感性的内在机制。通过公开数据集、代码和模型，我们为未来阿拉伯语法律NLP研究提供了坚实的基础。

> Large Language Models (LLMs) have shown exceptional capabilities in Natural Language Processing (NLP) across diverse domains. However, their application in specialized tasks such as Legal Judgment Prediction (LJP) for low-resource languages like Arabic remains underexplored. In this work, we address this gap by developing an Arabic LJP dataset, collected and preprocessed from Saudi commercial court judgments. We benchmark state-of-the-art open-source LLMs, including LLaMA-3.2-3B and LLaMA-3.1-8B, under varying configurations such as zero-shot, one-shot, and fine-tuning using QLoRA. Additionally, we used a comprehensive evaluation framework combining quantitative metrics (BLEU and ROUGE) and qualitative assessments (Coherence, legal language, clarity). Our results demonstrate that fine-tuned smaller models achieve comparable performance to larger models in task-specific contexts while offering significant resource efficiency. Furthermore, we investigate the effects of prompt engineering and fine-tuning on model outputs, providing insights into performance variability and instruction sensitivity. By making the dataset, implementation code, and models publicly available, we establish a robust foundation for future research in Arabic legal NLP.

[Arxiv](https://arxiv.org/abs/2501.09768)