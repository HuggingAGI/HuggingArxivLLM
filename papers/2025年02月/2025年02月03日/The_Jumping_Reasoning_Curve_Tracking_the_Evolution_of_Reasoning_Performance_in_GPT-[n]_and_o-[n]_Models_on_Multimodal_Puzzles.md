# 推理能力的飞跃？追踪 GPT-[n] 和 o-[n] 模型在多模态谜题上的推理性能演变

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（如 OpenAI 的 o1 和 o3）在高级推理能力上的表现，特别是它们在多模态任务中的表现。论文通过追踪模型在复杂多模态谜题上的表现，分析了模型在推理能力上的提升和局限性。这些内容主要涉及对大型语言模型的理论分析和性能评估，因此应归类为LLM理论。` `人工智能` `多模态学习`

> The Jumping Reasoning Curve? Tracking the Evolution of Reasoning Performance in GPT-[n] and o-[n] Models on Multimodal Puzzles

# 摘要

> OpenAI 的 o1 和 o3 发布标志着大型语言模型在高级推理能力上的重大突破。o3 在 ARC-AGI 基准测试中，其问题解决和技能获取能力甚至超越了人类。然而，这一基准仅针对符号模式，而人类通常能处理涉及视觉和语言的多模态场景。因此，研究多模态任务中的高级推理能力迫在眉睫。为此，我们追踪了 GPT-[n] 和 o-[n] 系列模型在复杂多模态谜题上的表现，这些谜题需要结合细粒度视觉感知与抽象或算法推理。o1 的卓越性能是以 GPT-4o 近 750 倍的计算成本为代价的，这引发了对其效率的担忧。结果显示，模型迭代中推理能力显著提升，尤其是从 GPT 系列到 o1 的跨越。然而，o1 在处理需要抽象推理的简单多模态谜题时仍显吃力，且在算法谜题上的表现也不尽如人意。我们将持续跟踪该系列新模型，并更新本文结果。所有评估资源均已公开：https://github.com/declare-lab/LLM-PuzzleTest。

> The releases of OpenAI's o1 and o3 mark a significant paradigm shift in Large Language Models towards advanced reasoning capabilities. Notably, o3 outperformed humans in novel problem-solving and skill acquisition on the Abstraction and Reasoning Corpus for Artificial General Intelligence (ARC-AGI). However, this benchmark is limited to symbolic patterns, whereas humans often perceive and reason about multimodal scenarios involving both vision and language data. Thus, there is an urgent need to investigate advanced reasoning capabilities in multimodal tasks. To this end, we track the evolution of the GPT-[n] and o-[n] series models on challenging multimodal puzzles, requiring fine-grained visual perception with abstract or algorithmic reasoning. The superior performance of o1 comes at nearly 750 times the computational cost of GPT-4o, raising concerns about its efficiency. Our results reveal a clear upward trend in reasoning capabilities across model iterations, with notable performance jumps across GPT-series models and subsequently to o1. Nonetheless, we observe that the o1 model still struggles with simple multimodal puzzles requiring abstract reasoning. Furthermore, its performance in algorithmic puzzles remains poor. We plan to continuously track new models in the series and update our results in this paper accordingly. All resources used in this evaluation are openly available https://github.com/declare-lab/LLM-PuzzleTest.

[Arxiv](https://arxiv.org/abs/2502.01081)