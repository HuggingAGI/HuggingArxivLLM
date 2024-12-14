# GeLoRA：实现高效 LoRA 微调的几何自适应秩

发布时间：2024年12月12日

`LLM理论` `计算机科学`

> GeLoRA: Geometric Adaptive Ranks For Efficient LoRA Fine-tuning

# 摘要

> 微调大型语言模型（LLMs）的计算量很大，因为要更新所有参数。低秩自适应（LoRA）仅修改部分权重以提升效率，但在表现力和计算成本之间存在权衡：秩越低，资源消耗越少，但表现力受限；秩越高，表现力增强，但成本增加。尽管自适应LoRA技术近来有所进步，现有方法却未能为优化模型性能与效率的权衡提供理论依据。我们提出了几何低秩自适应（GeLoRA）这一全新框架，它能计算隐藏状态表示的内在维度，从而自适应地选择LoRA的秩。我们证明内在维度为LoRA矩阵的最优秩提供了下限，有助于在效率和表现力之间做出平衡的选择。GeLoRA依据输入和输出表示的内在维度为每一层动态调整秩，因为并非所有模型参数对微调的影响都相同。在多个任务上的实证验证显示，在相同参数预算下，GeLoRA始终优于近期的基线。

> Fine-tuning large language models (LLMs) is computationally intensive because it requires updating all parameters. Low-Rank Adaptation (LoRA) improves efficiency by modifying only a subset of weights but introduces a trade-off between expressivity and computational cost: lower ranks reduce resources but limit expressiveness, while higher ranks enhance expressivity at increased cost. Despite recent advances in adaptive LoRA techniques, existing methods fail to provide a theoretical basis for optimizing the trade-off between model performance and efficiency. We propose Geometric Low-Rank Adaptation (GeLoRA), a novel framework that computes the intrinsic dimensionality of hidden state representations to adaptively select LoRA ranks. We demonstrate that the intrinsic dimension provides a lower bound for the optimal rank of LoRA matrices, allowing for a principled selection that balances efficiency and expressivity. GeLoRA dynamically adjusts the rank for each layer based on the intrinsic dimensionality of its input and output representations, recognizing that not all model parameters equally impact fine-tuning. Empirical validation on multiple tasks shows that GeLoRA consistently outperforms recent baselines within the same parameter budget.

[Arxiv](https://arxiv.org/abs/2412.09250)