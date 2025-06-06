# # **测试时缩放方法的样本复杂度与表示能力**  
探讨测试时缩放方法在样本复杂度与表示能力方面的表现。

发布时间：2025年06月05日

`LLM理论` `大型语言模型` `多任务学习`

> Sample Complexity and Representation Ability of Test-time Scaling Paradigms

# 摘要

> 测试时缩放范式显著提升了大型语言模型 (LLMs) 在复杂任务中的能力。尽管这些策略在实践中取得了成功，但我们对各种测试时策略的样本效率 -- 如自我一致性、最佳选择策略和自我修正 -- 的理论理解仍然有限。在本研究中，我们首先明确了两种重复采样策略之间的区别：自我一致性需要 $Θ(1/Δ^2)$ 个样本才能生成正确答案，而最佳选择策略只需 $Θ(1/Δ)$ 个样本，其中 $Δ < 1$ 表示正确答案与次可能答案的概率差。接下来，我们展示了自我修正方法结合验证器反馈的表达能力：它使 Transformer 模型能够在测试时模拟对专家池的在线学习。因此，单一的 Transformer 架构可以在没有特定任务先验知识的情况下，证明能够解决多个任务，从而将 Transformer 的表示理论从单任务扩展到多任务场景。最后，我们通过实验验证了我们的理论结果，展示了自我修正方法的实际有效性。

> Test-time scaling paradigms have significantly advanced the capabilities of large language models (LLMs) on complex tasks. Despite their empirical success, theoretical understanding of the sample efficiency of various test-time strategies -- such as self-consistency, best-of-$n$, and self-correction -- remains limited. In this work, we first establish a separation result between two repeated sampling strategies: self-consistency requires $Θ(1/Δ^2)$ samples to produce the correct answer, while best-of-$n$ only needs $Θ(1/Δ)$, where $Δ< 1$ denotes the probability gap between the correct and second most likely answers. Next, we present an expressiveness result for the self-correction approach with verifier feedback: it enables Transformers to simulate online learning over a pool of experts at test time. Therefore, a single Transformer architecture can provably solve multiple tasks without prior knowledge of the specific task associated with a user query, extending the representation theory of Transformers from single-task to multi-task settings. Finally, we empirically validate our theoretical results, demonstrating the practical effectiveness of self-correction methods.

[Arxiv](https://arxiv.org/abs/2506.05295)