# 探索拟人化对话AI 第一部分：实用框架指南

发布时间：2025年02月27日

`LLM应用` `对话系统` `人机交互`

> Towards Anthropomorphic Conversational AI Part I: A Practical Framework

# 摘要

> 大型语言模型（LLMs）凭借其强大的自然语言处理能力，在以会话式AI代理为用户界面的应用中取得了显著成功，这些代理通过多轮对话与用户互动。然而，许多场景要求代理展现出更强的社交和对话智能，并呈现更像人类的反应。这是基础大型语言模型尚未完全解决的一个方面，因此仅凭基础模型的一次调用可能不足以满足需求。  
    为弥合这一差距，我们提出了一种两阶段解决方案。在本研究中，我们专注于第一阶段，引入了一个多模块框架，旨在模拟人类对话中涉及的关键智能要素。该框架包含用于推理的思考模块、用于管理知识和外部信息的资源模块，以及用于生成情境合适交互的响应模块。通过所有模块的协同工作，该框架将使代理能够提供更人性化的对话体验。  
    在我们的方法的第二阶段，这些经过筛选和标注的对话数据可用于强化学习的训练和测试，使AI更好地捕捉人类偏好。这一阶段留待未来工作。  
    在我们的实验中，志愿者与由独立LLM驱动的同一AI角色以及集成同一LLM的我们框架进行了超过3000轮的对话。一组独立的评估人员对对话样本进行了评分，结果显示，即使没有对LLM进行微调，我们的框架也显著提升了社交和对话智能。

> Large language models (LLMs), due to their advanced natural language capabilities, have seen significant success in applications where the user interface is usually a conversational artificial intelligence (AI) agent and engages the user through multi-round conversations. However, many scenarios require the agents to exhibit stronger social and conversational intelligence and demonstrate more human-like (anthropomorphic) reactions. This is an aspect that foundational LLMs have yet to fully address such that a single call of foundational models might be insufficient.
  To bridge this gap, we propose a two-stage solution. In this work, we focus on the first stage, introducing a multi-module framework designed to replicate the key aspects of human intelligence involved in conversations. This framework comprises thinking modules for reasoning, resource modules for managing knowledge and external information, and response modules for generating contextually appropriate interactions. With all the modules cooperating, the framework would empower the agents to provide a better human-like conversation experience. In the second stage of our approach, these conversational data, after filtering and labeling, can serve as training and testing data for reinforcement learning, enabling AI to better capture human preferences. This stage is left for future work.
  In our experiments, volunteers engaged in over 3000 rounds of conversation with the same AI character powered by a standalone LLM and our framework which integrates the same LLM. A separate group of evaluators rated the conversation samples, revealing that our framework significantly enhanced the social and conversational intelligence, even without fine-tuning the LLM.

[Arxiv](https://arxiv.org/abs/2503.04787)