# ReGATE：用更少的令牌，实现多语言模型更高效、更优质的训练效果

发布时间：2025年07月28日

`LLM应用

理由：这篇论文提出了一种新的训练优化方法ReGATE，用于加速多模态大型语言模型的训练。它专注于在训练阶段减少计算开销，通过自适应Token剪枝来提升效率，属于LLM应用层面的优化方法。` `人工智能` `模型训练`

> ReGATE: Learning Faster and Better with Fewer Tokens in MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）的训练成本随着token数量的增加而迅速攀升。现有优化方法主要针对推理阶段，依赖于减少或合并token，对训练阶段的帮助有限。本文提出了一种名为ReGATE（参考引导自适应Token删除）的自适应Token剪枝方法，旨在加速MLLM训练。ReGATE采用教师-学生框架，将正在训练的MLLM设为学生，冻结的参考大型语言模型（LLM）作为教师。教师计算每个token的参考损失，并与学生自身难度分数的指数移动平均（EMA）结合，形成自适应难度评分机制。这使得在前向传播中可以选择性地处理关键token，跳过信息量较少的token，从而大幅降低计算开销。实验结果表明，ReGATE应用于VideoLLaMA2时，在MVBench上达到标准训练的峰值精度，速度提升2倍，仅使用35%的token。通过额外训练，它甚至在多个多模态基准测试中超越基线，同时将总token数量减少了41%以上。代码和模型即将发布。

> The computational cost of training multimodal large language models (MLLMs) rapidly increases with the number of tokens involved. Existing efficiency methods primarily target inference and rely on token reduction or merging, offering limited benefit during training. In this paper, we propose ReGATE (Reference$-$Guided Adaptive Token Elision), an adaptive token pruning method for accelerating MLLM training. Specifically, ReGATE adopts a teacher-student framework in which the MLLM being trained serves as the student, and a frozen reference large language model (LLM) acts as the teacher. The teacher computes per-token reference losses, which are combined with an exponential moving average (EMA) of the student's own difficulty scores. This adaptive difficulty-based scoring enables the selective processing of crucial tokens while bypassing less informative ones in the forward pass, significantly reducing computational overhead. Experiments demonstrate that ReGATE, when applied to VideoLLaMA2, matches the peak accuracy of standard training on MVBench up to 2$\times$ faster, using only 35% of the tokens. With additional training, it even surpasses the baseline on several multimodal benchmarks, all while reducing the total token count by over 41%. Code and models will be released soon.

[Arxiv](https://arxiv.org/abs/2507.21420)