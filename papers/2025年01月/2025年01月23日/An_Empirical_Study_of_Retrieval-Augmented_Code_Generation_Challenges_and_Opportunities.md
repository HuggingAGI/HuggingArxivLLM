# 检索增强代码生成的实证研究：挑战与机遇

发布时间：2025年01月23日

`RAG

理由：这篇论文主要讨论了在代码生成任务中使用检索增强框架（Retrieval-Augmented Generation, RAG）来提升预训练模型的性能。论文详细研究了检索代码的质量和利用对生成结果的影响，并提出了具体的改进方法。因此，这篇论文的核心内容与RAG相关，属于RAG分类。` `软件开发` `代码生成`

> An Empirical Study of Retrieval-Augmented Code Generation: Challenges and Opportunities

# 摘要

> 代码生成的目标是根据自然语言描述自动生成特定编程语言的代码片段。随着深度学习的不断进步，尤其是预训练模型的发展，代码生成任务的性能得到了显著提升。然而，预训练模型在代码生成中面临的主要挑战是自然语言需求与源代码之间的语义鸿沟。为解决这一问题，先前的研究通常采用检索增强框架，通过检索相似代码片段来帮助理解需求并指导生成过程。然而，关于该框架在代码生成中的应用，尤其是其对最终生成结果的影响以及具体使用方式，目前缺乏系统的研究。本文选择了三种流行的预训练代码模型——CodeGen、UniXcoder和CodeT5，评估了检索代码的质量和利用对检索增强框架的影响。分析表明，检索增强框架能够有效提升现有预训练模型的性能。我们建议使用BM25和顺序集成融合，因其便捷性和优越性能。此外，提取相关代码草图的草图填充融合可以进一步提升模型性能。我们还通过实验研究了检索增强框架对大型语言模型在代码生成中的影响，验证了该框架的有效性，并探讨了框架内各阶段性能提升与计算成本之间的权衡。

> Code generation aims to automatically generate code snippets of specific programming language according to natural language descriptions. The continuous advancements in deep learning, particularly pre-trained models, have empowered the code generation task to achieve remarkable performance. One main challenge of pre-trained models for code generation is the semantic gap between natural language requirements and source code. To address the issue, prior studies typically adopt a retrieval-augmented framework for the task, where the similar code snippets collected by a retrieval process can be leveraged to help understand the requirements and provide guidance for the generation process. However, there is a lack of systematic study on the application of this framework for code generation, including the impact of the final generated results and the specific usage of the framework. In this paper, we choose three popular pre-trained code models, namely CodeGen, UniXcoder, and CodeT5, to assess the impact of the quality and utilization of retrieved code on the retrieval-augmented framework. Our analysis shows that the retrieval-augmented framework is beneficial for improving the performance of the existing pre-trained models. We also provide suggestions on the utilization of the retrieval-augmented code generation framework: BM25 and Sequential Integration Fusion are recommended due to their convenience and superior performance. Sketch Filling Fusion, which extracts a sketch of relevant code, could help the model improve its performance further. Additionally, we conduct experiments to investigate the influence of the retrieval-augmented framework on large language models for code generation, showing the effectiveness of the framework, and we discuss the trade-off between performance improvement and computational costs in each phase within the framework.

[Arxiv](https://arxiv.org/abs/2501.13742)