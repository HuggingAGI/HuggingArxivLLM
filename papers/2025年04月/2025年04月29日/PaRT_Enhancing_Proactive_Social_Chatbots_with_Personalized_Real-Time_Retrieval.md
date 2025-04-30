# PaRT：结合个性化实时检索，提升主动社交聊天机器人的性能

发布时间：2025年04月29日

`LLM应用` `聊天机器人`

> PaRT: Enhancing Proactive Social Chatbots with Personalized Real-Time Retrieval

# 摘要

> 社交型聊天机器人已经成为人们日常生活中不可或缺的智能伙伴，应用场景从情感支持到个人互动不一而足。然而，传统聊天机器人由于被动响应机制，往往需要用户主动发起或维持对话，导致参与度下降和对话时间缩短。本文中，我们提出了PaRT——一个全新的框架，通过个性化实时检索与生成，赋予社交型聊天机器人具备语境感知的主动对话能力。具体而言，PaRT首先将用户档案和对话上下文整合到大型语言模型（LLM）中，该模型最初被提示用于优化用户查询并识别其潜在意图，以准备即将到来的对话。基于优化后的意图，LLM生成个性化的对话主题，这些主题随后作为定向查询，从RedNote中检索相关段落。最后，我们通过总结后的段落提示LLM，生成既具知识基础又优化参与度的回复。我们的方法已在真实生产环境中稳定运行超过30天，实现了对话平均时长21.77%的显著提升。

> Social chatbots have become essential intelligent companions in daily scenarios ranging from emotional support to personal interaction. However, conventional chatbots with passive response mechanisms usually rely on users to initiate or sustain dialogues by bringing up new topics, resulting in diminished engagement and shortened dialogue duration. In this paper, we present PaRT, a novel framework enabling context-aware proactive dialogues for social chatbots through personalized real-time retrieval and generation. Specifically, PaRT first integrates user profiles and dialogue context into a large language model (LLM), which is initially prompted to refine user queries and recognize their underlying intents for the upcoming conversation. Guided by refined intents, the LLM generates personalized dialogue topics, which then serve as targeted queries to retrieve relevant passages from RedNote. Finally, we prompt LLMs with summarized passages to generate knowledge-grounded and engagement-optimized responses. Our approach has been running stably in a real-world production environment for more than 30 days, achieving a 21.77\% improvement in the average duration of dialogues.

[Arxiv](https://arxiv.org/abs/2504.20624)