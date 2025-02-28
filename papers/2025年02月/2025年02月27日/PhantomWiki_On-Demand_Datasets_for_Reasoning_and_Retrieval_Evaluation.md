# PhantomWiki：按需推理与检索评估的数据集

发布时间：2025年02月27日

`LLM应用

摘要中提到的PhantomWiki用于评估LLM的推理和检索能力，属于应用层面的评估工具。`

> PhantomWiki: On-Demand Datasets for Reasoning and Retrieval Evaluation

# 摘要

> 高质量基准测试是评估大型语言模型（LLMs）推理与检索能力的关键。然而，为这一目的整理数据集并非一劳永逸的解决方案，因为它们容易受到数据泄漏和夸大性能结果的影响。为了解决这些挑战，我们提出了PhantomWiki：一个生成独特且事实一致的文档语料库以及多样化问答对的流水线。与之前的工作不同，PhantomWiki 既不是固定的数据集，也不是基于任何现有数据。相反，为每次评估生成一个新的PhantomWiki实例。我们通过调整问题难度和语料库规模来分别解开推理和检索能力，并发现PhantomWiki数据集对前沿LLMs极具挑战性。因此，我们为推理、检索和工具使用能力的分离评估贡献了一个可扩展且抗数据泄漏的框架。我们的代码可在https://github.com/kilian-group/phantom-wiki获取。

> High-quality benchmarks are essential for evaluating reasoning and retrieval capabilities of large language models (LLMs). However, curating datasets for this purpose is not a permanent solution as they are prone to data leakage and inflated performance results. To address these challenges, we propose PhantomWiki: a pipeline to generate unique, factually consistent document corpora with diverse question-answer pairs. Unlike prior work, PhantomWiki is neither a fixed dataset, nor is it based on any existing data. Instead, a new PhantomWiki instance is generated on demand for each evaluation. We vary the question difficulty and corpus size to disentangle reasoning and retrieval capabilities respectively, and find that PhantomWiki datasets are surprisingly challenging for frontier LLMs. Thus, we contribute a scalable and data leakage-resistant framework for disentangled evaluation of reasoning, retrieval, and tool-use abilities. Our code is available at https://github.com/kilian-group/phantom-wiki.

[Arxiv](https://arxiv.org/abs/2502.20377)