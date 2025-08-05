# CAAD: 上下文感知自适应解码助力真实文本生成

发布时间：2025年08月04日

`LLM应用` `问答系统`

> CAAD: Context-Aware Adaptive Decoding for Truthful Text Generation

# 摘要

> 在大型语言模型中，确保生成文本的真实性仍然是一个关键挑战。虽然监督微调和带有反馈的强化学习展现出潜力，但它们需要大量标注数据和计算资源，限制了实际应用的扩展性。相比之下，解码时的干预提供了一种无需重新训练模型的轻量级解决方案。然而，现有的解码策略常常面临提示敏感性、有限的泛化能力或对内部模型状态的依赖等问题。

我们提出了一种上下文感知的自适应解码方法，该方法利用一个由最少10个标注示例构建的紧凑参考 grounding 空间，在推理过程中实现基于检索的 logits 形塑。这个空间包含上下文嵌入和真实响应的下一个标记 logits 的配对。在每个解码步骤，我们的方法检索与当前上下文语义最相似的前N个上下文，并聚合它们的下一个标记 logits 来修改 LLM 的 logits。

在三个开放问答基准测试中，我们的方法在 TruthfulQA 上平均提高了2.8个百分点，并在 Biographies 和 WikiQA 上进一步超越现有基线。实验结果还展示了跨任务的泛化能力，TruthfulQA 衍生的 grounding 有助于传记生成。我们的模型不可知、可扩展且高效的方法仅需一次生成过程，突显了上下文感知解码在提升 LLM 事实可靠性方面的潜力。

> Ensuring truthfulness in large language models remains a critical challenge for reliable text generation. While supervised fine-tuning and reinforcement learning with human feedback have shown promise, they require substantial amount of annotated data and computational resources, limiting scalability. In contrast, decoding-time interventions offer lightweight alternatives without model retraining. However, existing decoding strategies often face issues like prompt sensitivity, limited generalization, or dependence on internal model states. We propose a context-aware adaptive decoding method that leverages a compact reference grounding space, built from as few as 10 annotated examples and comprising pairs of context embeddings and next token logits from truthful responses, to enable retrieval-based logit shaping during inference. At each decoding step, our method retrieves top-N semantically similar contexts and aggregates their associated next token logits to modify the LLM's logits. Across three open-ended question-answering benchmarks, our approach achieves a 2.8 percent average improvement on TruthfulQA and further outperforms existing baselines on both Biographies and WikiQA. Experimental results also demonstrate cross-task generalization, with TruthfulQA-derived grounding enhancing biography generation. Our model-agnostic, scalable, and efficient method requires only a single generation pass, highlighting the potential of context-aware decoding for factual reliability in LLMs.

[Arxiv](https://arxiv.org/abs/2508.02184)