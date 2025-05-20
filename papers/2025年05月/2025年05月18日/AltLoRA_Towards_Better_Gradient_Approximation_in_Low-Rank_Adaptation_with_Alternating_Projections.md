# # **AltLoRA**：利用交替投影优化低秩适配中的梯度近似

发布时间：2025年05月18日

`LLM理论` `模型优化`

> AltLoRA: Towards Better Gradient Approximation in Low-Rank Adaptation with Alternating Projections

# 摘要

> 低秩适应（LoRA）作为减少大模型微调内存开销的有效技术，但其性能受限于低秩空间。近期LoRA-Pro等变体尝试通过梯度调整优化，但存在非唯一解和内存开销高等问题。本文提出AltLoRA方法，通过交替投影避免梯度近似难题，实现低内存成本下动量优化。理论分析表明AltLoRA具备稳定特征学习和变换不变性鲁棒性。实验结果证实，AltLoRA在性能上超越LoRA及其变体，同时保持高效内存利用率。

> Low-Rank Adaptation (LoRA) has emerged as an effective technique for reducing memory overhead in fine-tuning large language models. However, it often suffers from sub-optimal performance compared with full fine-tuning since the update is constrained in the low-rank space. Recent variants such as LoRA-Pro attempt to mitigate this by adjusting the gradients of the low-rank matrices to approximate the full gradient. However, LoRA-Pro's solution is not unique, and different solutions can lead to significantly varying performance in ablation studies. Besides, to incorporate momentum or adaptive optimization design, approaches like LoRA-Pro must first compute the equivalent gradient, causing a higher memory cost close to full fine-tuning. A key challenge remains in integrating momentum properly into the low-rank space with lower memory cost. In this work, we propose AltLoRA, an alternating projection method that avoids the difficulties in gradient approximation brought by the joint update design, meanwhile integrating momentum without higher memory complexity. Our theoretical analysis provides convergence guarantees and further shows that AltLoRA enables stable feature learning and robustness to transformation invariance. Extensive experiments across multiple tasks demonstrate that AltLoRA outperforms LoRA and its variants, narrowing the gap toward full fine-tuning while preserving superior memory efficiency.

[Arxiv](https://arxiv.org/abs/2505.12455)