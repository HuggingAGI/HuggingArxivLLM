# TeleMath：评估大型语言模型在电信数学问题求解能力的基准测试

发布时间：2025年06月12日

`LLM应用`

> TeleMath: A Benchmark for Large Language Models in Telecom Mathematical Problem Solving

# 摘要

> 人工智能在电信领域的蓬勃发展，引发了人们对大型语言模型（LLMs）解决领域特定、数学密集型任务能力的广泛关注。尽管LLMs在一般数学推理方面取得了显著进步，但其在信号处理、网络优化和性能分析等专业领域的有效性仍待深入探索。为填补这一研究空白，我们推出了TeleMath——首个专注于评估LLMs解决电信领域数值解数学问题能力的基准数据集。该数据集包含500个问答（QnA）对，覆盖了电信领域的广泛主题。本文详细介绍了我们从主题专家精心设计的问题种子开始的QnA生成管道。对多种开源LLMs的评估表明，在TeleMath上表现最佳的模型是那些专门针对数学或逻辑推理设计的近期模型。相比之下，通用模型，即便参数规模庞大，也往往难以应对这些挑战。为促进研究进展，我们已公开发布了数据集和评估代码，便于结果的复现和未来研究的开展。

> The increasing adoption of artificial intelligence in telecommunications has raised interest in the capability of Large Language Models (LLMs) to address domain-specific, mathematically intensive tasks. Although recent advancements have improved the performance of LLMs in general mathematical reasoning, their effectiveness within specialized domains, such as signal processing, network optimization, and performance analysis, remains largely unexplored. To address this gap, we introduce TeleMath, the first benchmark dataset specifically designed to evaluate LLM performance in solving mathematical problems with numerical solutions in the telecommunications domain. Comprising 500 question-answer (QnA) pairs, TeleMath covers a wide spectrum of topics in the telecommunications field. This paper outlines the proposed QnAs generation pipeline, starting from a selected seed of problems crafted by Subject Matter Experts. The evaluation of a wide range of open-source LLMs reveals that best performance on TeleMath is achieved by recent models explicitly designed for mathematical or logical reasoning. In contrast, general-purpose models, even those with a large number of parameters, often struggle with these challenges. We have released the dataset and the evaluation code to ease result reproducibility and support future research.

[Arxiv](https://arxiv.org/abs/2506.10674)