# STU-PID：利用PID控制器优化大型语言模型推理中的令牌使用，实现高效推理

发布时间：2025年06月23日

`LLM应用

摘要讨论了大型语言模型（LLM）在链式思维推理中的优化，提出了一种动态调节方法，属于应用层面的改进，因此归类为LLM应用。` `人工智能`

> STU-PID: Steering Token Usage via PID Controller for Efficient Large Language Model Reasoning

# 摘要

> 采用扩展链式思维（CoT）推理的大型语言模型常出现过度思考问题，导致生成大量冗余推理步骤，不仅增加计算成本，还可能影响性能表现。尽管近期研究尝试通过静态引导方法来缓解这一问题，但这些方法缺乏根据实时推理质量动态调整干预强度的能力。我们提出了一种无训练的创新方法——STUPID（通过PID控制器引导令牌使用），该方法利用PID控制器在推理过程中动态调节激活引导强度。我们的方法结合了用于检测冗余推理模式的分块级分类器，以及基于预测冗余概率自适应调整引导强度的PID控制机制。在GSM8K数据集上的实验结果显示，与静态引导基线相比，STUPID不仅将准确性提升了6%，还将令牌使用量减少了32%。我们的方法为动态推理校准提供了一个原理性框架，在保持推理质量的同时显著提升了计算效率。

> Large Language Models employing extended chain-of-thought (CoT) reasoning often suffer from the overthinking phenomenon, generating excessive and redundant reasoning steps that increase computational costs while potentially degrading performance. While recent work has explored static steering approaches to mitigate this issue, they lack the adaptability to dynamically adjust intervention strength based on real-time reasoning quality. We propose STUPID (Steering Token Usage via PID controller), a novel training-free method that employs a PID controller to dynamically modulate activation steering strength during inference. Our approach combines a chunk-level classifier for detecting redundant reasoning patterns with a PID control mechanism that adaptively adjusts steering intensity based on the predicted redundancy probability. Experimental evaluation on GSM8K demonstrates that STUPID achieves a 6% improvement in accuracy while reducing token usage by 32%, outperforming static steering baselines. Our method provides a principled framework for dynamic reasoning calibration that maintains reasoning quality while significantly improving computational efficiency.

[Arxiv](https://arxiv.org/abs/2506.18831)