# # AltLoRA：通过交替投影优化低秩适配中的梯度近似

发布时间：2025年05月18日

`LLM理论` `人工智能` `机器学习`

> AltLoRA: Towards Better Gradient Approximation in Low-Rank Adaptation with Alternating Projections

# 摘要

> 低秩适配（LoRA）作为一种有效技术，能够降低大型语言模型微调过程中的内存开销。然而，由于更新受限于低秩空间，其性能往往不如全参数微调理想。近期的改进版本如LoRA-Pro尝试通过调整低秩矩阵的梯度以近似全梯度，从而缓解这一问题。然而，LoRA-Pro的解决方案并不唯一，不同方案在消融研究中可能导致显著的性能差异。此外，为了纳入动量或自适应优化设计，类似LoRA-Pro的方法必须首先计算等效梯度，这会导致内存成本接近全参数微调。如何在低秩空间中合理整合动量优化并保持较低的内存消耗仍是一个关键挑战。

在本研究中，我们提出了交替投影方法AltLoRA，该方法避免了联合更新设计带来的梯度近似难题，同时实现了无额外内存复杂度的动量优化。我们的理论分析提供了收敛性保证，并进一步表明AltLoRA能够实现稳定的特征学习，并对变换不变性具备更强的鲁棒性。跨多任务的广泛实验表明，AltLoRA在性能上超越了LoRA及其变体，同时保持了卓越的内存效率，显著缩小了与全参数微调的性能差距。

> Low-Rank Adaptation (LoRA) has emerged as an effective technique for reducing memory overhead in fine-tuning large language models. However, it often suffers from sub-optimal performance compared with full fine-tuning since the update is constrained in the low-rank space. Recent variants such as LoRA-Pro attempt to mitigate this by adjusting the gradients of the low-rank matrices to approximate the full gradient. However, LoRA-Pro's solution is not unique, and different solutions can lead to significantly varying performance in ablation studies. Besides, to incorporate momentum or adaptive optimization design, approaches like LoRA-Pro must first compute the equivalent gradient, causing a higher memory cost close to full fine-tuning. A key challenge remains in integrating momentum properly into the low-rank space with lower memory cost. In this work, we propose AltLoRA, an alternating projection method that avoids the difficulties in gradient approximation brought by the joint update design, meanwhile integrating momentum without higher memory complexity. Our theoretical analysis provides convergence guarantees and further shows that AltLoRA enables stable feature learning and robustness to transformation invariance. Extensive experiments across multiple tasks demonstrate that AltLoRA outperforms LoRA and its variants, narrowing the gap toward full fine-tuning while preserving superior memory efficiency.

[Arxiv](https://arxiv.org/abs/2505.12455)