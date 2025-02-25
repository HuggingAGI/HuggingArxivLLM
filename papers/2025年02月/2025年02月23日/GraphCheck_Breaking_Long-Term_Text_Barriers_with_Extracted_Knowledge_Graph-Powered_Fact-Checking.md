# # **GraphCheck**: 基于知识图谱的事实核查，突破长期文本屏障

发布时间：2025年02月23日

`LLM应用` `知识图谱`

> GraphCheck: Breaking Long-Term Text Barriers with Extracted Knowledge Graph-Powered Fact-Checking

# 摘要

> 大型语言模型 (LLMs) 虽然应用广泛，但常在长文本中产生细微的事实性错误，尤其在医学等专业领域可能造成严重后果。现有基于文档的事实核查方法面临两大挑战：(1) 难以理解长文档中的复杂多跳关系，常忽略细微事实错误；(2) 多数专用方法依赖多次模型调用的成对比较，导致高资源和计算成本。为解决这些问题，我们提出了 \textbf{\textit{GraphCheck}}，一个通过提取知识图谱增强文本表示的事实核查框架。该框架利用图神经网络将知识图谱作为软提示处理，使 LLM 更高效地整合结构化知识。借助基于图的推理增强，GraphCheck 捕捉到现有方法常忽略的多跳推理链，从而在单次推理调用中实现精确高效的事实核查。在涵盖通用和医学领域的七个基准测试中，GraphCheck 相对于基线模型整体提升了 6.1%。值得注意的是，GraphCheck 不仅超越现有专用事实核查器，更以更少的参数量与 DeepSeek-V3 和 OpenAI-o1 等先进 LLM 实现相当性能。

> Large language models (LLMs) are widely used, but they often generate subtle factual errors, especially in long-form text. These errors are fatal in some specialized domains such as medicine. Existing fact-checking with grounding documents methods face two main challenges: (1) they struggle to understand complex multihop relations in long documents, often overlooking subtle factual errors; (2) most specialized methods rely on pairwise comparisons, requiring multiple model calls, leading to high resource and computational costs. To address these challenges, we propose \textbf{\textit{GraphCheck}}, a fact-checking framework that uses extracted knowledge graphs to enhance text representation. Graph Neural Networks further process these graphs as a soft prompt, enabling LLMs to incorporate structured knowledge more effectively. Enhanced with graph-based reasoning, GraphCheck captures multihop reasoning chains which are often overlooked by existing methods, enabling precise and efficient fact-checking in a single inference call. Experimental results on seven benchmarks spanning both general and medical domains demonstrate a 6.1\% overall improvement over baseline models. Notably, GraphCheck outperforms existing specialized fact-checkers and achieves comparable performance with state-of-the-art LLMs, such as DeepSeek-V3 and OpenAI-o1, with significantly fewer parameters.

[Arxiv](https://arxiv.org/abs/2502.16514)