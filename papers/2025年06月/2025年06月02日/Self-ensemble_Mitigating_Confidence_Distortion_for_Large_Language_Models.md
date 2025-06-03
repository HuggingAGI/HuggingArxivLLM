# Self-ensemble：缓解大型语言模型中的信心失真

发布时间：2025年06月02日

`LLM应用` `问答系统`

> Self-ensemble: Mitigating Confidence Distortion for Large Language Models

# 摘要

> 大型语言模型（LLMs）在通用领域表现优异，但在多选题问答（MCQA）中面临信心失真挑战，尤其当答案选项增加时问题更为突出。具体表现为对正确预测的不自信和对错误预测的过度自信，导致性能显著下滑。为应对这一挑战，我们提出了一种自集成方法。该方法通过将选项分组，并在各组间对 LLM 的预测结果进行集成，最终做出决策。自集成的优势在于其即插即用的特性，能够轻松集成到现有 LLM 架构中，无需额外标注数据集进行参数调优。实验结果表明，自集成方法有效解决了 LLM 的信心失真问题，在三个 LLM 和数据集上的表现优于标准推理和基线方法。

> Although Large Language Models (LLMs) perform well in general fields, they exhibit a confidence distortion problem on multi-choice question-answering (MCQA), particularly as the number of answer choices increases. Specifically, on MCQA with many choices, LLMs suffer from under-confidence in correct predictions and over-confidence in incorrect ones, leading to a substantially degraded performance. To solve this problem, we propose Self-ensemble in this work. Our method splits the choices into several groups and ensembles LLM predictions across these groups to reach a final decision. The advantage of Self-ensemble is its plug-and-play nature, where it can be integrated into existing LLM architecture based on a designed attention mask and positional encoding, without requiring labeled datasets for parameter tuning. Experimental results on three LLMs and datasets demonstrate that Self-ensemble comprehensively addresses the confidence distortion problem of LLMs, outperforming standard inference as well as baseline methods.

[Arxiv](https://arxiv.org/abs/2506.01951)