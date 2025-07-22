# 大语言模型智能体的拜占庭鲁棒去中心化协调

发布时间：2025年07月20日

`Agent

这篇论文主要探讨多大型语言模型（LLM）代理的协作机制，特别是在开放区块链平台上的应用。它关注多代理系统在存在拜占庭恶意代理情况下的鲁棒性和共识机制，提出了一种去中心化的共识方法DecentLLMs。研究重点在于多代理协作和共识算法，属于Agent领域。` `区块链`

> Byzantine-Robust Decentralized Coordination of LLM Agents

# 摘要

> 多大型语言模型 (LLM) 代理的协作是克服单个代理系统局限性（如幻觉和单点故障）的有效方法。随着 LLM 代理在开放区块链平台上的广泛应用，能够容忍恶意（拜占庭）代理的多代理系统变得不可或缺。
    当前的拜占庭鲁棒多代理系统普遍采用基于领导者的协调机制，但这种机制存在两大缺陷。首先，系统易受针对领导者的定向攻击。若连续领导者恶意行事，共识将反复失败，迫使系统启动新的共识轮次，而这在 LLM 调用延迟较高的情况下代价高昂。其次，现有方法一旦领导者提案获得法定票数，就会立即最终确定，导致劣质提案可能胜过更优选择。
    为解决这些问题，我们提出 DecentLLMs，一种适用于多代理 LLM 系统的新型去中心化共识方法。该方法通过工作代理并发生成答案，评估代理独立评分排序，最终选择最优答案。这种去中心化架构即使在存在拜占庭代理的情况下也能实现更快共识，并通过拜占庭鲁棒聚合技术始终选择更高质量答案。
    实验结果表明，DecentLLMs 在容忍拜占庭代理的同时，显著提升了所选答案的质量。
    

> Collaboration among multiple large language model (LLM) agents is a promising approach to overcome inherent limitations of single-agent systems, such as hallucinations and single points of failure. As LLM agents are increasingly deployed on open blockchain platforms, multi-agent systems capable of tolerating malicious (Byzantine) agents have become essential.
  Recent Byzantine-robust multi-agent systems typically rely on leader-driven coordination, which suffers from two major drawbacks. First, they are inherently vulnerable to targeted attacks against the leader. If consecutive leaders behave maliciously, the system repeatedly fails to achieve consensus, forcing new consensus rounds, which is particularly costly given the high latency of LLM invocations. Second, an underperforming proposal from the leader can be accepted as the final answer even when higher-quality alternatives are available, as existing methods finalize the leader's proposal once it receives a quorum of votes.
  To address these issues, we propose DecentLLMs, a novel decentralized consensus approach for multi-agent LLM systems, where worker agents generate answers concurrently and evaluator agents independently score and rank these answers to select the best available one. This decentralized architecture enables faster consensus despite the presence of Byzantine agents and consistently selects higher-quality answers through Byzantine-robust aggregation techniques.
  Experimental results demonstrate that DecentLLMs effectively tolerates Byzantine agents and significantly improves the quality of selected answers.

[Arxiv](https://arxiv.org/abs/2507.14928)