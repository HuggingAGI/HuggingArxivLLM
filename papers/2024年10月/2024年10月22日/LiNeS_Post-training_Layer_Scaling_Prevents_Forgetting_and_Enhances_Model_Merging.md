# LiNeS：训练后层缩放技术，防止遗忘并提升模型合并效果

发布时间：2024年10月22日

`LLM理论

**理由**：该论文主要讨论了如何通过后训练编辑技术（LiNeS）来缓解大型预训练模型在微调过程中出现的灾难性遗忘问题，并提升模型的泛化能力。这涉及到对大型语言模型（LLM）的理论改进和优化，属于对LLM内部机制和训练方法的研究，因此应归类为LLM理论。` `计算机视觉`

> LiNeS: Post-training Layer Scaling Prevents Forgetting and Enhances Model Merging

# 摘要

> 大型预训练模型在多种任务中表现出色，但微调常引发灾难性遗忘，即目标领域的改进会削弱其他任务的泛化能力。为此，我们提出了LiNeS（层递增网络缩放），一种后训练编辑技术，旨在保持预训练泛化能力的同时提升微调任务性能。LiNeS根据网络层深度线性调整参数更新，浅层保持接近预训练值以保留通用特征，深层则保留任务特定表示。我们还将此方法扩展到多任务模型合并场景，通过逐层缩放合并参数减少任务间干扰。LiNeS在视觉和自然语言处理的多个基准测试中，无论是单任务还是多任务设置，均表现出显著提升。它有效缓解了遗忘问题，增强了分布外泛化能力，并能无缝集成到现有多任务模型合并基线中，提升其性能。此外，LiNeS还能通过RLHF合并与不同奖励对齐的LLM策略，进一步提升泛化能力。重要的是，该方法实现简单，且与现有技术高度兼容。

> Large pre-trained models exhibit impressive zero-shot performance across diverse tasks, but fine-tuning often leads to catastrophic forgetting, where improvements on a target domain degrade generalization on other tasks. To address this challenge, we introduce LiNeS, Layer-increasing Network Scaling, a post-training editing technique designed to preserve pre-trained generalization while enhancing fine-tuned task performance. LiNeS scales parameter updates linearly based on their layer depth within the network, maintaining shallow layers close to their pre-trained values to preserve general features while allowing deeper layers to retain task-specific representations. We further extend this approach to multi-task model merging scenarios, where layer-wise scaling of merged parameters reduces negative task interference. LiNeS demonstrates significant improvements in both single-task and multi-task settings across various benchmarks in vision and natural language processing. It mitigates forgetting, enhances out-of-distribution generalization, integrates seamlessly with existing multi-task model merging baselines improving their performance across benchmarks and model sizes, and can boost generalization when merging LLM policies aligned with different rewards via RLHF. Importantly, our method is simple to implement and complementary to many existing techniques.

[Arxiv](https://arxiv.org/abs/2410.17146)