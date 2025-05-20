# 感知与敏感性：探究语义记忆对长上下文代码推理能力的影响

发布时间：2025年05月19日

`LLM理论

理由：这篇论文深入分析了大型语言模型在代码推理中的性能，探讨了上下文长度和召回能力之间的关系，并提出了新的评估方法。它不仅评估了模型的表现，还探讨了模型背后的机制差异，属于对LLM内在机制和性能的理论研究。` `软件工程`

> Sense and Sensitivity: Examining the Influence of Semantic Recall on Long Context Code Reasoning

# 摘要

> 现代大型语言模型（LLMs）虽支持超大上下文，但其在长上下文代码推理中的有效性尚不明朗。本文探讨了LLMs在大型代码仓库中处理代码片段的推理能力及其与召回能力的关系。我们区分了词汇代码召回（逐字逐句检索）和语义代码召回（理解代码功能）。为量化语义召回，我们提出了SemTrace——一种特定语句对输出影响可归因且不可预测的代码推理技术，并开发了量化现有基准中语义召回敏感性的方法。评估表明，当代码片段接近输入上下文中部时，LLMs的推理准确度显著下降，尤其在需高语义召回的技术（如SemTrace）中。此外，模型在函数检索上表现优异，但逐行召回则困难重重。值得注意的是，词汇与语义召回间存在脱节，暗示其背后机制不同。最后，当前代码推理基准可能语义召回敏感性不足，低估了LLMs在利用上下文信息上的挑战。

> Although modern Large Language Models (LLMs) support extremely large contexts, their effectiveness in utilizing long context for code reasoning remains unclear. This paper investigates LLM reasoning ability over code snippets within large repositories and how it relates to their recall ability. Specifically, we differentiate between lexical code recall (verbatim retrieval) and semantic code recall (remembering what the code does). To measure semantic recall, we propose SemTrace, a code reasoning technique where the impact of specific statements on output is attributable and unpredictable. We also present a method to quantify semantic recall sensitivity in existing benchmarks. Our evaluation of state-of-the-art LLMs reveals a significant drop in code reasoning accuracy as a code snippet approaches the middle of the input context, particularly with techniques requiring high semantic recall like SemTrace. Moreover, we find that lexical recall varies by granularity, with models excelling at function retrieval but struggling with line-by-line recall. Notably, a disconnect exists between lexical and semantic recall, suggesting different underlying mechanisms. Finally, our findings indicate that current code reasoning benchmarks may exhibit low semantic recall sensitivity, potentially underestimating LLM challenges in leveraging in-context information.

[Arxiv](https://arxiv.org/abs/2505.13353)