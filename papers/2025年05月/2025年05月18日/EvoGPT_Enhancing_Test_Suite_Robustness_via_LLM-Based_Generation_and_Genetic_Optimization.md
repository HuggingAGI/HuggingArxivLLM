# EvoGPT：提升测试套件鲁棒性，基于LLM生成与遗传优化

发布时间：2025年05月18日

`LLM应用` `软件工程` `单元测试`

> EvoGPT: Enhancing Test Suite Robustness via LLM-Based Generation and Genetic Optimization

# 摘要

> 大型语言模型（LLMs）作为自动化单元测试生成的有潜力工具，最近表现出色。我们提出了一种名为EvoGPT的混合框架，该框架将基于LLM的测试生成与进化搜索技术相结合，旨在创建多样化且能够揭示故障的单元测试。初始测试通过多种温度采样生成，以最大化行为和测试套件的多样性，随后通过生成-修复循环和覆盖率引导的断言增强进行优化。测试套件通过遗传算法进行进化，适应度函数优先考虑变异分数而非传统覆盖率指标。这一设计突出了单元测试的核心目标——故障检测。在多个开源Java项目上的评估显示，EvoGPT在代码覆盖率和变异分数方面均比LLMs和传统基于搜索的软件测试基线平均提高了10%。这些结果表明，结合LLM驱动的多样性、有针对性的修复和进化优化，可以生成更有效和健壮的测试套件。

> Large Language Models (LLMs) have recently emerged as promising tools for automated unit test generation. We introduce a hybrid framework called EvoGPT that integrates LLM-based test generation with evolutionary search techniques to create diverse, fault-revealing unit tests. Unit tests are initially generated with diverse temperature sampling to maximize behavioral and test suite diversity, followed by a generation-repair loop and coverage-guided assertion enhancement. The resulting test suites are evolved using genetic algorithms, guided by a fitness function prioritizing mutation score over traditional coverage metrics. This design emphasizes the primary objective of unit testing-fault detection. Evaluated on multiple open-source Java projects, EvoGPT achieves an average improvement of 10% in both code coverage and mutation score compared to LLMs and traditional search-based software testing baselines. These results demonstrate that combining LLM-driven diversity, targeted repair, and evolutionary optimization produces more effective and resilient test suites.

[Arxiv](https://arxiv.org/abs/2505.12424)