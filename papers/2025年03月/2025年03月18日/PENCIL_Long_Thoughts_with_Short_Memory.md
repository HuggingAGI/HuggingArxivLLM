# PENCIL：长思考，短记忆

发布时间：2025年03月18日

`LLM应用` `人工智能` `推理系统`

> PENCIL: Long Thoughts with Short Memory

# 摘要

> 近期研究（如o1、DeepSeek R1等）在利用长链式思考（CoT）提升语言模型推理能力方面展现出巨大潜力，但在测试阶段实现其扩展性仍面临挑战，主要源于内存使用效率低下——中间计算结果在上下文中不断累积，即使对未来思考不再有用。我们提出PENCIL方法，该方法在自回归生成过程中引入了缩减机制，使模型能够基于训练过程中学习到的模式，递归清理不再需要的中间思考内容。借助这一缩减机制，PENCIL显著降低了生成过程中所需的最大上下文长度，从而在有限内存条件下实现更长的思考链，给予更多思考时间即可解决更大规模的问题。例如，我们展示了PENCIL在极具挑战性的爱因斯坦谜题上实现了97%的准确率——即使是GPT-4这样的大型模型也难以完成这一任务——而我们仅使用了一个参数量为25M、上下文长度为2048的小型变压器模型。从理论上讲，我们证明PENCIL能够通过模拟具有最优时间和空间复杂度的图灵机，实现通用的空间高效计算，从而能够解决任意给定上下文窗口限制的原本不可处理的计算任务。

> While recent works (e.g. o1, DeepSeek R1) have demonstrated great promise of using long Chain-of-Thought (CoT) to improve reasoning capabilities of language models, scaling it up during test-time is challenging due to inefficient memory usage -- intermediate computations accumulate indefinitely in context even no longer needed for future thoughts. We propose PENCIL, which incorporates a reduction mechanism into the autoregressive generation process, allowing the model to recursively clean up intermediate thoughts based on patterns learned from training. With this reduction mechanism, PENCIL significantly reduces the maximal context length required during generation, and thus can generate longer thoughts with limited memory, solving larger-scale problems given more thinking time. For example, we demonstrate PENCIL achieves 97\% accuracy on the challenging Einstein's puzzle -- a task even large models like GPT-4 struggle with -- using only a small 25M-parameter transformer with 2048 context length. Theoretically, we prove PENCIL can perform universal space-efficient computation by simulating Turing machines with optimal time and space complexity, and thus can solve arbitrary computational tasks that would otherwise be intractable given context window constraints.

[Arxiv](https://arxiv.org/abs/2503.14337)