# # 并行提示：从大型语言模型查询中提取并行性

发布时间：2025年06月23日

`LLM应用` `LLM服务`

> PARALLELPROMPT: Extracting Parallelism from Large Language Model Queries

# 摘要

> LLM服务系统通常将用户提示视为整体输入，通过解码技巧或跨查询批处理来优化推理。然而，许多实际提示中包含潜在的语义并行性——即可以分解为独立执行的子任务的结构，从而在保持语义的同时减少延迟。我们引入了PARALLELPROMPT，这是首个用于衡量自然用户提示中查询内并行性的基准。我们的数据集包含来自公共LLM聊天记录的37,000多个实际提示，每个提示都带有结构化模式注释，捕捉任务模板、共享上下文和迭代输入。这些模式通过基于规则的多语言验证辅助LLM提示提取。为了评估分解的优势，我们提供了一个执行套件，用于基准测试串行与并行策略，测量延迟、结构遵循度和语义保真度。我们的结果显示，超过75%的整理数据集可以成功解析查询内并行性，使翻译、理解、比较分析等任务的速度提升高达5倍，同时质量下降最小。通过发布此基准、整理管道和评估套件，我们为研究LLM服务管道中的结构感知执行提供了首个标准化测试床。

> LLM serving systems typically treat user prompts as monolithic inputs, optimizing inference through decoding tricks or inter-query batching. However, many real-world prompts contain latent semantic parallelism--decomposable structures where subtasks can be executed independently to reduce latency while preserving meaning. We introduce PARALLELPROMPT, the first benchmark for measuring intra-query parallelism in natural user prompts. Our dataset comprises over 37,000 real-world prompts from public LLM chat logs, each annotated with a structured schema capturing task templates, shared context, and iteration inputs. These schemas are extracted using LLM-assisted prompting with rule-based multilingual validation. To evaluate the benefits of decomposition, we provide an execution suite that benchmarks serial vs. parallel strategies, measuring latency, structural adherence, and semantic fidelity. Our results show that intra-query parallelism can be successfully parsed in over 75% of curated datasets, unlocking up to 5x speedups on tasks like translation, comprehension, and comparative analysis, with minimal quality degradation. By releasing this benchmark, curation pipeline, and evaluation suite, we provide the first standardized testbed for studying structure-aware execution in LLM serving pipelines.

[Arxiv](https://arxiv.org/abs/2506.18728)