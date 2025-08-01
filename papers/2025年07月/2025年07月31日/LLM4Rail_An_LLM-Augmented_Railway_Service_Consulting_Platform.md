# LLM4Rail：LLM增强型铁路服务咨询平台

发布时间：2025年07月31日

`LLM应用` `铁路服务` `推荐系统`

> LLM4Rail: An LLM-Augmented Railway Service Consulting Platform

# 摘要

> 大型语言模型（LLMs）正在深刻改变商业领域的方方面面。为满足日益增长的个性化铁路服务需求，我们开发了LLM4Rail——一个全新的基于LLM增强的铁路服务咨询平台。借助LLM的强大能力，LLM4Rail能够提供售票、铁路餐饮推荐、天气信息查询以及闲聊等定制模块。在LLM4Rail中，我们提出了迭代式的“问题-思考-行动-观察（QTAO）”提示框架。该框架将语言推理与任务导向型动作有机结合，即通过推理指导行动选择，从而有效检索与铁路运营和服务相关的外部观察结果，生成准确的回复。为了提供个性化的车上餐饮服务，我们首先构建了中文铁路餐饮数据集（CRFD-25）——一个专为铁路服务设计的公开可用外卖数据集。CRFD-25涵盖了按城市、菜系、年龄群体和辣度等级分类的各种特色菜品。我们进一步引入了一个基于LLM的零样本对话推荐系统，用于铁路餐饮服务。为了解决开放推荐的无约束性质，我们引入了基于特征相似性的后处理步骤，以确保所有推荐项与CRFD-25数据集保持一致。

> Large language models (LLMs) have significantly reshaped different walks of business. To meet the increasing demands for individualized railway service, we develop LLM4Rail - a novel LLM-augmented railway service consulting platform. Empowered by LLM, LLM4Rail can provide custom modules for ticketing, railway food & drink recommendations, weather information, and chitchat. In LLM4Rail, we propose the iterative "Question-Thought-Action-Observation (QTAO)" prompting framework. It meticulously integrates verbal reasoning with task-oriented actions, that is, reasoning to guide action selection, to effectively retrieve external observations relevant to railway operation and service to generate accurate responses. To provide personalized onboard dining services, we first construct the Chinese Railway Food and Drink (CRFD-25) - a publicly accessible takeout dataset tailored for railway services. CRFD-25 covers a wide range of signature dishes categorized by cities, cuisines, age groups, and spiciness levels. We further introduce an LLM-based zero-shot conversational recommender for railway catering. To address the unconstrained nature of open recommendations, the feature similarity-based post-processing step is introduced to ensure all the recommended items are aligned with CRFD-25 dataset.

[Arxiv](https://arxiv.org/abs/2507.23377)