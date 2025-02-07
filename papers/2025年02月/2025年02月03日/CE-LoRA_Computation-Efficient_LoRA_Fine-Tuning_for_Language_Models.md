# CE-LoRA: 语言模型的高效计算LoRA微调

发布时间：2025年02月03日

`LLM理论

**理由**：这篇论文主要讨论了大型语言模型（LLMs）的微调过程中的计算效率问题，提出了CE-LoRA算法来优化计算成本。这属于对LLM的理论研究，特别是关于如何改进和优化LLM的训练和微调过程。因此，将其分类为LLM理论是合适的。` `机器学习` `优化算法`

> CE-LoRA: Computation-Efficient LoRA Fine-Tuning for Language Models

# 摘要

> 大型语言模型（LLMs）在各种任务中表现出色，但微调计算需要大量资源。虽然低秩适应（LoRA）显著减少了内存消耗，但对计算成本的降低效果有限。本文发现激活梯度的计算是LoRA反向传播的主要瓶颈，并提出了计算高效的LoRA（CE-LoRA）算法，在保持内存效率的同时提升计算效率。CE-LoRA采用了两项关键技术：近似矩阵乘法，用稀疏乘法替代密集矩阵乘法；以及双LoRA技术，减少激活梯度中的误差传播。理论上，CE-LoRA的收敛速度与LoRA相同，即【数学公式】，其中T为迭代次数。实验表明，CE-LoRA在显著降低计算成本的同时，性能无明显下降。

> Large Language Models (LLMs) demonstrate exceptional performance across various tasks but demand substantial computational resources even for fine-tuning computation. Although Low-Rank Adaptation (LoRA) significantly alleviates memory consumption during fine-tuning, its impact on computational cost reduction is limited. This paper identifies the computation of activation gradients as the primary bottleneck in LoRA's backward propagation and introduces the Computation-Efficient LoRA (CE-LoRA) algorithm, which enhances computational efficiency while preserving memory efficiency. CE-LoRA leverages two key techniques: Approximated Matrix Multiplication, which replaces dense multiplications of large and complete matrices with sparse multiplications involving only critical rows and columns, and the Double-LoRA technique, which reduces error propagation in activation gradients. Theoretically, CE-LoRA converges at the same rate as LoRA, $ \mathcal{O}(1/\sqrt{T}) $, where $T$ is the number of iteartions. Empirical evaluations confirm that CE-LoRA significantly reduces computational costs compared to LoRA without notable performance degradation.

[Arxiv](https://arxiv.org/abs/2502.01378)