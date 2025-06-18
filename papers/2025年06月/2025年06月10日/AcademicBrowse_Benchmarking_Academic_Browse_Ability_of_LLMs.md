# # 学术浏览：评估大型语言模型的学术检索能力

发布时间：2025年06月10日

`LLM应用

理由：这篇论文专注于评估和提升大型语言模型在复杂学术信息检索任务中的性能，属于LLM的应用研究。` `信息检索`

> AcademicBrowse: Benchmarking Academic Browse Ability of LLMs

# 摘要

> 大型语言模型（LLMs）的搜索能力引发了广泛关注。然而，现有的基准测试如OpenAI的BrowseComp主要聚焦于通用搜索场景，未能充分满足学术搜索的特定需求。为此，我们提出了AcademicBrowse——首个专为评估LLMs在学术研究中复杂信息检索能力而设计的数据集。AcademicBrowse具有以下特点：

1. **学术实用性**：问题贴近真实学术学习与研究环境，避免刻意误导模型。
2. **高难度**：答案通常需要至少三次深度搜索才能得出，超越单一模型（如Grok DeepSearch或Gemini Deep Research）的直接输出能力。
3. **简洁性**：通过限制条件确保答案唯一性，并附有清晰来源与简要说明，极大便利后续审核与验证，超越当前国内外缺乏分析性搜索数据集的现状。
4. **广泛覆盖**：涵盖至少15个不同学术学科。

借助AcademicBrowse，我们期望更精确地衡量并推动LLMs在复杂学术信息检索任务中的性能提升。数据集地址：https://huggingface.co/datasets/PKU-DS-LAB/AcademicBrowse

> Large Language Models (LLMs)' search capabilities have garnered significant attention. Existing benchmarks, such as OpenAI's BrowseComp, primarily focus on general search scenarios and fail to adequately address the specific demands of academic search. These demands include deeper literature tracing and organization, professional support for academic databases, the ability to navigate long-tail academic knowledge, and ensuring academic rigor. Here, we proposed AcademicBrowse, the first dataset specifically designed to evaluate the complex information retrieval capabilities of Large Language Models (LLMs) in academic research. AcademicBrowse possesses the following key characteristics: Academic Practicality, where question content closely mirrors real academic learning and research environments, avoiding deliberately misleading models; High Difficulty, with answers that are challenging for single models (e.g., Grok DeepSearch or Gemini Deep Research) to provide directly, often requiring at least three deep searches to derive; Concise Evaluation, where limiting conditions ensure answers are as unique as possible, accompanied by clear sources and brief solution explanations, greatly facilitating subsequent audit and verification, surpassing the current lack of analyzed search datasets both domestically and internationally; and Broad Coverage, as the dataset spans at least 15 different academic disciplines. Through AcademicBrowse, we expect to more precisely measure and promote the performance improvement of LLMs in complex academic information retrieval tasks. The data is available at: https://huggingface.co/datasets/PKU-DS-LAB/AcademicBrowse

[Arxiv](https://arxiv.org/abs/2506.13784)