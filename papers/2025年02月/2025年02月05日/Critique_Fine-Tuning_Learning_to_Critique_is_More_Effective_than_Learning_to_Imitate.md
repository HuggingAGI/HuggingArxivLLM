# # 批判性微调：学习批判比学习模仿更高效

发布时间：2025年02月05日

`LLM应用`

> Critique Fine-Tuning: Learning to Critique is More Effective than Learning to Imitate

# 摘要

> 监督微调（SFT）是训练语言模型模仿标注响应的常用方法。本文提出了一种全新范式——批判微调（CFT），模型通过学习批判噪声响应而非简单模仿正确答案来提升能力。受人类批判性思维学习过程启发，CFT能培养更深入的分析能力和细致的理解力，这些往往是标准SFT所忽视的。

我们从WebInstruct构建了一个5万样本的数据集，使用GPT-4o作为教师生成批判性反馈，形式为([query; noisy response], critique)。在基于Qwen2.5、Qwen2.5-Math和DeepSeek-Math等不同基础模型的六个数学基准测试中，CFT的表现始终比SFT高出4-10%。进一步扩展到MetaMath和NuminaMath数据集，发现CFT同样显著超越SFT。

值得注意的是，我们的模型Qwen2.5-Math-CFT仅需在8xH100上对5万个示例进行1小时训练，便能在大多数基准测试中与使用超过200万个样本的强竞争者Qwen2.5-Math-Instruct相匹配或超越。此外，它还能达到SimpleRL的性能，这是一个使用140倍计算资源训练的深度求索-r1复现。

消融研究表明，CFT对噪声响应来源和教师批判模型具有良好的鲁棒性。通过这些发现，我们主张CFT为推进语言模型推理提供了一个更有效的替代方案。

> Supervised Fine-Tuning (SFT) is commonly used to train language models to imitate annotated responses for given instructions. In this paper, we challenge this paradigm and propose Critique Fine-Tuning (CFT), a strategy where models learn to critique noisy responses rather than simply imitate correct ones. Inspired by human learning processes that emphasize critical thinking, CFT encourages deeper analysis and nuanced understanding-traits often overlooked by standard SFT. To validate the effectiveness of CFT, we construct a 50K-sample dataset from WebInstruct, using GPT-4o as the teacher to generate critiques in the form of ([query; noisy response], critique). CFT on this dataset yields a consistent 4-10% improvement over SFT on six math benchmarks with different base models like Qwen2.5, Qwen2.5-Math and DeepSeek-Math. We further expand to MetaMath and NuminaMath datasets and observe similar gains over SFT. Notably, our model Qwen2.5-Math-CFT only requires 1 hour training on 8xH100 over the 50K examples. It can match or outperform strong competitors like Qwen2.5-Math-Instruct on most benchmarks, which use over 2M samples. Moreover, it can match the performance of SimpleRL, which is a deepseek-r1 replication trained with 140x more compute. Ablation studies show that CFT is robust to the source of noisy response and teacher critique model. Through these findings, we argue that CFT offers a more effective alternative to advance the reasoning of language models.

[Arxiv](https://arxiv.org/abs/2501.17703)