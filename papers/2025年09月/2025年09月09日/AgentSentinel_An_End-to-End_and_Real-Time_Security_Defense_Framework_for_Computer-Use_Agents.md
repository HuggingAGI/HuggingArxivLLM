# AgentSentinel：面向计算机使用智能体的端到端实时安全防御框架

发布时间：2025年09月09日

`Agent` `基础理论`

> AgentSentinel: An End-to-End and Real-Time Security Defense Framework for Computer-Use Agents

# 摘要

> 大型语言模型（LLMs）正越来越多地融入计算机使用代理，这类代理能自主操作用户计算机上的工具以完成复杂任务。然而，由于LLM输出本质上具有不稳定和不可预测性，可能会发出非预期的工具命令或错误输入，进而引发潜在的有害操作。与传统上因不安全用户提示导致的安全风险不同，LLM驱动决策产生的工具执行结果带来了全新且独特的安全挑战——这些漏洞遍布计算机使用代理的各个组件。为缓解这些风险，我们提出了AgentSentinel——一个端到端的实时防御框架，专为抵御用户计算机上的潜在安全威胁而设计。AgentSentinel会拦截代理相关服务中的所有敏感操作，并暂停执行，直至完成全面的安全审计。我们的安全审计机制引入了一种新颖的检查流程，能将当前任务上下文与任务执行期间生成的系统痕迹关联起来。为全面评估AgentSentinel，我们构建了BadComputerUse基准测试，它涵盖六个攻击类别中的60个不同攻击场景。该基准测试在四个最先进的LLM上实现了87%的平均攻击成功率，而评估结果显示，AgentSentinel的平均防御成功率达79.6%，显著优于所有基线防御方法。

> Large Language Models (LLMs) have been increasingly integrated into computer-use agents, which can autonomously operate tools on a user's computer to accomplish complex tasks. However, due to the inherently unstable and unpredictable nature of LLM outputs, they may issue unintended tool commands or incorrect inputs, leading to potentially harmful operations. Unlike traditional security risks stemming from insecure user prompts, tool execution results from LLM-driven decisions introduce new and unique security challenges. These vulnerabilities span across all components of a computer-use agent. To mitigate these risks, we propose AgentSentinel, an end-to-end, real-time defense framework designed to mitigate potential security threats on a user's computer. AgentSentinel intercepts all sensitive operations within agent-related services and halts execution until a comprehensive security audit is completed. Our security auditing mechanism introduces a novel inspection process that correlates the current task context with system traces generated during task execution. To thoroughly evaluate AgentSentinel, we present BadComputerUse, a benchmark consisting of 60 diverse attack scenarios across six attack categories. The benchmark demonstrates a 87% average attack success rate on four state-of-the-art LLMs. Our evaluation shows that AgentSentinel achieves an average defense success rate of 79.6%, significantly outperforming all baseline defenses.

[Arxiv](https://arxiv.org/abs/2509.07764)