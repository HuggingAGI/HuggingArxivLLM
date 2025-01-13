# QuIM-RAG: 利用倒置问题匹配优化检索增强生成，提升问答性能
发布时间：2025年01月05日

`RAG`
> QuIM-RAG: Advancing Retrieval-Augmented Generation with Inverted Question Matching for Enhanced QA Performance
>
> # 摘要
本文提出了一种新颖的检索增强生成（RAG）系统架构，旨在提升目标语料库中的问答（QA）任务表现。大型语言模型（LLMs）在类人文本的分析与生成方面取得了革命性进展，但其依赖预训练数据且缺乏实时更新能力。RAG通过整合在线资源与数据库，生成上下文相关的响应，从而增强了LLMs的能力。然而，传统RAG在处理海量数据时仍面临信息稀释与幻觉等挑战。我们的解决方案是将语料库转化为特定领域数据集，并构建RAG架构以从目标文档生成响应。我们引入了QuIM-RAG（问题到问题倒排索引匹配），这是一种创新的检索机制，通过从文档块生成潜在问题并与用户查询匹配，精准定位最相关的文本块以生成准确答案。我们在Meta Inc.开源的Meta-LLaMA3-8B-instruct模型（Hugging Face平台提供）上实现了这一RAG系统，并构建了一个包含500多页高流量网站内容的自定义语料库，用于回答复杂问题，同时准备了手动标注的真实QA数据用于评估。通过BERT-Score和RAGAS这两种先进的LLM应用评估指标，我们与传统RAG模型进行了对比，结果显示我们的方法在这两项指标上均优于传统RAG架构。
>
> https://arxiv.org/abs/2501.02702

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2501.02702](https://arxiv.org/abs/2501.02702)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)