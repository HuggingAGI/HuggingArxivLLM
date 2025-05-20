# # ReEx-SQL：一种基于执行感知强化学习的文本到SQL推理方法

发布时间：2025年05月19日

`LLM应用

理由：这篇论文探讨了如何在Text-to-SQL任务中利用执行反馈来提升大型语言模型的生成准确性。通过提出ReEx-SQL框架，论文展示了如何在生成过程中动态调整推理路径，从而提高模型的性能和鲁棒性。这一研究属于将LLM应用于特定任务的范畴，因此归类为LLM应用。` `数据管理`

> ReEx-SQL: Reasoning with Execution-Aware Reinforcement Learning for Text-to-SQL

# 摘要

> 在 Text-to-SQL 任务中，执行反馈对于指导大型语言模型（LLMs）准确推理并生成可靠 SQL 查询至关重要。然而，现有方法将执行反馈仅作为事后修正或选择的信号，未能将其融入生成过程。这一局限性使得模型无法在推理错误发生时及时调整，最终导致查询准确性和鲁棒性下降。为了解决这一问题，我们提出了 ReEx-SQL（基于执行感知的强化学习推理），一个用于 Text-to-SQL 的框架。该框架使模型能够在解码过程中与数据库进行交互，并根据执行反馈动态调整推理路径。ReEx-SQL 通过在推理过程中穿插中间 SQL 执行，形成一种执行感知的推理范式，从而实现上下文敏感的动态修订。它借助带有标记标签的结构化提示和分步展开策略，将执行反馈有机整合到生成的每个阶段。为了监督策略学习，我们开发了一个复合奖励函数，其中包括探索奖励，以鼓励模型与数据库进行有效交互。此外，ReEx-SQL 采用基于树的解码策略，支持探索性推理，从而实现替代推理路径的动态扩展。值得注意的是，ReEx-SQL 在 7B 规模下分别在 Spider 和 BIRD 数据集上达到了 88.8% 和 64.9% 的性能，分别超过了标准推理基线 2.7% 和 2.6%。它还表现出强大的鲁棒性，在 Spider-Realistic 数据集上实现了 85.2% 的领先性能。此外，其树结构解码在效率和性能上优于线性解码，在 BIRD 开发集上将推理时间减少了 51.9%。

> In Text-to-SQL, execution feedback is essential for guiding large language models (LLMs) to reason accurately and generate reliable SQL queries. However, existing methods treat execution feedback solely as a post-hoc signal for correction or selection, failing to integrate it into the generation process. This limitation hinders their ability to address reasoning errors as they occur, ultimately reducing query accuracy and robustness. To address this issue, we propose ReEx-SQL (Reasoning with Execution-Aware Reinforcement Learning), a framework for Text-to-SQL that enables models to interact with the database during decoding and dynamically adjust their reasoning based on execution feedback. ReEx-SQL introduces an execution-aware reasoning paradigm that interleaves intermediate SQL execution into reasoning paths, facilitating context-sensitive revisions. It achieves this through structured prompts with markup tags and a stepwise rollout strategy that integrates execution feedback into each stage of generation. To supervise policy learning, we develop a composite reward function that includes an exploration reward, explicitly encouraging effective database interaction. Additionally, ReEx-SQL adopts a tree-based decoding strategy to support exploratory reasoning, enabling dynamic expansion of alternative reasoning paths. Notably, ReEx-SQL achieves 88.8% on Spider and 64.9% on BIRD at the 7B scale, surpassing the standard reasoning baseline by 2.7% and 2.6%, respectively. It also shows robustness, achieving 85.2% on Spider-Realistic with leading performance. In addition, its tree-structured decoding improves efficiency and performance over linear decoding, reducing inference time by 51.9% on the BIRD development set.

[Arxiv](https://arxiv.org/abs/2505.12768)