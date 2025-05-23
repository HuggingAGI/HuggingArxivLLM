# ScholarBench：面向学术情境的双语抽象、理解与推理评测基准

发布时间：2025年05月22日

`LLM应用

理由：这篇论文介绍了一个新的基准测试ScholarBench，用于评估大型语言模型在学术推理任务中的表现。基准测试本身属于应用层面，因为它展示了如何将LLM应用于特定的学术任务，并提供了评估其能力的标准。因此，它被归类为LLM应用。` `基准测试`

> ScholarBench: A Bilingual Benchmark for Abstraction, Comprehension, and Reasoning Evaluation in Academic Contexts

# 摘要

> # 学术基准测试
大型语言模型（LLMs）在特定领域知识评估中，传统基准测试在处理复杂学术任务时表现有限。为此，我们推出	exttt{ScholarBench}——一个专注于深度专业知识与复杂学术问题解决的基准测试，旨在全面评估LLMs的学术推理能力。该基准测试基于学术文献，聚焦于更具专业性和逻辑复杂性的场景，涵盖五种独特问题类型，并通过三步构建流程精心打造。

与现有基准测试不同，	exttt{ScholarBench}的独特之处在于，它首次全面评估LLMs在八个不同研究领域中的抽象、理解及推理能力。为确保评估数据的高质量，我们为每个领域量身定制了特定的示例属性，并设计了与各领域研究方法和话语结构相匹配的问题。此外，	exttt{ScholarBench}还作为一个英韩双语数据集运行，支持对LLMs在两种语言中的语言能力进行同步评估。

目前，该基准测试包含5,031个韩语示例和5,309个英语示例。即便是像o3-mini这样先进的模型，在这一基准测试中的平均得分也只有0.543，这充分说明了	exttt{ScholarBench}的挑战性与高标准。

> Prior benchmarks for evaluating the domain-specific knowledge of large language models (LLMs) lack the scalability to handle complex academic tasks. To address this, we introduce \texttt{ScholarBench}, a benchmark centered on deep expert knowledge and complex academic problem-solving, which evaluates the academic reasoning ability of LLMs and is constructed through a three-step process. \texttt{ScholarBench} targets more specialized and logically complex contexts derived from academic literature, encompassing five distinct problem types. Unlike prior benchmarks, \texttt{ScholarBench} evaluates the abstraction, comprehension, and reasoning capabilities of LLMs across eight distinct research domains. To ensure high-quality evaluation data, we define category-specific example attributes and design questions that are aligned with the characteristic research methodologies and discourse structures of each domain. Additionally, this benchmark operates as an English-Korean bilingual dataset, facilitating simultaneous evaluation for linguistic capabilities of LLMs in both languages. The benchmark comprises 5,031 examples in Korean and 5,309 in English, with even state-of-the-art models like o3-mini achieving an average evaluation score of only 0.543, demonstrating the challenging nature of this benchmark.

[Arxiv](https://arxiv.org/abs/2505.16566)