# K12Vista：探索多模态大语言模型在K-12教育领域的边界与潜力

发布时间：2025年06月02日

`LLM应用

理由：这篇论文探讨了多模态大语言模型在K12教育中的应用，特别是在知识理解和推理能力方面。他们开发了基准测试、数据集和评估模型，这些都是应用层面的工作，属于LLM的应用研究。` `人工智能`

> K12Vista: Exploring the Boundaries of MLLMs in K-12 Education

# 摘要

> 多模态大语言模型在视觉任务中展现出了强大的推理能力，但在K12教育场景中的潜力仍未被充分挖掘。现有研究受限于学科覆盖范围狭窄、数据规模不足、题目类型单一以及评估方法过于简单等问题，导致对模型能力的探索不够深入。为解决这些问题，我们推出了K12Vista——首个针对中文K12学科知识理解和推理能力的全面多模态基准测试，包含从小学到高中五个核心学科的33,000道题目及三种题型。除了关注最终结果，我们还特别注重多模态大语言模型推理过程的正确性。为此，我们系统性地整理了多模态大语言模型推理过程中的错误，并通过自动化数据管道构建了K12-PEM-800K，这是目前规模最大的过程评估数据集，提供了针对多模态大语言模型推理过程的详细分步评估标注。在此基础上，我们开发了K12-PEM，一个能够综合评估推理过程和答案正确性的先进过程评估模型。此外，我们还推出了K12-PEBench，这是首个专门用于评估推理过程评估能力的高质量人工标注基准测试。通过大量实验，我们发现当前多模态大语言模型在K12Vista中的推理表现仍存在明显不足，这一发现为开发更强大的多模态大语言模型提供了重要参考。我们的研究资源已开源，详情请访问https://github.com/lichongod/K12Vista。


> Multimodal large language models have demonstrated remarkable reasoning capabilities in various visual tasks. However, their abilities in K12 scenarios are still systematically underexplored. Previous studies suffer from various limitations including narrow subject coverage, insufficient data scale, lack of diversity in question types, and naive answer-centric evaluation method, resulting in insufficient exploration of model capabilities. To address these gaps, we propose K12Vista, the most comprehensive multimodal benchmark for Chinese K12 subject knowledge understanding and reasoning to date, featuring 33,000 questions across five core subjects from primary to high school and three question types. Moreover, beyond the final outcome, we are also concerned with the correctness of MLLMs' reasoning processes. For this purpose, we meticulously compiles errors from MLLMs' reasoning processes and leverage an automated data pipeline to construct K12-PEM-800K, the largest process evaluation dataset offering detailed step-by-step judgement annotations for MLLMs' reasoning. Subsequently, we developed K12-PEM, an advanced process evaluation model that integrates an overall assessment of both the reasoning process and answer correctness. Moreover, we also introduce K12-PEBench, the first high-quality, human-annotated benchmark specifically designed for evaluating abilities of reasoning process evaluation.Extensive experiments reveal that current MLLMs exhibit significant flaws when reasoning within K12Vista, providing critical insights for the development of more capable MLLMs.We open our resources at https://github.com/lichongod/K12Vista.

[Arxiv](https://arxiv.org/abs/2506.01676)