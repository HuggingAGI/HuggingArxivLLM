# # **面向现实世界中文心理支持对话：CPsDD数据集与协同演进的多智能体系统**

发布时间：2025年07月10日

`LLM应用` `心理支持` `对话生成`

> Toward Real-World Chinese Psychological Support Dialogues: CPsDD Dataset and a Co-Evolving Multi-Agent System

# 摘要

> 随着压力的不断增加，心理支持的需求日益增长，这凸显了相关数据集，特别是在非英语语言中的稀缺性。为了解决这一问题，我们提出了一种框架，利用有限的真实世界数据和专家知识，微调了两个大型语言模型：对话生成器和对话修改器。生成器基于预定义的路径创建大规模的心理咨询对话，指导系统回应策略和用户互动，形成有效支持的基础。修改器则对这些对话进行优化，使其与真实世界的数据质量相匹配。通过自动化和人工审查相结合的方式，我们构建了中文心理支持对话数据集（CPsDD），包含13个组别、16种心理问题、13种诱因和12种支持重点的68,000个对话。此外，我们还引入了综合代理对话支持系统（CADSS），其中分析器剖析用户特征，摘要器浓缩对话历史，规划器选择策略，而支持者则生成富有同理心的回应。在策略预测和情感支持对话（ESC）任务的实验中，CADSS在CPsDD和ESConv数据集上均达到了最先进的性能。

> The growing need for psychological support due to increasing pressures has exposed the scarcity of relevant datasets, particularly in non-English languages. To address this, we propose a framework that leverages limited real-world data and expert knowledge to fine-tune two large language models: Dialog Generator and Dialog Modifier. The Generator creates large-scale psychological counseling dialogues based on predefined paths, which guide system response strategies and user interactions, forming the basis for effective support. The Modifier refines these dialogues to align with real-world data quality. Through both automated and manual review, we construct the Chinese Psychological support Dialogue Dataset (CPsDD), containing 68K dialogues across 13 groups, 16 psychological problems, 13 causes, and 12 support focuses. Additionally, we introduce the Comprehensive Agent Dialogue Support System (CADSS), where a Profiler analyzes user characteristics, a Summarizer condenses dialogue history, a Planner selects strategies, and a Supporter generates empathetic responses. The experimental results of the Strategy Prediction and Emotional Support Conversation (ESC) tasks demonstrate that CADSS achieves state-of-the-art performance on both CPsDD and ESConv datasets.

[Arxiv](https://arxiv.org/abs/2507.07509)