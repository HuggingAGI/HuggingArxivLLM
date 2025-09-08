# 警惕差距：基于行动图评估大型语言模型（LLMs）的模型级与智能体级漏洞

发布时间：2025年09月05日

`Agent` `基础理论`

> Mind the Gap: Evaluating Model- and Agentic-Level Vulnerabilities in LLMs with Action Graphs

# 摘要

> 随着大型语言模型逐步演变为智能体系统，现有安全评估框架在评估部署特定风险时暴露出重大缺陷。为此，我们提出AgentSeer——一个基于可观测性的评估框架，它能将智能体执行过程分解为细粒度的动作与组件图谱，从而实现系统化的智能体情境评估。通过在GPT-OSS-20B和Gemini-2.0-flash模型上采用HarmBench单轮攻击与迭代优化攻击进行跨模型验证，我们发现模型级与智能体级漏洞特征存在本质区别。模型级评估显示：GPT-OSS-20B的攻击成功率（ASR）为39.47%，Gemini-2.0-flash则为50.00%；两者均易受社会工程学攻击，但对基于逻辑的攻击具有抗性。然而，智能体级评估却揭示了传统评估难以发现的智能体特有风险。我们发现了“仅智能体”漏洞——这类漏洞仅在智能体环境中显现，其中工具调用功能使两种模型的攻击成功率均提升了24-60%。跨模型分析还发现了通用智能体规律：智能体转移操作为最高风险工具，漏洞机制源于语义而非语法，攻击效果依赖上下文；同时，不同模型在绝对攻击成功率和最优注入策略上呈现出特定的安全特征。从模型级直接迁移至智能体环境的攻击效果显著下降（GPT-OSS-20B人工注入攻击成功率57%，Gemini-2.0-flash为28%），而上下文感知迭代攻击却能成功突破模型级评估中未被攻克的目标，这进一步证实了现有评估体系的系统性缺陷。这些发现凸显了构建智能体情境评估范式的迫切性，而AgentSeer恰好为此提供了标准化方法与实证支持。

> As large language models transition to agentic systems, current safety evaluation frameworks face critical gaps in assessing deployment-specific risks. We introduce AgentSeer, an observability-based evaluation framework that decomposes agentic executions into granular action and component graphs, enabling systematic agentic-situational assessment. Through cross-model validation on GPT-OSS-20B and Gemini-2.0-flash using HarmBench single turn and iterative refinement attacks, we demonstrate fundamental differences between model-level and agentic-level vulnerability profiles. Model-level evaluation reveals baseline differences: GPT-OSS-20B (39.47% ASR) versus Gemini-2.0-flash (50.00% ASR), with both models showing susceptibility to social engineering while maintaining logic-based attack resistance. However, agentic-level assessment exposes agent-specific risks invisible to traditional evaluation. We discover "agentic-only" vulnerabilities that emerge exclusively in agentic contexts, with tool-calling showing 24-60% higher ASR across both models. Cross-model analysis reveals universal agentic patterns, agent transfer operations as highest-risk tools, semantic rather than syntactic vulnerability mechanisms, and context-dependent attack effectiveness, alongside model-specific security profiles in absolute ASR levels and optimal injection strategies. Direct attack transfer from model-level to agentic contexts shows degraded performance (GPT-OSS-20B: 57% human injection ASR; Gemini-2.0-flash: 28%), while context-aware iterative attacks successfully compromise objectives that failed at model-level, confirming systematic evaluation gaps. These findings establish the urgent need for agentic-situation evaluation paradigms, with AgentSeer providing the standardized methodology and empirical validation.

[Arxiv](https://arxiv.org/abs/2509.04802)