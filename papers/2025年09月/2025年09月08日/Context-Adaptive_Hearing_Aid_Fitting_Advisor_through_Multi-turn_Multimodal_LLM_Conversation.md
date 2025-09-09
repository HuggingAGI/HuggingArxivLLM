# 基于多轮多模态LLM对话的上下文自适应助听器验配顾问

发布时间：2025年09月08日

`Agent` `医疗健康`

> Context-Adaptive Hearing Aid Fitting Advisor through Multi-turn Multimodal LLM Conversation

# 摘要

> 传统助听器往往依赖静态参数配置，难以适应动态变化的声学环境。为此，我们提出了CAFA——上下文自适应适配顾问，它通过多智能体大型语言模型（LLM）工作流，为用户提供个性化的实时助听器调整方案。CAFA在多轮对话系统中整合了实时环境音频、听力图和用户反馈。系统采用基于YAMNet嵌入的轻量级神经网络，将环境声音分为对话、噪音或安静三类，准确率达91.2%。该系统的模块化LLM工作流包含上下文获取、子问题分类、策略生成和伦理规范四个环节，并由LLM法官进行监督，能将上下文信息和用户反馈转化为精准且安全的调谐指令。评估结果表明，实时声音分类提升了对话交互效率。CAFA展示了智能体多模态人工智能如何推动智能、以用户为中心的辅助技术发展。

> Traditional hearing aids often rely on static fittings that fail to adapt to their dynamic acoustic environments. We propose CAFA, a Context-Adaptive Fitting Advisor that provides personalized, real-time hearing aid adjustments through a multi-agent Large Language Model (LLM) workflow. CAFA combines live ambient audio, audiograms, and user feedback in a multi-turn conversational system. Ambient sound is classified into conversation, noise, or quiet with 91.2\% accuracy using a lightweight neural network based on YAMNet embeddings. This system utilizes a modular LLM workflow, comprising context acquisition, subproblem classification, strategy provision, and ethical regulation, and is overseen by an LLM Judge. The workflow translates context and feedback into precise, safe tuning commands. Evaluation confirms that real-time sound classification enhances conversational efficiency. CAFA exemplifies how agentic, multimodal AI can enable intelligent, user-centric assistive technologies.

[Arxiv](https://arxiv.org/abs/2509.06382)