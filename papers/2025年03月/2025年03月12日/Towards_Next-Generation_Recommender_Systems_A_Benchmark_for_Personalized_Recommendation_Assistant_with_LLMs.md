# 迈向下一代推荐系统：基于大语言模型的个性化推荐助手基准评测

发布时间：2025年03月12日

`LLM应用` `推荐系统` `人工智能`

> Towards Next-Generation Recommender Systems: A Benchmark for Personalized Recommendation Assistant with LLMs

# 摘要

> 推荐系统（RecSys）在现代数字平台上广泛应用，备受关注。传统推荐系统仅关注固定简单的推荐场景，难以在交互式范式下推广到新任务。大型语言模型（LLMs）的突破性进展彻底改变了推荐系统的架构，推动其发展为更智能、更互动的个性化推荐助手。然而，现有研究依赖固定任务特定提示模板生成推荐并评估助手性能，限制了对其能力的全面评估。这是因为常用数据库缺乏反映真实推荐场景的高质量文本查询，不适合评估LLM推荐助手。为填补这一空白，我们推出RecBench+，这是一个全新数据集基准，旨在评估LLMs在处理复杂用户推荐需求方面的表现。RecBench+包含多样化查询，涵盖硬性条件和软性偏好，难度各异。我们在RecBench+上评估了常用LLMs，发现：1）LLMs展现作为推荐助手的初步能力，2）LLMs在处理明确条件查询时表现优异，但在处理需推理或含误导信息的查询时面临挑战。我们的数据集已发布在https://github.com/jiani-huang/RecBench.git。

> Recommender systems (RecSys) are widely used across various modern digital platforms and have garnered significant attention. Traditional recommender systems usually focus only on fixed and simple recommendation scenarios, making it difficult to generalize to new and unseen recommendation tasks in an interactive paradigm. Recently, the advancement of large language models (LLMs) has revolutionized the foundational architecture of RecSys, driving their evolution into more intelligent and interactive personalized recommendation assistants. However, most existing studies rely on fixed task-specific prompt templates to generate recommendations and evaluate the performance of personalized assistants, which limits the comprehensive assessments of their capabilities. This is because commonly used datasets lack high-quality textual user queries that reflect real-world recommendation scenarios, making them unsuitable for evaluating LLM-based personalized recommendation assistants. To address this gap, we introduce RecBench+, a new dataset benchmark designed to access LLMs' ability to handle intricate user recommendation needs in the era of LLMs. RecBench+ encompasses a diverse set of queries that span both hard conditions and soft preferences, with varying difficulty levels. We evaluated commonly used LLMs on RecBench+ and uncovered below findings: 1) LLMs demonstrate preliminary abilities to act as recommendation assistants, 2) LLMs are better at handling queries with explicitly stated conditions, while facing challenges with queries that require reasoning or contain misleading information. Our dataset has been released at https://github.com/jiani-huang/RecBench.git.

[Arxiv](https://arxiv.org/abs/2503.09382)