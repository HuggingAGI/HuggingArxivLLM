# # 零调优：无需训练，释放初始令牌的潜力，提升大型语言模型的能力

发布时间：2025年05月16日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的注意力机制，并提出了一种新的无需训练的调优方法（ZeroTuning）。论文通过理论分析和实证研究，揭示了初始token在注意力机制中的作用及其对模型性能的影响，属于对模型机制的深入理解和优化，因此归类为LLM理论。` `对话系统`

> ZeroTuning: Unlocking the Initial Token's Power to Enhance Large Language Models Without Training

# 摘要

> # 摘要  
近期，无需训练的大型语言模型（LLMs）改进方法引发了广泛关注，其中基于token级别的注意力调优作为一种有前景且可解释的方向正在兴起。然而，现有方法通常依赖辅助机制来识别特定任务中的重要或无关token，这可能引入偏差并限制其应用。在这篇论文中，我们发现了一个令人惊喜且优雅的替代方案：语义空的初始token是一个强大且未被充分探索的控制点，可用于优化模型行为。

通过理论分析，我们发现调整初始token的注意力会锐化或平坦化后续token的注意力分布，而其作为注意力汇的作用进一步放大了这一效果。实证研究表明：(1) 调整其注意力比调整其他特定任务token更有效地提升LLM性能；(2) 这种效果在不同层之间呈现一致趋势，早期层影响更大，但在不同注意力头之间则表现出差异，不同头对如何关注这个token显示出不同偏好。

基于这些发现，我们提出了ZeroTuning——一种无需训练的方法，通过针对这个特殊token应用特定头部的注意力调整来提升LLM性能。尽管仅调整一个token，ZeroTuning在文本分类、多项选择和多轮对话任务上，在Llama、Qwen和DeepSeek等模型中实现了更高的性能。例如，ZeroTuning将Llama-3.1-8B在分类任务上的准确率提高了11.71%，在问答任务上提高了2.64%，并将多轮对话得分从7.804提升至7.966。

该方法在资源有限、少样本设置、长上下文、量化、解码策略和提示变体等情况下也表现出稳健性。我们的研究揭示了LLMs中一个被忽视的控制点，为推理时的调优和模型可解释性提供了新的见解。


> Recently, training-free methods for improving large language models (LLMs) have attracted growing interest, with token-level attention tuning emerging as a promising and interpretable direction. However, existing methods typically rely on auxiliary mechanisms to identify important or irrelevant task-specific tokens, introducing potential bias and limiting applicability. In this paper, we uncover a surprising and elegant alternative: the semantically empty initial token is a powerful and underexplored control point for optimizing model behavior. Through theoretical analysis, we show that tuning the initial token's attention sharpens or flattens the attention distribution over subsequent tokens, and its role as an attention sink amplifies this effect. Empirically, we find that: (1) tuning its attention improves LLM performance more effectively than tuning other task-specific tokens; (2) the effect follows a consistent trend across layers, with earlier layers having greater impact, but varies across attention heads, with different heads showing distinct preferences in how they attend to this token. Based on these findings, we propose ZeroTuning, a training-free approach that improves LLM performance by applying head-specific attention adjustments to this special token. Despite tuning only one token, ZeroTuning achieves higher performance on text classification, multiple-choice, and multi-turn conversation tasks across models such as Llama, Qwen, and DeepSeek. For example, ZeroTuning improves Llama-3.1-8B by 11.71% on classification, 2.64% on QA tasks, and raises its multi-turn score from 7.804 to 7.966. The method is also robust to limited resources, few-shot settings, long contexts, quantization, decoding strategies, and prompt variations. Our work sheds light on a previously overlooked control point in LLMs, offering new insights into both inference-time tuning and model interpretability.

[Arxiv](https://arxiv.org/abs/2505.11739)