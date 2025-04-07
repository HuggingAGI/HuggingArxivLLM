# # OnRL-RAG：实时个性化心理健康对话系统

发布时间：2025年04月02日

`LLM应用` `心理健康` `心理学`

> OnRL-RAG: Real-Time Personalized Mental Health Dialogue System

# 摘要

> 大型语言模型 (LLMs) 在各种任务和应用中得到了广泛应用。然而，LLMs 的能力受限于预训练数据，例如 ChatGPT 截至 2021 年的知识可能已过时或不准确。为了解决这一问题，检索增强生成 (RAG) 被提出，通过为 LLMs 提供额外的、最新的信息来增强其能力。虽然 RAG 能够提供正确信息，但在呈现方式上可能不尽如人意，尤其是对于需要个性化服务的不同人群。基于人类反馈的强化学习 (RLHF) 通过反馈循环调整模型响应，使其更贴近人类偏好。在现实生活中，例如应对心理健康问题时，动态反馈模型能够根据日常环境中复杂因素的变化，持续适应新信息并提供个性化支持。因此，我们提出了一种基于在线强化学习的检索增强生成 (OnRL-RAG) 系统，专门用于检测和个性化应对压力、焦虑和抑郁等心理健康问题。我们使用一个开源数据集进行演示，该数据集包含 2028 名大学生的 28 个调查问题回答。实验结果表明，我们的系统在性能上显著优于标准 RAG 和简单 LLM（如 GPT-4o、GPT-4o-mini、Gemini-1.5 和 GPT-3.5）。这项研究不仅为 LLMs 在日常环境中的个性化服务应用提供了新思路，也为社会学、心理学和神经科学领域的研究者提供了理论与实践相结合的桥梁。

> Large language models (LLMs) have been widely used for various tasks and applications. However, LLMs and fine-tuning are limited to the pre-trained data. For example, ChatGPT's world knowledge until 2021 can be outdated or inaccurate. To enhance the capabilities of LLMs, Retrieval-Augmented Generation (RAG), is proposed to augment LLMs with additional, new, latest details and information to LLMs. While RAG offers the correct information, it may not best present it, especially to different population groups with personalizations. Reinforcement Learning from Human Feedback (RLHF) adapts to user needs by aligning model responses with human preference through feedback loops. In real-life applications, such as mental health problems, a dynamic and feedback-based model would continuously adapt to new information and offer personalized assistance due to complex factors fluctuating in a daily environment. Thus, we propose an Online Reinforcement Learning-based Retrieval-Augmented Generation (OnRL-RAG) system to detect and personalize the responding systems to mental health problems, such as stress, anxiety, and depression. We use an open-source dataset collected from 2028 College Students with 28 survey questions for each student to demonstrate the performance of our proposed system with the existing systems. Our system achieves superior performance compared to standard RAG and simple LLM via GPT-4o, GPT-4o-mini, Gemini-1.5, and GPT-3.5. This work would open up the possibilities of real-life applications of LLMs for personalized services in the everyday environment. The results will also help researchers in the fields of sociology, psychology, and neuroscience to align their theories more closely with the actual human daily environment.

[Arxiv](https://arxiv.org/abs/2504.02894)