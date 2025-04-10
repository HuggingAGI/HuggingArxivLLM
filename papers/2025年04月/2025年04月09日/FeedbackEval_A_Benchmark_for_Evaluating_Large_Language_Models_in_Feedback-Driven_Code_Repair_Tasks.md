# # FeedbackEval：用于反馈驱动代码修复任务的大型语言模型评估基准

发布时间：2025年04月09日

`LLM应用` `软件工程` `代码修复`

> FeedbackEval: A Benchmark for Evaluating Large Language Models in Feedback-Driven Code Repair Tasks

# 摘要

> 代码修复是软件开发中的基本任务，能够有效促进 bug 修复和软件维护。尽管大型语言模型（LLMs）在自动化代码修复方面展现了巨大潜力，但它们对多种反馈类型的理解与利用能力仍有待深入。为解决这一问题，我们提出了 FeedbackEval，这是一个系统化的基准测试，用于评估 LLMs 在代码修复任务中的反馈理解与表现。我们对 GPT-4o、Claude-3.5、Gemini-1.5、GLM-4 和 Qwen2.5 等五种先进 LLMs 进行了全面实证研究，评估它们在单次迭代与多次迭代代码修复场景下的行为表现。研究结果显示，结构化反馈，尤其是测试反馈形式，能够带来最高的修复成功率，而无结构反馈效果则明显较弱。迭代反馈进一步提升了修复性能，但在两到三轮之后，边际效益逐渐减弱。此外，提示结构至关重要：在提示中加入文档字符串、上下文信息和明确指导方针能显著改善修复效果，而基于角色扮演、思考链和少量样本的提示策略在单次迭代场景中提供的益处有限。这项研究不仅引入了一个稳健的基准测试，还提供了实用见解，有助于推进基于反馈的 LLMs 代码修复能力的理解与开发。

> Code repair is a fundamental task in software development, facilitating efficient bug resolution and software maintenance. Although large language models (LLMs) have demonstrated considerable potential in automated code repair, their ability to comprehend and effectively leverage diverse types of feedback remains insufficiently understood. To bridge this gap, we introduce FeedbackEval, a systematic benchmark for evaluating LLMs' feedback comprehension and performance in code repair tasks. We conduct a comprehensive empirical study on five state-of-the-art LLMs, including GPT-4o, Claude-3.5, Gemini-1.5, GLM-4, and Qwen2.5, to evaluate their behavior under both single-iteration and iterative code repair settings. Our results show that structured feedback, particularly in the form of test feedback, leads to the highest repair success rates, while unstructured feedback proves significantly less effective. Iterative feedback further enhances repair performance, though the marginal benefit diminishes after two or three rounds. Moreover, prompt structure is shown to be critical: incorporating docstrings, contextual information, and explicit guidelines substantially improves outcomes, whereas persona-based, chain-of-thought, and few-shot prompting strategies offer limited benefits in single-iteration scenarios. This work introduces a robust benchmark and delivers practical insights to advance the understanding and development of feedback-driven code repair using LLMs.

[Arxiv](https://arxiv.org/abs/2504.06939)