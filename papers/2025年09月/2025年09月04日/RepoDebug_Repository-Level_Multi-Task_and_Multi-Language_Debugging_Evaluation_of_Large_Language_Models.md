# RepoDebug：大型语言模型的仓库级多任务多语言调试评估

发布时间：2025年09月04日

`LLM应用` `基础理论`

> RepoDebug: Repository-Level Multi-Task and Multi-Language Debugging Evaluation of Large Language Models

# 摘要

> 大型语言模型（LLMs）在代码调试领域展现出卓越能力，尤其在自动程序修复方面，有望大幅节省开发者时间并提升工作效率。为推动代码调试技术发展，调试数据集已取得显著进步。然而，现有数据集多聚焦于评估LLM的函数级代码修复能力，却忽略了更复杂、更贴近实际的仓库级场景，导致我们对LLM在仓库级调试中面临的挑战认识不全面。尽管已有部分仓库级数据集被提出，但它们普遍存在任务、语言及错误类型多样性不足等局限。为此，本文提出RepoDebug——一个多任务、多语言的仓库级代码调试数据集，涵盖22种错误子类型，支持8种常用编程语言和3类调试任务。此外，我们对10个LLM进行了评估，结果显示即使表现最佳的Claude 3.5 Sonnect模型，在仓库级调试中仍表现欠佳。

> Large Language Models (LLMs) have exhibited significant proficiency in code debugging, especially in automatic program repair, which may substantially reduce the time consumption of developers and enhance their efficiency. Significant advancements in debugging datasets have been made to promote the development of code debugging. However, these datasets primarily focus on assessing the LLM's function-level code repair capabilities, neglecting the more complex and realistic repository-level scenarios, which leads to an incomplete understanding of the LLM's challenges in repository-level debugging. While several repository-level datasets have been proposed, they often suffer from limitations such as limited diversity of tasks, languages, and error types. To mitigate this challenge, this paper introduces RepoDebug, a multi-task and multi-language repository-level code debugging dataset with 22 subtypes of errors that supports 8 commonly used programming languages and 3 debugging tasks. Furthermore, we conduct evaluation experiments on 10 LLMs, where Claude 3.5 Sonnect, the best-performing model, still cannot perform well in repository-level debugging.

[Arxiv](https://arxiv.org/abs/2509.04078)