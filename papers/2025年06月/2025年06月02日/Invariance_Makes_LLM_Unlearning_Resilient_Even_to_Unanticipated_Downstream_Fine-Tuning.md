# 不变性让大型语言模型的遗忘能力在面对未预期的下游微调时依然强韧。

发布时间：2025年06月02日

`LLM理论` `人工智能`

> Invariance Makes LLM Unlearning Resilient Even to Unanticipated Downstream Fine-Tuning

# 摘要

> 机器遗忘通过有选择地移除特定知识同时保留实用性，为大型语言模型（LLMs）中的隐私和安全问题提供了一个有前景的解决方案。然而，现有方法在下游微调时非常敏感，容易迅速恢复遗忘的信息，甚至来自无关任务。为了解决这一问题，我们首次将不变性引入遗忘，受到不变风险最小化（IRM）的启发。基于这一原则，我们提出了基于正则化的不变LLM遗忘（ILU）框架，以增强鲁棒性。值得注意的是，ILU在多样化的微调任务上表现良好，即使使用单一数据集进行训练。我们还提供了一个任务向量分析，以进一步阐明ILU有效性的原理。在WMDP和MUSE基准上的广泛实验表明，ILU显著优于现有最先进的遗忘方法，包括负偏好优化（NPO）和用于遗忘的表征误导（RMU）。值得注意的是，ILU在各种下游微调场景（如数学、句子改写检测和情感分析）中实现了卓越的遗忘鲁棒性，同时保持了微调性能。

> Machine unlearning offers a promising solution to privacy and safety concerns in large language models (LLMs) by selectively removing targeted knowledge while preserving utility. However, current methods are highly sensitive to downstream fine-tuning, which can quickly recover forgotten information-even from unrelated tasks. To address this, we introduce invariance into unlearning for the first time, inspired by invariant risk minimization (IRM). Building on this principle, we propose invariant LLM unlearning (ILU), a regularization-based framework that enhances robustness. Notably, ILU generalizes well to diverse fine-tuning tasks, even when trained using a single dataset. A task vector analysis is also provided to further elucidate the rationale behind ILU's effectiveness. Extensive experiments on the WMDP and MUSE benchmark, reveal that ILU significantly outperforms state-of-the-art unlearning methods, including negative preference optimization (NPO) and representation misdirection for unlearning (RMU). Notably, ILU achieves superior unlearning robustness across diverse downstream fine-tuning scenarios (e.g., math, paraphrase detection, and sentiment analysis) while preserving the fine-tuning performance.

[Arxiv](https://arxiv.org/abs/2506.01339)