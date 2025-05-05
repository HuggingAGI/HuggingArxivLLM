# 更高效的大语言模型探索：AMP下的注意力头与MLP剪枝研究

发布时间：2025年04月29日

`LLM应用` `人工智能` `计算系统`

> Efficient LLMs with AMP: Attention Heads and MLP Pruning

# 摘要

> 深度学习正在掀起计算系统的新一波变革，并推动日益复杂的自动化问题的解决。大型语言模型（LLMs）在认知任务方面取得了显著进展，经常能达到甚至超越人类水平的表现。然而，这些模型的庞大参数量带来了高昂的计算成本和缓慢的推理速度，这在资源受限的环境中部署时带来了挑战。在克服上述挑战的各种策略中，剪枝作为一种成功机制脱颖而出。它不仅降低了模型规模，还保持了预测能力。本文中，我们引入了AMP：注意力头和MLP剪枝（AMP: Attention Heads and MLP Pruning），这是一种新型的结构化剪枝方法，通过去除多头注意力（MHA）和多层感知机（MLP）中不太关键的结构，高效地压缩大型语言模型。通过将输入数据投射到权重上，AMP评估结构重要性，并克服了现有技术在灵活性或效率上的不足。特别地，在常识推理任务上，AMP超越了当前最先进水平，最高提升了1.49个百分点，同时实现了30%的剪枝比例，对零样本任务性能的影响最小。此外，AMP还提高了推理速度，使其非常适合在资源受限的环境中部署。我们验证了AMP在不同家族的大型语言模型上的灵活性，包括LLaMA和Phi。

> Deep learning drives a new wave in computing systems and triggers the automation of increasingly complex problems. In particular, Large Language Models (LLMs) have significantly advanced cognitive tasks, often matching or even surpassing human-level performance. However, their extensive parameters result in high computational costs and slow inference, posing challenges for deployment in resource-limited settings. Among the strategies to overcome the aforementioned challenges, pruning emerges as a successful mechanism since it reduces model size while maintaining predictive ability. In this paper, we introduce AMP: Attention Heads and MLP Pruning, a novel structured pruning method that efficiently compresses LLMs by removing less critical structures within Multi-Head Attention (MHA) and Multilayer Perceptron (MLP). By projecting the input data onto weights, AMP assesses structural importance and overcomes the limitations of existing techniques, which often fall short in flexibility or efficiency. In particular, AMP surpasses the current state-of-the-art on commonsense reasoning tasks by up to 1.49 percentage points, achieving a 30% pruning ratio with minimal impact on zero-shot task performance. Moreover, AMP also improves inference speeds, making it well-suited for deployment in resource-constrained environments. We confirm the flexibility of AMP on different families of LLMs, including LLaMA and Phi.

[Arxiv](https://arxiv.org/abs/2504.21174)