# 精准高效的核心空间低秩模型合并

发布时间：2025年09月22日

`LLM理论` `基础理论`

> Accurate and Efficient Low-Rank Model Merging in Core Space

# 摘要

> 本文旨在解决大型神经网络低秩适应合并所面临的挑战。随着低秩适应（LoRA）等参数高效适配技术的兴起，模型微调已变得更为便捷。尽管LoRA微调模型效率极高，但现有合并方法往往因合并全尺寸权重矩阵而牺牲了这一效率。为此，我们提出核心空间（Core Space）合并框架，该框架可在公共对齐基下合并LoRA适配模型，从而在保留低秩适配效率的同时，大幅提升跨任务精度。我们进一步给出形式化证明：投影到核心空间可确保无信息损失，并通过复杂度分析验证了效率提升。大量实证结果表明，核心空间显著优于现有合并技术，在视觉与语言任务上均达到了最先进水平，且仅需消耗少量计算资源。代码库详见https://github.com/apanariello4/core-space-merging。

> In this paper, we address the challenges associated with merging low-rank adaptations of large neural networks. With the rise of parameter-efficient adaptation techniques, such as Low-Rank Adaptation (LoRA), model fine-tuning has become more accessible. While fine-tuning models with LoRA is highly efficient, existing merging methods often sacrifice this efficiency by merging fully-sized weight matrices. We propose the Core Space merging framework, which enables the merging of LoRA-adapted models within a common alignment basis, thereby preserving the efficiency of low-rank adaptation while substantially improving accuracy across tasks. We further provide a formal proof that projection into Core Space ensures no loss of information and provide a complexity analysis showing the efficiency gains. Extensive empirical results demonstrate that Core Space significantly improves existing merging techniques and achieves state-of-the-art results on both vision and language tasks while utilizing a fraction of the computational resources. Codebase is available at https://github.com/apanariello4/core-space-merging.

[Arxiv](https://arxiv.org/abs/2509.17786)