# CoLA: 协作式低秩适配

发布时间：2025年05月21日

`LLM理论` `人工智能`

> CoLA: Collaborative Low-Rank Adaptation

# 摘要

> 大型语言模型 (LLMs) 的缩放定律揭示了一种幂律关系，表明随着模型规模的增大，性能提升逐渐减弱。尽管从头训练 LLM 需要大量资源，但对预训练模型进行特定任务的微调已成为一种实用的替代方案。全微调 (FFT) 能够实现强大的性能，但其计算成本高且效率低下。为了应对这些挑战，提出了参数高效微调 (PEFT) 方法，如 LoRA，通过冻结预训练模型并添加轻量级任务特定模块来解决这些问题。LoRA 特别有效，但其在多任务场景中的应用因任务间的干扰而受限。最近的方法，如专家混合 (MOE) 和非对称 LoRA，旨在缓解这些问题，但由于其固定结构，仍难以应对样本稀缺和噪声干扰。针对这些挑战，我们提出了 CoLA，一种更灵活的 LoRA 架构，配备高效的初始化方案，并引入了三种协作策略，通过更好地利用矩阵 $A$ 和 $B$ 之间的定量关系来提升性能。实验结果表明，CoLA 在低样本场景下表现尤为出色，优于现有的 PEFT 方法。我们的数据和代码可在 https://github.com/zyy-2001/CoLA 公开获取。

> The scaling law of Large Language Models (LLMs) reveals a power-law relationship, showing diminishing return on performance as model scale increases. While training LLMs from scratch is resource-intensive, fine-tuning a pre-trained model for specific tasks has become a practical alternative. Full fine-tuning (FFT) achieves strong performance; however, it is computationally expensive and inefficient. Parameter-efficient fine-tuning (PEFT) methods, like LoRA, have been proposed to address these challenges by freezing the pre-trained model and adding lightweight task-specific modules. LoRA, in particular, has proven effective, but its application to multi-task scenarios is limited by interference between tasks. Recent approaches, such as Mixture-of-Experts (MOE) and asymmetric LoRA, have aimed to mitigate these issues but still struggle with sample scarcity and noise interference due to their fixed structure. In response, we propose CoLA, a more flexible LoRA architecture with an efficient initialization scheme, and introduces three collaborative strategies to enhance performance by better utilizing the quantitative relationships between matrices $A$ and $B$. Our experiments demonstrate the effectiveness and robustness of CoLA, outperforming existing PEFT methods, especially in low-sample scenarios. Our data and code are fully publicly available at https://github.com/zyy-2001/CoLA.

[Arxiv](https://arxiv.org/abs/2505.15471)