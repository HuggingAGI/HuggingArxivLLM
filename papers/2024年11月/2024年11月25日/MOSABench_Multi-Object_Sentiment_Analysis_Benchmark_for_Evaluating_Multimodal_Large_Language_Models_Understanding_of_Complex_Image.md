# MOSABench：用于评估多模态大型语言模型对复杂图像理解能力的多目标情感分析基准

发布时间：2024年11月25日

`LLM应用` `情感分析` `图像识别`

> MOSABench: Multi-Object Sentiment Analysis Benchmark for Evaluating Multimodal Large Language Models Understanding of Complex Image

# 摘要

> 多模态大型语言模型（MLLMs）在视觉问答、图像字幕、情感识别等高阶语义任务方面进展显著。然而，即便有所进步，在多对象情感分析这一语义理解的关键任务上，评估 MLLMs 性能的标准化基准仍缺失。为此，我们推出了 MOSABench，这是专为多对象情感分析打造的全新评估数据集。MOSABench 涵盖约 1000 张含多个对象的图像，要求 MLLMs 分别评估每个对象的情感，以此反映现实世界的复杂性。MOSABench 的关键创新点有基于距离的目标标注、用于规范输出的评估后处理以及优化的评分机制。我们的实验表明当前 MLLMs 存在明显局限：诸如 mPLUG-owl 和 Qwen-VL2 等部分模型能有效关注与情感相关的特征，而其他模型则出现注意力分散和性能下滑的情况，特别是当对象间的空间距离增大时。本研究凸显了 MLLMs 在复杂多对象情感分析任务中提升准确性的必要性，并将 MOSABench 确立为提升 MLLMs 情感分析能力的基础工具。

> Multimodal large language models (MLLMs) have shown remarkable progress in high-level semantic tasks such as visual question answering, image captioning, and emotion recognition. However, despite advancements, there remains a lack of standardized benchmarks for evaluating MLLMs performance in multi-object sentiment analysis, a key task in semantic understanding. To address this gap, we introduce MOSABench, a novel evaluation dataset designed specifically for multi-object sentiment analysis. MOSABench includes approximately 1,000 images with multiple objects, requiring MLLMs to independently assess the sentiment of each object, thereby reflecting real-world complexities. Key innovations in MOSABench include distance-based target annotation, post-processing for evaluation to standardize outputs, and an improved scoring mechanism. Our experiments reveal notable limitations in current MLLMs: while some models, like mPLUG-owl and Qwen-VL2, demonstrate effective attention to sentiment-relevant features, others exhibit scattered focus and performance declines, especially as the spatial distance between objects increases. This research underscores the need for MLLMs to enhance accuracy in complex, multi-object sentiment analysis tasks and establishes MOSABench as a foundational tool for advancing sentiment analysis capabilities in MLLMs.

[Arxiv](https://arxiv.org/abs/2412.00060)