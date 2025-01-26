# 语言模型持续学习中的虚假遗忘问题

发布时间：2025年01月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在持续学习中的性能下降问题，提出了“虚假遗忘”的概念，并通过实验和理论分析解释了这一现象。论文的核心在于对LLMs内部机制的理解和理论框架的构建，属于对LLM的理论研究，因此应归类为LLM理论。` `人工智能` `持续学习`

> Spurious Forgetting in Continual Learning of Language Models

# 摘要

> # 摘要
最近大型语言模型（LLMs）的进展揭示了一个持续学习中的谜题：尽管模型经过大量训练，性能却大幅下降，这让人对任务对齐和知识保留产生了疑问。本研究首次提出了“虚假遗忘”的概念，认为这种性能下降往往源于任务对齐的减弱，而非真正的知识丢失。通过合成数据集的实验，我们探索了新任务初期训练阶段模型性能的变化，发现早期优化步骤可能会破坏已有的任务对齐。理论分析表明，这些变化与模型权重的正交更新有关，为理解这一现象提供了坚实的框架。最终，我们提出了一种冻结策略，固定模型底层，显著提升了四种持续学习场景的性能。这一发现强调了任务对齐与知识保留的关键区别，为持续学习策略的优化指明了方向。

> Recent advancements in large language models (LLMs) reveal a perplexing phenomenon in continual learning: despite extensive training, models experience significant performance declines, raising questions about task alignment and underlying knowledge retention. This study first explores the concept of "spurious forgetting", proposing that such performance drops often reflect a decline in task alignment rather than true knowledge loss. Through controlled experiments with a synthesized dataset, we investigate the dynamics of model performance during the initial training phases of new tasks, discovering that early optimization steps can disrupt previously established task alignments. Our theoretical analysis connects these shifts to orthogonal updates in model weights, providing a robust framework for understanding this behavior. Ultimately, we introduce a Freezing strategy that fix the bottom layers of the model, leading to substantial improvements in four continual learning scenarios. Our findings underscore the critical distinction between task alignment and knowledge retention, paving the way for more effective strategies in continual learning.

[Arxiv](https://arxiv.org/abs/2501.13453)