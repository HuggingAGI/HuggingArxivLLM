# 语义变异视角下的代码 LLM 基准测试再评估

发布时间：2025年06月20日

`LLM应用

理由：这篇论文探讨了在代码基准测试中提示敏感性的问题，分析了提示设计对大型语言模型评估的影响，并提出了一种改进的方法。这属于对大型语言模型应用的研究，因此归类为LLM应用。` `软件工程` `代码基准测试`

> Re-Evaluating Code LLM Benchmarks Under Semantic Mutation

# 摘要

> 在大型语言模型（LLMs）时代，代码基准测试已成为软件工程领域的重要研究方向，并被从业者广泛应用。这些基准测试用于评估大型语言模型在特定代码相关任务（如代码理解和生成）上的性能。在构建代码基准测试时，提示设计是一个关键步骤。然而，现有代码基准测试通常每个任务仅依赖单一提示模板，这导致了提示敏感性问题：轻微的提示变化可能导致显著的性能波动，从而影响模型能力评估的可靠性。

尽管先前研究探讨过提示敏感性，但其实验设计和发现主要局限于传统自然语言处理（NLP）任务。本文通过实证研究，深入探讨代码基准测试中的提示敏感性问题。我们首先提出了一种通用框架，该框架在保持提示模板语义和结构尽可能一致的前提下，对其进行修改。基于此框架，我们在10个代表性的开源大型语言模型上，针对8个代码基准测试任务进行了广泛实验，每个任务采用了100个语义相似的提示模板。随后，我们采用多种统计指标分析评估结果，重点关注模型的绝对和相对性能表现。研究发现，即使是轻微的提示变化也可能引发显著的性能波动。此外，我们还观察到，这种变化可能导致不同模型性能排名的不一致。这些发现凸显了在设计未来代码基准测试时考虑提示敏感性的必要性，以确保对大型语言模型能力的评估更加可靠和准确。

> In the era of large language models (LLMs), code benchmarks have become an important research area in software engineering and are widely used by practitioners. These benchmarks evaluate the performance of LLMs on specific code-related tasks, such as code understanding and generation. A critical step in constructing code benchmarks is the design of prompts. However, as existing code benchmarks typically rely on a single prompt template per task, they are prone to the issue of prompt sensitivity, where minor prompt variations could result in substantial performance variations, leading to unreliable evaluations of model capabilities.
  While previous studies have explored prompt sensitivity, their experimental designs and findings are limited to traditional natural language processing (NLP) tasks. In this paper, we present an empirical study to investigate prompt sensitivity in code benchmarks. We first propose a general framework that modifies prompt templates in a manner that preserves both their semantics and their structure as much as possible. Based on the framework, we conduct extensive experiments across eight code benchmark tasks on 10 representative open-source LLMs, with each task featuring 100 semantically similar prompt templates. We then analyze the evaluation results using various statistical metrics, focusing on both absolute and relative model performance. Our findings suggest that even slight prompt variations can lead to significant shifts in performance. Additionally, we observe that such variations can introduce inconsistencies in the performance rankings across different models. These insights highlight the need for considering prompt sensitivity when designing future code benchmarks, to ensure more reliable and accurate evaluation of LLM capabilities.

[Arxiv](https://arxiv.org/abs/2506.17369)