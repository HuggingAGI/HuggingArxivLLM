# 基于分层专家的多目标大型语言模型对齐

发布时间：2025年05月27日

`LLM理论

摘要讨论了如何对齐大型语言模型以适应多样化的用户偏好，提出了一种新的模型结构HoE，属于理论研究，专注于模型优化和对齐方法。` `模型优化`

> Multi-objective Large Language Model Alignment with Hierarchical Experts

# 摘要

> 对齐大型语言模型（LLMs）以同时满足多个目标仍然是一个重大挑战，尤其是考虑到人类偏好多样化且往往相互冲突。现有的对齐方法难以有效平衡这些权衡，通常需要昂贵的重新训练或在Pareto前沿上产生次优结果。本文介绍了	extit{HoE}（分层专家混合模型），这是一种轻量级、参数高效且即插即用的方法，无需进行模型训练，同时使LLMs能够适应整个Pareto前沿，并适应多样化的用户偏好。具体而言，	extit{HoE}由三个分层组件组成：LoRA专家、路由器专家和偏好路由，达到最优Pareto前沿，并在参数规模、训练成本和性能之间取得平衡。我们在14个目标和6个基准中的200种不同偏好下，对	extit{HoE}进行了各种任务的评估，结果优于15个近期基线。代码可在补充材料中找到。

> Aligning large language models (LLMs) to simultaneously satisfy multiple objectives remains a significant challenge, especially given the diverse and often conflicting nature of human preferences. Existing alignment methods struggle to balance trade-offs effectively, often requiring costly retraining or yielding suboptimal results across the Pareto frontier of preferences. In this paper, we introduce \textit{HoE}(Hierarchical Mixture-of-Experts), a \textit{lightweight}, \textit{parameter-efficient}, and \textit{plug-and-play} approach that eliminates the need for model training, while enabling LLMs to adapt across the entire Pareto frontier and accommodate diverse user preferences. In particular, \textit{HoE} consists of three hierarchical components: LoRA Experts, Router Experts and Preference Routing, reaching optimal Pareto frontiers and achieving a trade-off between parameter size, training cost, and performance. We evaluate \textit{HoE} across various tasks on 14 objectives and 200 different preferences among 6 benchmarks, demonstrating superior performance over 15 recent baselines. Code is available in the supplementary materials.

[Arxiv](https://arxiv.org/abs/2505.20925)