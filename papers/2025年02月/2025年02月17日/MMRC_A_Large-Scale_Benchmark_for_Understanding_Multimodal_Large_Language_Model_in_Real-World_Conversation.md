# # 摘要
MMRC：大规模多模态语言模型对话基准，助力理解真实世界对话能力。

发布时间：2025年02月17日

`LLM应用` `对话系统`

> MMRC: A Large-Scale Benchmark for Understanding Multimodal Large Language Model in Real-World Conversation

# 摘要

> 多模态大型语言模型（MLLMs）在开放对话中展现出巨大潜力，能生成更准确、个性化的回复。然而，这些模型在现实场景中的持续交互中，记忆、推理等能力仍待深入探索。本文提出MMRC——一个多模态现实对话基准测试，用于评估MLLMs的六项核心开放能力：信息提取、多轮推理、信息更新、图像管理、记忆召回及拒绝回答。MMRC从真实场景中收集数据，包含5,120次对话及28,720个标注问题，对现有MLLMs构成重大挑战。在MMRC上对20个MLLMs的评估显示，开放交互中准确率有所下降。我们发现四种常见失败模式：长期记忆衰退、知识更新不足、错误累积传播及拒绝回答意愿低。为解决这些问题，我们提出简单有效的NOTE-TAKING策略，记录对话关键信息并在模型回应时提醒，显著提升对话能力。实验表明，该策略在六种MLLMs上均带来性能提升。


> Recent multimodal large language models (MLLMs) have demonstrated significant potential in open-ended conversation, generating more accurate and personalized responses. However, their abilities to memorize, recall, and reason in sustained interactions within real-world scenarios remain underexplored. This paper introduces MMRC, a Multi-Modal Real-world Conversation benchmark for evaluating six core open-ended abilities of MLLMs: information extraction, multi-turn reasoning, information update, image management, memory recall, and answer refusal. With data collected from real-world scenarios, MMRC comprises 5,120 conversations and 28,720 corresponding manually labeled questions, posing a significant challenge to existing MLLMs. Evaluations on 20 MLLMs in MMRC indicate an accuracy drop during open-ended interactions. We identify four common failure patterns: long-term memory degradation, inadequacies in updating factual knowledge, accumulated assumption of error propagation, and reluctance to say no. To mitigate these issues, we propose a simple yet effective NOTE-TAKING strategy, which can record key information from the conversation and remind the model during its responses, enhancing conversational capabilities. Experiments across six MLLMs demonstrate significant performance improvements.

[Arxiv](https://arxiv.org/abs/2502.11903)