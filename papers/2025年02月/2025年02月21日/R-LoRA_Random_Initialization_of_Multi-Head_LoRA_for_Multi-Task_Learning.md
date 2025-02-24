# R-LoRA：多头LoRA随机初始化方法在多任务学习中的应用

发布时间：2025年02月21日

`LLM理论

理由：这篇论文探讨了微调大型语言模型的方法，特别是低秩适应（LoRA）及其改进版本R-LoRA，以提升多任务学习中的性能。它属于模型优化和训练方法的研究，属于LLM的理论层面。` `多任务学习`

> R-LoRA: Random Initialization of Multi-Head LoRA for Multi-Task Learning

# 摘要

> 微调大型语言模型 (LLMs) 的计算和内存成本高昂。低秩适应 (LoRA) 作为最受欢迎的参数高效微调 (PEFT) 方法之一，通过将模型变化【数学公式】近似为降维矩阵【数学公式】和头矩阵【数学公式】的乘积（其中【数学公式】），提供了一种经济高效的替代方案。在实际应用中，LLMs 通常需要在多个领域的数据上进行微调，以执行跨领域的任务，这体现了多任务学习 (MTL) 的特点。然而，LoRA 在这种复杂场景下往往表现不佳。为了提升 LoRA 在多任务学习中的能力，我们提出了一种结合多头随机化的改进方法 R-LoRA。多头随机化通过多头随机初始化和多头 dropout，使头矩阵多样化，从而在保持共享知识表示的同时，更高效地学习任务特定特征。大量实验表明，R-LoRA 更擅长捕捉任务特定知识，从而在多任务场景中提升了性能。代码可在 https://github.com/jinda-liu/R-LoRA 获取。


> Fine-tuning large language models (LLMs) is prohibitively expensive in terms of computational and memory costs. Low-rank Adaptation (LoRA), as one of the most popular parameter-efficient fine-tuning (PEFT) methods, offers a cost-effective alternative by approximating the model changes $ΔW \in \mathbb{R}^{m \times n}$ through the product of down-projection matrix $A \in \mathbb{R}^{m \times r}$ and head matrix $B \in \mathbb{R}^{r \times n}$, where $r \ll \min(m, n)$. In real-world scenarios, LLMs are fine-tuned on data from multiple domains to perform tasks across various fields, embodying multi-task learning (MTL). LoRA often underperforms in such complex scenarios. To enhance LoRA's capability in multi-task learning, we propose R-LoRA, which incorporates Multi-Head Randomization. Multi-Head Randomization diversifies the head matrices through Multi-Head Random Initialization and Multi-Head Dropout, enabling more efficient learning of task-specific features while maintaining shared knowledge representation. Extensive experiments demonstrate that R-LoRA is better at capturing task-specific knowledge, thereby improving performance in multi-task scenarios. The code is available at https://github.com/jinda-liu/R-LoRA.

[Arxiv](https://arxiv.org/abs/2502.15455)