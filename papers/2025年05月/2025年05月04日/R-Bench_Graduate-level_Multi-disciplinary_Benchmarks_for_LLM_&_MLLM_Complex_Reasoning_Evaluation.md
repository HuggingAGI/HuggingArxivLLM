# **R-Bench**：面向大型语言模型（LLM）与多语言大模型（MLLM）的研究生水平跨学科复杂推理评估基准。

发布时间：2025年05月04日

`LLM应用`

> R-Bench: Graduate-level Multi-disciplinary Benchmarks for LLM & MLLM Complex Reasoning Evaluation

# 摘要

> 推理是智能的基石，它能够整合现有知识来解决复杂问题。尽管在推理能力方面取得了显著进展，现有的推理基准测试通常未能严格评估解决复杂现实问题所需的细致推理能力，尤其是在跨学科和多模态情境下。本文介绍了一个研究生水平的跨学科英中双语基准测试，名为推理基准（R-Bench），用于评估语言模型和多模态模型的推理能力。

R-Bench涵盖108个学科的1,094个问题用于语言模型评估，并在英中双语环境下涵盖83个学科的665个问题用于多模态模型测试。这些问题经过精心筛选，以确保难度校准、学科平衡和跨语言对齐，使其成为一个奥运水平的跨学科基准测试。

我们对广泛使用的模型进行了评估，包括OpenAI o1、GPT-4o、DeepSeek-R1等。实验结果表明，先进模型在复杂推理，尤其是多模态推理方面表现不佳。即使是表现最佳的OpenAI o1模型，在我们的多模态评估中也仅达到53.2%的准确率。数据和代码可在[此处](链接)公开获取。

> Reasoning stands as a cornerstone of intelligence, enabling the synthesis of existing knowledge to solve complex problems. Despite remarkable progress, existing reasoning benchmarks often fail to rigorously evaluate the nuanced reasoning capabilities required for complex, real-world problemsolving, particularly in multi-disciplinary and multimodal contexts. In this paper, we introduce a graduate-level, multi-disciplinary, EnglishChinese benchmark, dubbed as Reasoning Bench (R-Bench), for assessing the reasoning capability of both language and multimodal models. RBench spans 1,094 questions across 108 subjects for language model evaluation and 665 questions across 83 subjects for multimodal model testing in both English and Chinese. These questions are meticulously curated to ensure rigorous difficulty calibration, subject balance, and crosslinguistic alignment, enabling the assessment to be an Olympiad-level multi-disciplinary benchmark. We evaluate widely used models, including OpenAI o1, GPT-4o, DeepSeek-R1, etc. Experimental results indicate that advanced models perform poorly on complex reasoning, especially multimodal reasoning. Even the top-performing model OpenAI o1 achieves only 53.2% accuracy on our multimodal evaluation. Data and code are made publicly available at here.

[Arxiv](https://arxiv.org/abs/2505.02018)