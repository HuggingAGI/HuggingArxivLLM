# AssertBench: 评估大型语言模型自述能力的基准测试

发布时间：2025年06月08日

`LLM理论` `人工智能` `信息检索`

> AssertBench: A Benchmark for Evaluating Self-Assertion in Large Language Models

# 摘要

> 近期的基准测试揭示了大型语言模型（LLMs）在事实一致性与修辞稳健性方面的表现。然而，关于事实正确陈述的方向性引导如何影响模型的一致性，仍存在研究空白。AssertBench通过从事实验证数据集FEVEROUS中采样有证据支持的事实，填补了这一空白。针对每个事实，我们构建了两种引导提示：一种是用户声称该陈述正确，另一种是用户声称其错误。随后，我们记录模型的评估结果与推理过程。理想情况下，模型应保持立场坚定，无论引导如何变化，都应维持一致的事实评估，而不是随用户观点改变。AssertBench通过基于模型在中立呈现相同声明时的准确性对结果进行分层，从而分离引导引起的变异性与模型内在的事实知识。通过这种方式，该基准测试旨在衡量LLM在面对用户对同一事实提出相互矛盾的主张时，是否能够“坚守立场”。完整的源代码可在https://github.com/achowd32/assert-bench获取。

> Recent benchmarks have probed factual consistency and rhetorical robustness in Large Language Models (LLMs). However, a knowledge gap exists regarding how directional framing of factually true statements influences model agreement, a common scenario for LLM users. AssertBench addresses this by sampling evidence-supported facts from FEVEROUS, a fact verification dataset. For each (evidence-backed) fact, we construct two framing prompts: one where the user claims the statement is factually correct, and another where the user claims it is incorrect. We then record the model's agreement and reasoning. The desired outcome is that the model asserts itself, maintaining consistent truth evaluation across both framings, rather than switching its evaluation to agree with the user. AssertBench isolates framing-induced variability from the model's underlying factual knowledge by stratifying results based on the model's accuracy on the same claims when presented neutrally. In doing so, this benchmark aims to measure an LLM's ability to "stick to its guns" when presented with contradictory user assertions about the same fact. The complete source code is available at https://github.com/achowd32/assert-bench.

[Arxiv](https://arxiv.org/abs/2506.11110)