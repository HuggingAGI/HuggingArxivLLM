# MoTE：内存高效的大型多模态模型三元专家混合方案

发布时间：2025年06月17日

`LLM应用` `模型优化`

> MoTE: Mixture of Ternary Experts for Memory-efficient Large Multimodal Models

# 摘要

> 大规模多模态专家混合模型（MoEs）在扩大模型规模的同时保持了性能提升，但之前的方法主要依赖全精度专家进行稀疏升级。尽管这些方法在最终任务中表现出色，但它们的内存占用较高，给边缘设备的部署带来了挑战。为此，我们提出了MoTE方法，一种可扩展且内存高效的解决方案，用于从密集检查点训练三元专家混合模型。我们建议在升级过程中训练更多的低精度专家，而不是训练更少的高精度专家。具体来说，我们采用预训练的FFN作为共享专家，并训练参数为{-1, 0, 1}的三元路由专家。大量实验表明，我们的方法在模型规模上展现出良好的扩展趋势。MoTE在性能上与全精度基线MoE-LLaVA相当，同时占用更少的内存。此外，该方法还与后训练量化方法兼容，且当内存约束进一步降低时，优势会进一步放大。在相同的3.4GB专家内存占用下，并结合后训练量化方法，MoTE在最终任务上的平均准确率提高了4.3%，优于MoE-LLaVA，这证明了其在内存受限设备上的有效性和应用潜力。

> Large multimodal Mixture-of-Experts (MoEs) effectively scale the model size to boost performance while maintaining fixed active parameters. However, previous works primarily utilized full-precision experts during sparse up-cycling. Despite they show superior performance on end tasks, the large amount of experts introduces higher memory footprint, which poses significant challenges for the deployment on edge devices. In this work, we propose MoTE, a scalable and memory-efficient approach to train Mixture-of-Ternary-Experts models from dense checkpoint. Instead of training fewer high-precision experts, we propose to train more low-precision experts during up-cycling. Specifically, we use the pre-trained FFN as a shared expert and train ternary routed experts with parameters in {-1, 0, 1}. Extensive experiments show that our approach has promising scaling trend along model size. MoTE achieves comparable performance to full-precision baseline MoE-LLaVA while offering lower memory footprint. Furthermore, our approach is compatible with post-training quantization methods and the advantage further amplifies when memory-constraint goes lower. Given the same amount of expert memory footprint of 3.4GB and combined with post-training quantization, MoTE outperforms MoE-LLaVA by a gain of 4.3% average accuracy on end tasks, demonstrating its effectiveness and potential for memory-constrained devices.

[Arxiv](https://arxiv.org/abs/2506.14435)