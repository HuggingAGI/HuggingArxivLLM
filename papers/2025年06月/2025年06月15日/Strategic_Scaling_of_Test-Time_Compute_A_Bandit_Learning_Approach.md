# 战略性扩展推理计算：基于多臂老虎机的学习方法

发布时间：2025年06月15日

`LLM理论

这篇论文探讨了大型语言模型的计算资源分配策略，通过理论分析和算法设计来优化模型性能，属于LLM理论类别。`

> Strategic Scaling of Test-Time Compute: A Bandit Learning Approach

# 摘要

> 测试时间计算扩展策略已成为提升大型语言模型性能的有力手段。然而，现有方法通常采用"一刀切"的计算资源分配方式，忽视了不同查询难度的差异。针对这一低效现状，我们将测试时间计算分配建模为一个新型多臂老虎机学习问题，并提出自适应算法，实时评估查询难度并动态分配计算资源。与均匀分配方式相比，我们的算法为更具挑战性的查询分配更多计算资源，同时保持对简单查询的处理精度。在处理困难查询时，我们的算法进一步学习优先处理可解实例，从而有效避免对不可解查询的过度计算。我们从理论上证明，相较于均匀分配，我们的算法在计算效率上更具优势，并通过数学和代码基准测试实证验证了其有效性。具体而言，我们的算法在MATH-500数据集上实现了最高11.10%（15.04%相对）的性能提升，在LiveCodeBench上实现了最高7.41%（14.40%相对）的性能提升。

> Scaling test-time compute has emerged as an effective strategy for improving the performance of large language models. However, existing methods typically allocate compute uniformly across all queries, overlooking variation in query difficulty. To address this inefficiency, we formulate test-time compute allocation as a novel bandit learning problem and propose adaptive algorithms that estimate query difficulty on the fly and allocate compute accordingly. Compared to uniform allocation, our algorithms allocate more compute to challenging queries while maintaining accuracy on easier ones. Among challenging queries, our algorithms further learn to prioritize solvable instances, effectively reducing excessive computing on unsolvable queries. We theoretically prove that our algorithms achieve better compute efficiency than uniform allocation and empirically validate their effectiveness on math and code benchmarks. Specifically, our algorithms achieve up to an 11.10% performance improvement (15.04% relative) on the MATH-500 dataset and up to a 7.41% performance improvement (14.40% relative) on LiveCodeBench.

[Arxiv](https://arxiv.org/abs/2506.12721)