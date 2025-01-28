# 基于语言的贝叶斯优化研究助手 (BORA)

发布时间：2025年01月27日

`LLM应用

理由：该论文摘要描述了如何利用大型语言模型（LLMs）来增强贝叶斯优化（BO）框架，通过结合LLM的领域知识和随机推理，智能地推荐搜索空间中更具潜力的区域。这种方法在实际实验任务中展示了LLMs的推理能力，并显著提升了优化效果。因此，这篇论文属于LLM应用的范畴，因为它探讨了如何将LLMs应用于优化问题，并展示了其在实际任务中的有效性。` `实验设计`

> Language-Based Bayesian Optimization Research Assistant (BORA)

# 摘要

> 许多科学难题涉及多元优化与耗时费力的实验测量。这些复杂的高维搜索常面临非凸优化问题，犹如大海捞针，容易陷入局部最优。结合人类领域知识来引导优化器是一种有效策略，但这种方法易受确认偏见影响，且领域专家难以跟上快速增长的文献。为此，我们提出利用大型语言模型（LLMs）通过混合优化框架来情境化贝叶斯优化（BO），该框架巧妙地将随机推理与LLM的领域知识结合，智能地推荐搜索空间中更具潜力的区域。我们的方法通过实时反馈优化进展和解释搜索策略，增强了用户参与感。我们在多达15个变量的合成基准上验证了该方法的有效性，并展示了LLMs在四个实际实验任务中的推理能力，情境感知建议显著提升了优化效果。

> Many important scientific problems involve multivariate optimization coupled with slow and laborious experimental measurements. These complex, high-dimensional searches can be defined by non-convex optimization landscapes that resemble needle-in-a-haystack surfaces, leading to entrapment in local minima. Contextualizing optimizers with human domain knowledge is a powerful approach to guide searches to localized fruitful regions. However, this approach is susceptible to human confirmation bias and it is also challenging for domain experts to keep track of the rapidly expanding scientific literature. Here, we propose the use of Large Language Models (LLMs) for contextualizing Bayesian optimization (BO) via a hybrid optimization framework that intelligently and economically blends stochastic inference with domain knowledge-based insights from the LLM, which is used to suggest new, better-performing areas of the search space for exploration. Our method fosters user engagement by offering real-time commentary on the optimization progress, explaining the reasoning behind the search strategies. We validate the effectiveness of our approach on synthetic benchmarks with up to 15 independent variables and demonstrate the ability of LLMs to reason in four real-world experimental tasks where context-aware suggestions boost optimization performance substantially.

[Arxiv](https://arxiv.org/abs/2501.16224)