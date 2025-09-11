# 低资源微调：十亿参数指令微调模型赋能多任务结构化信息抽取

发布时间：2025年09月10日

`LLM应用` `金融科技` `法律科技`

> Low-Resource Fine-Tuning for Multi-Task Structured Information Extraction with a Billion-Parameter Instruction-Tuned Model

# 摘要

> 在金融合规报告、法律文档分析和多语言知识库构建等领域，小型团队往往难以部署大型语言模型（LLMs）进行结构化数据提取——不仅因为运行大型模型成本高昂，准备大规模高质量数据集也颇具挑战。目前多数指令微调研究聚焦于70亿参数及以上的模型，而对于小得多的模型在低资源、多任务场景下能否稳定工作，相关证据却十分匮乏。本研究推出ETLCH：这是一款基于LLaMA的10亿参数模型，通过低秩适应（LoRA）在每个任务仅用几百到一千个样本进行了微调，可用于JSON抽取、知识图谱抽取和命名实体识别。尽管模型规模不大，ETLCH却在多数评估指标上超越了强劲基线，即便在数据量最少的情况下也展现出显著性能提升。这些发现证实：精心调优的小型模型能以极低计算成本输出稳定准确的结构化结果，为资源受限环境打造经济高效且可靠的信息提取流程。

> Deploying large language models (LLMs) for structured data extraction in domains such as financial compliance reporting, legal document analytics, and multilingual knowledge base construction is often impractical for smaller teams due to the high cost of running large architectures and the difficulty of preparing large, high-quality datasets. Most recent instruction-tuning studies focus on seven-billion-parameter or larger models, leaving limited evidence on whether much smaller models can work reliably under low-resource, multi-task conditions. This work presents ETLCH, a billion-parameter LLaMA-based model fine-tuned with low-rank adaptation on only a few hundred to one thousand samples per task for JSON extraction, knowledge graph extraction, and named entity recognition. Despite its small scale, ETLCH outperforms strong baselines across most evaluation metrics, with substantial gains observed even at the lowest data scale. These findings demonstrate that well-tuned small models can deliver stable and accurate structured outputs at a fraction of the computational cost, enabling cost-effective and reliable information extraction pipelines in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2509.08381)