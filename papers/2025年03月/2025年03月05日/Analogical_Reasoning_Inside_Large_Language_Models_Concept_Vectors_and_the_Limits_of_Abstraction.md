# 大型语言模型中的类比推理：概念向量与抽象能力的边界

发布时间：2025年03月05日

`LLM理论` `人工智能`

> Analogical Reasoning Inside Large Language Models: Concept Vectors and the Limits of Abstraction

# 摘要

> 类比推理依赖于概念的抽象，但目前尚不清楚大型语言模型（LLMs）是否具备此类内部表征。我们从LLM的激活中提取了蒸馏表征，发现功能向量（FVs；Todd等人，2024年）——用于在上下文学习（ICL）任务中的紧凑表征——并非对简单的输入变化（例如，开放性问题与多项选择题）保持不变，这表明它们捕捉的不仅仅是纯粹的概念。通过表征相似性分析（RSA），我们定位到一组编码不变概念向量（CVs）的小型注意力头，这些CVs对应于诸如“反义词”等语言概念。这些CVs充当特征检测器，其运作独立于最终输出——这意味着模型可能形成正确的内部表征，却仍产生错误的输出。此外，CVs可用于因果引导模型行为。然而，对于更抽象的概念如“之前”和“之后”，我们并未观察到不变的线性表征，这一发现与LLMs在这些领域中表现出的泛化问题相联系。

> Analogical reasoning relies on conceptual abstractions, but it is unclear whether Large Language Models (LLMs) harbor such internal representations. We explore distilled representations from LLM activations and find that function vectors (FVs; Todd et al., 2024) - compact representations for in-context learning (ICL) tasks - are not invariant to simple input changes (e.g., open-ended vs. multiple-choice), suggesting they capture more than pure concepts. Using representational similarity analysis (RSA), we localize a small set of attention heads that encode invariant concept vectors (CVs) for verbal concepts like "antonym". These CVs function as feature detectors that operate independently of the final output - meaning that a model may form a correct internal representation yet still produce an incorrect output. Furthermore, CVs can be used to causally guide model behaviour. However, for more abstract concepts like "previous" and "next", we do not observe invariant linear representations, a finding we link to generalizability issues LLMs display within these domains.

[Arxiv](https://arxiv.org/abs/2503.03666)