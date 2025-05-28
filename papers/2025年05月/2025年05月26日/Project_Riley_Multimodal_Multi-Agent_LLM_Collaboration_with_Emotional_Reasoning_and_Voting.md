# # Riley 项目：多模态多智能体大语言模型协作能力，融合情感推理与投票机制

发布时间：2025年05月26日

`LLM应用

理由：这篇论文主要介绍了一个结合了文本和视觉大型语言模型（LLMs）的多模态、多模型对话AI架构，重点在于其在情感化推理和多轮对话中的应用，因此应归类为LLM应用。` `应急管理` `智能客服`

> Project Riley: Multimodal Multi-Agent LLM Collaboration with Emotional Reasoning and Voting

# 摘要

> 本文介绍了Project Riley——一个模拟情绪化推理的多模态、多模型对话AI架构。受皮克斯动画《头脑特工队》启发，系统由五个情绪代理（快乐、悲伤、恐惧、愤怒和厌恶）组成，它们通过多轮对话协作生成、批评并优化回复。最终推理机制将这些情绪观点整合为一个连贯输出，既可突出主导情绪，也能融合多元视角。该架构结合了文本和视觉大型语言模型（LLMs），并辅以先进推理和自我完善机制。原型在离线环境优化部署，兼顾情感表达与计算效率。基于此，专为紧急场景设计的Armando系统应运而生，通过检索增强生成（RAG）和累积上下文跟踪，提供情感适配且事实准确的信息。用户测试显示，Project Riley在结构化场景中表现出色，尤其在情感对齐和沟通清晰度方面具有显著优势。

> This paper presents Project Riley, a novel multimodal and multi-model conversational AI architecture oriented towards the simulation of reasoning influenced by emotional states. Drawing inspiration from Pixar's Inside Out, the system comprises five distinct emotional agents - Joy, Sadness, Fear, Anger, and Disgust - that engage in structured multi-round dialogues to generate, criticise, and iteratively refine responses. A final reasoning mechanism synthesises the contributions of these agents into a coherent output that either reflects the dominant emotion or integrates multiple perspectives. The architecture incorporates both textual and visual large language models (LLMs), alongside advanced reasoning and self-refinement processes. A functional prototype was deployed locally in an offline environment, optimised for emotional expressiveness and computational efficiency. From this initial prototype, another one emerged, called Armando, which was developed for use in emergency contexts, delivering emotionally calibrated and factually accurate information through the integration of Retrieval-Augmented Generation (RAG) and cumulative context tracking. The Project Riley prototype was evaluated through user testing, in which participants interacted with the chatbot and completed a structured questionnaire assessing three dimensions: Emotional Appropriateness, Clarity and Utility, and Naturalness and Human-likeness. The results indicate strong performance in structured scenarios, particularly with respect to emotional alignment and communicative clarity.

[Arxiv](https://arxiv.org/abs/2505.20521)