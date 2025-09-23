# RephQA：评估大型语言模型在公共卫生问答中的可读性

发布时间：2025年09月19日

`LLM应用` `医疗健康`

> RephQA: Evaluating Readability of Large Language Models in Public Health Question Answering

# 摘要

> 大型语言模型（LLMs）为解决复杂医疗难题带来了希望。然而，尽管以往多数研究聚焦于提升准确性与推理能力，开发高效医疗智能体的一大瓶颈却在于LLM生成内容的可读性——尤其是能否用通俗易懂的方式向非医学背景人群解答公共卫生问题。为此，我们提出RephQA基准，专门用于评估LLMs在公共卫生问答（QA）场景下的可读性表现。该基准包含533组经专家评审的问答对，源自27个信息源、覆盖13个主题，同时设有代理多项选择题（用于评估信息充分性）及两项可读性指标：Flesch-Kincaid年级水平与专业术语得分。对25个LLM模型的测试表明，多数模型未能达标，暴露出推理能力与有效沟通间的显著鸿沟。针对这一问题，我们探索了四种可读性增强策略：标准提示、思维链提示、群体相对策略优化（GRPO）及令牌适配变体。其中，令牌适配GRPO策略表现最优，为开发更实用、更亲民的公共卫生智能体奠定了基础。这些发现为打造更实用的公共卫生智能体迈出了关键一步。

> Large Language Models (LLMs) hold promise in addressing complex medical problems. However, while most prior studies focus on improving accuracy and reasoning abilities, a significant bottleneck in developing effective healthcare agents lies in the readability of LLM-generated responses, specifically, their ability to answer public health problems clearly and simply to people without medical backgrounds. In this work, we introduce RephQA, a benchmark for evaluating the readability of LLMs in public health question answering (QA). It contains 533 expert-reviewed QA pairs from 27 sources across 13 topics, and includes a proxy multiple-choice task to assess informativeness, along with two readability metrics: Flesch-Kincaid grade level and professional score. Evaluation of 25 LLMs reveals that most fail to meet readability standards, highlighting a gap between reasoning and effective communication. To address this, we explore four readability-enhancing strategies-standard prompting, chain-of-thought prompting, Group Relative Policy Optimization (GRPO), and a token-adapted variant. Token-adapted GRPO achieves the best results, advancing the development of more practical and user-friendly public health agents. These results represent a step toward building more practical agents for public health.

[Arxiv](https://arxiv.org/abs/2509.16360)