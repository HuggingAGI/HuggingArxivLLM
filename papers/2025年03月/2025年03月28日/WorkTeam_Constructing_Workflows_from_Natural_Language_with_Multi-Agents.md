# WorkTeam：基于多智能体的自然语言工作流构建方法

发布时间：2025年03月28日

`Agent` `工作流管理`

> WorkTeam: Constructing Workflows from Natural Language with Multi-Agents

# 摘要

> 工作流在提升企业效率方面发挥着重要作用，通过协调多个工具或组件的复杂流程来实现。然而，传统手工构建工作流需要专业知识，这给企业带来了技术门槛。近年来，大型语言模型（LLMs）的进步显著提升了从自然语言指令生成工作流的能力（即NL2Workflow），但现有基于单一LLM代理的方法在复杂任务上表现欠佳，原因在于需要专业知识和任务切换的压力。为了解决这些问题，我们提出了WorkTeam——一个多智能体的NL2Workflow框架，由监督员、协调员和填充员组成，每个角色各司其职，协同提升转换效果。目前尚无公开的NL2Workflow基准数据集，为此我们推出了HW-NL2Workflow数据集，包含3,695个真实业务场景样本，用于训练和评估。实验结果表明，我们的方法显著提升了工作流构建的成功率，为企业的NL2Workflow服务提供了创新且有效的解决方案。

> Workflows play a crucial role in enhancing enterprise efficiency by orchestrating complex processes with multiple tools or components. However, hand-crafted workflow construction requires expert knowledge, presenting significant technical barriers. Recent advancements in Large Language Models (LLMs) have improved the generation of workflows from natural language instructions (aka NL2Workflow), yet existing single LLM agent-based methods face performance degradation on complex tasks due to the need for specialized knowledge and the strain of task-switching. To tackle these challenges, we propose WorkTeam, a multi-agent NL2Workflow framework comprising a supervisor, orchestrator, and filler agent, each with distinct roles that collaboratively enhance the conversion process. As there are currently no publicly available NL2Workflow benchmarks, we also introduce the HW-NL2Workflow dataset, which includes 3,695 real-world business samples for training and evaluation. Experimental results show that our approach significantly increases the success rate of workflow construction, providing a novel and effective solution for enterprise NL2Workflow services.

[Arxiv](https://arxiv.org/abs/2503.22473)