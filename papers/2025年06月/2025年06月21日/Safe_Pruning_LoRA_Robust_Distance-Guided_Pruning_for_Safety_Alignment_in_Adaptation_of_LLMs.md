# 安全剪枝 LoRA：实现 LLMs 适配安全对齐的鲁棒距离引导方法

发布时间：2025年06月21日

`LLM理论

摘要讨论了LoRA微调技术对模型安全对齐的影响，并提出了一种新的方法SPLoRA来解决相关问题，属于理论层面的探讨。` `人工智能` `模型安全`

> Safe Pruning LoRA: Robust Distance-Guided Pruning for Safety Alignment in Adaptation of LLMs

# 摘要

> 利用低秩适配（LoRA）微调大型语言模型（LLMs）不仅能提升模型的适应性，还能有效降低计算成本。然而，这种微调方式可能会影响模型的安全对齐，即使使用良性数据，模型也更容易产生有害输出。现有的安全对齐方法在捕捉复杂的参数变化方面存在困难，导致安全性和实用性之间的权衡效果不尽如人意。针对这一问题，我们提出了基于剪枝的安全LoRA方法（SPLoRA），通过选择性地移除削弱安全对齐的LoRA层，在提升模型安全性的同时保持其性能。在技术核心，我们引入了维度不敏感的相似度度量Empirical-DIEM（E-DIEM），能够有效检测LoRA适配模型中的安全对齐问题。我们在使用良性与恶意数据混合微调的LLMs以及纯良性数据集上进行了广泛实验，从实用性、安全性和可靠性三个维度全面评估了SPLoRA的表现。实验结果表明，SPLoRA在显著降低安全风险的同时，不仅保持了模型性能，还提升了模型的可靠性，优于现有的安全对齐技术。此外，SPLoRA还显著降低了推理开销，使其成为部署更安全、更可靠的LLMs的可扩展且高效解决方案。代码已开源，地址为https://github.com/AoShuang92/SPLoRA。

> Fine-tuning Large Language Models (LLMs) with Low-Rank Adaptation (LoRA) enhances adaptability while reducing computational costs. However, fine-tuning can compromise safety alignment, even with benign data, increasing susceptibility to harmful outputs. Existing safety alignment methods struggle to capture complex parameter shifts, leading to suboptimal safety-utility trade-offs. To address this issue, we propose Safe Pruning LoRA (SPLoRA), a novel pruning-based approach that selectively removes LoRA layers that weaken safety alignment, improving safety while preserving performance. At its core, we introduce Empirical-DIEM (E-DIEM), a dimension-insensitive similarity metric that effectively detects safety misalignment in LoRA-adapted models. We conduct extensive experiments on LLMs fine-tuned with mixed of benign and malicious data, and purely benign datasets, evaluating SPLoRA across utility, safety, and reliability metrics. Results demonstrate that SPLoRA outperforms state-of-the-art safety alignment techniques, significantly reducing safety risks while maintaining or improving model performance and reliability. Additionally, SPLoRA reduces inference overhead, making it a scalable and efficient solution for deploying safer and more reliable LLMs. The code is available at https://github.com/AoShuang92/SPLoRA.

[Arxiv](https://arxiv.org/abs/2506.18931)