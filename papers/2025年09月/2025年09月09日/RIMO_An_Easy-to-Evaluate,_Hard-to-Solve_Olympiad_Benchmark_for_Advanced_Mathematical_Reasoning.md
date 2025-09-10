# RIMO：一个易于评估却难以解答的高级数学推理奥赛基准

发布时间：2025年09月09日

`LLM应用` `基础理论`

> RIMO: An Easy-to-Evaluate, Hard-to-Solve Olympiad Benchmark for Advanced Mathematical Reasoning

# 摘要

> 随着大型语言模型（LLMs）在GSM8K、MATH等成熟数学基准测试中取得高分，研究界开始将目光投向国际数学奥林匹克（IMO）题目，以拓展评估边界。但现有奥林匹克级基准测试存在实际局限，会导致评分噪音与潜在偏差——例如答案格式异构需依赖模型评判，且可能依赖有缺陷的解题步骤。为此，我们提出RIMO双赛道基准测试——在保留奥林匹克顶级难度的同时，彻底消除这类评估噪音。第一赛道RIMO-N重写了335道IMO题目，使其仅存在唯一整数答案，可实现确定性的正确性校验；第二赛道RIMO-P包含456道证明题，配有专家校验的标准答案，并将其拆解为一系列子问题，通过自动化评分系统评估逐步推理过程。我们对GPT-4o、Gemini 2.5 Flash等10个前沿大型语言模型进行了测试，结果显示：尽管这些模型在传统基准测试中表现优异，但在RIMO上的性能却大幅下降。这些结果表明，当前大型语言模型的能力与真正的奥林匹克级别推理之间仍存在显著差距。RIMO不仅提供了极具挑战性的测试场景，还实现了便捷评估，为未来研究提供了高分辨率的衡量标准，也为弥合我们发现的这一巨大推理差距指明了明确方向。

> As large language models (LLMs) reach high scores on established mathematical benchmarks, such as GSM8K and MATH, the research community has turned to International Mathematical Olympiad (IMO) problems to push the evaluation frontier. However, existing Olympiad-level benchmarks suffer from practical constraints that introduce grading noise and potential bias, such as heterogeneous answer formats requiring model-based judges and a reliance on potentially flawed solutions. We introduce RIMO, a two-track benchmark designed to preserve peak Olympiad difficulty while eliminating this evaluation noise. The first track, RIMO-N, rewrites 335 IMO problems to admit a single, unique integer answer, allowing for deterministic correctness checking. The second track, RIMO-P, features 456 proof problems with expert-checked solutions, which are decomposed into a sequence of sub-problems to evaluate the step-by-step reasoning process via an automated grading system. Our benchmarking of ten frontier LLMs, including GPT-4o and Gemini 2.5 Flash, reveals that while these systems excel on older benchmarks, their performance drops sharply on RIMO. These results highlight a substantial gap between current LLM capabilities and actual Olympiad-level reasoning. By providing a challenging yet easy-to-evaluate suite, RIMO offers a high-resolution yardstick for future research, presenting a clear target for closing the profound reasoning gap our findings expose.

[Arxiv](https://arxiv.org/abs/2509.07711)