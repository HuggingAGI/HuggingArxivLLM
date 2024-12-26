# CodeV：借助视觉数据解决问题

发布时间：2024年12月23日

`LLM应用` `软件工程` `GitHub 问题解决`

> CodeV: Issue Resolving with Visual Data

# 摘要

> 近年来，大型语言模型（LLMs）发展迅猛，其在软件工程中的应用拓展到了更为复杂的库级任务。在这些任务中，GitHub 问题的解决是关键挑战。尽管近来的方法在该任务上有所进展，但它们聚焦于问题中的文本数据，而忽视了视觉数据。然而，这种视觉数据对于解决问题极为关键，因为它能传递仅靠文本无法传递的额外知识。我们提出了 CodeV，这是首个利用视觉数据来增强 LLMs 解决问题能力的方法。CodeV 遵循数据处理和补丁生成这两个阶段的流程来解决每个问题。为了评估 CodeV，我们构建了用于视觉问题解决的基准——Visual SWE-bench。通过大量实验，我们展示了 CodeV 的有效性，同时也为利用视觉数据解决 GitHub 问题提供了宝贵的见解。

> Large Language Models (LLMs) have advanced rapidly in recent years, with their applications in software engineering expanding to more complex repository-level tasks. GitHub issue resolving is a key challenge among these tasks. While recent approaches have made progress on this task, they focus on textual data within issues, neglecting visual data. However, this visual data is crucial for resolving issues as it conveys additional knowledge that text alone cannot. We propose CodeV, the first approach to leveraging visual data to enhance the issue-resolving capabilities of LLMs. CodeV resolves each issue by following a two-phase process: data processing and patch generation. To evaluate CodeV, we construct a benchmark for visual issue resolving, namely Visual SWE-bench. Through extensive experiments, we demonstrate the effectiveness of CodeV, as well as provide valuable insights into leveraging visual data to resolve GitHub issues.

[Arxiv](https://arxiv.org/abs/2412.17315)