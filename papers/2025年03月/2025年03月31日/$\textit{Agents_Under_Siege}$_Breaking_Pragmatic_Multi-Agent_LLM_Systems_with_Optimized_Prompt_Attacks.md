# $	extit{Agents Under Siege}$: 围攻下的智能体：优化提示攻击破解实用多智能体LLM系统

发布时间：2025年03月31日

`LLM应用` `多智能体系统` `模型安全`

> $\textit{Agents Under Siege}$: Breaking Pragmatic Multi-Agent LLM Systems with Optimized Prompt Attacks

# 摘要

> 目前关于大型语言模型（LLM）安全性的探讨多集中于单智能体环境，但多智能体LLM系统带来了全新的对抗风险，其行为依赖于智能体间的通信与去中心化推理。本研究聚焦于受限的实际系统，如受限的token带宽、消息传递时延及防御机制。我们创新性地提出了一种【数学公式】，该方法通过优化时延和带宽受限网络拓扑中的提示分布，成功绕过了系统内部的分布式安全机制。将攻击路径建模为【数学公式】问题，并结合创新的【数学公式】，我们利用图优化技术实现了攻击成功率的最大化，同时将检测风险降至最低。在【Llama】、【Mistral】、【Gemma】、【DeepSeek】等模型及其变体，以及【JailBreakBench】和【AdversarialBench】等数据集上的评估显示，我们的方法在攻击效果上比传统手段高出多达7倍，揭示了多智能体系统中的关键漏洞。此外，我们发现现有防御措施，包括【Llama-Guard】和【PromptGuard】的不同变体，均无法有效抵御我们的攻击，凸显了开发专门针对多智能体系统的安全机制的紧迫性。

> Most discussions about Large Language Model (LLM) safety have focused on single-agent settings but multi-agent LLM systems now create novel adversarial risks because their behavior depends on communication between agents and decentralized reasoning. In this work, we innovatively focus on attacking pragmatic systems that have constrains such as limited token bandwidth, latency between message delivery, and defense mechanisms. We design a $\textit{permutation-invariant adversarial attack}$ that optimizes prompt distribution across latency and bandwidth-constraint network topologies to bypass distributed safety mechanisms within the system. Formulating the attack path as a problem of $\textit{maximum-flow minimum-cost}$, coupled with the novel $\textit{Permutation-Invariant Evasion Loss (PIEL)}$, we leverage graph-based optimization to maximize attack success rate while minimizing detection risk. Evaluating across models including $\texttt{Llama}$, $\texttt{Mistral}$, $\texttt{Gemma}$, $\texttt{DeepSeek}$ and other variants on various datasets like $\texttt{JailBreakBench}$ and $\texttt{AdversarialBench}$, our method outperforms conventional attacks by up to $7\times$, exposing critical vulnerabilities in multi-agent systems. Moreover, we demonstrate that existing defenses, including variants of $\texttt{Llama-Guard}$ and $\texttt{PromptGuard}$, fail to prohibit our attack, emphasizing the urgent need for multi-agent specific safety mechanisms.

[Arxiv](https://arxiv.org/abs/2504.00218)