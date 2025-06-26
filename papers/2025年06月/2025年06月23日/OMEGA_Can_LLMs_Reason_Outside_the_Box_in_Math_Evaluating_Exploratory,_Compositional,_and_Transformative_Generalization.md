# OMEGA：大型语言模型能否在数学中跳出思维定式？探索探索性、组合性和变革性泛化能力

发布时间：2025年06月23日

`LLM应用

理由：这篇论文探讨了大型语言模型在数学推理任务中的应用，特别是在评估模型的分布外推能力方面。它引入了一个新的评测基准OMEGA，用于系统性地评估模型在不同维度上的推理能力，并通过实验分析模型的表现和局限性。这些研究属于大型语言模型的应用层面，因此归类为LLM应用。` `数学推理` `机器学习`

> OMEGA: Can LLMs Reason Outside the Box in Math? Evaluating Exploratory, Compositional, and Transformative Generalization

# 摘要

> 近期，具有长链式推理能力的大型语言模型（如DeepSeek-R1）在奥赛级别的数学基准测试中取得了令人瞩目的成绩。但它们往往依赖于有限的策略集，难以应对需要全新思维方式的问题。为了系统性探究这些局限性，我们引入了OMEGA——一个基于Boden创造力分类法设计的分布外推评测基准，旨在从三个维度评估模型的分布外推能力：

(1) 探索性——将已知解题技巧应用于同一领域更复杂的实例；
(2) 组合性——整合孤立学习的不同推理技能，解决需要新型整合方式的新型问题；
(3) 转化性——突破传统方法，采用新颖甚至非传统的策略更高效地解决问题。

OMEGA由几何、数论、代数、组合数学、逻辑和谜题等领域的模板化问题生成器程序化生成训练-测试配对，通过符号、数值或图形方法验证解答。我们评估了前沿大型语言模型，发现随着问题复杂度增加，模型性能急剧下降。此外，我们对Qwen系列模型进行了全维度微调，观察到探索性外推能力显著提升，但组合性外推仍受限制，转化性推理改进微乎其微。通过隔离和量化这些精细失败模式，OMEGA为推动大型语言模型超越机械熟练度，迈向真正的数学创造力奠定了基础。

> Recent large-scale language models (LLMs) with long Chain-of-Thought reasoning-such as DeepSeek-R1-have achieved impressive results on Olympiad-level mathematics benchmarks. However, they often rely on a narrow set of strategies and struggle with problems that require a novel way of thinking. To systematically investigate these limitations, we introduce OMEGA-Out-of-distribution Math Problems Evaluation with 3 Generalization Axes-a controlled yet diverse benchmark designed to evaluate three axes of out-of-distribution generalization, inspired by Boden's typology of creativity: (1) Exploratory-applying known problem solving skills to more complex instances within the same problem domain; (2) Compositional-combining distinct reasoning skills, previously learned in isolation, to solve novel problems that require integrating these skills in new and coherent ways; and (3) Transformative-adopting novel, often unconventional strategies by moving beyond familiar approaches to solve problems more effectively. OMEGA consists of programmatically generated training-test pairs derived from templated problem generators across geometry, number theory, algebra, combinatorics, logic, and puzzles, with solutions verified using symbolic, numerical, or graphical methods. We evaluate frontier (or top-tier) LLMs and observe sharp performance degradation as problem complexity increases. Moreover, we fine-tune the Qwen-series models across all generalization settings and observe notable improvements in exploratory generalization, while compositional generalization remains limited and transformative reasoning shows little to no improvement. By isolating and quantifying these fine-grained failures, OMEGA lays the groundwork for advancing LLMs toward genuine mathematical creativity beyond mechanical proficiency.

[Arxiv](https://arxiv.org/abs/2506.18880)