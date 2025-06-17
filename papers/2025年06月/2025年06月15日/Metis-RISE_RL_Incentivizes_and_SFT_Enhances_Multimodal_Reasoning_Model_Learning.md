# Metis-RISE：强化学习驱动，监督微调优化，助力多模态推理模型学习

发布时间：2025年06月15日

`LLM应用` `多模态` `大规模语言模型`

> Metis-RISE: RL Incentivizes and SFT Enhances Multimodal Reasoning Model Learning

# 摘要

> 近期，大型语言模型（LLMs）在高级推理范式方面的突破性进展推动了这些范式被整合到多模态大语言模型（MLLMs）中。然而，现有方法存在不足：仅使用强化学习（RL）的方法可能在采样效率和激活完全缺失的推理能力方面表现不佳，而传统的从冷启动监督微调（SFT）阶段开始、随后进行 RL 的管道可能限制模型的探索能力，并面临次优收敛的问题。在本研究中，我们引入了 	extbf{Metis-RISE}（	extbf{R}L 	extbf{I}ncentivizes 和 	extbf{S}FT 	extbf{E}nhances），用于多模态推理模型学习。与传统方法不同，Metis-RISE 独特地省略了初始 SFT 阶段，而是从 RL 阶段（例如使用一种 Group Relative Policy Optimization 的变体）开始，以激励和激活模型的潜在推理能力。随后，针对 RL 阶段识别出的两大关键挑战，我们进入目标明确的 SFT 阶段：（1）对于模型具备但未能一致应用正确推理能力的任务，存在 	extit{低效轨迹采样}的问题，我们通过从 RL 模型自身中提取自我蒸馏的推理轨迹来解决；（2）对于模型完全失效的提示，存在 	extit{基本能力缺失}的问题，我们通过注入增强专家知识来解决。这种先利用 RL 激励推理能力、再通过 SFT 进行增强的战略性应用构成了 Metis-RISE 的核心，最终形成了我们两个版本的 MLLMs（7B 和 72B 参数）。在 OpenCompass 多模态推理排行榜上的评估表明，这两个模型在同类规模的模型中均达到了最先进的性能水平，其中 72B 版本整体排名第四。

> Recent advancements in large language models (LLMs) have witnessed a surge in the development of advanced reasoning paradigms, which are now being integrated into multimodal large language models (MLLMs). However, existing approaches often fall short: methods solely employing reinforcement learning (RL) can struggle with sample inefficiency and activating entirely absent reasoning capabilities, while conventional pipelines that initiate with a cold-start supervised fine-tuning (SFT) phase before RL may restrict the model's exploratory capacity and face suboptimal convergence. In this work, we introduce \textbf{Metis-RISE} (\textbf{R}L \textbf{I}ncentivizes and \textbf{S}FT \textbf{E}nhances) for multimodal reasoning model learning. Unlike conventional approaches, Metis-RISE distinctively omits an initial SFT stage, beginning instead with an RL phase (e.g., using a Group Relative Policy Optimization variant) to incentivize and activate the model's latent reasoning capacity. Subsequently, the targeted SFT stage addresses two key challenges identified during RL: (1) \textit{inefficient trajectory sampling} for tasks where the model possesses but inconsistently applies correct reasoning, which we tackle using self-distilled reasoning trajectories from the RL model itself; and (2) \textit{fundamental capability absence}, which we address by injecting expert-augmented knowledge for prompts where the model entirely fails. This strategic application of RL for incentivization followed by SFT for enhancement forms the core of Metis-RISE, leading to two versions of our MLLMs (7B and 72B parameters). Evaluations on the OpenCompass Multimodal Reasoning Leaderboard demonstrate that both models achieve state-of-the-art performance among similar-sized models, with the 72B version ranking fourth overall.

[Arxiv](https://arxiv.org/abs/2506.13056)