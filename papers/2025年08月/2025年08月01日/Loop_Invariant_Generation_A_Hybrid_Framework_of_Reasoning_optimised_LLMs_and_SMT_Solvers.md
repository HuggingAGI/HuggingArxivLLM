# 循环不变式生成：推理优化LLMs与SMT求解器的混合框架

发布时间：2025年08月01日

`LLM应用` `软件工程` `程序分析`

> Loop Invariant Generation: A Hybrid Framework of Reasoning optimised LLMs and SMT Solvers

# 摘要

> 循环不变式是证明循环程序正确性的关键。然而，开发循环不变式极具挑战性，完全自动化的合成难以实现。已有研究提出了基于符号技术和神经方法的解决方案，但这些方法仅适用于标准基准测试的部分子集。在本研究中，我们探讨现代大型语言模型是否能在这方面做得更好。

我们整合了 OpenAI 的 O1、O1-mini 和 O3-mini 模型，与 Z3 SMT 求解器构建了一个生成与验证的流水线，通过求解器的反例迭代优化不变式。我们的实验基于 Code2Inv 基准测试，该测试提供了 C 程序及其形式化的前提和后置条件。在包含 133 个任务的测试中，我们的框架实现了 100% 的覆盖率，超越了此前 107 个任务的最佳表现，且每个实例仅需 1-2 次模型提案，耗时 14-55 秒。这表明，大型语言模型具备潜在的逻辑推理能力，可助力循环不变式的自动化合成。尽管当前实验聚焦于 C 语言，但该方法应可推广至其他命令式语言。

> Loop invariants are essential for proving the correctness of programs with loops. Developing loop invariants is challenging, and fully automatic synthesis cannot be guaranteed for arbitrary programs. Some approaches have been proposed to synthesize loop invariants using symbolic techniques and more recently using neural approaches. These approaches are able to correctly synthesize loop invariants only for subsets of standard benchmarks. In this work, we investigate whether modern, reasoning-optimized large language models can do better. We integrate OpenAI's O1, O1-mini, and O3-mini into a tightly coupled generate-and-check pipeline with the Z3 SMT solver, using solver counterexamples to iteratively guide invariant refinement. We use Code2Inv benchmark, which provides C programs along with their formal preconditions and postconditions. On this benchmark of 133 tasks, our framework achieves 100% coverage (133 out of 133), outperforming the previous best of 107 out of 133, while requiring only 1-2 model proposals per instance and 14-55 seconds of wall-clock time. These results demonstrate that LLMs possess latent logical reasoning capabilities which can help automate loop invariant synthesis. While our experiments target C-specific programs, this approach should be generalizable to other imperative languages.

[Arxiv](https://arxiv.org/abs/2508.00419)