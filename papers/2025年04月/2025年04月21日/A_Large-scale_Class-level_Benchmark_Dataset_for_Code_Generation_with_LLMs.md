# # 面向大语言模型的代码生成大规模类级别基准数据集
一个专为大语言模型设计的大规模类级别基准数据集，用于代码生成任务。

发布时间：2025年04月21日

`LLM应用` `软件工程`

> A Large-scale Class-level Benchmark Dataset for Code Generation with LLMs

# 摘要

> 大型语言模型（LLMs）在代码生成任务中展现出令人鼓舞的能力，但现有基准测试多聚焦于孤立函数，难以反映现实世界中类级别软件结构的复杂性。为此，我们从13,174个真实开源项目中整理出一个大规模Python类级别数据集，包含842,000余个类骨架，涵盖类和方法签名及文档字符串。我们保留了现实软件开发中关键的结构和上下文依赖关系，并通过添加静态代码指标丰富数据集，支持后续分析。为评估该数据集的实用性，我们使用类骨架作为提示，让GPT-4生成完整类实现。结果显示，LLM生成的类在词汇和结构上与人工编写类高度相似，ROUGE@L、BLEU和TSED平均得分分别为0.80、0.59和0.73。这表明基于真实类骨架构建的结构化提示能显著提升LLM的类级别代码生成性能。该数据集为在现实软件工程场景中对LLMs进行基准测试、训练和优化提供了宝贵资源。

> Recent advancements in large language models (LLMs) have demonstrated promising capabilities in code generation tasks. However, most existing benchmarks focus on isolated functions and fail to capture the complexity of real-world, class-level software structures. To address this gap, we introduce a large-scale, Python class-level dataset curated from $13{,}174$ real-world open-source projects. The dataset contains over 842,000 class skeletons, each including class and method signatures, along with associated docstrings when available. We preserve structural and contextual dependencies critical to realistic software development scenarios and enrich the dataset with static code metrics to support downstream analysis. To evaluate the usefulness of this dataset, we use extracted class skeletons as prompts for GPT-4 to generate full class implementations. Results show that the LLM-generated classes exhibit strong lexical and structural similarity to human-written counterparts, with average ROUGE@L, BLEU, and TSED scores of 0.80, 0.59, and 0.73, respectively. These findings confirm that well-structured prompts derived from real-world class skeletons significantly enhance LLM performance in class-level code generation. This dataset offers a valuable resource for benchmarking, training, and improving LLMs in realistic software engineering contexts.

[Arxiv](https://arxiv.org/abs/2504.15564)