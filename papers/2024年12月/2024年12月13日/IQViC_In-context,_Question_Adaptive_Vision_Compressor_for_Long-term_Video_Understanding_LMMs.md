# IQViC：适用于长期视频理解 LMMs 的上下文内、问题自适应视觉压缩器

发布时间：2024年12月13日

`LLM应用` `问答系统`

> IQViC: In-context, Question Adaptive Vision Compressor for Long-term Video Understanding LMMs

# 摘要

> 随着视频数据愈发复杂，对更高效的长期时间理解的需求也日益增长，现有的长期视频理解方法常常难以精确捕捉和分析较长的视频序列。这些方法通常在长时间内难以维持性能，也难以处理视频内容中的复杂依赖关系。为应对这些局限，我们提出了一个简洁而有效的用于长期视频理解的大型多模态模型框架，它融合了一种新颖的视觉压缩器——上下文内、问题自适应视觉压缩器（IQViC）。其核心思路受人类的选择性注意和上下文内记忆机制启发，即引入全新的视觉压缩器，并融入高效的内存管理技术，以强化长期视频问答能力。我们的框架运用了基于变压器的视觉压缩器 IQViC，能够实现基于问题条件的上下文内压缩，这与依赖完整视频视觉特征的现有方法不同。它能有针对性地提取相关信息，大幅降低内存令牌需求。通过在基于 InfiniBench 的新数据集上针对长期视频理解展开的大量实验，以及用于评估现有方法的标准基准，我们证实了所提出的 IQViC 框架的有效性，及其在视频理解准确性和内存效率方面相较最先进方法的优越性。

> With the increasing complexity of video data and the need for more efficient long-term temporal understanding, existing long-term video understanding methods often fail to accurately capture and analyze extended video sequences. These methods typically struggle to maintain performance over longer durations and to handle the intricate dependencies within the video content. To address these limitations, we propose a simple yet effective large multi-modal model framework for long-term video understanding that incorporates a novel visual compressor, the In-context, Question Adaptive Visual Compressor (IQViC). The key idea, inspired by humans' selective attention and in-context memory mechanisms, is to introduce a novel visual compressor and incorporate efficient memory management techniques to enhance long-term video question answering. Our framework utilizes IQViC, a transformer-based visual compressor, enabling question-conditioned in-context compression, unlike existing methods that rely on full video visual features. This selectively extracts relevant information, significantly reducing memory token requirements. Through extensive experiments on a new dataset based on InfiniBench for long-term video understanding, and standard benchmarks used for existing methods' evaluation, we demonstrate the effectiveness of our proposed IQViC framework and its superiority over state-of-the-art methods in terms of video understanding accuracy and memory efficiency.

[Arxiv](https://arxiv.org/abs/2412.09907)