# 无需再用 Adam：初始化时的学习率缩放就足够了

发布时间：2024年12月16日

`LLM应用` `优化器`

> No More Adam: Learning Rate Scaling at Initialization is All You Need

# 摘要

> 在这项工作中，我们对训练深度神经网络时自适应梯度方法的必要性提出了质疑。SGD-SaI 是对带有动量的随机梯度下降（SGDM）的一种简便且有效的强化。SGD-SaI 在初始化时依据各自的梯度信噪比（g-SNR）对不同参数组进行学习率缩放（SaI）。通过不依赖自适应二阶动量来调整学习率，SGD-SaI 从首次迭代起就能防止训练失衡，且与 AdamW 相比，优化器的内存使用量减半。尽管简单高效，SGD-SaI 在训练各类基于 Transformer 的任务时，始终能与 AdamW 持平甚至更优，成功克服了用 SGD 训练 Transformer 的长期难题。SGD-SaI 在 Vision Transformers（ViT）的 ImageNet-1K 分类以及大型语言模型（LLMs，仅解码器的 Transformer）的 GPT-2 预训练中表现卓越，展现出对超参数变化的强适应性和在多种应用中的实用性。我们还在 LLMs 的 LoRA 微调以及扩散模型等任务上进一步测试了其稳健性，它在这些任务中始终优于前沿的优化器。从内存效率的角度看，SGD-SaI 为优化器状态大幅节省了内存，在全精度训练设置下，相比 AdamW，为 GPT-2（1.5B 参数）节省 5.93 GB 内存，为 Llama2-7B 节省 25.15 GB 内存。

> In this work, we question the necessity of adaptive gradient methods for training deep neural networks. SGD-SaI is a simple yet effective enhancement to stochastic gradient descent with momentum (SGDM). SGD-SaI performs learning rate Scaling at Initialization (SaI) to distinct parameter groups, guided by their respective gradient signal-to-noise ratios (g-SNR). By adjusting learning rates without relying on adaptive second-order momentum, SGD-SaI helps prevent training imbalances from the very first iteration and cuts the optimizer's memory usage by half compared to AdamW. Despite its simplicity and efficiency, SGD-SaI consistently matches or outperforms AdamW in training a variety of Transformer-based tasks, effectively overcoming a long-standing challenge of using SGD for training Transformers. SGD-SaI excels in ImageNet-1K classification with Vision Transformers(ViT) and GPT-2 pretraining for large language models (LLMs, transformer decoder-only), demonstrating robustness to hyperparameter variations and practicality for diverse applications. We further tested its robustness on tasks like LoRA fine-tuning for LLMs and diffusion models, where it consistently outperforms state-of-the-art optimizers. From a memory efficiency perspective, SGD-SaI achieves substantial memory savings for optimizer states, reducing memory usage by 5.93 GB for GPT-2 (1.5B parameters) and 25.15 GB for Llama2-7B compared to AdamW in full-precision training settings.

[Arxiv](https://arxiv.org/abs/2412.11768)