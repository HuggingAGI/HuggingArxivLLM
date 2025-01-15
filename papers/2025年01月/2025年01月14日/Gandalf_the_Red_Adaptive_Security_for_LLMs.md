# 甘道夫之红：LLM 的自适应安全

发布时间：2025年01月14日

`LLM应用

理由：这篇论文主要讨论了在LLM应用中如何防御提示攻击，并提出了一个动态安全效用威胁模型（D-SEC）以及一个用于生成真实、自适应攻击数据集的平台（Gandalf）。论文的核心关注点是如何在实际应用中提高LLM的安全性，同时不影响合法用户的可用性。因此，这篇论文属于LLM应用类别。` `网络安全` `人工智能`

> Gandalf the Red: Adaptive Security for LLMs

# 摘要

> # 摘要
当前对LLM应用中防御提示攻击的评估常忽视两个关键点：对抗行为的动态性和防御措施对合法用户可用性的影响。我们提出了D-SEC（动态安全效用威胁模型），明确区分攻击者与合法用户，建模多步交互，并以可优化形式表达安全与效用的关系。为弥补现有评估的不足，我们推出了Gandalf——一个众包、游戏化的红队平台，用于生成真实、自适应的攻击数据集。通过Gandalf，我们收集并发布了包含279k条提示攻击的数据集。结合良性用户数据，分析揭示了安全与效用的相互作用，表明LLM内置的防御（如系统提示）即使不阻止请求也可能影响可用性。我们证明，限制应用领域、深度防御和自适应防御是构建安全且实用的LLM应用的有效策略。代码详见\href{https://github.com/lakeraai/dsec-gandalf}{	exttt{https://github.com/lakeraai/dsec-gandalf}}。

> Current evaluations of defenses against prompt attacks in large language model (LLM) applications often overlook two critical factors: the dynamic nature of adversarial behavior and the usability penalties imposed on legitimate users by restrictive defenses. We propose D-SEC (Dynamic Security Utility Threat Model), which explicitly separates attackers from legitimate users, models multi-step interactions, and rigorously expresses the security-utility in an optimizable form. We further address the shortcomings in existing evaluations by introducing Gandalf, a crowd-sourced, gamified red-teaming platform designed to generate realistic, adaptive attack datasets. Using Gandalf, we collect and release a dataset of 279k prompt attacks. Complemented by benign user data, our analysis reveals the interplay between security and utility, showing that defenses integrated in the LLM (e.g., system prompts) can degrade usability even without blocking requests. We demonstrate that restricted application domains, defense-in-depth, and adaptive defenses are effective strategies for building secure and useful LLM applications. Code is available at \href{https://github.com/lakeraai/dsec-gandalf}{\texttt{https://github.com/lakeraai/dsec-gandalf}}.

[Arxiv](https://arxiv.org/abs/2501.07927)