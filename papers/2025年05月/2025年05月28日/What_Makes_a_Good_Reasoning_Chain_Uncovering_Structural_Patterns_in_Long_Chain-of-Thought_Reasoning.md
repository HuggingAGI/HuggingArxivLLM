# 什么成就了一个优秀的推理链？长链式推理中的结构模式解析

发布时间：2025年05月28日

`LLM理论` `人工智能`

> What Makes a Good Reasoning Chain? Uncovering Structural Patterns in Long Chain-of-Thought Reasoning

# 摘要

> 近年来，大型语言模型（LLMs）在推理领域的突破使长链式推理（LCoT）备受关注。LCoT作为一种鼓励在生成最终答案前进行刻意且逐步推理的策略，在复杂任务中实现了专家级表现。然而，其推理链的内部结构如何驱动，甚至预测最终答案的正确性，仍是一个关键但未充分探索的问题。在本研究中，我们提出了LCoT2Tree，这是一个将顺序推理链转换为分层树结构的自动化框架，从而支持对LLM推理的更深入结构分析。通过图神经网络（GNNs），我们揭示了LCoT2Tree提取的结构模式，包括探索、回溯和验证，这些模式在广泛的任务和模型中是最终性能的更强预测指标。借助可解释性技术，我们进一步识别了导致推理失败的关键思维模式，如过度分支。除了诊断洞察，LCoT2Tree的结构模式还支持实际应用，例如提升Best-of-N解码的有效性。总体而言，我们的结果强调了推理链内部结构的关键作用，并将LCoT2Tree定位为诊断、解释和改进LLM推理的强大工具。
    

> Recent advances in reasoning with large language models (LLMs) have popularized Long Chain-of-Thought (LCoT), a strategy that encourages deliberate and step-by-step reasoning before producing a final answer. While LCoTs have enabled expert-level performance in complex tasks, how the internal structures of their reasoning chains drive, or even predict, the correctness of final answers remains a critical yet underexplored question. In this work, we present LCoT2Tree, an automated framework that converts sequential LCoTs into hierarchical tree structures and thus enables deeper structural analysis of LLM reasoning. Using graph neural networks (GNNs), we reveal that structural patterns extracted by LCoT2Tree, including exploration, backtracking, and verification, serve as stronger predictors of final performance across a wide range of tasks and models. Leveraging an explainability technique, we further identify critical thought patterns such as over-branching that account for failures. Beyond diagnostic insights, the structural patterns by LCoT2Tree support practical applications, including improving Best-of-N decoding effectiveness. Overall, our results underscore the critical role of internal structures of reasoning chains, positioning LCoT2Tree as a powerful tool for diagnosing, interpreting, and improving reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2505.22148)