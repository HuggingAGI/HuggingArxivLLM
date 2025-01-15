# 借助元记忆机制提升LLMs的无数据代码生成能力

发布时间：2025年01月14日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来提升代码生成的性能，特别是在缺乏专门训练数据的情况下。论文提出了一个新颖的框架（M^2WF），旨在通过自主生成、评估和利用合成示例来提升LLMs的一次性代码生成能力。这属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `软件开发` `人工智能`

> Leveraging Metamemory Mechanisms for Enhanced Data-Free Code Generation in LLMs

# 摘要

> # 摘要
大型语言模型（LLMs）在自动化代码生成中的应用因其高效和灵活而备受瞩目。然而，现实中的编码任务或基准测试（如HumanEval和StudentEval）往往缺乏专门的训练数据，这对依赖参考示例的少样本提示方法提出了挑战。受人类元记忆（一种涉及回忆和评估的认知过程）的启发，我们提出了一个新颖的框架（M^2WF），旨在提升LLMs的一次性代码生成能力。该框架使LLMs能够自主生成、评估并利用合成示例，从而提升代码生成的可靠性和性能。与以往方法不同，它减少了对精选数据的依赖，并能灵活适应多种编码场景。实验结果显示，该框架在编码基准测试中表现显著提升，为无数据环境提供了一个可扩展且稳健的解决方案。代码和框架将在GitHub和HuggingFace上开源。

> Automated code generation using large language models (LLMs) has gained attention due to its efficiency and adaptability. However, real-world coding tasks or benchmarks like HumanEval and StudentEval often lack dedicated training datasets, challenging existing few-shot prompting approaches that rely on reference examples. Inspired by human metamemory-a cognitive process involving recall and evaluation-we present a novel framework (namely M^2WF) for improving LLMs' one-time code generation. This approach enables LLMs to autonomously generate, evaluate, and utilize synthetic examples to enhance reliability and performance. Unlike prior methods, it minimizes dependency on curated data and adapts flexibly to various coding scenarios. Our experiments demonstrate significant improvements in coding benchmarks, offering a scalable and robust solution for data-free environments. The code and framework will be publicly available on GitHub and HuggingFace.

[Arxiv](https://arxiv.org/abs/2501.07892)