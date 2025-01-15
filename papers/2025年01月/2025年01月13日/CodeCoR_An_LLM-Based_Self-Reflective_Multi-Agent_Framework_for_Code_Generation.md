# CodeCoR: 基于LLM的自反思多智能体代码生成框架

发布时间：2025年01月13日

`Agent

理由：这篇论文主要讨论了一个多智能体框架（CodeCoR），用于代码生成和测试。该框架通过多个智能体（如生成提示、代码、测试用例和修复建议的智能体）协作完成任务，并通过自反思机制评估和改进每个智能体的表现。虽然涉及大型语言模型（LLMs），但论文的核心在于多智能体系统的设计和应用，因此应归类为Agent。` `软件开发` `代码生成`

> CodeCoR: An LLM-Based Self-Reflective Multi-Agent Framework for Code Generation

# 摘要

> # 摘要
代码生成旨在自动生成满足自然语言需求的代码。尽管像ChatGPT这样的大型语言模型（LLMs）在这一领域表现出色，但它们往往无法确保生成代码的语法和语义正确性。为此，研究人员提出了多智能体框架，通过不同提示引导LLMs分析任务、生成代码并执行测试。然而，由于代码生成依赖于每个智能体的表现，工作流的性能并不稳定。为解决这一问题，我们提出了CodeCoR，一个自反思的多智能体框架，用于评估每个智能体及其协作效果。CodeCoR中的四个智能体分别生成提示、代码、测试用例和修复建议，并剔除低质量输出。生成的代码在本地环境中测试，未通过的代码由修复智能体处理，编码智能体根据修复建议重新生成代码。最终，通过最多测试用例的代码将返回给用户。我们在HumanEval、HumanEval-ET、MBPP和MBPP-ET四个数据集上的实验表明，CodeCoR显著优于现有基线（如CodeCoT和MapCoder），平均Pass@1得分为77.8%。

> Code generation aims to produce code that fulfills requirements written in natural languages automatically. Large language Models (LLMs) like ChatGPT have demonstrated promising effectiveness in this area. Nonetheless, these LLMs often fail to ensure the syntactic and semantic correctness of the generated code. Recently, researchers proposed multi-agent frameworks that guide LLMs with different prompts to analyze programming tasks, generate code, perform testing in a sequential workflow. However, the performance of the workflow is not robust as the code generation depends on the performance of each agent. To address this challenge, we propose CodeCoR, a self-reflective multi-agent framework that evaluates the effectiveness of each agent and their collaborations. Specifically, for a given task description, four agents in CodeCoR generate prompts, code, test cases, and repair advice, respectively. Each agent generates more than one output and prunes away the low-quality ones. The generated code is tested in the local environment: the code that fails to pass the generated test cases is sent to the repair agent and the coding agent re-generates the code based on repair advice. Finally, the code that passes the most number of generated test cases is returned to users. Our experiments on four widely used datasets, HumanEval, HumanEval-ET, MBPP, and MBPP-ET, demonstrate that CodeCoR significantly outperforms existing baselines (e.g., CodeCoT and MapCoder), achieving an average Pass@1 score of 77.8%.

[Arxiv](https://arxiv.org/abs/2501.07811)