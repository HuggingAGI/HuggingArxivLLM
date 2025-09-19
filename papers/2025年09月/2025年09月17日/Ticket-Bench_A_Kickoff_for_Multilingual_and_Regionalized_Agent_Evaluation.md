# Ticket-Bench：多语言与区域化智能体评估的开端

发布时间：2025年09月17日

`Agent` `零售与电商`

> Ticket-Bench: A Kickoff for Multilingual and Regionalized Agent Evaluation

# 摘要

> 大型语言模型（LLMs）正越来越多地被部署为面向任务的智能体，其成功与否取决于它们在真实多语言环境下生成准确函数调用的能力。然而，现有的智能体评估在很大程度上忽视了文化和语言多样性，往往依赖单语或简单翻译的基准测试。为此，我们引入了Ticket-Bench——一个面向任务场景的多语言智能体评估基准。该基准模拟足球票购买场景，涵盖葡萄牙语、英语、西班牙语、德语、意大利语及法语六种主要语言，并通过本地化的球队、城市和用户资料设计，提升了场景的真实感。我们对众多商业及开源LLM进行了评估，重点衡量其跨语言的函数调用准确性与一致性。结果显示，GPT-5、Qwen3-235B等面向推理的模型虽性能领先，但仍存在显著的跨语言差异。这些发现凸显了构建具有文化意识的多语言基准的必要性，以指导稳健LLM智能体的开发。

> Large language models (LLMs) are increasingly deployed as task-oriented agents, where success depends on their ability to generate accurate function calls under realistic, multilingual conditions. However, existing agent evaluations largely overlook cultural and linguistic diversity, often relying on monolingual or naively translated benchmarks. We introduce Ticket-Bench, a benchmark for multilingual agent evaluation in task-oriented scenarios. Ticket-Bench simulates the domain of soccer ticket purchases across six major languages: Portuguese, English, Spanish, German, Italian, and French. Using localized teams, cities, and user profiles to provide a higher level of realism. We evaluate a wide range of commercial and open-source LLMs, measuring function-calling accuracy and consistency across languages. Results show that reasoning-oriented models (e.g., GPT-5, Qwen3-235B) dominate performance but still exhibit notable cross-lingual disparities. These findings underscore the need for culturally aware, multilingual benchmarks to guide the development of robust LLM agents.

[Arxiv](https://arxiv.org/abs/2509.14477)