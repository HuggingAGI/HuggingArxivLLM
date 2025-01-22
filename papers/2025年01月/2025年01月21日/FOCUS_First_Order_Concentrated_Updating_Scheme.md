# FOCUS: 一阶集中更新方案

发布时间：2025年01月21日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的预训练过程优化，特别是通过分析损失景观和梯度噪声，提出了一种新的优化器FOCUS。这些内容属于对LLM训练过程的理论研究和改进，因此应归类为LLM理论。` `人工智能` `优化算法`

> FOCUS: First Order Concentrated Updating Scheme

# 摘要

> 大型语言模型（LLMs）表现出色，而优化其预训练过程是提升其能力的关键。基于Adam、学习率衰减和权重衰减的成功经验，我们推测预训练损失景观呈现逐渐收窄的谷结构。通过合成损失函数的实验，我们发现当梯度噪声相对于谷的锐度较高时，Adam的表现不如Signum，因为Adam过于激进地减小了有效步长。这一发现促使我们开发了FOCUS，一种优化器，通过引入对移动平均参数的吸引力来增强Signum，使其在保持较大步长的同时更好地应对噪声。在GPT-2的训练中，FOCUS比Signum更稳定，比Adam更快。这些结果表明，梯度噪声可能是LLM训练中一个被忽视的限制因素，而FOCUS提供了有效的解决方案。

> Large language models (LLMs) demonstrate remarkable performance, and improving their pre-training process appears to be key to enhancing their capabilities further. Based on the documented success of Adam, learning rate decay, and weight decay, we hypothesize that the pre-training loss landscape features a narrowing valley structure. Through experiments with synthetic loss functions, we discover that when gradient query noise is high relative to the valley's sharpness, Adam's performance falls behind that of Signum because Adam reduces the effective step size too drastically. This observation led us to develop FOCUS, an optimizer that enhances Signum by incorporating attraction toward moving averaged parameters, allowing it to handle noise better while maintaining larger step sizes. In training GPT-2, FOCUS proves to be more stable than Signum and faster than Adam. These results suggest that gradient noise may be an underappreciated limiting factor in LLM training, and FOCUS offers promising solutions.

[Arxiv](https://arxiv.org/abs/2501.12243)