# 基于大型语言模型的多臂老虎机优化

发布时间：2025年02月03日

`LLM应用

**理由**：这篇论文主要讨论了如何将大型语言模型（LLMs）应用于多臂赌博机（MAB）任务中，通过结合经典MAB算法和LLMs的上下文学习能力来改进奖励预测和决策过程。论文的核心在于如何利用LLMs的强大能力来解决具体的决策任务，而不是探讨LLMs的理论基础或构建新的LLM架构。因此，这篇论文属于**LLM应用**的范畴。` `决策系统` `机器学习`

> Large Language Model-Enhanced Multi-Armed Bandits

# 摘要

> # 摘要
大型语言模型（LLMs）已被用于解决顺序决策任务，如多臂赌博机（MAB），其中LLM直接指导每次迭代中选择要拉动的臂。然而，这种直接使用LLMs选择臂的方式在许多MAB任务中表现不佳。因此，我们提出了一种结合经典MAB和LLMs优势的新方法。具体来说，我们采用经典MAB算法作为高层框架，并利用LLMs强大的上下文学习能力来执行奖励预测的子任务。首先，我们将基于LLM的奖励预测器集成到经典的Thompson采样（TS）算法中，并通过LLM温度的衰减计划确保从探索到利用的过渡。接着，我们将基于LLM的奖励预测器（温度为0）集成到具有显式探索机制的基于回归oracle的MAB算法中。我们还将基于TS的算法扩展到决斗赌博机，其中只有臂对之间的偏好反馈可用，这需要复杂的算法修改。我们使用合成的MAB任务和基于真实世界文本数据集设计的实验进行实证评估，结果表明我们的算法始终优于基于直接臂选择的先前基线方法。有趣的是，我们还证明了在具有挑战性的任务中，当臂缺乏LLM可以利用的语义含义时，我们的方法比基于LLM的直接臂选择方法表现更好。

> Large language models (LLMs) have been adopted to solve sequential decision-making tasks such as multi-armed bandits (MAB), in which an LLM is directly instructed to select the arms to pull in every iteration. However, this paradigm of direct arm selection using LLMs has been shown to be suboptimal in many MAB tasks. Therefore, we propose an alternative approach which combines the strengths of classical MAB and LLMs. Specifically, we adopt a classical MAB algorithm as the high-level framework and leverage the strong in-context learning capability of LLMs to perform the sub-task of reward prediction. Firstly, we incorporate the LLM-based reward predictor into the classical Thompson sampling (TS) algorithm and adopt a decaying schedule for the LLM temperature to ensure a transition from exploration to exploitation. Next, we incorporate the LLM-based reward predictor (with a temperature of 0) into a regression oracle-based MAB algorithm equipped with an explicit exploration mechanism. We also extend our TS-based algorithm to dueling bandits where only the preference feedback between pairs of arms is available, which requires non-trivial algorithmic modifications. We conduct empirical evaluations using both synthetic MAB tasks and experiments designed using real-world text datasets, in which the results show that our algorithms consistently outperform previous baseline methods based on direct arm selection. Interestingly, we also demonstrate that in challenging tasks where the arms lack semantic meanings that can be exploited by the LLM, our approach achieves considerably better performance than LLM-based direct arm selection.

[Arxiv](https://arxiv.org/abs/2502.01118)