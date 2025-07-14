# 强化学习在Agent安全对齐中的应用

发布时间：2025年07月10日

`LLM应用` `人工智能`

> Agent Safety Alignment via Reinforcement Learning

# 摘要

> 自主大型语言模型（LLM）代理的工具使用能力，带来了超越传统对话滥用的新安全风险。这些代理能够执行外部功能，因此既可能受到用户发起的威胁（例如对抗性提示），也可能面临工具发起的威胁（例如被篡改工具生成的恶意输出）。本文首次提出了一种针对工具使用型代理的统一安全对齐框架，使模型能够通过结构化推理和沙盒强化学习来应对这两种威胁渠道。我们引入了三元分类法，将用户提示和工具响应分别归类为良性、恶意和敏感，并定义了一个基于策略的决策模型。我们的框架采用了一个定制设计的沙盒环境，模拟现实世界中的工具执行，并允许进行精细的奖励塑造。通过在公共和自建基准上的广泛评估，包括Agent SafetyBench、InjecAgent和BFCL，我们证明了我们的安全对齐代理在显著提升对安全威胁的抵抗力的同时，仍保持了在良性任务上的强大实用性。我们的结果显示，安全性和有效性可以共同优化，为可信的自主LLM代理部署奠定了基础。

> The emergence of autonomous Large Language Model (LLM) agents capable of tool usage has introduced new safety risks that go beyond traditional conversational misuse. These agents, empowered to execute external functions, are vulnerable to both user-initiated threats (e.g., adversarial prompts) and tool-initiated threats (e.g., malicious outputs from compromised tools). In this paper, we propose the first unified safety-alignment framework for tool-using agents, enabling models to handle both channels of threat via structured reasoning and sandboxed reinforcement learning. We introduce a tri-modal taxonomy, including benign, malicious, and sensitive for both user prompts and tool responses, and define a policy-driven decision model. Our framework employs a custom-designed sandbox environment that simulates real-world tool execution and allows fine-grained reward shaping. Through extensive evaluations on public and self-built benchmarks, including Agent SafetyBench, InjecAgent, and BFCL, we demonstrate that our safety-aligned agents significantly improve resistance to security threats while preserving strong utility on benign tasks. Our results show that safety and effectiveness can be jointly optimized, laying the groundwork for trustworthy deployment of autonomous LLM agents.

[Arxiv](https://arxiv.org/abs/2507.08270)