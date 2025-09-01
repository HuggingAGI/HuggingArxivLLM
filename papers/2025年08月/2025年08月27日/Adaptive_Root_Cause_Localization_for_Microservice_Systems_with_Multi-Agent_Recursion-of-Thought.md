# 微服务系统的自适应根因定位：多智能体递归思维方法

发布时间：2025年08月27日

`Agent` `工业与制造`

> Adaptive Root Cause Localization for Microservice Systems with Multi-Agent Recursion-of-Thought

# 摘要

> 如今，微服务系统愈发普及且复杂——往往包含数百甚至数千个细粒度、相互依赖的子系统，故障发生也因此更加频繁。确保系统可靠运行，精准定位根因至关重要。尽管追踪数据和指标已被证实是该任务的有效数据源，但现有方法存在两大局限：一是过度依赖预定义模式，难以适应动态变化的运行场景；二是推理过程缺乏可解释性，让站点可靠性工程师（SRE）倍感困惑。为此，本文调研了不同组织的多位专业SRE，深入探究了他们定位故障根因的方法，开展了全面研究。调研发现，人类根因分析呈现出三个关键特征：递归性、多维度扩展与跨模态推理。受此启发，我们提出了RCLAgent——一种适用于微服务系统的自适应根因定位方法，其核心是多智能体“思维递归”框架。该方法创新性地采用“思维递归”策略引导大型语言模型（LLM）的推理过程，通过高效整合多智能体数据与工具辅助分析，实现根因的精准定位。在多个公开数据集上的实验验证显示，RCLAgent仅需单次请求就能完成根因定位，性能超越了依赖多次请求聚合的现有最优方法。这些结果充分证明，RCLAgent能有效提升复杂微服务环境中根因定位的效率与精度。

> As contemporary microservice systems become increasingly popular and complex-often comprising hundreds or even thousands of fine-grained, interdependent subsystems-they are facing more frequent failures. Ensuring system reliability thus demands accurate root cause localization. While traces and metrics have proven to be effective data sources for this task, existing methods either heavily rely on pre-defined schemas, which struggle to adapt to evolving operational contexts, or lack interpretability in their reasoning process, thereby leaving Site Reliability Engineers (SREs) confused. In this paper, we conduct a comprehensive study on how SREs localize the root cause of failures, drawing insights from multiple professional SREs across different organizations. Our investigation reveals that human root cause analysis exhibits three key characteristics: recursiveness, multi-dimensional expansion, and cross-modal reasoning. Motivated by these findings, we introduce RCLAgent, an adaptive root cause localization method for microservice systems that leverages a multi-agent recursion-of-thought framework. RCLAgent employs a novel recursion-of-thought strategy to guide the LLM's reasoning process, effectively integrating data from multiple agents and tool-assisted analysis to accurately pinpoint the root cause. Experimental evaluations on various public datasets demonstrate that RCLAgent achieves superior performance by localizing the root cause using only a single request-outperforming state-of-the-art methods that depend on aggregating multiple requests. These results underscore the effectiveness of RCLAgent in enhancing the efficiency and precision of root cause localization in complex microservice environments.

[Arxiv](https://arxiv.org/abs/2508.20370)