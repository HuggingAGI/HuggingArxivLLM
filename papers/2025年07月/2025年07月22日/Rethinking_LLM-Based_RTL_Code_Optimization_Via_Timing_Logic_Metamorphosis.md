# # 基于时序逻辑变形，重新思考基于LLM的RTL代码优化

发布时间：2025年07月22日

`LLM应用` `EDA` `人工智能`

> Rethinking LLM-Based RTL Code Optimization Via Timing Logic Metamorphosis

# 摘要

> 寄存器传输级（RTL）代码优化对于实现高性能和低功耗的设计目标至关重要。然而，传统优化方法依赖于耗时且容易出错的手动调整和启发式策略。近期研究提出利用大型语言模型（LLMs）来辅助 RTL 代码优化。LLMs 可以根据自然语言描述生成优化后的代码片段，从而有望加速优化过程。然而，现有方法尚未对 LLM 基础的代码优化方法在处理具有复杂时序逻辑的 RTL 代码时的有效性进行充分评估。为填补这一空白，我们开展了一项全面的实证研究，以评估 LLM 基础的 RTL 代码优化方法在处理具有复杂时序逻辑的 RTL 代码时的能力。

在这项研究中，我们首先提出了一种新的 RTL 优化评估基准。该基准包含四个子集，每个子集对应 RTL 代码优化的一个特定领域。然后，我们引入了一种基于变形的系统化方法，用于评估 LLM 基础的 RTL 代码优化方法的有效性。我们的核心见解在于，对于语义等价但更为复杂的代码，优化效果应保持一致。经过大量实验后，我们揭示了几个关键发现：

1. LLM 基础的 RTL 优化方法能够有效优化逻辑操作，并在现有编译器基础方法中表现更优。
2. 在处理具有复杂时序逻辑的 RTL 代码时，特别是时序控制流优化和时钟域优化方面，LLM 基础的 RTL 优化方法并未优于现有的编译器基础方法。这主要是由于 LLM 在理解 RTL 代码中的时序逻辑方面面临挑战。

基于这些发现，我们为利用 LLM 进行 RTL 代码优化的进一步研究提供了见解。

> Register Transfer Level(RTL) code optimization is crucial for achieving high performance and low power consumption in digital circuit design. However, traditional optimization methods often rely on manual tuning and heuristics, which can be time-consuming and error-prone. Recent studies proposed to leverage Large Language Models(LLMs) to assist in RTL code optimization. LLMs can generate optimized code snippets based on natural language descriptions, potentially speeding up the optimization process. However, existing approaches have not thoroughly evaluated the effectiveness of LLM-Based code optimization methods for RTL code with complex timing logic. To address this gap, we conducted a comprehensive empirical investigation to assess the capability of LLM-Based RTL code optimization methods in handling RTL code with complex timing logic. In this study, we first propose a new benchmark for RTL optimization evaluation. It comprises four subsets, each corresponding to a specific area of RTL code optimization. Then we introduce a method based on metamorphosis to systematically evaluate the effectiveness of LLM-Based RTL code optimization methods.Our key insight is that the optimization effectiveness should remain consistent for semantically equivalent but more complex code. After intensive experiments, we revealed several key findings. (1) LLM-Based RTL optimization methods can effectively optimize logic operations and outperform existing compiler-based methods. (2) LLM-Based RTL optimization methods do not perform better than existing compiler-based methods on RTL code with complex timing logic, particularly in timing control flow optimization and clock domain optimization. This is primarily attributed to the challenges LLMs face in understanding timing logic in RTL code. Based on these findings, we provide insights for further research in leveraging LLMs for RTL code optimization.

[Arxiv](https://arxiv.org/abs/2507.16808)