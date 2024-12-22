# CodeRepoQA：一个针对软件工程问答的大规模基准

发布时间：2024年12月19日

`LLM应用` `软件工程` `软件开发`

> CodeRepoQA: A Large-scale Benchmark for Software Engineering Question Answering

# 摘要

> 在这项工作中，我们推出了 CodeRepoQA，这是专门为评估软件工程领域中存储库级问答能力打造的大规模基准。它涵盖五种编程语言和众多场景，能对语言模型进行全方位评估。为构建此数据集，我们从 GitHub（最大的代码托管与协作平台）的 30 个知名存储库抓取数据，并精心筛选原始数据。总之，CodeRepoQA 是拥有 585,687 个条目的多轮问答基准，涵盖各类软件工程场景，平均每个条目有 6.62 个对话轮次。
    我们在该数据集上对十个热门大型语言模型进行评估，并给出深入分析。我们发现，在软件工程领域，LLM 的问答能力仍有局限，中等长度的上下文更有助于 LLM 发挥性能。整个基准可在 https://github.com/kinesiatricssxilm14/CodeRepoQA 公开获取。

> In this work, we introduce CodeRepoQA, a large-scale benchmark specifically designed for evaluating repository-level question-answering capabilities in the field of software engineering. CodeRepoQA encompasses five programming languages and covers a wide range of scenarios, enabling comprehensive evaluation of language models. To construct this dataset, we crawl data from 30 well-known repositories in GitHub, the largest platform for hosting and collaborating on code, and carefully filter raw data. In total, CodeRepoQA is a multi-turn question-answering benchmark with 585,687 entries, covering a diverse array of software engineering scenarios, with an average of 6.62 dialogue turns per entry.
  We evaluate ten popular large language models on our dataset and provide in-depth analysis. We find that LLMs still have limitations in question-answering capabilities in the field of software engineering, and medium-length contexts are more conducive to LLMs' performance. The entire benchmark is publicly available at https://github.com/kinesiatricssxilm14/CodeRepoQA.

[Arxiv](https://arxiv.org/abs/2412.14764)