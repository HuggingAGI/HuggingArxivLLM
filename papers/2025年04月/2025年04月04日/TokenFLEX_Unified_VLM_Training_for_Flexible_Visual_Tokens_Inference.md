# TokenFLEX：统一视觉语言模型训练，实现灵活视觉标记推理

发布时间：2025年04月04日

`LLM应用` `计算机视觉` `人工智能`

> TokenFLEX: Unified VLM Training for Flexible Visual Tokens Inference

# 摘要

> 传统视觉语言模型（VLMs）通常采用固定数量的视觉令牌，这种“一刀切”的方式无论面对简单还是复杂任务都显得力不从心。在简单任务中，过多的令牌会导致计算资源的浪费；而在复杂场景中，令牌数量不足又会影响模型对细节的理解。为了解决这一难题，我们提出了TokenFLEX，一个创新且灵活的视觉语言框架。它能根据图像内容自适应地生成不同数量的视觉令牌，从而实现与大型语言模型（LLM）的高效协同工作。

TokenFLEX的核心优势在于两大创新：首先，我们引入了一种全新的训练范式，通过在训练过程中随机调整视觉令牌的数量，使模型能够更好地适应不同数量的视觉信息；其次，我们设计了一个轻量级的视觉令牌投影器，其中包含自适应池化层和SwiGLU激活函数，能够灵活地对视觉令牌进行下采样，并根据具体的令牌数量自适应地选择最优特征。

实验结果表明，TokenFLEX在多种令牌数量设置下均优于传统固定令牌的模型。在64、144和256个令牌的配置下，TokenFLEX在八项视觉语言基准测试中的平均性能分别提升了1.6%、1.0%和0.4%。这些结果不仅证明了TokenFLEX的灵活性，更验证了其在高性能视觉语言理解任务中的有效性。


> Conventional Vision-Language Models(VLMs) typically utilize a fixed number of vision tokens, regardless of task complexity. This one-size-fits-all strategy introduces notable inefficiencies: using excessive tokens leads to unnecessary computational overhead in simpler tasks, whereas insufficient tokens compromise fine-grained visual comprehension in more complex contexts. To overcome these limitations, we present TokenFLEX, an innovative and adaptable vision-language framework that encodes images into a variable number of tokens for efficient integration with a Large Language Model (LLM). Our approach is underpinned by two pivotal innovations. Firstly, we present a novel training paradigm that enhances performance across varying numbers of vision tokens by stochastically modulating token counts during training. Secondly, we design a lightweight vision token projector incorporating an adaptive pooling layer and SwiGLU, allowing for flexible downsampling of vision tokens and adaptive selection of features tailored to specific token counts. Comprehensive experiments reveal that TokenFLEX consistently outperforms its fixed-token counterparts, achieving notable performance gains across various token counts enhancements of 1.6%, 1.0%, and 0.4% with 64, 144, and 256 tokens, respectively averaged over eight vision-language benchmarks. These results underscore TokenFLEX's remarkable flexibility while maintaining high-performance vision-language understanding.

[Arxiv](https://arxiv.org/abs/2504.03154)