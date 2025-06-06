# # 人类类推理对翻译有帮助吗？两个简单实验来验证

发布时间：2025年06月04日

`LLM应用

论文摘要讨论了大型语言模型（LLMs）在翻译任务中的应用，特别是通过链式思维（CoT）推理来分解翻译过程。研究者审视了基于LLM的翻译策略的有效性，并探讨了如何通过提示改进翻译性能。因此，这篇论文属于LLM应用类别。`

> Please Translate Again: Two Simple Experiments on Whether Human-Like Reasoning Helps Translation

# 摘要

> 大型语言模型（LLMs）在许多任务中展现出强大的推理能力，通常通过链式思维（CoT）推理显式分解任务来实现。近期基于LLM的翻译研究设计了手工编写的提示来分解翻译过程，或训练模型以整合中间步骤。例如，~	extit{Translating Step-by-step}~\citep{briakou2024translating}提出了一种多步骤提示，通过分解和优化翻译过程，该方法在WMT24上取得了最新技术水平。在本研究中，我们审视了这一策略的有效性。实证研究表明，我们并未发现明确证据表明翻译性能的提升源于对翻译过程的显式分解，至少对于测试中的模型而言；我们还发现，只需提示LLMs“再次翻译”即可获得比模仿人类逐步推理更好的结果。我们的分析并未否定推理的作用，而是呼吁未来研究探索链式思维在翻译情境中有效性的关键因素。

> Large Language Models (LLMs) demonstrate strong reasoning capabilities for many tasks, often by explicitly decomposing the task via Chain-of-Thought (CoT) reasoning. Recent work on LLM-based translation designs hand-crafted prompts to decompose translation, or trains models to incorporate intermediate steps.~\textit{Translating Step-by-step}~\citep{briakou2024translating}, for instance, introduces a multi-step prompt with decomposition and refinement of translation with LLMs, which achieved state-of-the-art results on WMT24. In this work, we scrutinise this strategy's effectiveness. Empirically, we find no clear evidence that performance gains stem from explicitly decomposing the translation process, at least for the models on test; and we show that simply prompting LLMs to ``translate again'' yields even better results than human-like step-by-step prompting. Our analysis does not rule out the role of reasoning, but instead invites future work exploring the factors for CoT's effectiveness in the context of translation.

[Arxiv](https://arxiv.org/abs/2506.04521)