# CF-RAG：基于检索增强生成的碳足迹问答数据集与方法

发布时间：2025年08月05日

`LLM应用` `可持续发展` `环境保护`

> CF-RAG: A Dataset and Method for Carbon Footprint QA Using Retrieval-Augmented Generation

# 摘要

> 产品可持续性报告提供了关于产品环境影响的有价值见解，通常以PDF格式分发。这些报告通常包含表格和文本的组合，增加了分析的复杂性。缺乏标准化和多变的报告格式进一步加剧了从大量文档中提取和解释相关信息的难度。在本文中，我们致力于解决从PDF格式的可持续性报告中回答与碳足迹相关问题的挑战。与以往方法不同，我们专注于解决从PDF解析中提取的文本的非结构化和不一致性质所带来的困难。

为了促进这一分析，我们引入了CarbonPDF-QA，这是一个开源数据集，包含1735份产品报告文档的问题-答案对，以及人工标注的答案。我们的分析表明，GPT-4o难以回答存在数据不一致的问题。为了解决这一限制，我们提出了CarbonPDF，这是一种专门针对此类数据集回答碳足迹问题的基于LLM的技术。我们通过使用我们的训练数据对Llama 3进行微调来开发CarbonPDF。我们的结果显示，我们的技术优于当前最先进的技术，包括在表格和文本数据上进行微调的问题回答（QA）系统。


> Product sustainability reports provide valuable insights into the environmental impacts of a product and are often distributed in PDF format. These reports often include a combination of tables and text, which complicates their analysis. The lack of standardization and the variability in reporting formats further exacerbate the difficulty of extracting and interpreting relevant information from large volumes of documents. In this paper, we tackle the challenge of answering questions related to carbon footprints within sustainability reports available in PDF format. Unlike previous approaches, our focus is on addressing the difficulties posed by the unstructured and inconsistent nature of text extracted from PDF parsing. To facilitate this analysis, we introduce CarbonPDF-QA, an open-source dataset containing question-answer pairs for 1735 product report documents, along with human-annotated answers. Our analysis shows that GPT-4o struggles to answer questions with data inconsistencies. To address this limitation, we propose CarbonPDF, an LLM-based technique specifically designed to answer carbon footprint questions on such datasets. We develop CarbonPDF by fine-tuning Llama 3 with our training data. Our results show that our technique outperforms current state-of-the-art techniques, including question-answering (QA) systems finetuned on table and text data.

[Arxiv](https://arxiv.org/abs/2508.03489)