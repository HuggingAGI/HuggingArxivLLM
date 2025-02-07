# 语言模型中时间性事实知识的鲁棒性探讨

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要研究了语言模型在处理时间性事实知识时的鲁棒性，探讨了模型在不同时间粒度上的表现。这属于对语言模型内部机制和能力的理论研究，旨在揭示模型在处理特定类型知识时的局限性。因此，将其归类为“LLM理论”更为合适。` `时间序列分析`

> On the Robustness of Temporal Factual Knowledge in Language Models

# 摘要

> 本文研究了语言模型（LMs）在处理事实知识时的时间鲁棒性。尽管LMs通常能完成简单的事实陈述，但它们处理时间性事实（仅在特定时间段内有效的事实）的能力尚不明确。我们设计了一个受控实验，测试LMs内部时间性事实知识的鲁棒性，并通过流行的Wikidata事实上的提示评估了几个预训练和指令调优的模型，考察它们在不同时间粒度（日、月、年）上的表现。结果显示，即使是像Llama-3.1-70B这样的顶尖模型，也严重缺乏对时间性事实的鲁棒知识，且无法将知识从一个粒度推广到另一个粒度。这些发现揭示了使用LMs作为时间知识库的固有局限性。我们将公开实验的源代码和数据，以便复现。

> This paper explores the temporal robustness of language models (LMs) in handling factual knowledge. While LMs can often complete simple factual statements, their ability to manage temporal facts (those valid only within specific timeframes) remains uncertain. We design a controlled experiment to test the robustness of temporal factual knowledge inside LMs, which we use to evaluate several pretrained and instruction-tuned models using prompts on popular Wikidata facts, assessing their performance across different temporal granularities (Day, Month, and Year). Our findings indicate that even very large state-of-the-art models, such as Llama-3.1-70B, vastly lack robust knowledge of temporal facts. In addition, they are incapable of generalizing their knowledge from one granularity to another. These results highlight the inherent limitations of using LMs as temporal knowledge bases. The source code and data to reproduce our experiments will be released.

[Arxiv](https://arxiv.org/abs/2502.01220)