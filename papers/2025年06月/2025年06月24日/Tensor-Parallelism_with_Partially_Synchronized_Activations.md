# 张量并行：部分同步激活的实现与应用

发布时间：2025年06月24日

`LLM应用` `人工智能` `并行计算`

> Tensor-Parallelism with Partially Synchronized Activations

# 摘要

> 在使用张量并行训练和推理大型语言模型 (LLMs) 时，同步激活值需要大量通信。我们的研究发现，通过在现有方法上进行微调，可以实现不完全同步激活值的训练，从而降低带宽需求。我们将其命名为“张量并行通信感知架构”（CAAT-Net）。我们训练了 10 亿和 70 亿参数的 CAAT-Net 模型，将张量并行通信量减少了 50%，且预训练准确率没有显著下降。此外，我们展示了 CAAT-Net 如何加速训练和推理任务。

> Training and inference of Large Language Models (LLMs) with tensor-parallelism requires substantial communication to synchronize activations. Our findings suggest that with a few minor adjustments to current practices, LLMs can be trained without fully synchronizing activations, reducing bandwidth demands. We name this "Communication-Aware Architecture for Tensor-parallelism" (CAAT-Net). We train 1B and 7B parameter CAAT-Net models, with a 50% reduction in tensor-parallel communication and no significant drop in pretraining accuracy. Furthermore, we demonstrate how CAAT-Net accelerates both training and inference workloads.

[Arxiv](https://arxiv.org/abs/2506.19645)