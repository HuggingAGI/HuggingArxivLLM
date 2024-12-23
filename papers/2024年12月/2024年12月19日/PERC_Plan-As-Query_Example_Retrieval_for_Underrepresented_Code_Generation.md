# PERC：针对代表性不足的代码生成的计划即查询示例检索

发布时间：2024年12月19日

`RAG` `代码生成` `编程语言`

> PERC: Plan-As-Query Example Retrieval for Underrepresented Code Generation

# 摘要

> 使用大型语言模型进行代码生成颇具前景，尤其是采用带有少量示例的检索增强生成（RAG）时。然而，挑选能提升生成质量的有效示例颇具难度，特别是目标编程语言（PL）缺乏代表性时。本研究有两大关键发现：（1）检索那些呈现的算法计划可用于生成所需行为的示例，能显著提高生成的准确性；（2）将代码转换为伪代码能有效捕获此类算法计划，即便源和目标编程语言不同，也能提升检索质量。基于这些发现，我们提出了用于代码生成中少量提示的“计划作为查询示例检索”（PERC）这一新颖框架，它利用算法计划来识别和检索有效示例。我们在 CodeContests、HumanEval 和 MultiPL-E 基准上开展了大量实验，验证了 PERC 的有效性：无论是源和目标编程语言相同还是不同，PERC 在代码生成方面始终优于最先进的 RAG 方法，凸显了其在不同编码环境中的适应性和稳健性。

> Code generation with large language models has shown significant promise, especially when employing retrieval-augmented generation (RAG) with few-shot examples. However, selecting effective examples that enhance generation quality remains a challenging task, particularly when the target programming language (PL) is underrepresented. In this study, we present two key findings: (1) retrieving examples whose presented algorithmic plans can be referenced for generating the desired behavior significantly improves generation accuracy, and (2) converting code into pseudocode effectively captures such algorithmic plans, enhancing retrieval quality even when the source and the target PLs are different. Based on these findings, we propose Plan-as-query Example Retrieval for few-shot prompting in Code generation (PERC), a novel framework that utilizes algorithmic plans to identify and retrieve effective examples. We validate the effectiveness of PERC through extensive experiments on the CodeContests, HumanEval and MultiPL-E benchmarks: PERC consistently outperforms the state-of-the-art RAG methods in code generation, both when the source and target programming languages match or differ, highlighting its adaptability and robustness in diverse coding environments.

[Arxiv](https://arxiv.org/abs/2412.12447)