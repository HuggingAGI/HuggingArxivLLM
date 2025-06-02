# RAGPPI：在药物发现领域中用于蛋白质-蛋白质相互作用的RAG基准测试

发布时间：2025年05月28日

`RAG` `药物开发` `问答系统`

> RAGPPI: RAG Benchmark for Protein-Protein Interactions in Drug Discovery

# 摘要

> 揭示蛋白质相互作用（PPIs）的生物影响对于药物开发中的靶点识别至关重要。然而，由于涉及蛋白质数量庞大，这一过程仍然耗时且充满挑战。尽管大型语言模型（LLMs）和检索增强生成（RAG）框架支持靶点识别，但目前尚无可用于识别PPIs生物影响的基准。为填补这一空白，我们推出了PPIs的RAG基准（RAGPPI），这是一个包含4,420个问答对的事实问答基准，专注于PPIs潜在的生物影响。

通过与专家访谈，我们确定了构建基准数据集的标准，包括问答类型和来源。我们通过专家驱动的数据标注构建了一个金标准数据集（500个问答对）。我们开发了一个集成自动评估的大型语言模型，该模型反映了专家标注的特征，从而促进了银标准数据集（3,720个问答对）的构建。我们致力于维护RAGPPI作为资源，支持研究界推进用于药物发现问答解决方案的RAG系统。

> Retrieving the biological impacts of protein-protein interactions (PPIs) is essential for target identification (Target ID) in drug development. Given the vast number of proteins involved, this process remains time-consuming and challenging. Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) frameworks have supported Target ID; however, no benchmark currently exists for identifying the biological impacts of PPIs. To bridge this gap, we introduce the RAG Benchmark for PPIs (RAGPPI), a factual question-answer benchmark of 4,420 question-answer pairs that focus on the potential biological impacts of PPIs. Through interviews with experts, we identified criteria for a benchmark dataset, such as a type of QA and source. We built a gold-standard dataset (500 QA pairs) through expert-driven data annotation. We developed an ensemble auto-evaluation LLM that reflected expert labeling characteristics, which facilitates the construction of a silver-standard dataset (3,720 QA pairs). We are committed to maintaining RAGPPI as a resource to support the research community in advancing RAG systems for drug discovery QA solutions.

[Arxiv](https://arxiv.org/abs/2505.23823)