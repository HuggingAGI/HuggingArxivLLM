# 伪代码注入魔法：赋能LLMs应对图计算任务

发布时间：2025年01月23日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）来解决图计算任务，提出了一个名为PIE的框架，该框架通过伪代码注入和LLM推理来生成高效代码。论文的核心在于如何将LLMs应用于具体的图计算任务中，并优化其推理成本。因此，这篇论文属于LLM应用类别。` `图计算` `算法优化`

> Pseudocode-Injection Magic: Enabling LLMs to Tackle Graph Computational Tasks

# 摘要

> # 摘要
图计算任务因其复杂性，往往需要开发高级算法来有效解决。随着大型语言模型（LLMs）的崛起，研究者开始探索其在解决此类任务中的潜力。然而，现有方法受限于LLMs对复杂图结构的理解能力不足和高昂的推理成本，难以应对大规模图计算。受人类解决图问题方法的启发，我们提出了PIE框架（Pseudocode-Injection-Enhanced LLM Reasoning for Graph Computational Tasks），该框架包含三个核心步骤：问题理解、提示设计和代码生成。在PIE中，LLMs负责理解问题并提取关键信息以生成代码，而图结构分析和代码执行则由解释器完成。我们通过在提示中注入任务相关的伪代码，进一步辅助LLMs生成高效代码，并采用低成本试错技术确保代码正确执行。与现有方法不同，PIE仅在代码生成阶段调用LLM，生成的代码可重复使用，大幅降低了推理成本。大量实验证明，PIE在准确性和计算效率上均优于现有方法。

> Graph computational tasks are inherently challenging and often demand the development of advanced algorithms for effective solutions. With the emergence of large language models (LLMs), researchers have begun investigating their potential to address these tasks. However, existing approaches are constrained by LLMs' limited capability to comprehend complex graph structures and their high inference costs, rendering them impractical for handling large-scale graphs. Inspired by human approaches to graph problems, we introduce a novel framework, PIE (Pseudocode-Injection-Enhanced LLM Reasoning for Graph Computational Tasks), which consists of three key steps: problem understanding, prompt design, and code generation. In this framework, LLMs are tasked with understanding the problem and extracting relevant information to generate correct code. The responsibility for analyzing the graph structure and executing the code is delegated to the interpreter. We inject task-related pseudocodes into the prompts to further assist the LLMs in generating efficient code. We also employ cost-effective trial-and-error techniques to ensure that the LLM-generated code executes correctly. Unlike other methods that require invoking LLMs for each individual test case, PIE only calls the LLM during the code generation phase, allowing the generated code to be reused and significantly reducing inference costs. Extensive experiments demonstrate that PIE outperforms existing baselines in terms of both accuracy and computational efficiency.

[Arxiv](https://arxiv.org/abs/2501.13731)