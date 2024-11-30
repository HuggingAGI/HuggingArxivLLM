# 在在线学习和游戏中，LLM 代理是否会产生“遗憾”？本文以案例研究的方式对此进行探讨。

发布时间：2024年03月25日

`Agent` `多智能体系统` `决策理论`

> Do LLM Agents Have Regret? A Case Study in Online Learning and Games

# 摘要

> 随着LLM自主智能体的发展，大型语言模型在（交互式）决策领域应用愈发广泛，但其在多智能体互动情境下的决策制定性能，特别是现实世界应用中的典型场景，尚未得到充分量化评估。为了深入探究LLM智能体在复杂交互环境中的能力边界，我们提议在在线学习和博弈论的标准决策环境中，通过“遗憾度”这一评价指标来研究它们的交互行为。首先，我们从实证角度探讨了LLMs在非平稳在线学习任务中的无遗憾特性，以及在智能体间通过重复博弈互动时可能出现的均衡状态。同时，在对人类决策者生成数据的监督预训练及理性模型做出合理假设的基础上，我们揭示了LLM智能体无遗憾行为的一些理论原理，并特别指出了即便像GPT-4这样的先进模型，在某些简单场景下也无法确保无遗憾。为此，我们创新性地提出了一种无需标注（最优）动作的无监督训练损失——遗憾损失。我们进一步确立了该遗憾损失最小化方法的泛化界统计保证，并论证了通过优化这种损失可以自发引导至已知有效的无遗憾学习算法。最后，通过更多实验验证了我们提出的遗憾损失在解决上述“遗憾”问题上的显著效果。

> Large language models (LLMs) have been increasingly employed for (interactive) decision-making, via the development of LLM-based autonomous agents. Despite their emerging successes, the performance of LLM agents in decision-making has not been fully investigated through quantitative metrics, especially in the multi-agent setting when they interact with each other, a typical scenario in real-world LLM-agent applications. To better understand the limits of LLM agents in these interactive environments, we propose to study their interactions in benchmark decision-making settings in online learning and game theory, through the performance metric of \emph{regret}. We first empirically study the {no-regret} behaviors of LLMs in canonical (non-stationary) online learning problems, as well as the emergence of equilibria when LLM agents interact through playing repeated games. We then provide some theoretical insights into the no-regret behaviors of LLM agents, under certain assumptions on the supervised pre-training and the rationality model of human decision-makers who generate the data. Notably, we also identify (simple) cases where advanced LLMs such as GPT-4 fail to be no-regret. To promote the no-regret behaviors, we propose a novel \emph{unsupervised} training loss of \emph{regret-loss}, which, in contrast to the supervised pre-training loss, does not require the labels of (optimal) actions. We then establish the statistical guarantee of generalization bound for regret-loss minimization, followed by the optimization guarantee that minimizing such a loss may automatically lead to known no-regret learning algorithms. Our further experiments demonstrate the effectiveness of our regret-loss, especially in addressing the above ``regrettable'' cases.

[Arxiv](https://arxiv.org/abs/2403.16843)