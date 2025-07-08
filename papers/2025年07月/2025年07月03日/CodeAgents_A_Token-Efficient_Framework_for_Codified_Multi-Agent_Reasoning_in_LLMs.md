# CodeAgents：面向LLMs的高效多智能体推理框架。

发布时间：2025年07月03日

`Agent` `多代理系统` `软件工程`

> CodeAgents: A Token-Efficient Framework for Codified Multi-Agent Reasoning in LLMs

# 摘要

> 提升LLM驱动代理的规划能力，离不开有效的提示设计。然而，现有的结构化提示策略存在诸多局限：它们往往局限于单代理、仅规划的场景，且评估性能时仅关注任务准确性，却忽视了多代理环境中令牌效率、模块化和可扩展性等关键因素。为突破这些限制，我们推出了CodeAgents——一个创新的提示框架，它将多代理推理过程转化为代码，实现了多代理系统中结构化、令牌高效的规划。在CodeAgents中，任务、计划、反馈、系统角色和外部工具调用等所有代理交互组件，都被转化为包含控制结构（如循环、条件）、布尔逻辑和类型变量的模块化伪代码。这种设计使松散的代理计划转变为连贯、可解释和可验证的多代理推理程序。我们采用多种代表性的LLMs，在GAIA、HotpotQA和VirtualHome三个基准测试中对CodeAgents进行了全面评估。实验结果显示，与自然语言提示基线相比，CodeAgents的规划性能有了显著提升，绝对增益达到3-36个百分点。在VirtualHome上，我们的方法更是达到了56%的成功率，创下了新的最先进水平。此外，CodeAgents将输入和输出令牌的使用量分别减少了55-87%和41-70%，这凸显了在开发可扩展的多代理LLM系统时，令牌感知评估指标的重要性。CodeAgents的代码和资源现已开放，获取链接为：https://anonymous.4open.science/r/CodifyingAgent-5A86

> Effective prompt design is essential for improving the planning capabilities of large language model (LLM)-driven agents. However, existing structured prompting strategies are typically limited to single-agent, plan-only settings, and often evaluate performance solely based on task accuracy - overlooking critical factors such as token efficiency, modularity, and scalability in multi-agent environments. To address these limitations, we introduce CodeAgents, a prompting framework that codifies multi-agent reasoning and enables structured, token-efficient planning in multi-agent systems. In CodeAgents, all components of agent interaction - Task, Plan, Feedback, system roles, and external tool invocations - are codified into modular pseudocode enriched with control structures (e.g., loops, conditionals), boolean logic, and typed variables. This design transforms loosely connected agent plans into cohesive, interpretable, and verifiable multi-agent reasoning programs. We evaluate the proposed framework across three diverse benchmarks - GAIA, HotpotQA, and VirtualHome - using a range of representative LLMs. Results show consistent improvements in planning performance, with absolute gains of 3-36 percentage points over natural language prompting baselines. On VirtualHome, our method achieves a new state-of-the-art success rate of 56%. In addition, our approach reduces input and output token usage by 55-87% and 41-70%, respectively, underscoring the importance of token-aware evaluation metrics in the development of scalable multi-agent LLM systems. The code and resources are available at: https://anonymous.4open.science/r/CodifyingAgent-5A86

[Arxiv](https://arxiv.org/abs/2507.03254)