# FriendsQA：一个用于故事视频细粒度主题分类的全新大规模深度视频理解数据集

发布时间：2024年12月22日

`LLM应用` `问答系统`

> FriendsQA: A New Large-Scale Deep Video Understanding Dataset with Fine-grained Topic Categorization for Story Videos

# 摘要

> 视频问答（VideoQA）旨在依据给定的视频来回答自然语言问题。虽说现有的模型在事实类视频问答任务里表现出色，但在深度视频理解（DVU）任务中却依旧面临挑战，此任务聚焦于故事视频。相较于事实类视频，故事视频最突出的特点是故事情节，其由包括人物、动作和地点等核心故事主题的复杂交互及长期演变构成。要理解这些主题，模型得具备DVU能力。然而，现有的DVU数据集很少依据这些故事主题来组织问题，导致难以全面评估视频问答模型对复杂故事情节的DVU能力。另外，由于手工构建数据集方法的劳动力成本高昂，这些数据集的问题数量和视频长度都受到了限制。在本文中，我们设计了一个基于大型语言模型的多智能体协作框架——StoryMind，用于自动生成一个新的大规模DVU数据集。该数据集——FriendsQA，源自著名的情景喜剧《老友记》，平均每集时长 1358 秒，涵盖 44.6 万个问题，均匀分布在 14 个细粒度主题中。最后，我们利用 FriendsQA 数据集对 10 个最先进的视频问答模型开展了全面的实验。

> Video question answering (VideoQA) aims to answer natural language questions according to the given videos. Although existing models perform well in the factoid VideoQA task, they still face challenges in deep video understanding (DVU) task, which focuses on story videos. Compared to factoid videos, the most significant feature of story videos is storylines, which are composed of complex interactions and long-range evolvement of core story topics including characters, actions and locations. Understanding these topics requires models to possess DVU capability. However, existing DVU datasets rarely organize questions according to these story topics, making them difficult to comprehensively assess VideoQA models' DVU capability of complex storylines. Additionally, the question quantity and video length of these dataset are limited by high labor costs of handcrafted dataset building method. In this paper, we devise a large language model based multi-agent collaboration framework, StoryMind, to automatically generate a new large-scale DVU dataset. The dataset, FriendsQA, derived from the renowned sitcom Friends with an average episode length of 1,358 seconds, contains 44.6K questions evenly distributed across 14 fine-grained topics. Finally, We conduct comprehensive experiments on 10 state-of-the-art VideoQA models using the FriendsQA dataset.

[Arxiv](https://arxiv.org/abs/2412.17022)