# # 各层独立调整位置编码，提升长上下文建模性能

发布时间：2025年03月06日

`LLM理论` `长文本处理`

> Layer-Specific Scaling of Positional Encodings for Superior Long-Context Modeling

# 摘要

> 尽管大型语言模型（LLMs）在处理长上下文输入方面取得了显著进展，但“中间信息丢失”问题依然存在，即上下文中关键的中间信息常常被低估或丢失。我们通过大量实验发现，这一问题可能源于旋转位置编码（RoPE）中长期衰减的快速下降。为了解决这一问题，我们提出了一种分层特定的位置编码缩放方法，为每一层分配不同的缩放因子，从而减缓RoPE引起的衰减速率，使模型更关注中间上下文。我们还特别设计了一种遗传算法，通过引入贝塞尔曲线来缩小搜索空间，从而高效地为每一层选择最优的缩放因子。通过全面的实验，我们证明了我们的方法显著缓解了“中间信息丢失”问题。在键值检索数据集上，我们的方法平均准确率提升了高达20%。此外，我们还展示了分层插值相较于所有层统一插值的优势：当与位置感应（PI）和动态NTK位置编码方案结合时，它能更好地提升模型的外推能力。

> Although large language models (LLMs) have achieved significant progress in handling long-context inputs, they still suffer from the ``lost-in-the-middle'' problem, where crucial information in the middle of the context is often underrepresented or lost. Our extensive experiments reveal that this issue may arise from the rapid long-term decay in Rotary Position Embedding (RoPE). To address this problem, we propose a layer-specific positional encoding scaling method that assigns distinct scaling factors to each layer, slowing down the decay rate caused by RoPE to make the model pay more attention to the middle context. A specially designed genetic algorithm is employed to efficiently select the optimal scaling factors for each layer by incorporating Bezier curves to reduce the search space. Through comprehensive experimentation, we demonstrate that our method significantly alleviates the ``lost-in-the-middle'' problem. Our approach results in an average accuracy improvement of up to 20% on the Key-Value Retrieval dataset. Furthermore, we show that layer-specific interpolation, as opposed to uniform interpolation across all layers, enhances the model's extrapolation capabilities when combined with PI and Dynamic-NTK positional encoding schemes.

[Arxiv](https://arxiv.org/abs/2503.04355)