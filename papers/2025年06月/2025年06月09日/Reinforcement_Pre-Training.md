# 强化预训练

发布时间：2025年06月09日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）的预训练方法，提出了一种新的范式——强化预训练（RPT），结合强化学习来提升模型的预测能力。这属于LLM的理论层面研究，因为它涉及模型的训练机制和改进方法，而不是具体的应用场景或模型的直接应用。`

> Reinforcement Pre-Training

# 摘要

> 在这项研究中，我们提出强化预训练（RPT）作为大型语言模型与强化学习结合的新扩展范式。具体而言，我们将下一个词的预测重新定义为一个通过强化学习训练的推理任务，模型在正确预测给定上下文的下一个词时获得奖励。RPT利用大量文本数据进行通用强化学习，无需依赖特定领域标注的数据。通过强化下一个词推理能力，RPT显著提升了语言模型的预测准确性。此外，RPT为后续强化微调提供了坚实基础。实验结果表明，增加训练计算量能持续提升预测准确性，证明RPT是推动语言模型预训练的有效且有前景的范式。

> In this work, we introduce Reinforcement Pre-Training (RPT) as a new scaling paradigm for large language models and reinforcement learning (RL). Specifically, we reframe next-token prediction as a reasoning task trained using RL, where it receives verifiable rewards for correctly predicting the next token for a given context. RPT offers a scalable method to leverage vast amounts of text data for general-purpose RL, rather than relying on domain-specific annotated answers. By incentivizing the capability of next-token reasoning, RPT significantly improves the language modeling accuracy of predicting the next tokens. Moreover, RPT provides a strong pre-trained foundation for further reinforcement fine-tuning. The scaling curves show that increased training compute consistently improves the next-token prediction accuracy. The results position RPT as an effective and promising scaling paradigm to advance language model pre-training.

[Arxiv](https://arxiv.org/abs/2506.08007)