# # Pro2Guard：通过概率模型检查实现LLM智能体的主动运行时安全防护

发布时间：2025年08月01日

`LLM应用

论文摘要：大型语言模型（LLM）代理在机器人、虚拟助手和网络自动化等领域展现出强大的自主能力。然而，其随机行为带来了难以预见的重大安全风险。现有的基于规则的 enforcement 系统（如 AgentSpec）专注于制定响应式安全规则，这些规则通常仅在不安全行为即将发生或已经发生时做出反应。这些系统缺乏前瞻性，难以处理长期依赖关系和分布偏移。

为了解决这些问题，我们提出了 Pro2Guard，这是一个基于概率可达性分析的主动运行时 enforcement 框架。Pro2Guard 将代理行为抽象为符号状态，并从执行轨迹中学习离散时间马尔可夫链（DTMC）。在运行时，它通过估计到达不安全状态的概率来预见未来风险，并在预测风险超过用户定义的阈值时触发干预，从而在违规发生前采取行动。通过引入语义有效性检查并利用 PAC 界限，Pro2Guard 在近似底层真实模型的同时确保了统计可靠性。

我们对 Pro2Guard 在两个关键安全领域进行了全面评估：具身家居代理和自动驾驶。在具身代理任务中，Pro2Guard 使用低阈值在早期对高达 93.6% 的不安全任务实施安全约束，而可配置模式（如 reflect）允许在安全与任务成功之间取得平衡，保持高达 80.4% 的任务完成率。在自动驾驶场景中，Pro2Guard 实现了对交通法规违规和碰撞的 100% 预测，提前 38.66 秒预见风险。` `智能家居` `自动驾驶`

> Pro2Guard: Proactive Runtime Enforcement of LLM Agent Safety via Probabilistic Model Checking

# 摘要

> 大型语言模型（LLM）代理在机器人、虚拟助手和网络自动化等领域展现出强大的自主能力。然而，其随机行为带来了难以预见的重大安全风险。现有的基于规则的 enforcement 系统（如 AgentSpec）专注于制定响应式安全规则，这些规则通常仅在不安全行为即将发生或已经发生时做出反应。这些系统缺乏前瞻性，难以处理长期依赖关系和分布偏移。

为了解决这些问题，我们提出了 Pro2Guard，这是一个基于概率可达性分析的主动运行时 enforcement 框架。Pro2Guard 将代理行为抽象为符号状态，并从执行轨迹中学习离散时间马尔可夫链（DTMC）。在运行时，它通过估计到达不安全状态的概率来预见未来风险，并在预测风险超过用户定义的阈值时触发干预，从而在违规发生前采取行动。通过引入语义有效性检查并利用 PAC 界限，Pro2Guard 在近似底层真实模型的同时确保了统计可靠性。

我们对 Pro2Guard 在两个关键安全领域进行了全面评估：具身家居代理和自动驾驶。在具身代理任务中，Pro2Guard 使用低阈值在早期对高达 93.6% 的不安全任务实施安全约束，而可配置模式（如 reflect）允许在安全与任务成功之间取得平衡，保持高达 80.4% 的任务完成率。在自动驾驶场景中，Pro2Guard 实现了对交通法规违规和碰撞的 100% 预测，提前 38.66 秒预见风险。

> Large Language Model (LLM) agents exhibit powerful autonomous capabilities across domains such as robotics, virtual assistants, and web automation. However, their stochastic behavior introduces significant safety risks that are difficult to anticipate. Existing rule-based enforcement systems, such as AgentSpec, focus on developing reactive safety rules, which typically respond only when unsafe behavior is imminent or has already occurred. These systems lack foresight and struggle with long-horizon dependencies and distribution shifts. To address these limitations, we propose Pro2Guard, a proactive runtime enforcement framework grounded in probabilistic reachability analysis. Pro2Guard abstracts agent behaviors into symbolic states and learns a Discrete-Time Markov Chain (DTMC) from execution traces. At runtime, it anticipates future risks by estimating the probability of reaching unsafe states, triggering interventions before violations occur when the predicted risk exceeds a user-defined threshold. By incorporating semantic validity checks and leveraging PAC bounds, Pro2Guard ensures statistical reliability while approximating the underlying ground-truth model. We evaluate Pro2Guard extensively across two safety-critical domains: embodied household agents and autonomous vehicles. In embodied agent tasks, Pro2Guard enforces safety early on up to 93.6% of unsafe tasks using low thresholds, while configurable modes (e.g., reflect) allow balancing safety with task success, maintaining up to 80.4% task completion. In autonomous driving scenarios, Pro2Guard achieves 100% prediction of traffic law violations and collisions, anticipating risks up to 38.66 seconds ahead.

[Arxiv](https://arxiv.org/abs/2508.00500)