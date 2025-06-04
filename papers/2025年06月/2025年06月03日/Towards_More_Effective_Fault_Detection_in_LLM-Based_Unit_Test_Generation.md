# 更有效的故障检测：基于LLM的单元测试生成探索

发布时间：2025年06月03日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在生成单元测试中的应用，特别是在提高变异分数方面的有效性。研究提出了一种新的基于LLM的测试生成方法MUTGEN，并通过实验验证了其在变异分数上的优越性。这属于LLM在特定任务中的应用，因此归类为LLM应用。` `软件工程` `测试生成`

> Towards More Effective Fault Detection in LLM-Based Unit Test Generation

# 摘要

> 单元测试是发现软件潜在缺陷的关键工具。尽管像EvoSuite这样的工具专注于最大化代码覆盖率，但大型语言模型（LLMs）的最新进展已将研究重点转向基于LLM的测试生成。然而，代码覆盖率指标（如行覆盖率和分支覆盖率）尽管在报告研究中被过度强调，但它们对测试套件缺陷检测能力的指示作用较弱。相比之下，	extit{变异分数}提供了更可靠和严格的度量标准。正如我们在研究中发现的那样，某些测试套件实现了100\%的覆盖率，但仅获得4\%的变异分数。尽管少数研究考虑了变异分数，但LLMs在杀死变异体方面的有效性仍未得到充分探索。
在本文中，我们提出了MUTGEN，这是一种变异引导的、基于LLM的测试生成方法，它将变异反馈直接整合到提示中。在来自两个基准的204个测试对象上进行评估，MUTGEN在变异分数方面显著优于EvoSuite和传统的基于提示的策略。此外，MUTGEN引入了一种迭代生成机制，进一步推动了LLMs在杀死额外变异体方面的极限。我们的研究还提供了对基于LLM生成的限制的见解，分析了变异体存活和未被覆盖的原因，以及不同变异算子对生成效果的影响。

> Unit tests play a vital role in uncovering potential faults in software. While tools like EvoSuite focus on maximizing code coverage, recent advances in large language models (LLMs) have shifted attention toward LLM-based test generation. However, code coverage metrics -- such as line and branch coverage -- remain overly emphasized in reported research, despite being weak indicators of a test suite's fault-detection capability. In contrast, \textit{mutation score} offers a more reliable and stringent measure, as demonstrated in our findings where some test suites achieve 100\% coverage but only 4\% mutation score. Although a few studies consider mutation score, the effectiveness of LLMs in killing mutants remains underexplored.
  In this paper, we propose MUTGEN, a mutation-guided, LLM-based test generation approach that incorporates mutation feedback directly into the prompt. Evaluated on 204 subjects from two benchmarks, MUTGEN significantly outperforms both EvoSuite and vanilla prompt-based strategies in terms of mutation score. Furthermore, MUTGEN introduces an iterative generation mechanism that pushes the limits of LLMs in killing additional mutants. Our study also provide insights into the limitations of LLM-based generation, analyzing the reasons for live and uncovered mutants, and the impact of different mutation operators on generation effectiveness.

[Arxiv](https://arxiv.org/abs/2506.02954)