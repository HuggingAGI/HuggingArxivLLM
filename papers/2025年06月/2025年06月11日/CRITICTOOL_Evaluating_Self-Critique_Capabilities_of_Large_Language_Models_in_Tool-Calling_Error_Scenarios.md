# 工具调用错误场景下大型语言模型自我批评能力评估：CRITICTOOL工具

发布时间：2025年06月11日

`LLM应用` `人工智能` `工具学习`

> CRITICTOOL: Evaluating Self-Critique Capabilities of Large Language Models in Tool-Calling Error Scenarios

# 摘要

> 大型语言模型（LLMs）通过利用外部工具，能够处理的任务类型日益多样化。然而，面对复杂且长期性的任务，工具使用过程中的复杂性可能引发各种意外错误。因此，如何有效处理这些错误，包括识别、诊断和恢复，已成为推进工具学习的关键研究方向。本研究首先在多个工具评估基准上，全面分析了功能调用过程中遇到的错误类型。基于此，我们提出了CRITICTOOL——一个专为工具学习设计的全面批判性评估基准。CRITICTOOL基于一种全新的数据集构建演化策略，涵盖了不同复杂度的工具使用错误，更贴近真实场景。通过在CRITICTOOL上进行深入实验，我们验证了该基准策略的泛化性和有效性。此外，我们还对多种LLMs的工具反思能力进行了深入分析，为工具学习领域提供了新的研究视角。代码已开源，访问地址为\href{https://github.com/Shellorley0513/CriticTool}{https://github.com/Shellorley0513/CriticTool}。

> The ability of large language models (LLMs) to utilize external tools has enabled them to tackle an increasingly diverse range of tasks. However, as the tasks become more complex and long-horizon, the intricate tool utilization process may trigger various unexpected errors. Therefore, how to effectively handle such errors, including identifying, diagnosing, and recovering from them, has emerged as a key research direction for advancing tool learning. In this work, we first extensively analyze the types of errors encountered during the function-calling process on several competitive tool evaluation benchmarks. Based on it, we introduce CRITICTOOL, a comprehensive critique evaluation benchmark specialized for tool learning. Building upon a novel evolutionary strategy for dataset construction, CRITICTOOL holds diverse tool-use errors with varying complexities, which better reflects real-world scenarios. We conduct extensive experiments on CRITICTOOL, and validate the generalization and effectiveness of our constructed benchmark strategy. We also provide an in-depth analysis of the tool reflection ability on various LLMs, offering a new perspective on the field of tool learning in LLMs. The code is available at \href{https://github.com/Shellorley0513/CriticTool}{https://github.com/Shellorley0513/CriticTool}.

[Arxiv](https://arxiv.org/abs/2506.13977)