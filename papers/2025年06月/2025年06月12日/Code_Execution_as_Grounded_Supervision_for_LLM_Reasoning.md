# 代码执行：为大语言模型推理提供基于事实的监督

发布时间：2025年06月12日

`LLM理论` `跨领域`

> Code Execution as Grounded Supervision for LLM Reasoning

# 摘要

> 链式思维（CoT）监督训练已被证实能显著提升大型语言模型（LLMs）的推理能力。然而，如何获取可靠且准确的推理监督仍是一个重大挑战。我们提出了一种创新方法，通过利用程序执行的确定性，生成高质量的CoT监督数据集。与现有方法不同，我们无需昂贵的人工标注或容易出错的LLM生成CoT，而是从代码执行中提取可验证的分步推理轨迹，并将其转化为自然语言的CoT推理。跨领域推理基准的实验结果表明，我们的方法能够有效赋予LLMs跨多种任务的可迁移推理能力。此外，消融研究证实，我们的方法不仅生成高准确性的推理数据，还通过减少无意义的重复和过度思考，在推理过程中显著缩短了整体token长度。

> Training large language models (LLMs) with chain-of-thought (CoT) supervision has proven effective for enhancing their reasoning abilities. However, obtaining reliable and accurate reasoning supervision remains a significant challenge. We propose a scalable method for generating a high-quality CoT supervision dataset by leveraging the determinism of program execution. Unlike existing reasoning dataset generation methods that rely on costly human annotations or error-prone LLM-generated CoT, our approach extracts verifiable, step-by-step reasoning traces from code execution and transforms them into a natural language CoT reasoning. Experiments on reasoning benchmarks across various domains show that our method effectively equips LLMs with transferable reasoning abilities across diverse tasks. Furthermore, the ablation studies validate that our method produces highly accurate reasoning data and reduces overall token length during inference by reducing meaningless repetition and overthinking.

[Arxiv](https://arxiv.org/abs/2506.10343)