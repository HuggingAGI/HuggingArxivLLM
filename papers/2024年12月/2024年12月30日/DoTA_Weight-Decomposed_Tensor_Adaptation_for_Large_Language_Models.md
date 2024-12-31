# DoTA：大型语言模型的权重分解张量自适应技术

发布时间：2024年12月30日

`LLM应用` `语言模型`

> DoTA: Weight-Decomposed Tensor Adaptation for Large Language Models

# 摘要

> 低秩适应（LoRA）借助低秩矩阵近似更新，大幅降低了大型语言模型（LLMs）微调时的计算和内存需求。但二维空间中的低秩近似难以捕捉目标矩阵内的高维结构。近来，张量分解方法被用于LLMs的微调，因其能提取结构化信息。然而，这些方法多依赖随机初始化，而初始化对张量适应的影响尚未充分探究。本文中，我们发现随机初始化与完全微调所达成的验证损失差异显著。为此，我们提出权重分解张量适应（DoTA），利用预训练权重的矩阵乘积算子（MPO）分解来有效初始化LLMs的微调。另外，我们引入了QDoTA，这是DoTA的4位量化版本。在常识和算术推理任务的实验表明，DoTA在参数更少的情况下优于随机初始化方法。QDoTA进一步降低了内存消耗，在常识推理任务上的表现与DoTA相当。我们会发布代码以助力未来研究。

> Low-rank adaptation (LoRA) reduces the computational and memory demands of fine-tuning large language models (LLMs) by approximating updates with low-rank matrices. However, low-rank approximation in two-dimensional space fails to capture high-dimensional structures within the target matrix. Recently, tensor decomposition methods have been explored for fine-tuning LLMs, leveraging their ability to extract structured information. Yet, these approaches primarily rely on random initialization, and the impact of initialization on tensor adaptation remains underexplored. In this paper, we reveal that random initialization significantly diverges from the validation loss achieved by full fine-tuning. To address this, we propose Weight-Decomposed Tensor Adaptation (DoTA), which leverages the Matrix Product Operator (MPO) decomposition of pre-trained weights for effective initialization in fine-tuning LLMs. Additionally, we introduce QDoTA, a quantized version of DoTA designed for 4-bit quantization. Experiments on commonsense and arithmetic reasoning tasks show that DoTA outperforms random initialization methods with fewer parameters. QDoTA further reduces memory consumption and achieves comparable performance to DoTA on commonsense reasoning tasks. We will release our code to support future research.

[Arxiv](https://arxiv.org/abs/2412.20891)