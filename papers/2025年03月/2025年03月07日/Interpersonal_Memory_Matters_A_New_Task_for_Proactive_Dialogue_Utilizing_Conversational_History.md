# # 人际记忆至关重要：一个利用对话历史的主动对话新任务

发布时间：2025年03月07日

`Agent` `人工智能` `对话系统`

> Interpersonal Memory Matters: A New Task for Proactive Dialogue Utilizing Conversational History

# 摘要

> 主动对话系统旨在赋予聊天机器人引导对话向特定目标发展的能力，从而提升用户参与度和服务自主性。现有系统通常针对预定义的关键词或实体进行目标设定，忽视了对话历史中隐含的用户属性和偏好，这阻碍了长期用户亲密度的发展。为应对这些挑战，我们提出了一种创新方法，将主动对话系统与长期记忆整合到一个统一框架中，构建更像人类的对话代理。具体而言，我们定义了一个名为记忆感知主动对话（MapDia）的新任务。通过分解该任务，我们提出了一种自动数据构建方法，并创建了首个中文记忆感知主动对话数据集（ChMapData）。此外，我们引入了一个基于检索增强生成（RAG）的联合框架，包含三个模块：主题总结、主题检索以及主动话题转换检测与生成，旨在在适当的时候将对话引导至相关的历史话题。我们的数据集和模型的有效性通过自动评估和人工评估得到了验证。我们已开源该框架和数据集，地址为 https://github.com/FrontierLabs/MapDia。


> Proactive dialogue systems aim to empower chatbots with the capability of leading conversations towards specific targets, thereby enhancing user engagement and service autonomy. Existing systems typically target pre-defined keywords or entities, neglecting user attributes and preferences implicit in dialogue history, hindering the development of long-term user intimacy. To address these challenges, we take a radical step towards building a more human-like conversational agent by integrating proactive dialogue systems with long-term memory into a unified framework. Specifically, we define a novel task named Memory-aware Proactive Dialogue (MapDia). By decomposing the task, we then propose an automatic data construction method and create the first Chinese Memory-aware Proactive Dataset (ChMapData). Furthermore, we introduce a joint framework based on Retrieval Augmented Generation (RAG), featuring three modules: Topic Summarization, Topic Retrieval, and Proactive Topic-shifting Detection and Generation, designed to steer dialogues towards relevant historical topics at the right time. The effectiveness of our dataset and models is validated through both automatic and human evaluations. We release the open-source framework and dataset at https://github.com/FrontierLabs/MapDia.

[Arxiv](https://arxiv.org/abs/2503.05150)