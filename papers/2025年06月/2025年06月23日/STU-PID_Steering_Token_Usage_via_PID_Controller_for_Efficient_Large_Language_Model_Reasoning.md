# STU-PID：通过PID控制器优化令牌使用，提升大语言模型推理效率

发布时间：2025年06月23日

`LLM应用` `人工智能`

> STU-PID: Steering Token Usage via PID Controller for Efficient Large Language Model Reasoning

# 摘要

> 采用扩展链式思维（CoT）推理的大语言模型（LLMs）容易陷入过度思考的问题，不仅生成大量冗余推理步骤，还显著增加了计算成本并可能降低模型性能。尽管近期研究探索了静态引导方法来缓解这一问题，但它们缺乏根据实时推理质量动态调整干预强度的适应性。我们提出了一种无训练的新型方法 STUPID（通过 PID 控制器调节引导令牌使用），该方法在推理过程中利用 PID 控制器动态调节激活引导强度。我们的方法结合了用于检测冗余推理模式的分块级分类器，以及基于预测冗余概率自适应调整引导强度的 PID 控制机制。在 GSM8K 上的实验评估表明，与静态引导基线相比，STUPID 实现了 6% 的准确率提升，同时将令牌使用量减少了 32%。我们的方法为动态推理校准提供了一个原理性框架，在保持推理质量的同时显著提高了计算效率。

> Large Language Models employing extended chain-of-thought (CoT) reasoning often suffer from the overthinking phenomenon, generating excessive and redundant reasoning steps that increase computational costs while potentially degrading performance. While recent work has explored static steering approaches to mitigate this issue, they lack the adaptability to dynamically adjust intervention strength based on real-time reasoning quality. We propose STUPID (Steering Token Usage via PID controller), a novel training-free method that employs a PID controller to dynamically modulate activation steering strength during inference. Our approach combines a chunk-level classifier for detecting redundant reasoning patterns with a PID control mechanism that adaptively adjusts steering intensity based on the predicted redundancy probability. Experimental evaluation on GSM8K demonstrates that STUPID achieves a 6% improvement in accuracy while reducing token usage by 32%, outperforming static steering baselines. Our method provides a principled framework for dynamic reasoning calibration that maintains reasoning quality while significantly improving computational efficiency.

[Arxiv](https://arxiv.org/abs/2506.18831)