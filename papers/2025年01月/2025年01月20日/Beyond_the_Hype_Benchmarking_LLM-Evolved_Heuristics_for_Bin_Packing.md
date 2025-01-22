# 超越炒作：LLM启发式装箱算法的基准测试

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了将大型语言模型（LLMs）与进化算法结合，用于解决组合优化问题，并进行了严格的基准测试。这属于LLM在实际问题中的应用，因此归类为LLM应用。` `组合优化` `启发式方法`

> Beyond the Hype: Benchmarking LLM-Evolved Heuristics for Bin Packing

# 摘要

> 将大型语言模型（LLMs）与进化算法结合，最近在组合优化领域展现出显著潜力，能够设计出优于现有方法的新启发式方法。一场激烈的竞争正在迅速催生新启发式方法，并提升其进化效率。然而，由于急于证明新方法的优越性，针对特定领域的新启发式方法的评估往往流于表面：仅在少数数据集上测试，且这些实例都属于特定类别，每个类别的实例也很少。以装箱问题为例，我们首次对LLM生成的启发式方法进行了严格的基准测试，使用三个性能指标在大量基准实例上与现有知名启发式方法进行对比。对于每个启发式方法，我们进化出该启发式方法获胜的新实例，并通过实例空间分析揭示其在特征空间中的优势区域。我们发现，与现有简单启发式方法相比，大多数LLM启发式方法在广泛基准测试中表现不佳，并建议在生成仅在实例空间小区域内有效的专业启发式方法时，需谨慎权衡其收益与生成成本。

> Coupling Large Language Models (LLMs) with Evolutionary Algorithms has recently shown significant promise as a technique to design new heuristics that outperform existing methods, particularly in the field of combinatorial optimisation. An escalating arms race is both rapidly producing new heuristics and improving the efficiency of the processes evolving them. However, driven by the desire to quickly demonstrate the superiority of new approaches, evaluation of the new heuristics produced for a specific domain is often cursory: testing on very few datasets in which instances all belong to a specific class from the domain, and on few instances per class. Taking bin-packing as an example, to the best of our knowledge we conduct the first rigorous benchmarking study of new LLM-generated heuristics, comparing them to well-known existing heuristics across a large suite of benchmark instances using three performance metrics. For each heuristic, we then evolve new instances won by the heuristic and perform an instance space analysis to understand where in the feature space each heuristic performs well. We show that most of the LLM heuristics do not generalise well when evaluated across a broad range of benchmarks in contrast to existing simple heuristics, and suggest that any gains from generating very specialist heuristics that only work in small areas of the instance space need to be weighed carefully against the considerable cost of generating these heuristics.

[Arxiv](https://arxiv.org/abs/2501.11411)