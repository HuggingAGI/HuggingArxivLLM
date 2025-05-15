# SafePath：基于大语言模型的自主导航安全符合性预测

发布时间：2025年05月14日

`LLM应用

理由：这篇论文探讨了大型语言模型在自动驾驶路径规划中的应用，并提出了一种框架来解决其安全性和可靠性问题，属于LLM的应用研究。` `自动驾驶` `路径规划`

> SafePath: Conformal Prediction for Safe LLM-Based Autonomous Navigation

# 摘要

> 大型语言模型（LLMs）在自动驾驶领域展现出巨大潜力，能够通过推理复杂交通场景生成路径规划。然而，它们过于自信和产生幻觉的倾向引发了严重的安全问题。为此，我们提出了SafePath——一个模块化框架，通过结合形式化安全保证和符合性预测，增强基于LLM的路径规划能力。SafePath分为三个阶段运行：

1. **路径生成**：使用LLM生成一组多样化的候选路径，基于智能体行为和环境提示探索可能的轨迹。
2. **风险过滤**：通过一种结合了符合性预测的多选问答形式，过滤掉高风险轨迹，同时保证至少包含一个安全选项的概率达到用户定义的水平。
3. **路径选择**：当不确定性较低时，选择碰撞风险最低的路径；当不确定性较高时，则将控制权委托给人类。

我们从理论上证明了SafePath能够以用户定义的概率保证一条安全轨迹，并展示了如何调整其对人类的委托率以平衡自主性和安全性。在nuScenes和Highway-env上的大量实验表明，SafePath将规划不确定性降低了77%，并将碰撞率降低了高达70%，证明了其在使LLM驱动的路径规划更加安全方面的显著有效性。

> Large Language Models (LLMs) show growing promise in autonomous driving by reasoning over complex traffic scenarios to generate path plans. However, their tendencies toward overconfidence, and hallucinations raise critical safety concerns. We introduce SafePath, a modular framework that augments LLM-based path planning with formal safety guarantees using conformal prediction. SafePath operates in three stages. In the first stage, we use an LLM that generates a set of diverse candidate paths, exploring possible trajectories based on agent behaviors and environmental cues. In the second stage, SafePath filters out high-risk trajectories while guaranteeing that at least one safe option is included with a user-defined probability, through a multiple-choice question-answering formulation that integrates conformal prediction. In the final stage, our approach selects the path with the lowest expected collision risk when uncertainty is low or delegates control to a human when uncertainty is high. We theoretically prove that SafePath guarantees a safe trajectory with a user-defined probability, and we show how its human delegation rate can be tuned to balance autonomy and safety. Extensive experiments on nuScenes and Highway-env show that SafePath reduces planning uncertainty by 77\% and collision rates by up to 70\%, demonstrating effectiveness in making LLM-driven path planning more safer.

[Arxiv](https://arxiv.org/abs/2505.09427)