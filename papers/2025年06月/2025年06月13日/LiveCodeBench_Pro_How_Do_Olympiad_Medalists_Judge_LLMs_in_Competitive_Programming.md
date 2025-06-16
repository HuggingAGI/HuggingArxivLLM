# LiveCodeBench Pro：金牌选手如何评估LLMs在编程竞赛中的能力？

发布时间：2025年06月13日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在竞技编程中的应用和表现，特别是与人类专家的比较。它引入了一个新的基准测试（LiveCodeBench Pro）来评估模型在不同难度问题上的表现，并分析了模型的局限性和优势。这些内容属于LLM在特定任务中的应用研究。` `算法竞赛`

> LiveCodeBench Pro: How Do Olympiad Medalists Judge LLMs in Competitive Programming?

# 摘要

> 最近有报告声称大型语言模型（LLMs）在竞技编程中已超越精英人类的表现。我们基于一群国际算法竞赛奖牌获得者的知识，重新审视这一说法，探讨LLMs与人类专家之间的差异以及仍存在的限制。我们引入了LiveCodeBench Pro，这是一个由Codeforces、ICPC和IOI的题目组成的基准测试，持续更新以减少数据污染的可能性。一支奥赛奖牌获得者团队对每个问题进行算法分类标注，并对失败的模型生成提交进行逐行分析。通过这一新的数据和基准测试，我们发现前沿模型仍存在显著局限性：在没有外部工具的情况下，最佳模型在中等难度问题上仅达到53%的pass@1通过率，在困难问题上则为0%，而这些都是人类专家仍表现出色的领域。我们还发现，LLMs在实现密集型问题上表现良好，但在细微的算法推理和复杂案例分析方面却力不从心，常常生成自信但错误的解释。高性能似乎主要由实现精度和工具增强驱动，而非更卓越的推理能力。因此，LiveCodeBench Pro凸显了与人类大师级水平之间的显著差距，同时提供了精细的诊断工具，以指导未来代码为中心的LLM推理改进。

> Recent reports claim that large language models (LLMs) now outperform elite humans in competitive programming. Drawing on knowledge from a group of medalists in international algorithmic contests, we revisit this claim, examining how LLMs differ from human experts and where limitations still remain. We introduce LiveCodeBench Pro, a benchmark composed of problems from Codeforces, ICPC, and IOI that are continuously updated to reduce the likelihood of data contamination. A team of Olympiad medalists annotates every problem for algorithmic categories and conducts a line-by-line analysis of failed model-generated submissions. Using this new data and benchmark, we find that frontier models still have significant limitations: without external tools, the best model achieves only 53% pass@1 on medium-difficulty problems and 0% on hard problems, domains where expert humans still excel. We also find that LLMs succeed at implementation-heavy problems but struggle with nuanced algorithmic reasoning and complex case analysis, often generating confidently incorrect justifications. High performance appears largely driven by implementation precision and tool augmentation, not superior reasoning. LiveCodeBench Pro thus highlights the significant gap to human grandmaster levels, while offering fine-grained diagnostics to steer future improvements in code-centric LLM reasoning.

[Arxiv](https://arxiv.org/abs/2506.11928)