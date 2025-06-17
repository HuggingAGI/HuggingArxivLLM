# # 直接推理优化：LLMs能够自我奖励并精进自己的推理能力，以应对开放性任务

发布时间：2025年06月16日

`LLM理论`

> Direct Reasoning Optimization: LLMs Can Reward And Refine Their Own Reasoning for Open-Ended Tasks

# 摘要

> 大型语言模型（LLMs）在数学和编程等结构化任务中展现出了令人印象深刻的推理能力，这一进步主要得益于基于可验证奖励的强化学习（RLVR）。然而，将类似技术应用于开放性的长篇推理任务仍具挑战，原因在于缺乏通用的、可验证的奖励信号。为解决这一问题，我们提出了一种新的强化学习框架——直接推理优化（DRO），用于微调LLMs在开放性、尤其是长篇推理任务上的表现。该框架采用了一种新型奖励信号：推理反思奖励（R3）。R3的核心机制在于，它能够识别并强调参考结果中反映模型先前推理链影响的关键令牌，从而在细粒度层面上捕捉推理与参考结果的一致性。至关重要的是，R3的计算完全依赖于正在优化的同一模型，从而实现了完全自洽的训练环境。此外，我们还引入了一种基于R3的动态数据过滤策略，专门针对开放性推理任务，该策略在降低训练成本的同时提升了下游任务的性能。我们在两个多样化的数据集上评估了DRO框架：ParaRev（长篇段落修订任务）和FinQA（数学导向问答基准）。实验结果表明，DRO不仅在开放性和结构化领域中表现优异，而且在整体适用性上也显著超越了现有的强基线方法。


> Recent advances in Large Language Models (LLMs) have showcased impressive reasoning abilities in structured tasks like mathematics and programming, largely driven by Reinforcement Learning with Verifiable Rewards (RLVR), which uses outcome-based signals that are scalable, effective, and robust against reward hacking. However, applying similar techniques to open-ended long-form reasoning tasks remains challenging due to the absence of generic, verifiable reward signals. To address this, we propose Direct Reasoning Optimization (DRO), a reinforcement learning framework for fine-tuning LLMs on open-ended, particularly long-form, reasoning tasks, guided by a new reward signal: the Reasoning Reflection Reward (R3). At its core, R3 selectively identifies and emphasizes key tokens in the reference outcome that reflect the influence of the model's preceding chain-of-thought reasoning, thereby capturing the consistency between reasoning and reference outcome at a fine-grained level. Crucially, R3 is computed internally using the same model being optimized, enabling a fully self-contained training setup. Additionally, we introduce a dynamic data filtering strategy based on R3 for open-ended reasoning tasks, reducing cost while improving downstream performance. We evaluate DRO on two diverse datasets -- ParaRev, a long-form paragraph revision task, and FinQA, a math-oriented QA benchmark -- and show that it consistently outperforms strong baselines while remaining broadly applicable across both open-ended and structured domains.

[Arxiv](https://arxiv.org/abs/2506.13351)