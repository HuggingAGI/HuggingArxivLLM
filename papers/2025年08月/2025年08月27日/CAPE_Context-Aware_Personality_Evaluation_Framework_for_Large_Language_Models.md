# CAPE：大型语言模型的上下文感知人格评估框架

发布时间：2025年08月27日

`LLM应用` `基础理论`

> CAPE: Context-Aware Personality Evaluation Framework for Large Language Models

# 摘要

> 传统用于评估人类的心理测量测试，如今正被用来评估大型语言模型（LLMs）的行为特征。然而，现有研究采用无上下文模式，孤立地回答每个问题，以排除上下文干扰。我们将这种方式称为“迪士尼世界测试”——一种脱离现实应用的人工场景，而现实中对话历史恰恰会塑造回答。为弥合这一鸿沟，我们首次提出适用于LLMs的上下文感知人格评估（CAPE）框架，该框架整合了先前的对话交互。为深入剖析上下文的影响，我们引入新指标来量化LLM回答的一致性，而一致性正是人类行为的一项基本特质。
  我们对7个LLM的详尽实验显示，对话历史通过上下文学习提升了回答的一致性，同时也会引发人格偏移，其中GPT-3.5-Turbo和GPT-4-Turbo的偏差尤为显著。GPT模型对问题顺序不敏感，表现稳健；而Gemini-1.5-Flash和Llama-8B则对问题顺序极为敏感。此外，GPT模型的回答既源于其内在人格特质，也受先前交互影响；而Gemini-1.5-Flash和Llama-8B则严重依赖先前交互。最后，将该框架应用于角色扮演智能体（RPAs）后发现，依赖上下文的人格偏移不仅提高了回答的一致性，还能更好地贴合人类判断。我们的代码与数据集已公开，地址为：https://github.com/jivnesh/CAPE

> Psychometric tests, traditionally used to assess humans, are now being applied to Large Language Models (LLMs) to evaluate their behavioral traits. However, existing studies follow a context-free approach, answering each question in isolation to avoid contextual influence. We term this the Disney World test, an artificial setting that ignores real-world applications, where conversational history shapes responses. To bridge this gap, we propose the first Context-Aware Personality Evaluation (CAPE) framework for LLMs, incorporating prior conversational interactions. To thoroughly analyze the influence of context, we introduce novel metrics to quantify the consistency of LLM responses, a fundamental trait in human behavior.
  Our exhaustive experiments on 7 LLMs reveal that conversational history enhances response consistency via in-context learning but also induces personality shifts, with GPT-3.5-Turbo and GPT-4-Turbo exhibiting extreme deviations. While GPT models are robust to question ordering, Gemini-1.5-Flash and Llama-8B display significant sensitivity. Moreover, GPT models response stem from their intrinsic personality traits as well as prior interactions, whereas Gemini-1.5-Flash and Llama--8B heavily depend on prior interactions. Finally, applying our framework to Role Playing Agents (RPAs) shows context-dependent personality shifts improve response consistency and better align with human judgments. Our code and datasets are publicly available at: https://github.com/jivnesh/CAPE

[Arxiv](https://arxiv.org/abs/2508.20385)