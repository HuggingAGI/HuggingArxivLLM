# 探究提示和外部工具在大型语言模型幻觉率方面所起的作用

发布时间：2024年10月25日

`LLM应用`

> Investigating the Role of Prompting and External Tools in Hallucination Rates of Large Language Models

# 摘要

> 大型语言模型（LLMs）是基于大量人类可读文本语料库训练而成的强大计算模型，能够实现通用的语言理解与生成。因其在各类自然语言处理（NLP）任务中的卓越表现，LLMs 在工业和学术界均备受瞩目。然而，LLMs 常出现不准确的情况，即所谓的“幻觉”。提示工程，即设计和制定让 LLMs 执行特定任务的指令的过程，已成为缓解幻觉现象的关键手段。本文对不同的提示策略和框架进行了全面的实证评估，以减少 LLMs 中的幻觉。多种提示技术被应用于广泛的基准数据集，以评估每种方法的准确性和幻觉率。此外，本文还探究了工具调用代理（借助外部工具增强其语言生成能力之外能力的 LLMs）对相同基准中幻觉率的影响。研究发现，最优的提示技术取决于问题类型，且在降低幻觉方面，较简单的技术往往比复杂的方法更有效。而且，由于外部工具使用的复杂性增加，LLM 代理可能会呈现出显著更高的幻觉率。

> Large Language Models (LLMs) are powerful computational models trained on extensive corpora of human-readable text, enabling them to perform general-purpose language understanding and generation. LLMs have garnered significant attention in both industry and academia due to their exceptional performance across various natural language processing (NLP) tasks. Despite these successes, LLMs often produce inaccuracies, commonly referred to as hallucinations. Prompt engineering, the process of designing and formulating instructions for LLMs to perform specific tasks, has emerged as a key approach to mitigating hallucinations. This paper provides a comprehensive empirical evaluation of different prompting strategies and frameworks aimed at reducing hallucinations in LLMs. Various prompting techniques are applied to a broad set of benchmark datasets to assess the accuracy and hallucination rate of each method. Additionally, the paper investigates the influence of tool-calling agents (LLMs augmented with external tools to enhance their capabilities beyond language generation) on hallucination rates in the same benchmarks. The findings demonstrate that the optimal prompting technique depends on the type of problem, and that simpler techniques often outperform more complex methods in reducing hallucinations. Furthermore, it is shown that LLM agents can exhibit significantly higher hallucination rates due to the added complexity of external tool usage.

[Arxiv](https://arxiv.org/abs/2410.19385)