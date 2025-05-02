# DeepCritic：借助大型语言模型进行深思熟虑的批判

发布时间：2025年05月01日

`LLM应用

摘要讨论了如何利用大型语言模型（LLMs）作为批注模型来提供自动化监督，特别是提升其数学批注能力。研究者提出了一种两阶段框架，生成种子数据并进行强化学习，以改进模型的批注能力，帮助LLM生成器修正错误。这属于应用层面的开发，因此归类为LLM应用。` `数学教育`

> DeepCritic: Deliberate Critique with Large Language Models

# 摘要

> 大型语言模型（LLMs）的飞速发展使得为其输出提供准确反馈和可扩展监督成为亟待解决的关键问题。利用 LLM 作为批注模型实现自动化监督，是解决这一问题的潜力方案。本研究聚焦于探索和提升 LLM 的数学批注能力。

当前 LLM 批注模型存在批注浅显、判断不准等问题，难以有效帮助 LLM 生成器修正错误。为解决这一问题，我们提出了一种创新的两阶段框架，用于开发能够对数学解题过程进行深入批注的 LLM 批注模型。

在第一阶段，我们利用 Qwen2.5-72B-Instruct 生成 4.5K 长篇批注作为有监督微调的种子数据。每个种子批注包含多角度验证和对每一步推理过程的深入分析，以及对初始批注的进一步优化。

随后，我们在微调后的模型上进行强化学习。通过使用现有标注数据集 PRM800K 或基于蒙特卡罗采样法获得的自动标注数据，进一步提升模型的批注能力。

我们基于 Qwen2.5-7B-Instruct 开发的批注模型，在各类错误识别基准测试中表现显著优于现有 LLM 批注模型（包括同规模的 DeepSeek-R1-distill 模型和 GPT-4o）。更重要的是，它能通过更详细的反馈，更有效地帮助 LLM 生成器修正错误步骤。

> As Large Language Models (LLMs) are rapidly evolving, providing accurate feedback and scalable oversight on their outputs becomes an urgent and critical problem. Leveraging LLMs as critique models to achieve automated supervision is a promising solution. In this work, we focus on studying and enhancing the math critique ability of LLMs. Current LLM critics provide critiques that are too shallow and superficial on each step, leading to low judgment accuracy and struggling to offer sufficient feedback for the LLM generator to correct mistakes. To tackle this issue, we propose a novel and effective two-stage framework to develop LLM critics that are capable of deliberately critiquing on each reasoning step of math solutions. In the first stage, we utilize Qwen2.5-72B-Instruct to generate 4.5K long-form critiques as seed data for supervised fine-tuning. Each seed critique consists of deliberate step-wise critiques that includes multi-perspective verifications as well as in-depth critiques of initial critiques for each reasoning step. Then, we perform reinforcement learning on the fine-tuned model with either existing human-labeled data from PRM800K or our automatically annotated data obtained via Monte Carlo sampling-based correctness estimation, to further incentivize its critique ability. Our developed critique model built on Qwen2.5-7B-Instruct not only significantly outperforms existing LLM critics (including the same-sized DeepSeek-R1-distill models and GPT-4o) on various error identification benchmarks, but also more effectively helps the LLM generator refine erroneous steps through more detailed feedback.

[Arxiv](https://arxiv.org/abs/2505.00662)