# 多智能体LLM的JUit测试生成：基于强oracle的解决方案

发布时间：2025年06月03日

`LLM应用` `软件工程` `软件开发`

> A Multi-agent LLM-based JUit Test Generation with Strong Oracles

# 摘要

> 单元测试是保障软件质量的关键环节。然而，手动编写测试用例不仅耗时，对于Java等强类型语言更是倍感繁琐，这推动了自动化测试方法的发展。传统测试生成主要依赖搜索或随机算法，通过模拟现有程序行为生成回归测试用例，但这类方法难以反映程序的实际预期功能。

我们提出了一种全新的自动化JUnit测试生成框架——CANDOR。该框架整合多种专业LLM代理，能够自动生成高质量的测试前缀和精准的预期结果。针对LLM常见的幻觉问题，我们创新性地采用多推理模型协同工作模式，通过共识机制生成可靠的预期结果。此外，我们设计了一套双模型流水线，有效精简推理输出，生成结构清晰的测试结果评估。

实验结果表明，CANDOR在HumanEvalJava和LeetCodeJava数据集上表现出色，不仅生成的预期结果准确可靠，在代码覆盖率和变异测试分数方面均超越现有工具EvoSuite。与当前最先进的基于提示的测试生成器相比，CANDOR在预期结果准确性上提升了15.8至25.1个百分点。消融实验进一步验证了关键组件对提升测试质量和准确性的重要作用。


> Unit testing plays a critical role in ensuring software correctness. However, writing unit tests manually is laborious, especially for strong typed languages like Java, motivating the need for automated approaches. Traditional methods primarily rely on search-based or randomized algorithms to generate tests that achieve high code coverage and produce regression oracles, which are derived from the program's current behavior rather than its intended functionality. Recent advances in large language models (LLMs) have enabled oracle generation from natural language descriptions. However, existing LLM-based methods often require LLM fine-tuning or rely on external tools such as EvoSuite for test prefix generation.
  In this work, we propose CANDOR, a novel end-to-end, prompt-based LLM framework for automated JUnit test generation. CANDOR orchestrates multiple specialized LLM agents to generate JUnit tests, including both high-quality test prefixes and accurate oracles. To mitigate the notorious hallucinations in LLMs, we introduce a novel strategy that engages multiple reasoning LLMs in a panel discussion and generate accurate oracles based on consensus. Additionally, to reduce the verbosity of reasoning LLMs' outputs, we propose a novel dual-LLM pipeline to produce concise and structured oracle evaluations.
  Our experiments on the HumanEvalJava and LeetCodeJava datasets show that CANDOR can generate accurate oracles and is slightly better than EvoSuite in generating tests with high line coverage and clearly superior in terms of mutation score. Moreover, CANDOR significantly outperforms the state-of-the-art, prompt-based test generator LLM-Empirical, achieving improvements of 15.8 to 25.1 percentage points in oracle correctness on both correct and faulty source code. Ablation studies confirm the critical contributions of key agents in improving test prefix quality and oracle accuracy.

[Arxiv](https://arxiv.org/abs/2506.02943)