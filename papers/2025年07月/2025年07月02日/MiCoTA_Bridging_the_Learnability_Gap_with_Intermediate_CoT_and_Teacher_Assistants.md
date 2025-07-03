# MiCoTA：通过中间 CoT 和教师助手构建可学习性桥梁

发布时间：2025年07月02日

`LLM理论` `人工智能`

> MiCoTA: Bridging the Learnability Gap with Intermediate CoT and Teacher Assistants

# 摘要

> 大型语言模型（LLMs）在需要长链思考序列的推理任务中表现出色，但其庞大的规模和高计算需求限制了广泛应用。我们发现小型语言模型（SLMs）由于容量限制，难以学习长链CoT推理，这一现象称为“SLMs可学习性差距”。为解决这一问题，我们提出了	extbf{Mi}d-	extbf{Co}T 	extbf{T}eacher 	extbf{A}ssistant Distillation（MiCoTA）框架，通过中等规模模型作为教师助手，利用中等长度的CoT序列，有效弥合了容量和推理长度的差距。实验表明，MiCoTA显著提升了SLMs的推理性能，在多个基准测试中，Qwen2.5-7B-Instruct和Qwen2.5-3B-Instruct的平均得分分别提升了3.47和3.93。通过定量实验，我们验证了MiCoTA生成的数据更贴近基础SLMs的分布，为未来研究SLMs的长链CoT数据蒸馏提供了重要见解。

> Large language models (LLMs) excel at reasoning tasks requiring long thought sequences for planning, reflection, and refinement. However, their substantial model size and high computational demands are impractical for widespread deployment. Yet, small language models (SLMs) often struggle to learn long-form CoT reasoning due to their limited capacity, a phenomenon we refer to as the "SLMs Learnability Gap". To address this, we introduce \textbf{Mi}d-\textbf{Co}T \textbf{T}eacher \textbf{A}ssistant Distillation (MiCoTAl), a framework for improving long CoT distillation for SLMs. MiCoTA employs intermediate-sized models as teacher assistants and utilizes intermediate-length CoT sequences to bridge both the capacity and reasoning length gaps. Our experiments on downstream tasks demonstrate that although SLMs distilled from large teachers can perform poorly, by applying MiCoTA, they achieve significant improvements in reasoning performance. Specifically, Qwen2.5-7B-Instruct and Qwen2.5-3B-Instruct achieve an improvement of 3.47 and 3.93 respectively on average score on AIME2024, AMC, Olympiad, MATH-500 and GSM8K benchmarks. To better understand the mechanism behind MiCoTA, we perform a quantitative experiment demonstrating that our method produces data more closely aligned with base SLM distributions. Our insights pave the way for future research into long-CoT data distillation for SLMs.

[Arxiv](https://arxiv.org/abs/2507.01887)