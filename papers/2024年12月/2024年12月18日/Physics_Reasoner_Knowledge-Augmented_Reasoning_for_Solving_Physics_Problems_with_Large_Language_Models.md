# 物理学推理器：借助大型语言模型解决物理问题的知识增强型推理

发布时间：2024年12月18日

`LLM应用`

> Physics Reasoner: Knowledge-Augmented Reasoning for Solving Physics Problems with Large Language Models

# 摘要

> 物理学问题是推理的重要一环，需要复杂的推理能力和丰富的物理知识。然而，现有的大型语言模型（LLMs）常因知识缺乏或知识运用不当而表现不佳。为解决这些问题，我们提出了物理推理器，这是一个借助LLMs解决物理问题的知识增强框架。具体而言，该框架构建了全面的公式集来提供明确的物理知识，并利用包含详细说明的检查表来引导有效的知识运用。即给定一个物理问题，物理推理器通过问题分析、公式检索和引导推理这三个阶段来解决。在此过程中，检查表用于增强LLMs在分析和推理阶段的自我完善能力。从实践来看，物理推理器缓解了知识不足和运用不当的问题，在SciBench上达到了最先进的性能，平均准确率提高了5.8%。

> Physics problems constitute a significant aspect of reasoning, necessitating complicated reasoning ability and abundant physics knowledge. However, existing large language models (LLMs) frequently fail due to a lack of knowledge or incorrect knowledge application. To mitigate these issues, we propose Physics Reasoner, a knowledge-augmented framework to solve physics problems with LLMs. Specifically, the proposed framework constructs a comprehensive formula set to provide explicit physics knowledge and utilizes checklists containing detailed instructions to guide effective knowledge application. Namely, given a physics problem, Physics Reasoner solves it through three stages: problem analysis, formula retrieval, and guided reasoning. During the process, checklists are employed to enhance LLMs' self-improvement in the analysis and reasoning stages. Empirically, Physics Reasoner mitigates the issues of insufficient knowledge and incorrect application, achieving state-of-the-art performance on SciBench with an average accuracy improvement of 5.8%.

[Arxiv](https://arxiv.org/abs/2412.13791)