# 大型语言模型堪称强大的电子健康记录编码器。

发布时间：2025年02月24日

`LLM应用` `临床预测`

> Large Language Models are Powerful EHR Encoders

# 摘要

> 电子健康记录（EHRs）在临床预测中潜力巨大，但传统机器学习方法难以应对其复杂性和多样性。基于大量未标注EHR数据训练的领域特定模型虽有所改进，但受限于数据质量和标准不一。本研究尝试使用通用大型语言模型（LLMs）的嵌入方法进行EHR编码。通过将患者记录转化为结构化的Markdown文本，并将代码转为人类可读描述，我们借助在大规模公开语料上预训练的LLMs的泛化能力，无需依赖专有医疗数据集。我们系统评估了GTE-Qwen2-7B-Instruct和LLM2Vec-Llama3.1-8B-Instruct两个先进模型在EHRSHOT基准中的15个临床预测任务表现，与CLIMBR-T-Base和传统机器学习方法对比。结果显示，LLM嵌入方法在少样本情况下表现优异，其效果与模型规模和上下文窗口相关。总体而言，将LLMs用于EHR编码为临床预测提供了更高效、通用的解决方案，推动了医疗应用的互操作性和泛化能力。

> Electronic Health Records (EHRs) offer rich potential for clinical prediction, yet their inherent complexity and heterogeneity pose significant challenges for traditional machine learning approaches. Domain-specific EHR foundation models trained on large collections of unlabeled EHR data have demonstrated promising improvements in predictive accuracy and generalization; however, their training is constrained by limited access to diverse, high-quality datasets and inconsistencies in coding standards and healthcare practices. In this study, we explore the possibility of using general-purpose Large Language Models (LLMs) based embedding methods as EHR encoders. By serializing patient records into structured Markdown text, transforming codes into human-readable descriptors, we leverage the extensive generalization capabilities of LLMs pretrained on vast public corpora, thereby bypassing the need for proprietary medical datasets. We systematically evaluate two state-of-the-art LLM-embedding models, GTE-Qwen2-7B-Instruct and LLM2Vec-Llama3.1-8B-Instruct, across 15 diverse clinical prediction tasks from the EHRSHOT benchmark, comparing their performance to an EHRspecific foundation model, CLIMBR-T-Base, and traditional machine learning baselines. Our results demonstrate that LLM-based embeddings frequently match or exceed the performance of specialized models, even in few-shot settings, and that their effectiveness scales with the size of the underlying LLM and the available context window. Overall, our findings demonstrate that repurposing LLMs for EHR encoding offers a scalable and effective approach for clinical prediction, capable of overcoming the limitations of traditional EHR modeling and facilitating more interoperable and generalizable healthcare applications.

[Arxiv](https://arxiv.org/abs/2502.17403)