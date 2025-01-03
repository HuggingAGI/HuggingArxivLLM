# 时间上下文一致性至上：通过学习和执行时间约束提升长期预测能力

发布时间：2024年12月26日

`其他

理由：这篇论文主要讨论的是长期动作预测（LTA）方法，涉及视频片段的分析和动作标签及其持续时间的预测。虽然提到了基于大型语言模型的方法，但论文的核心内容并不直接涉及LLM的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。因此，将其分类为“其他”更为合适。` `视频分析` `动作预测`

> Temporal Context Consistency Above All: Enhancing Long-Term Anticipation by Learning and Enforcing Temporal Constraints

# 摘要

> 本文提出了一种长期动作预测（LTA）方法，旨在预测给定初始未剪辑视频片段后的动作标签及其持续时间。我们基于并行解码的编码器-解码器架构，并做出了两个关键贡献：首先，我们在解码器顶部引入了一个双向动作上下文正则化模块，确保时间相邻片段的时间上下文一致性；其次，我们从分类片段中学习一个转移矩阵，模拟动作转移概率，并在整个预测区间内全局优化序列。此外，我们使用了一个专门用于动作分割的编码器，以提高推理时观察区间内的预测质量，从而更好地理解过去。我们在EpicKitchen-55、EGTEA+、50Salads和Breakfast四个LTA基准数据集上验证了方法，展示了优于或与最先进方法相当的性能，这些方法包括概率模型和基于大型语言模型的方法，且假设输入为剪辑后的视频。代码将在接受后发布。

> This paper proposes a method for long-term action anticipation (LTA), the task of predicting action labels and their duration in a video given the observation of an initial untrimmed video interval. We build on an encoder-decoder architecture with parallel decoding and make two key contributions. First, we introduce a bi-directional action context regularizer module on the top of the decoder that ensures temporal context coherence in temporally adjacent segments. Second, we learn from classified segments a transition matrix that models the probability of transitioning from one action to another and the sequence is optimized globally over the full prediction interval. In addition, we use a specialized encoder for the task of action segmentation to increase the quality of the predictions in the observation interval at inference time, leading to a better understanding of the past. We validate our methods on four benchmark datasets for LTA, the EpicKitchen-55, EGTEA+, 50Salads and Breakfast demonstrating superior or comparable performance to state-of-the-art methods, including probabilistic models and also those based on Large Language Models, that assume trimmed video as input. The code will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2412.19424)