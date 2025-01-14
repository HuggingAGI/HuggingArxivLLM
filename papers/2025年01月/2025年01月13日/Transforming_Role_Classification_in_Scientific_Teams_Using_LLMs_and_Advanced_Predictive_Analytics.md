# 利用LLMs和高级预测分析革新科学团队角色分类

发布时间：2025年01月13日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进科学团队中作者角色的分类方法。论文中提到了使用多种LLMs（如GPT-4、Llama3 70B等）来增强传统方法，并通过少量样本提示进行分类。此外，还构建了一个基于深度学习的预测模型。这些内容都涉及到LLM在实际应用中的使用，因此将其分类为LLM应用。` `学术研究` `团队管理`

> Transforming Role Classification in Scientific Teams Using LLMs and Advanced Predictive Analytics

# 摘要

> # 摘要
科学团队的动态对研究输出的性质和影响至关重要。然而，现有的基于自我报告和聚类的作者角色分类方法缺乏对贡献的全面上下文分析。为此，我们提出了一种利用先进大型语言模型（LLMs）对科学团队中的作者角色进行分类的创新方法，相比传统聚类方法，提供了更精细的分析。我们通过使用开源和专有的LLMs（如GPT-4、Llama3 70B、Llama2 70B和Mistral 7x8B）来增强传统方法，用于角色分类。通过少量样本提示，我们对作者角色进行分类，并证明GPT-4在多个类别中表现优异，超越了XGBoost和BERT等传统方法。此外，我们还构建了一个基于10个特征的预测性深度学习模型。通过在OpenAlex数据库提供的数据集上训练该模型，该数据集包含学术出版物的详细元数据（如作者-出版物历史、作者隶属关系、研究主题和引用次数），我们实现了0.76的F1分数，展示了作者角色的稳健分类。

> Scientific team dynamics are critical in determining the nature and impact of research outputs. However, existing methods for classifying author roles based on self-reports and clustering lack comprehensive contextual analysis of contributions. Thus, we present a transformative approach to classifying author roles in scientific teams using advanced large language models (LLMs), which offers a more refined analysis compared to traditional clustering methods. Specifically, we seek to complement and enhance these traditional methods by utilizing open source and proprietary LLMs, such as GPT-4, Llama3 70B, Llama2 70B, and Mistral 7x8B, for role classification. Utilizing few-shot prompting, we categorize author roles and demonstrate that GPT-4 outperforms other models across multiple categories, surpassing traditional approaches such as XGBoost and BERT. Our methodology also includes building a predictive deep learning model using 10 features. By training this model on a dataset derived from the OpenAlex database, which provides detailed metadata on academic publications -- such as author-publication history, author affiliation, research topics, and citation counts -- we achieve an F1 score of 0.76, demonstrating robust classification of author roles.

[Arxiv](https://arxiv.org/abs/2501.07267)