# 聚合知识模型：利用微调与检索增强生成技术提升领域问答性能

发布时间：2024年10月23日

`RAG

理由：这篇论文主要讨论了在封闭领域问答系统中，通过比较微调的大型语言模型和检索增强生成（RAG）模型，提出了一种新的聚合知识模型（AKM）来提升问答系统的性能。论文的核心内容集中在RAG模型的应用和优化上，因此将其分类为RAG。` `问答系统`

> Aggregated Knowledge Model: Enhancing Domain-Specific QA with Fine-Tuned and Retrieval-Augmented Generation Models

# 摘要

> 本文提出了一种提升封闭领域问答系统（QA）的新方法，专注于劳伦斯伯克利国家实验室（LBL）科学信息技术（ScienceIT）领域的独特需求。基于ScienceIT文档的丰富数据集，我们深入比较了两个微调的大型语言模型和五个检索增强生成（RAG）模型。通过数据处理技术，我们将文档转化为结构化的上下文-问题-答案三元组，并借助最新的大型语言模型（如AWS Bedrock、GCP PaLM2、Meta LLaMA2、OpenAI GPT-4、Google Gemini-Pro）进行数据驱动的分析。此外，我们提出了聚合知识模型（AKM），利用K-means聚类综合七个模型的响应，筛选出最具代表性的答案。通过对这些模型的多维度评估，我们全面揭示了它们在LBL ScienceIT环境中的表现与适用性。结果表明，结合微调与检索增强策略具有显著优势，AKM在性能上实现了显著提升。本研究的成果为开发针对特定领域的专用QA系统提供了宝贵见解。

> This paper introduces a novel approach to enhancing closed-domain Question Answering (QA) systems, focusing on the specific needs of the Lawrence Berkeley National Laboratory (LBL) Science Information Technology (ScienceIT) domain. Utilizing a rich dataset derived from the ScienceIT documentation, our study embarks on a detailed comparison of two fine-tuned large language models and five retrieval-augmented generation (RAG) models. Through data processing techniques, we transform the documentation into structured context-question-answer triples, leveraging the latest Large Language Models (AWS Bedrock, GCP PaLM2, Meta LLaMA2, OpenAI GPT-4, Google Gemini-Pro) for data-driven insights. Additionally, we introduce the Aggregated Knowledge Model (AKM), which synthesizes responses from the seven models mentioned above using K-means clustering to select the most representative answers. The evaluation of these models across multiple metrics offers a comprehensive look into their effectiveness and suitability for the LBL ScienceIT environment. The results demonstrate the potential benefits of integrating fine-tuning and retrieval-augmented strategies, highlighting significant performance improvements achieved with the AKM. The insights gained from this study can be applied to develop specialized QA systems tailored to specific domains.

[Arxiv](https://arxiv.org/abs/2410.18344)