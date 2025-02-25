# 乌尔都语LLaMA 1.0：数据集整理、预处理及低资源环境下的评估

发布时间：2025年02月24日

`LLM应用` `机器翻译`

> UrduLLaMA 1.0: Dataset Curation, Preprocessing, and Evaluation in Low-Resource Settings

# 摘要

> 多语言大型语言模型在乌尔都语等低资源语言上表现不尽如人意。本文推出UrduLLaMA 1.0，该模型基于开源的Llama-3.1-8B-Instruct架构，通过1.28亿乌尔都语令牌的持续预训练，充分展现了乌尔都语的丰富多样性。为了提升指令理解和翻译能力，我们采用低秩适应（LoRA）技术，在4.1万个乌尔都语指令和约5万个英乌翻译对上进行微调。在三个机器翻译数据集上的评估结果显示，UrduLLaMA 1.0显著超越现有最佳模型，为乌尔都语LLM树立了新标杆。这表明，即使在数据和计算资源有限的情况下，针对性适应策略也能有效应对低资源语言的独特挑战。

> Multilingual Large Language Models (LLMs) often provide suboptimal performance on low-resource languages like Urdu. This paper introduces UrduLLaMA 1.0, a model derived from the open-source Llama-3.1-8B-Instruct architecture and continually pre-trained on 128 million Urdu tokens, capturing the rich diversity of the language. To enhance instruction-following and translation capabilities, we leverage Low-Rank Adaptation (LoRA) to fine tune the model on 41,000 Urdu instructions and approximately 50,000 English-Urdu translation pairs. Evaluation across three machine translation datasets demonstrates significant performance improvements compared to state-of-the-art (SOTA) models, establishing a new benchmark for Urdu LLMs. These findings underscore the potential of targeted adaptation strategies with limited data and computational resources to address the unique challenges of low-resource languages.

[Arxiv](https://arxiv.org/abs/2502.16961)