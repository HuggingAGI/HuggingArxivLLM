# 开放式科学发现探索：基于贝叶斯惊奇的方法

发布时间：2025年06月30日

`LLM应用` `科学发现` `自主科学发现`

> Open-ended Scientific Discovery via Bayesian Surprise

# 摘要

> 自主科学发现（ASD）的成功不仅在于解答问题，更在于提出值得探索的问题。当前 ASD 研究主要集中在目标驱动环境下使用大型语言模型（LLMs），通过人类指定的研究问题来生成假设。然而，让 AI 系统根据自身标准驱动探索，可能进一步加速科学发现。现有的开放性 ASD 方法基于多样性和人类兴趣的主观指标选择假设，但前者难以有效探索庞大的假设空间，后者则因定义模糊而受限。本文提出 AutoDS —— 一种基于贝叶斯惊喜的开放性 ASD 方法。通过量化 LLM 对假设的先验和后验信念的知识转变，AutoDS 以惊喜作为奖励函数，结合蒙特卡洛树搜索（MCTS）策略，高效探索嵌套假设空间。我们在涵盖生物学、经济学、金融学和行为科学等领域的 21 个真实世界数据集上评估 AutoDS。结果显示，在固定预算下，AutoDS 产生的发现比竞争对手多出 5-29%，且这些发现被 LLM 认为更具惊喜价值。人工评估进一步表明，三分之二的 AutoDS 发现对领域专家来说也令人惊讶，这表明 AutoDS 是构建开放性 ASD 系统的重要进展。

> The promise of autonomous scientific discovery (ASD) hinges not only on answering questions, but also on knowing which questions to ask. Most recent works in ASD explore the use of large language models (LLMs) in goal-driven settings, relying on human-specified research questions to guide hypothesis generation. However, scientific discovery may be accelerated further by allowing the AI system to drive exploration by its own criteria. The few existing approaches in open-ended ASD select hypotheses based on diversity heuristics or subjective proxies for human interestingness, but the former struggles to meaningfully navigate the typically vast hypothesis space, and the latter suffers from imprecise definitions. This paper presents AutoDS -- a method for open-ended ASD that instead drives scientific exploration using Bayesian surprise. Here, we quantify the epistemic shift from the LLM's prior beliefs about a hypothesis to its posterior beliefs after gathering experimental results. To efficiently explore the space of nested hypotheses, our method employs a Monte Carlo tree search (MCTS) strategy with progressive widening using surprisal as the reward function. We evaluate AutoDS in the setting of data-driven discovery across 21 real-world datasets spanning domains such as biology, economics, finance, and behavioral science. Our results demonstrate that under a fixed budget, AutoDS substantially outperforms competitors by producing 5--29\% more discoveries deemed surprising by the LLM. Our human evaluation further finds that two-thirds of AutoDS discoveries are surprising to the domain experts, suggesting this is an important step forward towards building open-ended ASD systems.

[Arxiv](https://arxiv.org/abs/2507.00310)