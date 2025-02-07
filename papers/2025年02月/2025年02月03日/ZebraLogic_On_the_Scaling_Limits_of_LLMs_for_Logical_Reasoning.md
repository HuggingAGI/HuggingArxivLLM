# ZebraLogic: 探讨大型语言模型在逻辑推理中的扩展极限

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的逻辑推理能力及其在复杂非单调推理中的扩展性，提出了一个评估框架ZebraLogic，并研究了LLMs在逻辑网格谜题上的表现。论文还探讨了多种增强逻辑推理的策略，揭示了当前LLM推理能力的固有局限，并指出了潜在的改进路径。这些内容主要涉及LLM的理论研究和能力评估，因此归类为LLM理论。` `人工智能` `逻辑推理`

> ZebraLogic: On the Scaling Limits of LLMs for Logical Reasoning

# 摘要

> 我们深入探讨了大型语言模型（LLMs）的逻辑推理能力及其在复杂非单调推理中的扩展性。为此，我们推出了ZebraLogic，一个全面的评估框架，专门用于评估LLMs在基于约束满足问题（CSPs）的逻辑网格谜题上的推理表现。ZebraLogic能够生成复杂度可控且可量化的谜题，为Llama、o1模型和DeepSeek-R1等模型的扩展极限提供了系统研究的基础。通过覆盖广泛的搜索空间复杂性和多样化的逻辑约束，ZebraLogic为评估在难度递增情况下的推理能力提供了一个结构化的环境。
    研究结果表明，随着问题复杂度的提升，准确性显著下降，这一现象我们称之为“复杂性诅咒”。即便使用更大的模型和增加推理计算资源，这一限制依然存在，揭示了当前LLM推理能力的固有局限。此外，我们还探索了多种增强逻辑推理的策略，如Best-of-N采样、回溯机制和自我验证提示。这些发现不仅为LLM推理的可扩展性提供了深刻见解，还指出了基本限制，并勾勒出潜在的改进路径。

> We investigate the logical reasoning capabilities of large language models (LLMs) and their scalability in complex non-monotonic reasoning. To this end, we introduce ZebraLogic, a comprehensive evaluation framework for assessing LLM reasoning performance on logic grid puzzles derived from constraint satisfaction problems (CSPs). ZebraLogic enables the generation of puzzles with controllable and quantifiable complexity, facilitating a systematic study of the scaling limits of models such as Llama, o1 models, and DeepSeek-R1. By encompassing a broad range of search space complexities and diverse logical constraints, ZebraLogic provides a structured environment to evaluate reasoning under increasing difficulty.
  Our results reveal a significant decline in accuracy as problem complexity grows -- a phenomenon we term the curse of complexity. This limitation persists even with larger models and increased inference-time computation, suggesting inherent constraints in current LLM reasoning capabilities. Additionally, we explore strategies to enhance logical reasoning, including Best-of-N sampling, backtracking mechanisms, and self-verification prompts. Our findings offer critical insights into the scalability of LLM reasoning, highlight fundamental limitations, and outline potential directions for improvement.

[Arxiv](https://arxiv.org/abs/2502.01100)