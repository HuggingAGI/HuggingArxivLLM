# RSQ: 学习重要标记助力打造更优量化大语言模型

发布时间：2025年03月03日

`LLM理论` `模型压缩` `大型语言模型`

> RSQ: Learning from Important Tokens Leads to Better Quantized LLMs

# 摘要

> 层量化是高效压缩大型模型而不需昂贵重新训练的关键技术。传统方法通常采用均匀优化策略，对所有输出标记进行层重建损失优化以实现各层权重量化。然而，我们发现，通过优先关注重要标记（如具有较大注意力分数的标记）的学习，可以获得更优的量化效果。基于这一发现，我们提出了一种名为RSQ（旋转、缩放、量化）的新方法。RSQ包含三个步骤：（1）通过正交变换对模型进行旋转以缓解异常值问题，（2）根据标记的重要性对其进行特征缩放，（3）结合GPTQ框架，利用缩放后标记计算的第二阶统计量完成模型量化。在标记重要性计算方面，我们探索了多种策略，最终采用注意力集中度作为最佳方案，即以每个标记的注意力分数作为其重要性指标。实验结果表明，RSQ在多个下游任务和LLaMA3、Mistral、Qwen2.5等多种模型家族中均显著优于传统方法。此外，RSQ在长上下文任务中的卓越表现进一步验证了其有效性。值得注意的是，RSQ在不同模型规模、校准数据集、位精度和量化方法等多种设置下均展现出良好的泛化能力。

> Layer-wise quantization is a key technique for efficiently compressing large models without expensive retraining. Previous methods typically quantize the weights of each layer by "uniformly" optimizing the layer reconstruction loss across all output tokens. However, in this paper, we demonstrate that better-quantized models can be obtained by prioritizing learning from important tokens (e.g. which have large attention scores). Building on this finding, we propose RSQ (Rotate, Scale, then Quantize), which (1) applies rotations (orthogonal transformation) to the model to mitigate outliers (those with exceptionally large magnitude), (2) scales the token feature based on its importance, and (3) quantizes the model using the GPTQ framework with the second-order statistics computed by scaled tokens. To compute token importance, we explore both heuristic and dynamic strategies. Based on a thorough analysis of all approaches, we adopt attention concentration, which uses attention scores of each token as its importance, as the best approach. We demonstrate that RSQ consistently outperforms baseline methods across multiple downstream tasks and three model families: LLaMA3, Mistral, and Qwen2.5. Additionally, models quantized with RSQ achieve superior performance on long-context tasks, further highlighting its effectiveness. Lastly, RSQ demonstrates generalizability across various setups, including different model sizes, calibration datasets, bit precisions, and quantization methods.

[Arxiv](https://arxiv.org/abs/2503.01820)