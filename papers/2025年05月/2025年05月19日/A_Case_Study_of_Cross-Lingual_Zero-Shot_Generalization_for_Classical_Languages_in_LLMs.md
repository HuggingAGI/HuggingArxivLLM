# 大型语言模型在古典语言跨语言零样本泛化中的案例研究

发布时间：2025年05月19日

`LLM应用` `古典语言` `问答系统`

> A Case Study of Cross-Lingual Zero-Shot Generalization for Classical Languages in LLMs

# 摘要

> 大型语言模型（LLMs）在多种任务和语言中展现了卓越的泛化能力。本研究聚焦于梵文、古希腊语和拉丁语这三种古典语言的自然语言理解，旨在探究影响跨语言零样本泛化的因素。首先，我们在命名实体识别和机器翻译到英语的任务中发现，尽管LLMs在处理域外数据时表现优异，但较小规模的模型往往表现挣扎，尤其是在处理小众或抽象的实体类型时。此外，我们专注于梵文，提供了一个基于事实的问答（QA）数据集，并展示通过检索增强生成方法引入上下文信息，能显著提升模型性能。然而，我们观察到较小规模的LLMs在这些QA任务上表现明显下降。这些结果表明，模型规模是影响跨语言泛化的重要因素。假设所使用的模型如GPT-4o和Llama-3.1并未在古典语言上进行指令微调，我们的发现为LLMs在这些语言上的泛化能力及其在古典研究中的潜在应用提供了有价值的见解。

> Large Language Models (LLMs) have demonstrated remarkable generalization capabilities across diverse tasks and languages. In this study, we focus on natural language understanding in three classical languages -- Sanskrit, Ancient Greek and Latin -- to investigate the factors affecting cross-lingual zero-shot generalization. First, we explore named entity recognition and machine translation into English. While LLMs perform equal to or better than fine-tuned baselines on out-of-domain data, smaller models often struggle, especially with niche or abstract entity types. In addition, we concentrate on Sanskrit by presenting a factoid question-answering (QA) dataset and show that incorporating context via retrieval-augmented generation approach significantly boosts performance. In contrast, we observe pronounced performance drops for smaller LLMs across these QA tasks. These results suggest model scale as an important factor influencing cross-lingual generalization. Assuming that models used such as GPT-4o and Llama-3.1 are not instruction fine-tuned on classical languages, our findings provide insights into how LLMs may generalize on these languages and their consequent utility in classical studies.

[Arxiv](https://arxiv.org/abs/2505.13173)