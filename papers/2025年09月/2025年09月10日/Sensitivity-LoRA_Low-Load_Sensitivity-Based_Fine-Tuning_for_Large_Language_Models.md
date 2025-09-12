# Sensitivity-LoRA：面向大型语言模型的低负载敏感度基微调

发布时间：2025年09月10日

`LLM理论` `基础理论`

> Sensitivity-LoRA: Low-Load Sensitivity-Based Fine-Tuning for Large Language Models

# 摘要

> 大型语言模型（LLMs）已然改变了日常生活与科学研究的面貌。然而，将LLMs从通用模型适配为特定任务模型仍颇具挑战，尤其在资源有限的场景中。低秩适应（LoRA）作为参数高效微调（PEFT）中的主流方法，通过低秩分解近似模型权重更新，已成为处理LLMs的一种颇具前景的方案。但LoRA的局限性在于其对每个增量矩阵采用统一的秩（r）分配，而现有旨在解决此问题的秩分配技术仍存在计算效率低、复杂度高且稳定性差的问题，阻碍了其实际应用。为解决这些局限性，我们提出了Sensitivity-LoRA——一种高效的微调方法，它根据权重矩阵的全局和局部敏感性动态分配秩。该方法借助损失函数的二阶导数（海森矩阵）有效捕捉权重敏感性，从而以最小的计算开销实现最优秩分配。实验结果表明，Sensitivity-LoRA在不同任务和基准测试中均展现出强大的有效性、高效性和稳定性。

> Large Language Models (LLMs) have transformed both everyday life and scientific research. However, adapting LLMs from general-purpose models to specialized tasks remains challenging, particularly in resource-constrained environments. Low-Rank Adaptation (LoRA), a prominent method within Parameter-Efficient Fine-Tuning (PEFT), has emerged as a promising approach to LLMs by approximating model weight updates using low-rank decomposition. However, LoRA is limited by its uniform rank ( r ) allocation to each incremental matrix, and existing rank allocation techniques aimed at addressing this issue remain computationally inefficient, complex, and unstable, hindering practical applications. To address these limitations, we propose Sensitivity-LoRA, an efficient fine-tuning method that dynamically allocates ranks to weight matrices based on both their global and local sensitivities. It leverages the second-order derivatives (Hessian Matrix) of the loss function to effectively capture weight sensitivity, enabling optimal rank allocation with minimal computational overhead. Our experimental results have demonstrated robust effectiveness, efficiency and stability of Sensitivity-LoRA across diverse tasks and benchmarks.

[Arxiv](https://arxiv.org/abs/2509.09119)