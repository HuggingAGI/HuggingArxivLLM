# CharacterBench: 大型语言模型角色定制性能评估

发布时间：2024年12月16日

`LLM应用

理由：这篇论文主要讨论了如何评估大型语言模型（LLMs）在角色扮演对话中的角色定制能力，并提出了一个新的基准测试CharacterBench。论文的核心是LLMs在特定应用场景（角色扮演对话）中的表现和评估方法，因此属于LLM应用类别。` `对话系统`

> CharacterBench: Benchmarking Character Customization of Large Language Models

# 摘要

> # 摘要
基于角色的对话（角色扮演）让用户能够自由定制角色进行互动，这通常依赖于大型语言模型（LLMs），因此需要评估LLMs的角色定制能力。然而，现有基准测试往往只涉及单一角色类别或评估有限维度，难以确保稳健的评估。此外，响应中角色特征的稀疏性使得基于特征的生成评估既低效又无效。为此，我们提出了CharacterBench，这是最大的双语生成基准测试，包含22,859个人工标注样本，涵盖25个角色类别中的3,956个角色。我们定义了6个方面的11个维度，并根据角色特征在响应中的表现将其分为稀疏和密集维度。通过为每个维度设计定制查询，我们能够有效且高效地评估角色响应。此外，我们还开发了CharacterJudge模型，用于低成本且稳定的评估。实验表明，它优于GPT-4等最先进的自动评估模型，并且我们的基准测试具有优化LLMs角色定制的潜力。代码库地址：https://github.com/thu-coai/CharacterBench。

> Character-based dialogue (aka role-playing) enables users to freely customize characters for interaction, which often relies on LLMs, raising the need to evaluate LLMs' character customization capability. However, existing benchmarks fail to ensure a robust evaluation as they often only involve a single character category or evaluate limited dimensions. Moreover, the sparsity of character features in responses makes feature-focused generative evaluation both ineffective and inefficient. To address these issues, we propose CharacterBench, the largest bilingual generative benchmark, with 22,859 human-annotated samples covering 3,956 characters from 25 detailed character categories. We define 11 dimensions of 6 aspects, classified as sparse and dense dimensions based on whether character features evaluated by specific dimensions manifest in each response. We enable effective and efficient evaluation by crafting tailored queries for each dimension to induce characters' responses related to specific dimensions. Further, we develop CharacterJudge model for cost-effective and stable evaluations. Experiments show its superiority over SOTA automatic judges (e.g., GPT-4) and our benchmark's potential to optimize LLMs' character customization. Our repository is at https://github.com/thu-coai/CharacterBench.

[Arxiv](https://arxiv.org/abs/2412.11912)