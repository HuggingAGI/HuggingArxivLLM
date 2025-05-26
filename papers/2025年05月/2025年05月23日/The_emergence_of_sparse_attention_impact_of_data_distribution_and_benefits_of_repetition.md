# 稀疏注意力的崛起：数据分布的影响与重复机制的优势

发布时间：2025年05月23日

`LLM理论` `人工智能`

> The emergence of sparse attention: impact of data distribution and benefits of repetition

# 摘要

> 涌现特性是大型语言模型和神经网络中一个引人入胜的属性：当模型规模扩大、训练时间延长时，它们有时会突然展现出新的能力。尽管已有初步研究，但我们对这些能力如何以及何时出现的全面理解仍然不足。为了解决这一问题，我们研究了稀疏注意力在训练过程中的出现，这是一种在Transformer中常见且关键的注意力模式。通过结合对一个玩具模型的理论分析，以及在基于线性回归变体训练的小型Transformer上的实证观察，我们揭示了驱动稀疏注意力出现的机制，并发现出现的时间遵循基于任务结构、架构和优化器选择的幂律。我们还发现，重复可以极大地加速这一过程。最后，我们在一个被广泛研究的上下文联想记忆任务中验证了这些结果。我们的发现提供了一个简单且理论基础扎实的框架，用于理解数据分布和模型设计如何影响学习动力学，从而推动了一种形式的涌现特性。

> Emergence is a fascinating property of large language models and neural networks more broadly: as models scale and train for longer, they sometimes develop new abilities in sudden ways. Despite initial studies, we still lack a comprehensive understanding of how and when these abilities emerge. To address this gap, we study the emergence over training of sparse attention, a critical and frequently observed attention pattern in Transformers. By combining theoretical analysis of a toy model with empirical observations on small Transformers trained on a linear regression variant, we uncover the mechanics driving sparse attention emergence and reveal that emergence timing follows power laws based on task structure, architecture, and optimizer choice. We additionally find that repetition can greatly speed up emergence. Finally, we confirm these results on a well-studied in-context associative recall task. Our findings provide a simple, theoretically grounded framework for understanding how data distributions and model design influence the learning dynamics behind one form of emergence.

[Arxiv](https://arxiv.org/abs/2505.17863)