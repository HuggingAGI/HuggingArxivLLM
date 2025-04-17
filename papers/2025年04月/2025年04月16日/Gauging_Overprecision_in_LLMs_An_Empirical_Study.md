# 大型语言模型的过度精准现象：实证研究

发布时间：2025年04月16日

`LLM理论

理由：这篇论文探讨了大型语言模型的内在特性，特别是过度自信和精确度的问题，属于对模型理论层面的研究。` `人工智能` `数据分析`

> Gauging Overprecision in LLMs: An Empirical Study

# 摘要

> # 摘要
大型语言模型 (LLMs) 的过度自信问题最近吸引了广泛关注，因为它在量化 LLM 生成的信任度方面具有根本性的重要性。然而，现有方法促使黑箱 LLMs 生成其表达的信心，这种信心可能受到多种偏见和幻觉的影响。受认知科学中过度精确这一不同方面启发，我们设计了一个研究框架，用于在黑箱 LLMs 中研究过度精确。该框架包含三个主要阶段：生成、精炼和评估。在生成阶段，我们提示 LLM 以区间形式生成对数值问题的答案，并附带一定置信水平。这种置信水平是在提示中施加的，不需要 LLM 自行生成。我们使用多种提示技术，并多次使用相同的提示来评估生成过程中的随机性影响。在精炼阶段，前一阶段的答案经过精炼以生成更好的答案。在评估阶段，我们对 LLM 的答案进行评估和研究，以理解其内部工作原理。这项研究让我们对 LLM 的过度精确有了多方面的见解：1) LLM 在数值任务上严重未校准；2) 区间长度与施加的置信水平之间没有关联，这可能表明 a) 对置信概念缺乏理解，或 b) 无法通过遵循指令调整自信；3) LLM 的数值精确度因任务、答案范围和提示技术而异；4) 在大多数情况下，答案的精炼并未提高精确度。我们相信这项研究为 LLM 的过度自信提供了新的视角，并为 LLM 的过度精确提供了强大的基线。


> Recently, overconfidence in large language models (LLMs) has garnered considerable attention due to its fundamental importance in quantifying the trustworthiness of LLM generation. However, existing approaches prompt the \textit{black box LLMs} to produce their confidence (\textit{verbalized confidence}), which can be subject to many biases and hallucinations. Inspired by a different aspect of overconfidence in cognitive science called \textit{overprecision}, we designed a framework for its study in black box LLMs. This framework contains three main phases: 1) generation, 2) refinement and 3) evaluation. In the generation phase we prompt the LLM to generate answers to numerical questions in the form of intervals with a certain level of confidence. This confidence level is imposed in the prompt and not required for the LLM to generate as in previous approaches. We use various prompting techniques and use the same prompt multiple times to gauge the effects of randomness in the generation process. In the refinement phase, answers from the previous phase are refined to generate better answers. The LLM answers are evaluated and studied in the evaluation phase to understand its internal workings. This study allowed us to gain various insights into LLM overprecision: 1) LLMs are highly uncalibrated for numerical tasks 2) {\color{blue}there is no correlation between the length of the interval and the imposed confidence level, which can be symptomatic of a a) lack of understanding of the concept of confidence or b) inability to adjust self-confidence by following instructions}, {\color{blue}3)} LLM numerical precision differs depending on the task, scale of answer and prompting technique {\color{blue}4) Refinement of answers doesn't improve precision in most cases}. We believe this study offers new perspectives on LLM overconfidence and serves as a strong baseline for overprecision in LLMs.

[Arxiv](https://arxiv.org/abs/2504.12098)