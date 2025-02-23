# PEARL: 致力于实现排列不变性的大型语言模型

发布时间：2025年02月20日

`LLM理论` `机器学习` `模型安全`

> PEARL: Towards Permutation-Resilient LLMs

# 摘要

> 大型语言模型（LLMs）的上下文学习（ICL）能力使其能够利用提供的示例执行具有挑战性的任务。然而，ICL对示例的顺序高度敏感，导致预测结果不稳定。本文表明，这种脆弱性可以被利用来设计一种自然攻击——这种攻击对于模型提供者来说难以检测——通过仅仅重新排列示例，就能在LLaMA-3上实现近80%的成功率。现有的缓解方法主要依赖于后处理，未能提升模型对输入排列的内在鲁棒性，这引发了人们对LLMs安全性和可靠性的担忧。为了解决这一问题，我们提出了基于分布鲁棒优化（DRO）的抗排列学习框架PEARL，该框架针对最坏情况下的输入排列优化模型性能。具体而言，PEARL由一个排列提案网络（P-Net）和LLM组成。P-Net将最具有挑战性的排列生成视为一个最优传输问题，并通过熵约束的Sinkhorn算法求解。通过极小化极大优化，P-Net和LLM相互迭代优化，逐步提升LLM的鲁棒性。在合成预训练和真实世界指令微调任务上的实验表明，PEARL有效缓解了排列攻击并提升了性能。值得注意的是，尽管PEARL是在较少的样本和较短的上下文上进行训练，但当扩展到多样本和长上下文场景时，其性能提升可达40%，凸显了其高效性和泛化能力。

> The in-context learning (ICL) capability of large language models (LLMs) enables them to perform challenging tasks using provided demonstrations. However, ICL is highly sensitive to the ordering of demonstrations, leading to instability in predictions. This paper shows that this vulnerability can be exploited to design a natural attack - difficult for model providers to detect - that achieves nearly 80% success rate on LLaMA-3 by simply permuting the demonstrations. Existing mitigation methods primarily rely on post-processing and fail to enhance the model's inherent robustness to input permutations, raising concerns about safety and reliability of LLMs. To address this issue, we propose Permutation-resilient learning (PEARL), a novel framework based on distributionally robust optimization (DRO), which optimizes model performance against the worst-case input permutation. Specifically, PEARL consists of a permutation-proposal network (P-Net) and the LLM. The P-Net generates the most challenging permutations by treating it as an optimal transport problem, which is solved using an entropy-constrained Sinkhorn algorithm. Through minimax optimization, the P-Net and the LLM iteratively optimize against each other, progressively improving the LLM's robustness. Experiments on synthetic pre-training and real-world instruction tuning tasks demonstrate that PEARL effectively mitigates permutation attacks and enhances performance. Notably, despite being trained on fewer shots and shorter contexts, PEARL achieves performance gains of up to 40% when scaled to many-shot and long-context scenarios, highlighting its efficiency and generalization capabilities.

[Arxiv](https://arxiv.org/abs/2502.14628)