# MDCrow：借助大型语言模型实现分子动力学工作流的自动化处理

发布时间：2025年02月13日

`LLM应用

理由：这篇论文展示了如何将大型语言模型（LLM）应用于自动化分子动力学（MD）模拟工作流程。MDCrow 是一个基于 LLM 的智能助手，通过链式思考处理文件、设置模拟、分析输出，并从文献和数据库中检索信息。这属于 LLM 在科学自动化任务中的具体应用。` `生物化学` `科学自动化`

> MDCrow: Automating Molecular Dynamics Workflows with Large Language Models

# 摘要

> 分子动力学（MD）模拟是理解生物分子系统的关键，但自动化仍具挑战。大型语言模型（LLM）的最新进展通过基于LLM的代理成功实现了复杂科学任务的自动化。本文介绍MDCrow——一款智能型LLM助手，能够自动化MD工作流程。MDCrow借助40个专家设计工具，通过链式思考来处理文件、设置模拟、分析输出，并从文献和数据库中检索信息。我们在25个不同难度和子任务需求的任务中评估了MDCrow的表现，并测试了其在难度和提示风格上的鲁棒性。GPT-4o在复杂任务中表现稳定，紧随其后的是开源模型llama3-405b。值得注意的是，提示风格对最优模型影响不大，但对小型模型有显著影响。

> Molecular dynamics (MD) simulations are essential for understanding biomolecular systems but remain challenging to automate. Recent advances in large language models (LLM) have demonstrated success in automating complex scientific tasks using LLM-based agents. In this paper, we introduce MDCrow, an agentic LLM assistant capable of automating MD workflows. MDCrow uses chain-of-thought over 40 expert-designed tools for handling and processing files, setting up simulations, analyzing the simulation outputs, and retrieving relevant information from literature and databases. We assess MDCrow's performance across 25 tasks of varying required subtasks and difficulty, and we evaluate the agent's robustness to both difficulty and prompt style. \texttt{gpt-4o} is able to complete complex tasks with low variance, followed closely by \texttt{llama3-405b}, a compelling open-source model. While prompt style does not influence the best models' performance, it has significant effects on smaller models.

[Arxiv](https://arxiv.org/abs/2502.09565)