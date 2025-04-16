# # NP 问题挑战：针对大型语言模型（LLMs）的动态扩展推理能力评测基准

发布时间：2025年04月15日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的推理能力，并提出了一种新的基准测试方法（NPPC），用于评估LLMs的推理性能。它涉及LLMs的理论分析和基准测试设计，属于LLM理论的范畴。` `人工智能`

> Nondeterministic Polynomial-time Problem Challenge: An Ever-Scaling Reasoning Benchmark for LLMs

# 摘要

> 推理是大型语言模型 (LLMs) 的核心能力。鉴于 LLMs 的迅猛发展，当前的基准测试面临两大主要问题：i) 这些基准测试在短时间内可能被轻易突破，ii) 这些基准测试可能容易被破解。为了解决这些问题，我们提出了“持续扩展性”概念，用于构建不可破解、不可绕过的通用自动验证基准。本文介绍了 Nondeterministic Polynomial-time Problem Challenge (NPPC)，这是一个针对 LLMs 的持续扩展推理基准。

具体来说，NPPC 包含三个主要模块：i) npgym 提供 25 个著名 NP 完全问题的统一接口，并能生成任意数量和复杂度的实例；ii) npsolver 通过 API 和本地部署，统一评估问题实例的在线和离线模型；iii) npeval 提供全面且即用的工具，用于分析 LLMs 的性能、token 数量、顿悟时刻、推理错误和解错误。

对广泛使用的 LLMs 进行的大量实验表明：i) NPPC 成功将先进 LLMs 的性能降低到 10% 以下，证明其不可破解性；ii) DeepSeek-R1、Claude-3.7-Sonnet 和 o1/o3-mini 是目前最强大的 LLMs，其中 DeepSeek-R1 在大多数 NP 完全问题上表现更优；iii) 随着问题难度增加，Claude-3.7-Sonnet 和 DeepSeek-R1 等先进 LLMs 的 token 数量和顿悟时刻呈现先增后减的趋势。

我们相信，NPPC 是首个持续扩展的推理基准，作为不可破解且不可绕过的测试平台，助力 LLMs 向人工通用智能 (AGI) 迈进。

> Reasoning is the fundamental capability of large language models (LLMs). Due to the rapid progress of LLMs, there are two main issues of current benchmarks: i) these benchmarks can be crushed in a short time (less than 1 year), and ii) these benchmarks may be easily hacked. To handle these issues, we propose the ever-scalingness for building the benchmarks which are uncrushable, unhackable, auto-verifiable and general. This paper presents Nondeterministic Polynomial-time Problem Challenge (NPPC), an ever-scaling reasoning benchmark for LLMs. Specifically, the NPPC has three main modules: i) npgym, which provides a unified interface of 25 well-known NP-complete problems and can generate any number of instances with any levels of complexities, ii) npsolver: which provides a unified interface to evaluate the problem instances with both online and offline models via APIs and local deployments, respectively, and iii) npeval: which provides the comprehensive and ready-to-use tools to analyze the performances of LLMs over different problems, the number of tokens, the aha moments, the reasoning errors and the solution errors. Extensive experiments over widely-used LLMs demonstrate: i) NPPC can successfully decrease the performances of advanced LLMs' performances to below 10%, demonstrating that NPPC is uncrushable, ii) DeepSeek-R1, Claude-3.7-Sonnet, and o1/o3-mini are the most powerful LLMs, where DeepSeek-R1 outperforms Claude-3.7-Sonnet and o1/o3-mini in most NP-complete problems considered, and iii) the numbers of tokens, aha moments in the advanced LLMs, e.g., Claude-3.7-Sonnet and DeepSeek-R1, are observed first to increase and then decrease when the problem instances become more and more difficult. We believe that NPPC is the first ever-scaling reasoning benchmark, serving as the uncrushable and unhackable testbed for LLMs toward artificial general intelligence (AGI).

[Arxiv](https://arxiv.org/abs/2504.11239)