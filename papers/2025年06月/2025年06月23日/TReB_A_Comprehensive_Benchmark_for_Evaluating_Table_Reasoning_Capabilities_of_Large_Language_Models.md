# TReB：一个全面基准测试，用于评估大型语言模型的表格推理能力。

发布时间：2025年06月23日

`LLM应用

理由：这篇论文探讨了大型语言模型在处理表格结构化数据方面的应用和挑战，并提出了一种新的评估基准。它属于LLM应用的范畴，因为它专注于将LLMs应用于特定的领域（表格数据处理），并评估其性能。` `数据处理` `数据分析`

> TReB: A Comprehensive Benchmark for Evaluating Table Reasoning Capabilities of Large Language Models

# 摘要

> 企业与行业中绝大多数的数据都存储在表格、数据库和数据仓库中。大型语言模型（LLMs）在处理表格结构化数据时面临巨大挑战，原因在于其隐含的语义、固有的复杂性以及结构化的特性。其中一个主要挑战是缺乏一个有效的评估基准，能够公平地反映LLMs在广泛表格推理能力上的表现。本文将填补这一空白，提出一个全面的表格推理进化基准TReB，该基准涵盖了浅层表格理解能力和深层表格推理能力，共计26个子任务。我们通过迭代的数据处理流程构建了一个高质量的数据集。我们创建了一个评估框架，利用三种不同的推理模式（TCoT、PoT和ICoT）来稳健地衡量表格推理能力。进一步地，我们使用该框架对20多个最先进的LLMs进行了基准测试，并证明了其有效性。实验结果表明，现有的LLMs在处理复杂且现实的表格相关任务上仍有显著的提升空间。数据集和评估框架均已公开，数据集托管在[HuggingFace]，框架托管在[GitHub]。

> The majority of data in businesses and industries is stored in tables, databases, and data warehouses. Reasoning with table-structured data poses significant challenges for large language models (LLMs) due to its hidden semantics, inherent complexity, and structured nature. One of these challenges is lacking an effective evaluation benchmark fairly reflecting the performances of LLMs on broad table reasoning abilities. In this paper, we fill in this gap, presenting a comprehensive table reasoning evolution benchmark, TReB, which measures both shallow table understanding abilities and deep table reasoning abilities, a total of 26 sub-tasks. We construct a high quality dataset through an iterative data processing procedure. We create an evaluation framework to robustly measure table reasoning capabilities with three distinct inference modes, TCoT, PoT and ICoT. Further, we benchmark over 20 state-of-the-art LLMs using this frame work and prove its effectiveness. Experimental results reveal that existing LLMs still have significant room for improvement in addressing the complex and real world Table related tasks. Both the dataset and evaluation framework are publicly available, with the dataset hosted on [HuggingFace] and the framework on [GitHub].

[Arxiv](https://arxiv.org/abs/2506.18421)