# Uhura：评估低资源非洲语言中科学问题回答及真实性的基准

发布时间：2024年12月01日

`LLM应用` `低资源语言`

> Uhura: A Benchmark for Evaluating Scientific Question Answering and Truthfulness in Low-Resource African Languages

# 摘要

> 对于大型语言模型（LLMs）在知识密集型任务和事实准确性方面的评估，往往主要聚焦于高资源语言，原因在于低资源语言（LRLs）的数据集十分稀缺。在本文中，我们推出了 Uhura 这一新基准，它着眼于六种不同类型非洲语言中的两项任务，是通过对现有英语基准进行人工翻译而创建的。第一个数据集 Uhura-ARC-Easy 由多项选择的科学问题构成。第二个 Uhura-TruthfulQA 是一个安全基准，用于测试模型在诸如健康、法律、金融和政治等主题上的真实性。我们指出了为低资源语言创建高技术含量基准所面临的挑战，并简述了应对策略。我们的评估显示，像 GPT-4o 和 o1-preview 这样的专有模型、Claude 模型与 Meta 的 LLaMA 和 Google 的 Gemma 等开源模型之间存在显著的性能差距。另外，所有模型在英语中的表现都优于在非洲语言中的表现。这些结果表明，语言模型在回答科学问题时存在困难，在低资源的非洲语言中更容易出现错误断言。我们的发现凸显了在低资源语言环境中持续提升多语言 LM 能力的必要性，以保障在现实场景中安全可靠地运用。我们将 Uhura 基准和 Uhura 平台开源，以推动低资源语言的 NLP 进一步研究与发展。

> Evaluations of Large Language Models (LLMs) on knowledge-intensive tasks and factual accuracy often focus on high-resource languages primarily because datasets for low-resource languages (LRLs) are scarce. In this paper, we present Uhura -- a new benchmark that focuses on two tasks in six typologically-diverse African languages, created via human translation of existing English benchmarks. The first dataset, Uhura-ARC-Easy, is composed of multiple-choice science questions. The second, Uhura-TruthfulQA, is a safety benchmark testing the truthfulness of models on topics including health, law, finance, and politics. We highlight the challenges creating benchmarks with highly technical content for LRLs and outline mitigation strategies. Our evaluation reveals a significant performance gap between proprietary models such as GPT-4o and o1-preview, and Claude models, and open-source models like Meta's LLaMA and Google's Gemma. Additionally, all models perform better in English than in African languages. These results indicate that LMs struggle with answering scientific questions and are more prone to generating false claims in low-resource African languages. Our findings underscore the necessity for continuous improvement of multilingual LM capabilities in LRL settings to ensure safe and reliable use in real-world contexts. We open-source the Uhura Benchmark and Uhura Platform to foster further research and development in NLP for LRLs.

[Arxiv](https://arxiv.org/abs/2412.00948)