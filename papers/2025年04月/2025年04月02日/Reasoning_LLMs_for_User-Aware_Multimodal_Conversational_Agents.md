# 面向用户感知的多模态对话智能体的推理型大语言模型

发布时间：2025年04月02日

`LLM应用` `社交机器人` `个性化对话系统`

> Reasoning LLMs for User-Aware Multimodal Conversational Agents

# 摘要

> 社交机器人中的个性化问题是一个关键挑战，尤其是当系统无法获取初始用户偏好或特征时。本文提出了一种名为USER-LLM R1的创新框架，通过动态用户画像和模型初始化技术，为用户感知对话代理提供解决方案。我们的方法结合了链式推理（CoT）模型，用于逐步推断用户偏好，以及视觉语言模型（VLMs），用于从多模态输入中构建用户画像，从而实现首次交互即个性化的对话体验。借助检索增强生成（RAG）架构，系统能够在CoT推理过程中动态优化用户表示，确保生成的响应既上下文相关又灵活适应。实验结果表明，在ElderlyTech-VQA基准测试中，与现有最优方法相比，ROUGE-1、ROUGE-2和ROUGE-L的F1分数分别提升了23.2%、0.6%和8%。通过消融实验，我们发现推理模型的规模对整体性能有显著影响。此外，用户研究表明，该框架特别适用于老年用户群体，定制化响应显著提升了他们的参与度和信任感。我们还重点讨论了隐私保护和偏见缓解等伦理问题，以确保该技术的负责任应用。

> Personalization in social robotics is critical for fostering effective human-robot interactions, yet systems often face the cold start problem, where initial user preferences or characteristics are unavailable. This paper proposes a novel framework called USER-LLM R1 for a user-aware conversational agent that addresses this challenge through dynamic user profiling and model initiation. Our approach integrates chain-of-thought (CoT) reasoning models to iteratively infer user preferences and vision-language models (VLMs) to initialize user profiles from multimodal inputs, enabling personalized interactions from the first encounter. Leveraging a Retrieval-Augmented Generation (RAG) architecture, the system dynamically refines user representations within an inherent CoT process, ensuring contextually relevant and adaptive responses. Evaluations on the ElderlyTech-VQA Bench demonstrate significant improvements in ROUGE-1 (+23.2%), ROUGE-2 (+0.6%), and ROUGE-L (+8%) F1 scores over state-of-the-art baselines, with ablation studies underscoring the impact of reasoning model size on performance. Human evaluations further validate the framework's efficacy, particularly for elderly users, where tailored responses enhance engagement and trust. Ethical considerations, including privacy preservation and bias mitigation, are rigorously discussed and addressed to ensure responsible deployment.

[Arxiv](https://arxiv.org/abs/2504.01700)