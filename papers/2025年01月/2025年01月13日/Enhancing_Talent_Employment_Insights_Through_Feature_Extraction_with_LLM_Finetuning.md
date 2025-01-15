# 利用LLM微调进行特征提取，提升人才就业洞察

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）从非结构化职位发布中提取复杂职位特征，并结合了检索增强生成（RAG）等技术。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `人力资源` `劳动力市场`

> Enhancing Talent Employment Insights Through Feature Extraction with LLM Finetuning

# 摘要

> 本文研究了大型语言模型（LLMs）在从非结构化职位发布中提取复杂职位特征的应用。基于AdeptID提供的120万条职位发布数据，我们构建了一个强大的处理管道，用于识别和分类远程工作可用性、薪酬结构、教育要求和工作经验偏好等变量。我们的方法结合了语义分块、检索增强生成（RAG）和微调DistilBERT模型，有效克服了传统解析工具的不足。通过这些技术，我们在识别常被误标或忽略的变量（如非薪资补偿和推断的远程工作类别）方面取得了显著进展。我们对微调模型进行了全面评估，分析了其优势、局限性和扩展潜力。这项工作展示了LLMs在劳动力市场分析中的巨大潜力，为更精准和可操作的职位数据洞察奠定了基础。

> This paper explores the application of large language models (LLMs) to extract nuanced and complex job features from unstructured job postings. Using a dataset of 1.2 million job postings provided by AdeptID, we developed a robust pipeline to identify and classify variables such as remote work availability, remuneration structures, educational requirements, and work experience preferences. Our methodology combines semantic chunking, retrieval-augmented generation (RAG), and fine-tuning DistilBERT models to overcome the limitations of traditional parsing tools. By leveraging these techniques, we achieved significant improvements in identifying variables often mislabeled or overlooked, such as non-salary-based compensation and inferred remote work categories. We present a comprehensive evaluation of our fine-tuned models and analyze their strengths, limitations, and potential for scaling. This work highlights the promise of LLMs in labor market analytics, providing a foundation for more accurate and actionable insights into job data.

[Arxiv](https://arxiv.org/abs/2501.07663)