# 低秩适配是否会导致对抗训练时间攻击的鲁棒性降低？

发布时间：2025年05月19日

`LLM理论` `人工智能` `模型安全`

> Does Low Rank Adaptation Lead to Lower Robustness against Training-Time Attacks?

# 摘要

> 低秩适配（LoRA）作为一种出色的大型语言模型（LLMs）微调技术，凭借其相较于以往方法的卓越效率提升而崭露头角。尽管已有大量研究探讨了LoRA的性能及其结构特性，但关于其在训练时间攻击中的行为仍研究不足，这带来了显著的安全隐患。本文中，我们从理论上探讨了LoRA在微调过程中低秩结构的安全影响，特别是在抵御数据投毒和后门攻击方面的鲁棒性。我们提出了一种分析框架，该框架建模了LoRA的训练动力学，运用神经切线核简化训练过程的分析，并借助信息论建立LoRA低秩结构与其在训练时间攻击中易受攻击性的关联。我们的分析表明，相较于全参数微调，LoRA在后门攻击中展现出更强的鲁棒性，然而由于其信息几何的过度简化，也使其更易遭受非定向数据投毒的攻击。广泛的实验评估结果证实了我们的理论发现。

> Low rank adaptation (LoRA) has emerged as a prominent technique for fine-tuning large language models (LLMs) thanks to its superb efficiency gains over previous methods. While extensive studies have examined the performance and structural properties of LoRA, its behavior upon training-time attacks remain underexplored, posing significant security risks. In this paper, we theoretically investigate the security implications of LoRA's low-rank structure during fine-tuning, in the context of its robustness against data poisoning and backdoor attacks. We propose an analytical framework that models LoRA's training dynamics, employs the neural tangent kernel to simplify the analysis of the training process, and applies information theory to establish connections between LoRA's low rank structure and its vulnerability against training-time attacks. Our analysis indicates that LoRA exhibits better robustness to backdoor attacks than full fine-tuning, while becomes more vulnerable to untargeted data poisoning due to its over-simplified information geometry. Extensive experimental evaluations have corroborated our theoretical findings.

[Arxiv](https://arxiv.org/abs/2505.12871)