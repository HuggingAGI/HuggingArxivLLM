# 大型语言模型代理系统中的可解释风险缓解

发布时间：2025年05月15日

`Agent` `自主代理` `博弈论`

> Interpretable Risk Mitigation in LLM Agent Systems

# 摘要

> 大型语言模型（LLMs）驱动的自主代理为责任行动日益重要的领域带来了全新的应用场景。然而，LLMs固有的不可预测性引发了人们对代理可靠性的安全担忧。我们通过一种基于迭代囚徒困境变体的博弈论环境，探索了代理行为。提出了一种独立于游戏和提示的策略修改方法，通过从稀疏自动编码器潜在空间提取的可解释特征引导残差流。借助善意谈判特征进行引导，平均背叛概率降低了28个百分点。我们还确定了几个开源LLM代理的可行引导范围。最后，我们假设结合博弈论评估与表示引导对齐的方法，可以推广到终端用户设备和具身平台上的现实世界应用。

> Autonomous agents powered by large language models (LLMs) enable novel use cases in domains where responsible action is increasingly important. Yet the inherent unpredictability of LLMs raises safety concerns about agent reliability. In this work, we explore agent behaviour in a toy, game-theoretic environment based on a variation of the Iterated Prisoner's Dilemma. We introduce a strategy-modification method-independent of both the game and the prompt-by steering the residual stream with interpretable features extracted from a sparse autoencoder latent space. Steering with the good-faith negotiation feature lowers the average defection probability by 28 percentage points. We also identify feasible steering ranges for several open-source LLM agents. Finally, we hypothesise that game-theoretic evaluation of LLM agents, combined with representation-steering alignment, can generalise to real-world applications on end-user devices and embodied platforms.

[Arxiv](https://arxiv.org/abs/2505.10670)