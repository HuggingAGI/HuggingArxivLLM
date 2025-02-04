# 基于多智能体系统的自主遗留Web应用升级

发布时间：2025年01月31日

`Agent

理由：这篇论文描述了一个基于大型语言模型（LLM）的多代理系统，用于自动将遗留Web应用升级至最新版本。该系统通过将任务分解为多个阶段，并使用多个代理来逐一更新相关文件。论文的核心在于多代理系统的设计和实现，以及其在代码生成和升级中的应用。因此，这篇论文应归类为Agent。` `软件开发` `Web应用`

> Autonomous Legacy Web Application Upgrades Using a Multi-Agent System

# 摘要

> 大型语言模型（LLMs）在自主代码生成中的应用正逐渐成为新兴技术的焦点。随着LLM能力的不断提升，它们为代码重构、安全增强和遗留应用升级带来了新的可能性。许多过时的Web应用存在安全和可靠性问题，但由于升级的复杂性和高昂成本，企业往往选择继续使用。为此，我们提出了一种基于LLM的多代理系统，能够自动将遗留Web应用升级至最新版本。该系统将任务分解为多个阶段，逐一更新所有相关文件。为了评估其效果，我们采用了零样本学习（ZSL）和单样本学习（OSL）提示，并在两种情况下应用相同的指令。评估内容包括更新视图文件并统计输出中的错误类型和数量。对于复杂任务，我们计算了成功满足的需求数量。实验将所提出的系统与独立的LLM执行进行了对比，并多次重复以消除随机性影响。结果显示，我们的系统能够在任务和代理之间保持上下文一致性，在某些情况下显著提升了解决方案的质量，优于基础模型。这项研究为未来在遗留代码更新中的模型实现奠定了基础。此外，研究还表明，即使使用简单的提示，LLMs也能以高精度更新小型过时文件。源代码已公开在GitHub上：https://github.com/alasalm1/Multi-agent-pipeline。

> The use of Large Language Models (LLMs) for autonomous code generation is gaining attention in emerging technologies. As LLM capabilities expand, they offer new possibilities such as code refactoring, security enhancements, and legacy application upgrades. Many outdated web applications pose security and reliability challenges, yet companies continue using them due to the complexity and cost of upgrades. To address this, we propose an LLM-based multi-agent system that autonomously upgrades legacy web applications to the latest versions. The system distributes tasks across multiple phases, updating all relevant files. To evaluate its effectiveness, we employed Zero-Shot Learning (ZSL) and One-Shot Learning (OSL) prompts, applying identical instructions in both cases. The evaluation involved updating view files and measuring the number and types of errors in the output. For complex tasks, we counted the successfully met requirements. The experiments compared the proposed system with standalone LLM execution, repeated multiple times to account for stochastic behavior. Results indicate that our system maintains context across tasks and agents, improving solution quality over the base model in some cases. This study provides a foundation for future model implementations in legacy code updates. Additionally, findings highlight LLMs' ability to update small outdated files with high precision, even with basic prompts. The source code is publicly available on GitHub: https://github.com/alasalm1/Multi-agent-pipeline.

[Arxiv](https://arxiv.org/abs/2501.19204)