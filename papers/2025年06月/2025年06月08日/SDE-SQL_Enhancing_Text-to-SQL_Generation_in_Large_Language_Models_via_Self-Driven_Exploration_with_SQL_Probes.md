# SDE-SQL：通过SQL探针的自我驱动探索提升大型语言模型中的文本到SQL生成能力

发布时间：2025年06月08日

`LLM应用` `数据库` `数据处理`

> SDE-SQL: Enhancing Text-to-SQL Generation in Large Language Models via Self-Driven Exploration with SQL Probes

# 摘要

> 大型语言模型在Text-to-SQL任务上的性能有了显著提升。然而，现有方法通常依赖于推理时提供的静态预处理数据库信息，这限制了模型对数据库内容的全面理解。由于缺乏动态交互，模型只能依赖于固定的人工提供的上下文，无法自主探索数据。为了解决这一问题，我们提出了SDE-SQL框架，使模型能够在推理过程中进行自我驱动的数据库探索。通过生成和执行SQL探针，模型能够主动从数据库中检索信息，并逐步更新对数据的理解。与传统方法不同，SDE-SQL在零-shot设置下运行，无需依赖任何问题-SQL对作为上下文示例。在BIRD基准测试中，使用Qwen2.5-72B-Instruct进行评估时，SDE-SQL在执行准确性方面比原始基线提高了8.02%，在没有监督微调（SFT）或模型集成的开源模型方法中建立了新的最先进水平。此外，通过SFT，SDE-SQL的性能可以进一步提升，带来额外0.52%的改进。

> Recent advancements in large language models (LLMs) have significantly improved performance on the Text-to-SQL task. However, prior approaches typically rely on static, pre-processed database information provided at inference time, which limits the model's ability to fully understand the database contents. Without dynamic interaction, LLMs are constrained to fixed, human-provided context and cannot autonomously explore the underlying data. To address this limitation, we propose SDE-SQL, a framework that enables large language models to perform self-driven exploration of databases during inference. This is accomplished by generating and executing SQL probes, which allow the model to actively retrieve information from the database and iteratively update its understanding of the data. Unlike prior methods, SDE-SQL operates in a zero-shot setting, without relying on any question-SQL pairs as in-context demonstrations. When evaluated on the BIRD benchmark with Qwen2.5-72B-Instruct, SDE-SQL achieves an 8.02% relative improvement in execution accuracy over the vanilla Qwen2.5-72B-Instruct baseline, establishing a new state-of-the-art among methods based on open-source models without supervised fine-tuning (SFT) or model ensembling. Moreover, with SFT, the performance of SDE-SQL can be further enhanced, yielding an additional 0.52% improvement.

[Arxiv](https://arxiv.org/abs/2506.07245)