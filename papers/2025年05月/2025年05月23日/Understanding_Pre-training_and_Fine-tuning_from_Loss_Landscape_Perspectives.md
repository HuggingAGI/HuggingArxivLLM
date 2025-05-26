# 预训练与微调：从损失景观视角解析

发布时间：2025年05月23日

`LLM理论` `人工智能` `机器学习`

> Understanding Pre-training and Fine-tuning from Loss Landscape Perspectives

# 摘要

> 最近的研究揭示，大型语言模型的损失景观呈现出一个盆地状的特性：模型在盆地内部表现几乎相同，一旦超出这个范围，能力就会完全丧失。在这项研究中，我们深入探索了大型语言模型的损失景观。发现预训练形成了一个“基础能力”盆地，而后续的微调则在基础能力盆地内部创建了“特定能力”盆地（如数学、安全、编码等）。我们进一步研究了两种类型的损失景观：最常见情况下的景观（即沿着大多数方向的景观）和最坏情况下的景观（即沿着最坏方向的景观）。我们主张，只要良性的微调保持在最常见情况的盆地内，就不会损害模型的原有能力。同样，任何微调（包括对抗性的微调）只要保持在最坏情况的盆地内，也不会损害模型的原有能力。最后，我们从理论上证明了最常见情况盆地的规模可以界定最坏情况盆地的规模以及对输入扰动的鲁棒性。我们还表明，由于当前大型语言模型的过参数化特性，可以轻松将盆地扩大五倍。

> Recent studies have revealed that the loss landscape of large language models resembles a basin, within which the models perform nearly identically, and outside of which they lose all their capabilities. In this work, we conduct further studies on the loss landscape of large language models. We discover that pre-training creates a "basic capability" basin, and subsequent fine-tuning creates "specific capability" basins (e.g., math, safety, coding) within the basic capability basin. We further investigate two types of loss landscapes: the most-case landscape (i.e., the landscape along most directions) and the worst-case landscape (i.e., the landscape along the worst direction). We argue that as long as benign fine-tuning remains within the most-case basin, it will not compromise previous capabilities. Similarly, any fine-tuning (including the adversarial one) that stays within the worst-case basin would not compromise previous capabilities. Finally, we theoretically demonstrate that the size of the most-case basin can bound the size of the worst-case basin and the robustness with respect to input perturbations. We also show that, due to the over-parameterization property of current large language models, one can easily enlarge the basins by five times.

[Arxiv](https://arxiv.org/abs/2505.17646)