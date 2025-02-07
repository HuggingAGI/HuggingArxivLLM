# MeDiSumQA: 基于出院信的患者问答生成

发布时间：2025年02月05日

`LLM应用

解释：这篇论文主要讨论了如何利用大型语言模型（LLMs）来简化医疗信息，以帮助患者更好地理解复杂的医学术语。论文还介绍了MeDiSumQA数据集的开发，用于评估LLMs在生成安全和患者友好文本方面的能力。这些内容直接涉及到LLMs在医疗领域的应用，因此将其分类为“LLM应用”。`

> MeDiSumQA: Patient-Oriented Question-Answer Generation from Discharge Letters

# 摘要

> 尽管增加患者对医疗文件的访问有助于改善医疗护理，但不同健康素养水平和复杂医学术语限制了这一优势。大型语言模型（LLMs）通过简化医疗信息提供了解决方案。然而，由于缺乏标准化的评估资源，评估LLMs生成安全和患者友好文本的能力颇具挑战。为此，我们开发了MeDiSumQA，这是一个通过结合基于LLM的问题-答案生成和手动质量检查的自动化管道从MIMIC-IV出院摘要中创建的数据集。我们利用该数据集评估了多种LLMs在面向患者的问题回答上的表现。结果显示，通用LLMs往往优于生物医学适应模型，且自动化指标与人类判断高度一致。通过在PhysioNet上发布MeDiSumQA，我们旨在推动LLMs的发展，提升患者的理解能力，最终改善护理效果。

> While increasing patients' access to medical documents improves medical care, this benefit is limited by varying health literacy levels and complex medical terminology. Large language models (LLMs) offer solutions by simplifying medical information. However, evaluating LLMs for safe and patient-friendly text generation is difficult due to the lack of standardized evaluation resources. To fill this gap, we developed MeDiSumQA. MeDiSumQA is a dataset created from MIMIC-IV discharge summaries through an automated pipeline combining LLM-based question-answer generation with manual quality checks. We use this dataset to evaluate various LLMs on patient-oriented question-answering. Our findings reveal that general-purpose LLMs frequently surpass biomedical-adapted models, while automated metrics correlate with human judgment. By releasing MeDiSumQA on PhysioNet, we aim to advance the development of LLMs to enhance patient understanding and ultimately improve care outcomes.

[Arxiv](https://arxiv.org/abs/2502.03298)