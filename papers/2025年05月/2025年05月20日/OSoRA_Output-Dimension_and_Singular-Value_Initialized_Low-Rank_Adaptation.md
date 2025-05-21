# OSoRA：基于输出维度和奇异值初始化的低秩调整方法

发布时间：2025年05月20日

`LLM理论` `模型优化`

> OSoRA: Output-Dimension and Singular-Value Initialized Low-Rank Adaptation

# 摘要

> 微调大型语言模型（LLMs）面临规模庞大和计算成本高昂的双重挑战。为此，我们提出了OSoRA（基于输出维度和奇异值初始化的低秩适配），一种新型的参数高效微调（PEFT）方法。OSoRA在低秩适配（LoRA）的基础上，通过在统一框架中融合奇异值分解（SVD）与可学习的缩放向量，实现了性能的显著提升。具体而言，OSoRA首先对预训练权重矩阵进行SVD分解，然后在训练过程中优化一个输出维度向量，同时保持奇异向量矩阵不变。通过最大限度地减少微调过程中的可训练参数数量，OSoRA大幅降低了计算资源需求。在数学推理、常识推理等多个基准测试中的评估表明，OSoRA不仅达到了与现有先进方法（如LoRA和VeRA）相当甚至更优的性能，还实现了参数的线性缩放，即使在更高维度的秩增加时也是如此。我们的消融实验进一步证实，同时训练奇异值和输出维度向量是实现最佳性能的关键。

> Fine-tuning Large Language Models (LLMs) has become increasingly challenging due to their massive scale and associated computational costs. Parameter-Efficient Fine-Tuning (PEFT) methodologies have been proposed as computational alternatives; however, their implementations still require significant resources. In this paper, we present OSoRA (Output-Dimension and Singular-Value Initialized Low-Rank Adaptation), a novel PEFT method for LLMs. OSoRA extends Low-Rank Adaptation (LoRA) by integrating Singular Value Decomposition (SVD) with learnable scaling vectors in a unified framework. It first performs an SVD of pre-trained weight matrices, then optimizes an output-dimension vector during training, while keeping the corresponding singular vector matrices frozen. OSoRA substantially reduces computational resource requirements by minimizing the number of trainable parameters during fine-tuning. Comprehensive evaluations across mathematical reasoning, common sense reasoning, and other benchmarks demonstrate that OSoRA achieves comparable or superior performance to state-of-the-art methods like LoRA and VeRA, while maintaining a linear parameter scaling even as the rank increases to higher dimensions. Our ablation studies further confirm that jointly training both the singular values and the output-dimension vector is critical for optimal performance.

[Arxiv](https://arxiv.org/abs/2505.14350)