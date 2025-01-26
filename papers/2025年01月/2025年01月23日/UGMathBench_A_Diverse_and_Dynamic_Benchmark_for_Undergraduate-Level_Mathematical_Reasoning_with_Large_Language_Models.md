# UGMathBench: 一个多样且动态的基准，专为评估大型语言模型在本科数学推理中的能力而设计

发布时间：2025年01月23日

`LLM应用

**解释**：这篇论文主要讨论了如何评估大型语言模型（LLMs）在数学推理领域的能力，并提出了一个新的基准测试UGMathBench。论文的核心是LLMs在特定应用场景（数学推理）中的表现评估和改进，因此属于LLM应用类别。`

> UGMathBench: A Diverse and Dynamic Benchmark for Undergraduate-Level Mathematical Reasoning with Large Language Models

# 摘要

> 大型语言模型（LLMs）在数学推理领域取得了显著进展，这凸显了对它们能力进行全面和公平评估的迫切需求。然而，现有基准测试往往存在不足，要么覆盖范围有限，要么可能受到测试集污染的影响。为此，我们推出了UGMathBench，这是一个专为评估LLMs在本科水平数学推理能力而设计的多样化和动态基准测试。UGMathBench包含5,062个问题，涵盖16个学科和111个主题，并包含10种不同的答案类型。每个问题都有三个随机版本，随着领先的开源LLMs在UGMathBench中达到饱和，我们计划发布更多版本。此外，我们提出了两个关键指标：有效准确率（EAcc），用于衡量所有三个版本中正确解决问题的百分比；以及推理差距（$Δ$），通过计算所有版本的平均准确率与EAcc之间的差异来评估推理的稳健性。我们对23个领先的LLMs进行了广泛评估，结果显示OpenAI-o1-mini达到了最高的EAcc，为56.3\%，并且在不同模型中观察到较大的$Δ$值。这突显了未来研究需要开发具有高EAcc和$Δ= 0$的“大型推理模型”。我们预计UGMathBench的发布及其详细的评估代码将成为推动LLMs在解决数学问题方面发展的重要资源。

> Large Language Models (LLMs) have made significant strides in mathematical reasoning, underscoring the need for a comprehensive and fair evaluation of their capabilities. However, existing benchmarks often fall short, either lacking extensive coverage of undergraduate-level mathematical problems or probably suffering from test-set contamination. To address these issues, we introduce UGMathBench, a diverse and dynamic benchmark specifically designed for evaluating undergraduate-level mathematical reasoning with LLMs. UGMathBench comprises 5,062 problems across 16 subjects and 111 topics, featuring 10 distinct answer types. Each problem includes three randomized versions, with additional versions planned for release as leading open-source LLMs become saturated in UGMathBench. Furthermore, we propose two key metrics: effective accuracy (EAcc), which measures the percentage of correctly solved problems across all three versions, and reasoning gap ($Δ$), which assesses reasoning robustness by calculating the difference between the average accuracy across all versions and EAcc. Our extensive evaluation of 23 leading LLMs reveals that the highest EAcc achieved is 56.3\% by OpenAI-o1-mini, with large $Δ$ values observed across different models. This highlights the need for future research aimed at developing "large reasoning models" with high EAcc and $Δ= 0$. We anticipate that the release of UGMathBench, along with its detailed evaluation codes, will serve as a valuable resource to advance the development of LLMs in solving mathematical problems.

[Arxiv](https://arxiv.org/abs/2501.13766)