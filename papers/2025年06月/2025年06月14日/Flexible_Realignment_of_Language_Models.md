# # 语言模型的灵活重新对齐

发布时间：2025年06月14日

`LLM理论

理由：这篇论文讨论了语言模型的重新对齐方法，提出了一种灵活的重新对齐框架，涉及模型的训练和推理过程中的对齐控制。这属于大型语言模型的理论和训练方法的研究。` `人工智能` `模型优化`

> Flexible Realignment of Language Models

# 摘要

> 当语言模型的表现未达预期时，重新对齐就显得尤为重要。我们提出了一种灵活的重新对齐框架，支持在训练和推理过程中对对齐程度进行定量控制。该框架集成了训练时对齐（TrRa），通过利用参考模型和已对齐模型的logits可控融合，高效地重新对齐参考模型。例如，在DeepSeek-R1-Distill-Qwen-1.5B上，TrRa减少了54.63%的token使用量，且未导致性能下降，优于DeepScaleR-1.5B的33.86%。为了在推理时补充TrRa，我们引入了一个层适配器，支持平滑的推理时对齐（InRa）。该适配器初始化为在底部层执行恒等变换，并插入在原始层之前。在推理过程中，输入嵌入同时由适配器和原始层处理，随后经过剩余层，并在logit级别进行可控插值。我们将DeepSeek-R1-Distill-Qwen-7B从一个慢思维模型升级为支持快思维和慢思维的模型，即使在推理过程中也实现了灵活的对齐控制。通过鼓励更深入的推理，其性能甚至超越了原始水平。

> Realignment becomes necessary when a language model (LM) fails to meet expected performance. We propose a flexible realignment framework that supports quantitative control of alignment degree during training and inference. This framework incorporates Training-time Realignment (TrRa), which efficiently realigns the reference model by leveraging the controllable fusion of logits from both the reference and already aligned models. For example, TrRa reduces token usage by 54.63% on DeepSeek-R1-Distill-Qwen-1.5B without any performance degradation, outperforming DeepScaleR-1.5B's 33.86%. To complement TrRa during inference, we introduce a layer adapter that enables smooth Inference-time Realignment (InRa). This adapter is initialized to perform an identity transformation at the bottom layer and is inserted preceding the original layers. During inference, input embeddings are simultaneously processed by the adapter and the original layer, followed by the remaining layers, and then controllably interpolated at the logit level. We upgraded DeepSeek-R1-Distill-Qwen-7B from a slow-thinking model to one that supports both fast and slow thinking, allowing flexible alignment control even during inference. By encouraging deeper reasoning, it even surpassed its original performance.

[Arxiv](https://arxiv.org/abs/2506.12704)