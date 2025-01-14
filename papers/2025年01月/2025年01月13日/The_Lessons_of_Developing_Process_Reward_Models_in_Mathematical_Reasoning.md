# 数学推理中过程奖励模型开发的启示

发布时间：2025年01月13日

`LLM应用

**理由**：这篇论文主要讨论了过程奖励模型（PRMs）在大型语言模型（LLMs）数学推理中的应用，特别是如何通过改进数据合成方法和评估策略来提升PRMs的性能。论文还提出了新的评估框架和共识过滤机制，并发布了一个新的PRM模型。这些内容都属于LLM在实际应用中的优化和改进，因此应归类为“LLM应用”。` `数学推理` `模型评估`

> The Lessons of Developing Process Reward Models in Mathematical Reasoning

# 摘要

> # 摘要
过程奖励模型（PRMs）在LLMs的数学推理中展现出巨大潜力，旨在识别并纠正推理过程中的中间错误。然而，开发高效的PRMs面临诸多挑战，尤其是在数据标注和评估方法上。本文通过大量实验发现，常用的基于蒙特卡洛（MC）估计的数据合成方法在PRMs中表现不佳，泛化能力也不如LLM-as-a-judge和人工标注方法。MC估计依赖完成模型评估当前步骤的正确性，导致步骤验证不准确。此外，我们还发现传统Best-of-N（BoN）评估策略在PRMs中存在潜在偏差：（1）不可靠的策略模型生成的响应虽然答案正确但过程有误，导致BoN评估标准与PRM过程验证目标不一致。（2）PRMs对此类响应的容忍导致BoN评分虚高。（3）现有PRMs在最终答案步骤上集中了大量最低分，表明BoN优化PRMs从过程评估转向了结果评估。为解决这些问题，我们开发了一种共识过滤机制，将MC估计与LLM-as-a-judge有效结合，并提出了一个结合响应级和步骤级指标的更全面的评估框架。基于这些机制，我们在BoN评估和逐步错误识别任务中显著提升了模型性能和数据效率。最后，我们发布了一个新的最先进的PRM，其性能优于现有开源替代品，并为未来构建过程监督模型的研究提供了实用指南。

> Process Reward Models (PRMs) emerge as a promising approach for process supervision in mathematical reasoning of Large Language Models (LLMs), which aim to identify and mitigate intermediate errors in the reasoning processes. However, the development of effective PRMs faces significant challenges, particularly in data annotation and evaluation methodologies. In this paper, through extensive experiments, we demonstrate that commonly used Monte Carlo (MC) estimation-based data synthesis for PRMs typically yields inferior performance and generalization compared to LLM-as-a-judge and human annotation methods. MC estimation relies on completion models to evaluate current-step correctness, leading to inaccurate step verification. Furthermore, we identify potential biases in conventional Best-of-N (BoN) evaluation strategies for PRMs: (1) The unreliable policy models generate responses with correct answers but flawed processes, leading to a misalignment between the evaluation criteria of BoN and the PRM objectives of process verification. (2) The tolerance of PRMs of such responses leads to inflated BoN scores. (3) Existing PRMs have a significant proportion of minimum scores concentrated on the final answer steps, revealing the shift from process to outcome-based assessment in BoN Optimized PRMs. To address these challenges, we develop a consensus filtering mechanism that effectively integrates MC estimation with LLM-as-a-judge and advocates a more comprehensive evaluation framework that combines response-level and step-level metrics. Based on the mechanisms, we significantly improve both model performance and data efficiency in the BoN evaluation and the step-wise error identification task. Finally, we release a new state-of-the-art PRM that outperforms existing open-source alternatives and provides practical guidelines for future research in building process supervision models.

[Arxiv](https://arxiv.org/abs/2501.07301)