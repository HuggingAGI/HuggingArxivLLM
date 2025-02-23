# 结构化交流，分层行动：LLM多智能体系统的协作框架

发布时间：2025年02月16日

`Agent

理由：这篇论文主要探讨了基于LLM的多智能体系统（LLM-MA）的设计与改进，提出了一种名为TalkHier的创新框架，专注于解决智能体协作中的关键问题。论文的重点在于多智能体系统的结构化沟通和协作机制，而非LLM本身的理论或应用。因此，这篇论文应归类为Agent。` `问答系统`

> Talk Structurally, Act Hierarchically: A Collaborative Framework for LLM Multi-Agent Systems

# 摘要

> 基于LLM的多智能体 (LLM-MA) 系统虽展现出巨大潜力，但在智能体协作解决复杂任务时仍面临诸多挑战。本文提出了一种名为	extit{Talk Structurally, Act Hierarchically (TalkHier)}的创新框架，通过引入结构化沟通协议和分层细化系统，有效解决了错误输出、虚假信息和偏见等关键问题。在开放领域问答、领域特定选择性提问和广告文案生成等多种任务中，	extit{TalkHier}超越了包括推理扩展模型 (OpenAI-o1)、开源多智能体模型 (如AgentVerse) 以及基于当前LLM和单智能体基线 (如ReAct、GPT4o) 的多数投票策略在内的多种当前最优模型。这一成果不仅彰显了	extit{TalkHier}为LLM-MA系统树立新标准的潜力，更为构建更高效、更具适应性和协作性的多智能体框架奠定了基础。代码已开源，地址为https://github.com/sony/talkhier。

> Recent advancements in LLM-based multi-agent (LLM-MA) systems have shown promise, yet significant challenges remain in managing communication and refinement when agents collaborate on complex tasks. In this paper, we propose \textit{Talk Structurally, Act Hierarchically (TalkHier)}, a novel framework that introduces a structured communication protocol for context-rich exchanges and a hierarchical refinement system to address issues such as incorrect outputs, falsehoods, and biases. \textit{TalkHier} surpasses various types of SoTA, including inference scaling model (OpenAI-o1), open-source multi-agent models (e.g., AgentVerse), and majority voting strategies on current LLM and single-agent baselines (e.g., ReAct, GPT4o), across diverse tasks, including open-domain question answering, domain-specific selective questioning, and practical advertisement text generation. These results highlight its potential to set a new standard for LLM-MA systems, paving the way for more effective, adaptable, and collaborative multi-agent frameworks. The code is available https://github.com/sony/talkhier.

[Arxiv](https://arxiv.org/abs/2502.11098)