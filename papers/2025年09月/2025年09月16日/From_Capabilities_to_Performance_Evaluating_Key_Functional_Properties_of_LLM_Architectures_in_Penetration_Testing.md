# 从能力到性能：探究大型语言模型（LLM）架构在渗透测试中的关键功能特性

发布时间：2025年09月16日

`Agent` `基础理论`

> From Capabilities to Performance: Evaluating Key Functional Properties of LLM Architectures in Penetration Testing

# 摘要

> 大型语言模型（LLMs）在渗透测试的自动化与增强中应用日益广泛，但其在不同攻击阶段的有效性和可靠性仍有待明确。我们针对多种基于LLM的智能体（从单智能体到模块化设计），在真实渗透测试场景中开展了全面评估，重点衡量其实证性能及反复出现的失败模式。我们还通过针对性增强手段，分离出五种核心功能能力的影响：全局上下文记忆（GCM）、智能体间消息传递（IAM）、上下文条件调用（CCI）、自适应规划（AP）及实时监控（RTM）。这些增强措施分别实现：（i）上下文连贯性与记忆保留，（ii）组件间协调与状态管理，（iii）工具使用准确性与选择性执行，（iv）多步骤战略规划、错误检测及恢复，以及（v）实时动态响应能力。研究结果显示，尽管部分架构本身已具备上述部分特性，但针对性增强能显著提升模块化智能体的性能，尤其在复杂、多步骤及实时渗透测试任务中效果突出。

> Large language models (LLMs) are increasingly used to automate or augment penetration testing, but their effectiveness and reliability across attack phases remain unclear. We present a comprehensive evaluation of multiple LLM-based agents, from single-agent to modular designs, across realistic penetration testing scenarios, measuring empirical performance and recurring failure patterns. We also isolate the impact of five core functional capabilities via targeted augmentations: Global Context Memory (GCM), Inter-Agent Messaging (IAM), Context-Conditioned Invocation (CCI), Adaptive Planning (AP), and Real-Time Monitoring (RTM). These interventions support, respectively: (i) context coherence and retention, (ii) inter-component coordination and state management, (iii) tool use accuracy and selective execution, (iv) multi-step strategic planning, error detection, and recovery, and (v) real-time dynamic responsiveness. Our results show that while some architectures natively exhibit subsets of these properties, targeted augmentations substantially improve modular agent performance, especially in complex, multi-step, and real-time penetration testing tasks.

[Arxiv](https://arxiv.org/abs/2509.14289)