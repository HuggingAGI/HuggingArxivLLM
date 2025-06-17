# DRIFT: 动态规则基防御与注入隔离，守护LLM代理安全

发布时间：2025年06月13日

`Agent` `人工智能`

> DRIFT: Dynamic Rule-Based Defense with Injection Isolation for Securing LLM Agents

# 摘要

> 大型语言模型（LLMs）凭借其卓越的推理与规划能力，正逐步成为智能体系统的核心驱动力。通过与外部环境交互并运用预定义工具，这些智能体能够高效执行复杂任务。然而，这种交互模式也带来了提示注入攻击的风险，恶意输入可能误导智能体行为，引发经济、隐私或系统安全问题。近期，基于静态策略的系统级防御初见成效，但仍面临两大挑战：安全规则的动态更新与内存流隔离。为解决这些问题，我们提出DRIFT——一种面向可信智能体系统的动态规则隔离框架，该框架从控制与数据层面实施双重约束。具体而言，安全规划器根据用户查询构建函数节点的最小功能轨迹和参数清单；动态验证器实时监控执行偏差，确保变更符合权限与意图；注入隔离器则从内存流中屏蔽潜在冲突指令，降低长期风险。我们在AgentDojo基准上的实证表明，DRIFT在保持跨模型高实用性的同时，展现出强大的安全性能，充分体现了其鲁棒性与适应性。


> Large Language Models (LLMs) are increasingly central to agentic systems due to their strong reasoning and planning capabilities. By interacting with external environments through predefined tools, these agents can carry out complex user tasks. Nonetheless, this interaction also introduces the risk of prompt injection attacks, where malicious inputs from external sources can mislead the agent's behavior, potentially resulting in economic loss, privacy leakage, or system compromise. System-level defenses have recently shown promise by enforcing static or predefined policies, but they still face two key challenges: the ability to dynamically update security rules and the need for memory stream isolation. To address these challenges, we propose DRIFT, a Dynamic Rule-based Isolation Framework for Trustworthy agentic systems, which enforces both control- and data-level constraints. A Secure Planner first constructs a minimal function trajectory and a JSON-schema-style parameter checklist for each function node based on the user query. A Dynamic Validator then monitors deviations from the original plan, assessing whether changes comply with privilege limitations and the user's intent. Finally, an Injection Isolator detects and masks any instructions that may conflict with the user query from the memory stream to mitigate long-term risks. We empirically validate the effectiveness of DRIFT on the AgentDojo benchmark, demonstrating its strong security performance while maintaining high utility across diverse models -- showcasing both its robustness and adaptability.

[Arxiv](https://arxiv.org/abs/2506.12104)