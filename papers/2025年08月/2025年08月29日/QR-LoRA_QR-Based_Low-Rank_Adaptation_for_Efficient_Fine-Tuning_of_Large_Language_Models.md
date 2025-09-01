# QR-LoRA：基于QR的低秩适应助力大型语言模型高效微调

发布时间：2025年08月29日

`LLM理论` `基础理论`

> QR-LoRA: QR-Based Low-Rank Adaptation for Efficient Fine-Tuning of Large Language Models

# 摘要

> 随着大型语言模型（LLMs）规模持续扩大，参数高效微调技术的研发变得尤为必要。低秩适应（LoRA）凭借其通过低秩更新预训练权重以减少可训练参数的特性，成为了备受关注的方案。不过，标准LoRA需直接学习两个更新因子，而近期一些变体虽改用预训练权重的奇异值分解（SVD）来初始化矩阵，却存在大型模型上计算成本高、奇异向量解释性差的问题。本研究提出，通过带列主元的QR分解从预训练权重矩阵中提取正交基，并将LoRA更新表示为这些基向量的线性组合——仅训练标量系数，此举既为模型适应过程赋予了明确结构，又显著降低了参数数量。GLUE任务实验显示，QR-LoRA在性能上可媲美甚至超越全量微调、标准LoRA及SVD-LoRA（基于奇异值分解初始化更新矩阵的LoRA），且参数规模仅需601个——较全量微调减少超1000倍，比典型LoRA设置减少77倍。

> The growing scale of Large Language Models (LLMs) has necessitated the development of parameter-efficient fine-tuning techniques. Low-Rank Adaptation (LoRA) has emerged as a promising approach, reducing the number of trainable parameters by applying low-rank updates to pretrained weights. While standard LoRA learns both update factors directly, several recent variants first initialize those matrices via an SVD of the pretrained weights -- an operation that can be expensive on large models and yields singular vectors that are not always easy to interpret. In this work, we extract an orthonormal basis from the pretrained weight matrix using QR decomposition with column pivoting, and then express the LoRA update as a linear combination of these basis vectors -- training only the scalar coefficients, which imposes clear structure on adaptation and drastically reduces parameter count. Experiments across GLUE tasks show that QR-LoRA matches or exceeds the performance of full fine-tuning, standard LoRA, and SVD-LoRA (LoRA with update matrices initialized via singular value decomposition) with as few as 601 parameters -- a reduction of over 1000x compared to full fine-tuning and 77x fewer than typical LoRA setups.

[Arxiv](https://arxiv.org/abs/2508.21810)