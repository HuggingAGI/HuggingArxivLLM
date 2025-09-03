# DaCe AD：统一机器学习与科学计算的高性能自动微分

发布时间：2025年09月02日

`其他` `基础理论`

> DaCe AD: Unifying High-Performance Automatic Differentiation for Machine Learning and Scientific Computing

# 摘要

> 自动微分（AD）是一类无需人工干预、系统应用链式法则计算函数梯度的技术。尽管其技术基础早在数十年前就已确立，但如今它正迎来复兴——在机器学习算法的反向传播中，AD成为高效计算梯度的核心；同时，它对科学计算领域也至关重要，尤其是那些将机器学习模型融入科学模拟与方案的新兴技术。现有AD框架存在四大局限：编程语言支持不足、需修改代码以兼容AD、科学计算代码性能欠佳，以及对梯度计算所需的前向传播数据采用简单的“全存储”方案。这些局限迫使领域科学家不得不手动计算大型问题的梯度。本文提出DaCe AD——一款通用高效的自动微分引擎，无需任何代码修改。它采用基于ILP的新型算法，通过优化存储与重计算的权衡，在给定内存约束下实现性能最大化。我们将其应用于NPBench（一组包含多样科学计算模式的高性能计算基准测试套件）以验证通用性。结果显示，在无需任何代码改动的情况下，DaCe AD的性能平均超过JAX（具备最先进通用AD能力的Python框架）92倍以上。

> Automatic differentiation (AD) is a set of techniques that systematically applies the chain rule to compute the gradients of functions without requiring human intervention. Although the fundamentals of this technology were established decades ago, it is experiencing a renaissance as it plays a key role in efficiently computing gradients for backpropagation in machine learning algorithms. AD is also crucial for many applications in scientific computing domains, particularly emerging techniques that integrate machine learning models within scientific simulations and schemes. Existing AD frameworks have four main limitations: limited support of programming languages, requiring code modifications for AD compatibility, limited performance on scientific computing codes, and a naive store-all solution for forward-pass data required for gradient calculations. These limitations force domain scientists to manually compute the gradients for large problems. This work presents DaCe AD, a general, efficient automatic differentiation engine that requires no code modifications. DaCe AD uses a novel ILP-based algorithm to optimize the trade-off between storing and recomputing to achieve maximum performance within a given memory constraint. We showcase the generality of our method by applying it to NPBench, a suite of HPC benchmarks with diverse scientific computing patterns, where we outperform JAX, a Python framework with state-of-the-art general AD capabilities, by more than 92 times on average without requiring any code changes.

[Arxiv](https://arxiv.org/abs/2509.02197)