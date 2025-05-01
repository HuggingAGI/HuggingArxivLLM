# 隐秘提示传输：保障大型语言模型服务的安全性

发布时间：2025年04月30日

`LLM应用

理由：这篇论文探讨了在无线网络中高效且安全地传输大语言模型（LLM）提示的方法，结合了压缩、加密和优化策略，以实现更低的延迟和更高的隐蔽性。其重点在于实际应用中的优化和部署，属于LLM应用的范畴。` `无线通信` `人工智能`

> Covert Prompt Transmission for Secure Large Language Model Services

# 摘要

> 本文研究了无线网络中安全高效大语言模型 (LLM) 服务的隐藏提示传输。我们提出了一个在保真度和可检测性约束下的时延最小化问题，通过联合优化发射功率和提示压缩比来确保保密和隐蔽通信。为了解决这个问题，我们首先提出了一个提示压缩与加密（PCAE）框架，该框架通过 surprisal 指导的压缩，随后进行轻量级置换加密。具体而言，PCAE 利用本地部署的小语言模型 (SLM) 来估计 token 级的 surprisal 分数，在保留语义关键 token 的同时丢弃冗余 token。这显著降低了计算开销和传输时长。为了进一步提升隐蔽无线传输效果，我们开发了一种基于分组的近端策略优化方法（GPPO），该方法为每个状态采样多个候选动作，在每个组内选择最优动作，并引入 Kullback-Leibler (KL) 散度惩罚以提升策略稳定性和探索能力。仿真结果表明，PCAE 在保持与基线方法相当的 LLM 响应保真度的同时，将预处理时延降低了五个数量级，从而实现了实时边缘部署。我们进一步在多种 LLM 后端上验证了 PCAE 的有效性，包括 DeepSeek-32B、Qwen-32B 及其更小的变体。此外，与现有强化学习策略相比，GPPO 将隐蔽传输时延降低了高达 38.6%，进一步分析表明，增加发射功率可带来额外的时延收益。

> This paper investigates covert prompt transmission for secure and efficient large language model (LLM) services over wireless networks. We formulate a latency minimization problem under fidelity and detectability constraints to ensure confidential and covert communication by jointly optimizing the transmit power and prompt compression ratio. To solve this problem, we first propose a prompt compression and encryption (PCAE) framework, performing surprisal-guided compression followed by lightweight permutation-based encryption. Specifically, PCAE employs a locally deployed small language model (SLM) to estimate token-level surprisal scores, selectively retaining semantically critical tokens while discarding redundant ones. This significantly reduces computational overhead and transmission duration. To further enhance covert wireless transmission, we then develop a group-based proximal policy optimization (GPPO) method that samples multiple candidate actions for each state, selecting the optimal one within each group and incorporating a Kullback-Leibler (KL) divergence penalty to improve policy stability and exploration. Simulation results show that PCAE achieves comparable LLM response fidelity to baseline methods while reducing preprocessing latency by over five orders of magnitude, enabling real-time edge deployment. We further validate PCAE effectiveness across diverse LLM backbones, including DeepSeek-32B, Qwen-32B, and their smaller variants. Moreover, GPPO reduces covert transmission latency by up to 38.6\% compared to existing reinforcement learning strategies, with further analysis showing that increased transmit power provides additional latency benefits.

[Arxiv](https://arxiv.org/abs/2504.21311)