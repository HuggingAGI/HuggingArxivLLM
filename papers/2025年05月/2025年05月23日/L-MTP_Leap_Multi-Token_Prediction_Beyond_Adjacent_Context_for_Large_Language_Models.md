# # L-MTP：助力大型语言模型，跨越多标记预测能力，突破相邻上下文限制

发布时间：2025年05月23日

`LLM理论`

> L-MTP: Leap Multi-Token Prediction Beyond Adjacent Context for Large Language Models

# 摘要

> 大型语言模型（LLMs）已取得显著进展，但其主要依赖的下一时刻预测（NTP）方法因固有的顺序性而面临上下文覆盖和推理效率的限制。为突破这些限制，我们提出了一种创新的基于跳跃的多时刻预测（L-MTP）方法，通过引入跳跃机制扩展传统多时刻预测（MTP）的能力。与传统MTP生成相邻时刻不同，L-MTP在单次前向传递中跳过中间时刻，预测非连续时刻。这种结构化跳跃不仅提升了模型捕捉长距离依赖的能力，还支持了专门针对非连续跳跃时刻生成的优化解码策略，从而显著加速推理。我们从理论上证明了L-MTP在提升推理效率方面的优势，并通过多样化基准实验验证了其在增强LLMs性能和推理速度方面的效果。源代码即将公开发布。

> Large language models (LLMs) have achieved notable progress. Despite their success, next-token prediction (NTP), the dominant method for LLM training and inference, is constrained in both contextual coverage and inference efficiency due to its inherently sequential process. To overcome these challenges, we propose leap multi-token prediction~(L-MTP), an innovative token prediction method that extends the capabilities of multi-token prediction (MTP) by introducing a leap-based mechanism. Unlike conventional MTP, which generates multiple tokens at adjacent positions, L-MTP strategically skips over intermediate tokens, predicting non-sequential ones in a single forward pass. This structured leap not only enhances the model's ability to capture long-range dependencies but also enables a decoding strategy specially optimized for non-sequential leap token generation, effectively accelerating inference. We theoretically demonstrate the benefit of L-MTP in improving inference efficiency. Experiments across diverse benchmarks validate its merit in boosting both LLM performance and inference speed. The source code will be publicly available.

[Arxiv](https://arxiv.org/abs/2505.17505)