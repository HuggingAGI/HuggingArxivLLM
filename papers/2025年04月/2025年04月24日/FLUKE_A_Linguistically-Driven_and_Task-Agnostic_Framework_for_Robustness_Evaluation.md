# FLUKE：一种基于语言学驱动且具有任务无关性的鲁棒性评估框架

发布时间：2025年04月24日

`LLM应用

理由：这篇论文提出了一种评估框架FLUKE，用于评估大型语言模型（LLMs）的鲁棒性。它通过系统性地引入语言变化来测试模型的表现，展示了框架在不同任务上的应用，并分析了模型的脆弱性。这属于LLM的应用和评估，因此归类为LLM应用。` `模型评估`

> FLUKE: A Linguistically-Driven and Task-Agnostic Framework for Robustness Evaluation

# 摘要

> 我们提出了一种名为FLUKE（基于语言驱动且任务无关的鲁棒性评估框架）的通用框架，通过系统性地对测试数据进行最小变化来评估模型的鲁棒性。FLUKE在语言层面引入了受控变化，从拼写到方言和风格的变化，并利用大型语言模型（LLMs）结合人工验证来生成修改。我们通过在四种多样化的NLP任务上评估微调模型和LLMs，展示了FLUKE的实用性，并揭示了以下几点：(1) 语言变化对任务的影响高度依赖于具体任务，某些测试对某些任务至关重要，但对其他任务则无关紧要；(2) 虽然LLMs的整体鲁棒性优于微调模型，但它们仍然对某些语言变化表现出显著的脆弱性；(3) 所有模型在大多数任务上对否定修饰表现出显著的脆弱性。这些发现突显了系统性鲁棒性测试在理解模型行为方面的重要性。

> We present FLUKE (Framework for LingUistically-driven and tasK-agnostic robustness Evaluation), a task-agnostic framework for assessing model robustness through systematic minimal variations of test data. FLUKE introduces controlled variations across linguistic levels - from orthography to dialect and style varieties - and leverages large language models (LLMs) with human validation to generate modifications. We demonstrate FLUKE's utility by evaluating both fine-tuned models and LLMs across four diverse NLP tasks, and reveal that (1) the impact of linguistic variations is highly task-dependent, with some tests being critical for certain tasks but irrelevant for others; (2) while LLMs have better overall robustness compared to fine-tuned models, they still exhibit significant brittleness to certain linguistic variations; (3) all models show substantial vulnerability to negation modifications across most tasks. These findings highlight the importance of systematic robustness testing for understanding model behaviors.

[Arxiv](https://arxiv.org/abs/2504.17311)