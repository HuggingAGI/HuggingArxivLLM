# MHQA：面向语言模型的多样化、知识密集型心理健康问答挑战

发布时间：2025年02月21日

`LLM应用` `心理健康` `问答系统`

> MHQA: A Diverse, Knowledge Intensive Mental Health Question Answering Challenge for Language Models

# 摘要

> 心理健康仍然是全球性的难题，抑郁症、焦虑症等心理问题日益普遍。大型语言模型（LLMs）在医疗领域得到了广泛应用，尤其是在回答医学问题方面。然而，心理健康领域的问答（QA）缺乏标准的基准数据集。

我们的工作提出了一种新的多项选择数据集MHQA（心理健康问答），用于评估语言模型（LMs）。以往的心理健康数据集主要集中在将文本分类到特定标签或疾病上。而MHQA则专注于心理健康领域的问答，涵盖焦虑、抑郁、创伤和强迫症四个关键领域，并包含多种问题类型，即事实性问题、诊断性问题、预后性问题和预防性问题。

我们使用PubMed摘要作为问答的主要来源。我们开发了一个基于LLM从摘要中提取信息的严格流程，基于各种选择标准，并将其转换为问答对。此外，我们还根据事后验证标准提取了有效的问答对。

总体而言，我们的MHQA数据集包含2,475个专家验证的黄金标准实例，称为MHQA-gold，以及约56,100个使用外部医学参考伪标记的问答对。我们报告了不同LLMs的F1分数，并进行了少量样本和监督微调实验，进一步讨论了分数的见解。

> Mental health remains a challenging problem all over the world, with issues like depression, anxiety becoming increasingly common. Large Language Models (LLMs) have seen a vast application in healthcare, specifically in answering medical questions. However, there is a lack of standard benchmarking datasets for question answering (QA) in mental health. Our work presents a novel multiple choice dataset, MHQA (Mental Health Question Answering), for benchmarking Language models (LMs). Previous mental health datasets have focused primarily on text classification into specific labels or disorders. MHQA, on the other hand, presents question-answering for mental health focused on four key domains: anxiety, depression, trauma, and obsessive/compulsive issues, with diverse question types, namely, factoid, diagnostic, prognostic, and preventive. We use PubMed abstracts as the primary source for QA. We develop a rigorous pipeline for LLM-based identification of information from abstracts based on various selection criteria and converting it into QA pairs. Further, valid QA pairs are extracted based on post-hoc validation criteria. Overall, our MHQA dataset consists of 2,475 expert-verified gold standard instances called MHQA-gold and ~56.1k pairs pseudo labeled using external medical references. We report F1 scores on different LLMs along with few-shot and supervised fine-tuning experiments, further discussing the insights for the scores.

[Arxiv](https://arxiv.org/abs/2502.15418)