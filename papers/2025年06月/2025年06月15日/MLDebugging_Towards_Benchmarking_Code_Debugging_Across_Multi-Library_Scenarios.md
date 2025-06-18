# MLDebugging：多库场景下的代码调试基准测试

发布时间：2025年06月15日

`LLM应用` `软件工程`

> MLDebugging: Towards Benchmarking Code Debugging Across Multi-Library Scenarios

# 摘要

> 代码调试是软件工程中的关键任务，正吸引越来越多的关注。尽管在大型语言模型 (LLMs) 时代取得了显著进展，但现有研究仍局限于简单的无库或单库场景，忽视了现实应用中复杂的多库问题。为解决这一局限，我们首次提出 MLDebugging（多库调试），这是一个全面的基准测试，专注于评估多库 Python 代码中的调试挑战。MLDebugging 包含 126 个不同 Python 库，覆盖多库代码问题的广泛领域，并细分为七种类型。我们通过主流开源和闭源 LLM 对 MLDebugging 进行了全面评估，发现当前 LLM 在多库场景下的调试能力仍有待提升。我们期待这项工作能揭示 LLM 在多库调试中的潜力，并为未来研究提供启发。

> Code debugging is a crucial task in software engineering, which attracts increasing attention. While remarkable success has been made in the era of large language models (LLMs), current research still focuses on the simple no-library or single-library setting, ignoring the complex multi-library scenario in real-world applications. To address this limitation, we make the first attempt to introduce MLDebugging (Multi-Library Debugging), a comprehensive benchmark designed to assess debugging challenges within multi-library Python code. Specifically, MLDebugging encompasses 126 distinct Python libraries, covering a wide range of multi-library code issues, categorized into seven distinct types. Furthermore, we conduct a thorough evaluation of MLDebugging using both mainstream open-source and closed-source LLMs and highlight that current LLMs still struggle to correctly perform code debugging across multi-library scenarios. We hope this work can uncover the potential of LLMs in multi-library debugging scenario and offer insights for future research.

[Arxiv](https://arxiv.org/abs/2506.13824)