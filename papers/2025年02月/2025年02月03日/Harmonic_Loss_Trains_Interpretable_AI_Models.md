# 谐波损失助力训练可解释的AI模型

发布时间：2025年02月03日

`LLM理论

**理由**：这篇论文主要讨论了谐波损失作为一种新的损失函数，用于训练神经网络和大型语言模型（LLMs）。它涉及到了模型训练的理论基础，特别是损失函数的设计和其对模型性能的影响。因此，这篇论文更适合归类为LLM理论。` `机器学习`

> Harmonic Loss Trains Interpretable AI Models

# 摘要

> 本文提出**谐波损失**作为标准交叉熵损失的替代方案，用于训练神经网络和大型语言模型（LLMs）。谐波损失凭借其尺度不变性和设计上的有限收敛点（可视为类中心），能够提升模型的可解释性并加速收敛。我们首先在算法、视觉和语言数据集上验证了谐波模型的性能。大量实验表明，谐波损失训练的模型在以下方面优于标准模型：(a) 增强可解释性，(b) 减少泛化所需数据，(c) 降低“grokking”现象。此外，与标准GPT-2相比，谐波损失训练的GPT-2模型生成了更具可解释性的表示。展望未来，谐波损失有望在数据有限或对可解释性和可靠性要求极高的高风险应用领域中大放异彩，为更强大、高效的神经网络模型开辟新路径。

> In this paper, we introduce **harmonic loss** as an alternative to the standard cross-entropy loss for training neural networks and large language models (LLMs). Harmonic loss enables improved interpretability and faster convergence, owing to its scale invariance and finite convergence point by design, which can be interpreted as a class center. We first validate the performance of harmonic models across algorithmic, vision, and language datasets. Through extensive experiments, we demonstrate that models trained with harmonic loss outperform standard models by: (a) enhancing interpretability, (b) requiring less data for generalization, and (c) reducing grokking. Moreover, we compare a GPT-2 model trained with harmonic loss to the standard GPT-2, illustrating that the harmonic model develops more interpretable representations. Looking forward, we believe harmonic loss has the potential to become a valuable tool in domains with limited data availability or in high-stakes applications where interpretability and reliability are paramount, paving the way for more robust and efficient neural network models.

[Arxiv](https://arxiv.org/abs/2502.01628)