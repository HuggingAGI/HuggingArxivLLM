# # 基于蒙特卡洛树搜索的多智能体故障定位系统

发布时间：2025年07月30日

`LLM应用` `微服务` `系统可靠性工程`

> The Multi-Agent Fault Localization System Based on Monte Carlo Tree Search Approach

# 摘要

> 在现实场景中，微服务的高解耦和灵活性特性给系统可靠性带来了更大挑战。事故频发促使我们对能够快速识别和恢复事故的根本原因分析(RCA)方法产生了迫切需求。大型语言模型(LLM)凭借其强大的泛化能力和专家经验的结合，为快速定位和恢复事故开辟了新路径。目前用于RCA的LLM框架基于ReAct和Chain-of-Thought等思想，但LLM的幻觉现象和异常的传播特性常常导致定位结果偏差。此外，大型复杂系统中产生的海量异常信息对LLM的上下文窗口长度提出了严峻挑战。为解决这些问题，我们提出了KnowledgeMind，一个基于蒙特卡洛树搜索和知识库奖励机制的创新LLM多智能体系统，专为标准化的按服务推理设计。与现有最先进的(SOTA)用于RCA的LLM方法相比，我们的按服务探索方法显著降低了对最大上下文窗口长度的需求，仅需其十分之一。此外，通过引入基于规则的实时奖励机制，我们的方法有效缓解了推理过程中的幻觉问题。与现有用于RCA的SOTA LLM框架相比，我们的方法在根本原因定位准确性方面实现了49.29%到128.35%的显著提升。

> In real-world scenarios, due to the highly decoupled and flexible nature of microservices, it poses greater challenges to system reliability. The more frequent occurrence of incidents has created a demand for Root Cause Analysis(RCA) methods that enable rapid identification and recovery of incidents. Large language model (LLM) provides a new path for quickly locating and recovering from incidents by leveraging their powerful generalization ability combined with expert experience. Current LLM for RCA frameworks are based on ideas like ReAct and Chain-of-Thought, but the hallucination of LLM and the propagation nature of anomalies often lead to incorrect localization results. Moreover, the massive amount of anomalous information generated in large, complex systems presents a huge challenge for the context window length of LLMs. To address these challenges, we propose KnowledgeMind, an innovative LLM multi-agent system based on Monte Carlo Tree Search and a knowledge base reward mechanism for standardized service-by-service reasoning. Compared to State-Of-The-Art(SOTA) LLM for RCA methods, our service-by-service exploration approach significantly reduces the burden on the maximum context window length, requiring only one-tenth of its size. Additionally, by incorporating a rule-based real-time reward mechanism, our method effectively mitigates hallucinations during the inference process. Compared to the SOTA LLM for RCA framework, our method achieves a 49.29% to 128.35% improvement in root cause localization accuracy.

[Arxiv](https://arxiv.org/abs/2507.22800)