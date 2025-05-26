# ConciseRL: 通过简洁性引导的强化学习打造高效推理模型

发布时间：2025年05月22日

`LLM应用

摘要中提到，论文提出了一种方法来优化大型语言模型的推理过程，使其更高效、简洁，同时保持准确性。这涉及到模型的应用改进，属于LLM应用。` `人工智能`

> ConciseRL: Conciseness-Guided Reinforcement Learning for Efficient Reasoning Models

# 摘要

> 大型语言模型通过将复杂问题分解为结构化的推理步骤，在处理复杂任务时表现出色。然而，推理过程往往超出得出正确答案的范围，导致计算资源浪费、可读性降低以及产生幻觉。为了解决这一问题，我们提出了一种无需超参数的简洁性评分方法，将其作为强化学习框架中的奖励信号，引导模型生成既正确又简洁的推理过程。该评分由一个大型语言模型作为评估器进行计算，能够提供动态且语境感知的反馈，而不仅仅是简单地基于token数量进行评估。我们的方法在MATH数据集上实现了效率与准确性的最佳平衡，相比完整推理过程，简单问题的token使用量减少高达31倍，准确率提升7%；在最难的问题上，准确率提高了7.5%，token使用量减少高达3.6倍。在TheoremQA数据集上，我们的方法使用12.5倍少的token，准确率提升了2.2%。通过消融研究，我们发现，我们的方法能够根据问题难度动态调整推理长度，并且从更强大的评估器中获益显著。代码、模型权重和数据集已开源，地址为https://github.com/RazvanDu/ConciseRL。

> Large language models excel at complex tasks by breaking down problems into structured reasoning steps. However, reasoning traces often extend beyond reaching a correct answer, causing wasted computation, reduced readability, and hallucinations. To address this, we introduce a novel hyperparameter-free conciseness score used as a reward signal within a reinforcement learning framework to guide models toward generating correct and concise reasoning traces. This score is evaluated by a large language model acting as a judge, enabling dynamic, context-aware feedback beyond simple token length. Our method achieves state-of-the-art efficiency-accuracy trade-offs on the MATH dataset, reducing token usage by up to 31x on simple problems while improving accuracy by 7%, and on the hardest problems, it outperforms full reasoning by +7.5% accuracy with up to 3.6x fewer tokens. On TheoremQA, our method improves accuracy by +2.2% using 12.5x fewer tokens. We also conduct ablation studies on the judge model, reward composition, and problem difficulty, showing that our method dynamically adapts reasoning length based on problem difficulty and benefits significantly from stronger judges. The code, model weights, and datasets are open-sourced at https://github.com/RazvanDu/ConciseRL.

[Arxiv](https://arxiv.org/abs/2505.17250)