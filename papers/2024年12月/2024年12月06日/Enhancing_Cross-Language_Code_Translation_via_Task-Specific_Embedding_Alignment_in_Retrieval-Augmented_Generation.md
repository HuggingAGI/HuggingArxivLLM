# 在检索增强生成中借助特定任务的嵌入对齐来提升跨语言代码翻译

发布时间：2024年12月06日

`RAG` `代码翻译` `软件开发`

> Enhancing Cross-Language Code Translation via Task-Specific Embedding Alignment in Retrieval-Augmented Generation

# 摘要

> 我们推出了一种全新的办法，把针对特定任务的嵌入对齐融入检索增强生成（RAG）框架，以此强化从 Fortran 到 C++的跨语言代码翻译。传统的检索手段采用与下游任务无关的通用嵌入，而我们的策略直接让检索模型与以 CodeBLEU 指标衡量的最大化翻译质量这一目标相契合。这种对齐能保证嵌入对于特定的代码翻译任务在语义和语法上都富有意义。我们的方法是从 Stack-V2 数据集中构建包含 25,000 个 Fortran 代码片段的数据集，并借助 LLaMA 3.1-8B 语言模型生成相应的 C++翻译。我们算出生成的翻译与真实示例之间的成对 CodeBLEU 分数，以此捕捉细粒度的相似性。这些分数在对比学习框架中充当监督信号，我们优化嵌入模型来检索对提升语言模型翻译性能最有利的 Fortran-C++对。通过把这些经 CodeBLEU 优化的嵌入整合进 RAG 框架，我们的方法相比使用通用嵌入的方法，显著提升了检索的准确性和代码生成的质量。在 HPC Fortran2C++数据集中，我们的方法将平均 CodeBLEU 分数由 0.64 提升至 0.73，实现了 14%的相对提高。在数值配方数据集中，我们看到从 0.52 增长到 0.60，意味着 15%的相对提升。关键在于，这些成果是在未对语言模型进行任何微调的情况下达成的，凸显了我们方法的高效性和实用性。

> We introduce a novel method to enhance cross-language code translation from Fortran to C++ by integrating task-specific embedding alignment into a Retrieval-Augmented Generation (RAG) framework. Unlike conventional retrieval approaches that utilize generic embeddings agnostic to the downstream task, our strategy aligns the retrieval model directly with the objective of maximizing translation quality, as quantified by the CodeBLEU metric. This alignment ensures that the embeddings are semantically and syntactically meaningful for the specific code translation task. Our methodology involves constructing a dataset of 25,000 Fortran code snippets sourced from Stack-V2 dataset and generating their corresponding C++ translations using the LLaMA 3.1-8B language model. We compute pairwise CodeBLEU scores between the generated translations and ground truth examples to capture fine-grained similarities. These scores serve as supervision signals in a contrastive learning framework, where we optimize the embedding model to retrieve Fortran-C++ pairs that are most beneficial for improving the language model's translation performance. By integrating these CodeBLEU-optimized embeddings into the RAG framework, our approach significantly enhances both retrieval accuracy and code generation quality over methods employing generic embeddings. On the HPC Fortran2C++ dataset, our method elevates the average CodeBLEU score from 0.64 to 0.73, achieving a 14% relative improvement. On the Numerical Recipes dataset, we observe an increase from 0.52 to 0.60, marking a 15% relative improvement. Importantly, these gains are realized without any fine-tuning of the language model, underscoring the efficiency and practicality of our approach.

[Arxiv](https://arxiv.org/abs/2412.05159)