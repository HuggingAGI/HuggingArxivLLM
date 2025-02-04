# FALCON：基于对比正交不对齐的大型语言模型细粒度激活操作

发布时间：2025年02月03日

`LLM理论

理由：该论文主要讨论了大型语言模型（LLM）中的机器遗忘技术，提出了一种新的方法（FALCON）来解决现有方法在精确分离知识和平衡移除效果与模型实用性方面的不足。这涉及到对LLM内部机制的理论研究和改进，属于对LLM的理论探索和优化，因此应归类为LLM理论。` `人工智能` `信息安全`

> FALCON: Fine-grained Activation Manipulation by Contrastive Orthogonal Unalignment for Large Language Model

# 摘要

> 大型语言模型虽广泛应用，却可能无意中编码敏感或有害信息，带来安全隐患。机器遗忘技术应运而生，但现有方法依赖粗粒度损失组合，难以精确分离知识并平衡移除效果与模型实用性。为此，我们提出FALCON——一种基于对比正交不对齐的细粒度激活操作，利用信息论指导高效参数选择，通过对比机制增强表示分离，并将冲突梯度投影到正交子空间，解决遗忘与保留目标的冲突。实验表明，FALCON在保持模型实用性的同时，实现了卓越的遗忘效果，并对知识恢复尝试展现出强大抵抗力。

> Large language models have been widely applied, but can inadvertently encode sensitive or harmful information, raising significant safety concerns. Machine unlearning has emerged to alleviate this concern; however, existing training-time unlearning approaches, relying on coarse-grained loss combinations, have limitations in precisely separating knowledge and balancing removal effectiveness with model utility. In contrast, we propose Fine-grained Activation manipuLation by Contrastive Orthogonal uNalignment (FALCON), a novel representation-guided unlearning approach that leverages information-theoretic guidance for efficient parameter selection, employs contrastive mechanisms to enhance representation separation, and projects conflict gradients onto orthogonal subspaces to resolve conflicts between forgetting and retention objectives. Extensive experiments demonstrate that FALCON achieves superior unlearning effectiveness while maintaining model utility, exhibiting robust resistance against knowledge recovery attempts.

[Arxiv](https://arxiv.org/abs/2502.01472)