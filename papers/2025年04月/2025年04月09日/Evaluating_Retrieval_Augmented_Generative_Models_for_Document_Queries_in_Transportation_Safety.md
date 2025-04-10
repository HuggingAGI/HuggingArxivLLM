# 评估检索增强生成模型在交通安全文档查询中的应用

发布时间：2025年04月09日

`RAG` `交通安全` `人工智能`

> Evaluating Retrieval Augmented Generative Models for Document Queries in Transportation Safety

# 摘要

> 生成式大语言模型（LLMs）的应用正在迅速扩展到各个领域，有望显著提升工作流程效率和信息检索能力。然而，在危险品运输等专业且高风险领域，由于准确性和可靠性方面的担忧，其实施面临诸多挑战。本研究评估了三个微调生成模型——ChatGPT、Google的Vertex AI以及ORNL检索增强生成增强的LLaMA 2和LLaMA——在美国危险品运输合规所需监管信息检索方面的性能。我们利用约40份公开的联邦和州级监管文件，开发了100个与路线规划和许可要求相关的实际查询。根据准确性、详细程度和相关性对回答进行定性评分，并通过模型输出之间的语义相似性进行定量评估。结果显示，RAG增强的LLaMA模型在Vertex AI和ChatGPT之上表现显著更优，提供了更详细且通常准确的信息，尽管偶尔存在不一致。本研究首次将RAG应用于交通安全领域，强调了领域特定微调和严格评估方法的重要性，以确保可靠性并最大限度地减少高风险环境中不准确性的风险。

> Applications of generative Large Language Models LLMs are rapidly expanding across various domains, promising significant improvements in workflow efficiency and information retrieval. However, their implementation in specialized, high-stakes domains such as hazardous materials transportation is challenging due to accuracy and reliability concerns. This study evaluates the performance of three fine-tuned generative models, ChatGPT, Google's Vertex AI, and ORNL Retrieval Augmented Generation augmented LLaMA 2 and LLaMA in retrieving regulatory information essential for hazardous material transportation compliance in the United States. Utilizing approximately 40 publicly available federal and state regulatory documents, we developed 100 realistic queries relevant to route planning and permitting requirements. Responses were qualitatively rated based on accuracy, detail, and relevance, complemented by quantitative assessments of semantic similarity between model outputs. Results demonstrated that the RAG-augmented LLaMA models significantly outperformed Vertex AI and ChatGPT, providing more detailed and generally accurate information, despite occasional inconsistencies. This research introduces the first known application of RAG in transportation safety, emphasizing the need for domain-specific fine-tuning and rigorous evaluation methodologies to ensure reliability and minimize the risk of inaccuracies in high-stakes environments.

[Arxiv](https://arxiv.org/abs/2504.07022)