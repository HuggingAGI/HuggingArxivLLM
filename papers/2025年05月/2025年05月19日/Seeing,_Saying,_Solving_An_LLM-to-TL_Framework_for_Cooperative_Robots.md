# 看、说、解：LLM到TL的协作机器人框架

发布时间：2025年05月19日

`LLM应用` `机器人协作`

> Seeing, Saying, Solving: An LLM-to-TL Framework for Cooperative Robots

# 摘要

> 随着机器人在仓储等领域的广泛应用，异构机器人团队需要无缝协作以解决意外冲突。我们提出了一种去中心化的框架，帮助机器人之间互相请求和提供协助。首先，机器人利用视觉语言模型（VLM）检测冲突，并判断是否需要帮助。若需要帮助，系统会通过大型语言模型（LLM）生成并广播自然语言（NL）请求。潜在的 helper 机器人会评估请求并提供帮助（如果能力范围内），同时说明对当前任务的影响。我们采用基于信号时态逻辑（STL）的 LLM 进行推理，并使用巴科斯-诺尔范式（BNF）语法确保 NL 到 STL 的转换有效，最终将其转化为混合整数线性规划（MILP）问题求解。最后，请求者机器人会根据对整体系统的影响来选择合适的 helper。实验表明，与简单启发式（如选择最近的机器人）相比，考虑多个帮助请求的策略能够更好地降低对系统整体时间的影响。

> Increased robot deployment, such as in warehousing, has revealed a need for seamless collaboration among heterogeneous robot teams to resolve unforeseen conflicts. To address this challenge, we propose a novel, decentralized framework for robots to request and provide help. The framework begins with robots detecting conflicts using a Vision Language Model (VLM), then reasoning over whether help is needed. If so, it crafts and broadcasts a natural language (NL) help request using a Large Language Model (LLM). Potential helper robots reason over the request and offer help (if able), along with information about impact to their current tasks. Helper reasoning is implemented via an LLM grounded in Signal Temporal Logic (STL) using a Backus-Naur Form (BNF) grammar to guarantee syntactically valid NL-to-STL translations, which are then solved as a Mixed Integer Linear Program (MILP). Finally, the requester robot chooses a helper by reasoning over impact on the overall system. We evaluate our system via experiments considering different strategies for choosing a helper, and find that a requester robot can minimize overall time impact on the system by considering multiple help offers versus simple heuristics (e.g., selecting the nearest robot to help).

[Arxiv](https://arxiv.org/abs/2505.13376)