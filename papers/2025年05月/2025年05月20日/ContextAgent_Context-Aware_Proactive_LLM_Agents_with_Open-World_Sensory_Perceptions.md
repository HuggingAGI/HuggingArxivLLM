# # ContextAgent: 具备开放世界感知能力的上下文感知主动型 LLM 代理
ContextAgent 是一种全新的主动型 LLM 代理，它不仅能够感知上下文，还具备开放世界感知能力，能够更好地适应复杂多变的真实环境。

发布时间：2025年05月20日

`Agent` `智能体` `智能服务`

> ContextAgent: Context-Aware Proactive LLM Agents with Open-World Sensory Perceptions

# 摘要

> 大型语言模型（LLMs）的最新进展引领智能体从被动响应迈向主动服务。尽管主动智能体展现出巨大潜力，现有方案要么受限于封闭环境（如桌面UI）的直接LLM推理，要么依赖基于规则的主动提醒，导致用户意图理解不足且主动服务功能有限。本文推出ContextAgent——首个结合多模态感知的上下文感知主动智能体，旨在提升LLM智能体的主动服务能力。通过整合可穿戴设备（如视频和音频）的多维度感官数据，ContextAgent深入理解用户意图。随后，结合历史数据中的角色上下文，ContextAgent精准预测主动服务需求。当主动协助必要时，ContextAgent自动调用所需工具，为用户提供无缝、无干扰的智能支持。为评估这一创新任务，我们构建了ContextAgentBench——首个专注于上下文感知主动LLM智能体的评估基准，涵盖九种日常场景和二十种工具的1,000个样本。实验结果表明，ContextAgent在主动预测和工具调用方面分别较基线提升了8.5%和6.0%的准确率。我们期待这项研究能够启发更多先进、以人为本的主动式AI助手的开发。

> Recent advances in Large Language Models (LLMs) have propelled intelligent agents from reactive responses to proactive support. While promising, existing proactive agents either rely exclusively on observations from enclosed environments (e.g., desktop UIs) with direct LLM inference or employ rule-based proactive notifications, leading to suboptimal user intent understanding and limited functionality for proactive service. In this paper, we introduce ContextAgent, the first context-aware proactive agent that incorporates extensive sensory contexts to enhance the proactive capabilities of LLM agents. ContextAgent first extracts multi-dimensional contexts from massive sensory perceptions on wearables (e.g., video and audio) to understand user intentions. ContextAgent then leverages the sensory contexts and the persona contexts from historical data to predict the necessity for proactive services. When proactive assistance is needed, ContextAgent further automatically calls the necessary tools to assist users unobtrusively. To evaluate this new task, we curate ContextAgentBench, the first benchmark for evaluating context-aware proactive LLM agents, covering 1,000 samples across nine daily scenarios and twenty tools. Experiments on ContextAgentBench show that ContextAgent outperforms baselines by achieving up to 8.5% and 6.0% higher accuracy in proactive predictions and tool calling, respectively. We hope our research can inspire the development of more advanced, human-centric, proactive AI assistants.

[Arxiv](https://arxiv.org/abs/2505.14668)