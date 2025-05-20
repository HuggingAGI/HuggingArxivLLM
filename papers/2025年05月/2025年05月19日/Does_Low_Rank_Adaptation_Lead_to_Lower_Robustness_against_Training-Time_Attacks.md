# 低秩适应是否会使模型对抗训练攻击的鲁棒性下降？

发布时间：2025年05月19日

`LLM理论` `人工智能`

> Does Low Rank Adaptation Lead to Lower Robustness against Training-Time Attacks?

# 摘要

> 低秩适配（LoRA）凭借其相较于传统方法的显著效率优势，已成为微调大型语言模型（LLMs）的突出技术。尽管已有大量研究深入探讨了LoRA的性能和结构特性，但其在训练时间受到攻击时的行为仍是一个未充分探索的领域，这给实际应用带来了重大的安全风险。本文从理论上探究了LoRA在微调过程中其低秩结构的安全影响，特别是在抵御数据投毒和后门攻击的鲁棒性方面。我们提出了一种分析框架，该框架通过建模LoRA的训练动力学，运用神经切向核（Neural Tangent Kernel）来简化训练过程的分析，并借助信息论方法，建立了LoRA的低秩结构与其在训练时间攻击下易受攻击性之间的联系。我们的分析表明，相较于全量微调，LoRA在后门攻击面前展现出更好的鲁棒性，然而由于其过度简化的信息几何特性，它对非目标数据投毒攻击变得更为脆弱。大量实验评估结果充分验证了我们的理论发现。

> Low rank adaptation (LoRA) has emerged as a prominent technique for fine-tuning large language models (LLMs) thanks to its superb efficiency gains over previous methods. While extensive studies have examined the performance and structural properties of LoRA, its behavior upon training-time attacks remain underexplored, posing significant security risks. In this paper, we theoretically investigate the security implications of LoRA's low-rank structure during fine-tuning, in the context of its robustness against data poisoning and backdoor attacks. We propose an analytical framework that models LoRA's training dynamics, employs the neural tangent kernel to simplify the analysis of the training process, and applies information theory to establish connections between LoRA's low rank structure and its vulnerability against training-time attacks. Our analysis indicates that LoRA exhibits better robustness to backdoor attacks than full fine-tuning, while becomes more vulnerable to untargeted data poisoning due to its over-simplified information geometry. Extensive experimental evaluations have corroborated our theoretical findings.

[Arxiv](https://arxiv.org/abs/2505.12871)