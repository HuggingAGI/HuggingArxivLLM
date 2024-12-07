# PrefixLLM：由 LLM 辅助的前缀电路设计

发布时间：2024年12月03日

`LLM应用` `数字电路` `计算系统`

> PrefixLLM: LLM-aided Prefix Circuit Design

# 摘要

> 前缀电路作为数字加法器的基础组件，因其在计算进位信号时的高效性，在数字系统中得到广泛应用。以最小化面积和延迟来合成前缀电路，对提升现代计算系统性能极为关键。近来，大型语言模型（LLMs）在执行文本生成任务上展现出惊人能力。我们提出了 PrefixLLM，借助 LLMs 来实现前缀电路合成。PrefixLLM 把前缀电路合成任务转变为结构化文本生成问题，即结构化前缀电路表示（SPCR），还引入了一个迭代框架，能自动且精准地生成有效的 SPCRs。我们进一步给出了一个设计空间探索（DSE）框架，利用 LLMs 迭代搜索面积和延迟优化的前缀电路。相较于现有最先进技术，在相同延迟约束下，PrefixLLM 能将面积减少 3.70%。此项工作凸显了 LLMs 在算术电路合成中的运用，可将其转化为结构化文本生成。

> Prefix circuits are fundamental components in digital adders, widely used in digital systems due to their efficiency in calculating carry signals. Synthesizing prefix circuits with minimized area and delay is crucial for enhancing the performance of modern computing systems. Recently, large language models (LLMs) have demonstrated a surprising ability to perform text generation tasks. We propose PrefixLLM, that leverages LLMs for prefix circuit synthesis. PrefixLLM transforms the prefix circuit synthesis task into a structured text generation problem, termed the Structured Prefix Circuit Representation (SPCR), and introduces an iterative framework to automatically and accurately generate valid SPCRs. We further present a design space exploration (DSE) framework that uses LLMs to iteratively search for area and delay optimized prefix circuits. Compared to state-of-the-art, PrefixLLM can reduce the area by 3.70% under the same delay constraint. This work highlights the use of LLMs in the synthesis of arithmetic circuits, which can be transformed into the structured text generation.

[Arxiv](https://arxiv.org/abs/2412.02594)