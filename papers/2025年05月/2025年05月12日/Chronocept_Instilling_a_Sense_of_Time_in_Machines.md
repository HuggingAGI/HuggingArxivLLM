# # Chronocept：赋予机器时间感知能力

发布时间：2025年05月12日

`LLM应用` `信息检索`

> Chronocept: Instilling a Sense of Time in Machines

# 摘要

> 人类认知与时间感知（Chronoception）密不可分，这种感知让我们能够判断事实的有效期以及知识何时过时。尽管AI在视觉、语言和运动控制方面取得了进展，但在时间有效性推理上仍显不足。我们推出Chronocept，这是首个将时间有效性建模为随时间连续概率分布的基准测试。通过在语义分解的时间轴上拟合偏正态曲线，Chronocept捕捉了出现、衰减和峰值相关性的微妙模式。它包含两个数据集：基准I（原子事实）和基准II（多句子段落）。标注结果显示了较强的标注者一致性（84%和89%）。我们的基线模型预测曲线参数——位置、尺度和偏态——实现了可解释且可推广的学习，并超越了基于分类的方法。Chronocept填补了AI在时间推理中的基础空白，支持知识接地、事实核查、增强检索生成（RAG）和主动代理等应用。代码和数据公开可用。


> Human cognition is deeply intertwined with a sense of time, known as Chronoception. This sense allows us to judge how long facts remain valid and when knowledge becomes outdated. Despite progress in vision, language, and motor control, AI still struggles to reason about temporal validity. We introduce Chronocept, the first benchmark to model temporal validity as a continuous probability distribution over time. Using skew-normal curves fitted along semantically decomposed temporal axes, Chronocept captures nuanced patterns of emergence, decay, and peak relevance. It includes two datasets: Benchmark I (atomic facts) and Benchmark II (multi-sentence passages). Annotations show strong inter-annotator agreement (84% and 89%). Our baselines predict curve parameters - location, scale, and skewness - enabling interpretable, generalizable learning and outperforming classification-based approaches. Chronocept fills a foundational gap in AI's temporal reasoning, supporting applications in knowledge grounding, fact-checking, retrieval-augmented generation (RAG), and proactive agents. Code and data are publicly available.

[Arxiv](https://arxiv.org/abs/2505.07637)