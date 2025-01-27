# 多阶段 LLM 管道在相关性评估中表现优于 GPT-4o

发布时间：2025年01月24日

`LLM应用

**理由**：该论文提出了一种基于LLM的模块化分类管道，用于相关性评估任务。这种方法直接应用了LLM技术来解决实际问题（即相关性评估），并且通过实验验证了其有效性和成本效益。因此，它属于LLM应用的范畴。` `搜索系统` `相关性评估`

> Multi-stage Large Language Model Pipelines Can Outperform GPT-4o in Relevance Assessment

# 摘要

> 搜索系统的有效性通过相关性标签来评估，这些标签反映了文档对特定查询和用户的有用性。虽然从真实用户获取这些标签最为理想，但大规模数据收集颇具挑战。因此，我们通常依赖第三方注释者，但其准确性参差不齐，需要昂贵的审计、培训和监控。我们提出了一种基于LLM的模块化分类管道，将相关性评估任务分解为多个阶段，每个阶段使用不同的提示和不同规模、能力的模型。在TREC深度学习（TREC-DL）上的应用表明，我们的一种方法在Krippendorff的$α$准确性上比OpenAI的GPT-4o mini提高了18.4%，同时每百万输入令牌的成本仅为0.2美元，为相关性评估提供了更高效、可扩展的解决方案。该方法不仅超越了GPT-4o（5美元）的基线性能，还通过管道方法将GPT-4o旗舰模型的$α$准确性提升了9.7%。

> The effectiveness of search systems is evaluated using relevance labels that indicate the usefulness of documents for specific queries and users. While obtaining these relevance labels from real users is ideal, scaling such data collection is challenging. Consequently, third-party annotators are employed, but their inconsistent accuracy demands costly auditing, training, and monitoring. We propose an LLM-based modular classification pipeline that divides the relevance assessment task into multiple stages, each utilising different prompts and models of varying sizes and capabilities. Applied to TREC Deep Learning (TREC-DL), one of our approaches showed an 18.4% Krippendorff's $α$ accuracy increase over OpenAI's GPT-4o mini while maintaining a cost of about 0.2 USD per million input tokens, offering a more efficient and scalable solution for relevance assessment. This approach beats the baseline performance of GPT-4o (5 USD). With a pipeline approach, even the accuracy of the GPT-4o flagship model, measured in $α$, could be improved by 9.7%.

[Arxiv](https://arxiv.org/abs/2501.14296)