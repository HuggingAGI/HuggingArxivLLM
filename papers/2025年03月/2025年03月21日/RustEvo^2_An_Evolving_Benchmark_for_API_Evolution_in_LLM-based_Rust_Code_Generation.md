# RustEvo^2：一个不断演进的基准测试，旨在评估基于大语言模型的Rust代码生成中的API演变。

发布时间：2025年03月21日

`LLM应用` `软件开发` `代码生成`

> RustEvo^2: An Evolving Benchmark for API Evolution in LLM-based Rust Code Generation

# 摘要

> 大型语言模型（LLMs）在软件开发中的代码生成自动化方面发挥着关键作用。然而，面对Rust等快速发展的编程语言，这些模型在生成版本感知代码时面临重大挑战。由于不同版本之间的API频繁更改，导致兼容性问题和正确性错误。现有基准测试在评估模型应对API过渡的能力时存在不足，主要依赖劳动密集型的手动整理，且缺乏版本特定的深入见解。

为了解决这一问题，我们提出了RustEvo——一个创新框架，用于构建动态基准测试，专门评估LLMs适应Rust API演进的能力。RustEvo通过自动化合成588个API更改（包括380个来自Rust标准库和208个来自第三方 crates）到反映真实世界挑战的编程任务中，实现了数据集的自动化创建。这些任务涵盖四个主要的API演化类别：Stabilizations、Signature Changes、Behavioral Changes 和 Deprecations，全面反映了Rust生态系统中的实际演化模式。

实验结果表明，最先进的（SOTA）LLMs在不同API演化类型上的表现存在显著差异：在稳定API上的平均成功率为65.8%，而在行为更改上的成功率仅为38.0%，凸显了模型在没有签名更改的情况下检测语义变化的困难。此外，模型的知识截止日期对性能有显著影响，在截止日期前的API上得分56.1%，而在截止日期后的任务上得分仅为32.5%。通过引入检索增强生成（RAG），这一差距得到了显著缓解，平均将API发布后模型训练的成功率提高了13.5%。

我们的研究结果强调了演化感知基准测试在提升LLMs适应快速变化软件生态系统能力方面的必要性。RustEvo框架及其基准测试已公开发布，访问地址为https://github.com/SYSUSELab/RustEvo，为研究和实践提供了宝贵的资源和参考。


> Large Language Models (LLMs) have become pivotal tools for automating code generation in software development. However, these models face significant challenges in producing version-aware code for rapidly evolving languages like Rust, where frequent Application Programming Interfaces (API) changes across versions lead to compatibility issues and correctness errors. Existing benchmarks lack systematic evaluation of how models navigate API transitions, relying on labor-intensive manual curation and offering limited version-specific insights. To address this gap, we present RustEvo, a novel framework for constructing dynamic benchmarks that evaluate the ability of LLMs to adapt to evolving Rust APIs. RustEvo automates dataset creation by synthesizing 588 API changes (380 from Rust standard libraries, 208 from 15 third-party crates) into programming tasks mirroring real-world challenges. These tasks cover four API evolution categories: Stabilizations, Signature Changes, Behavioral Changes, and Deprecations, reflecting their actual distribution in the Rust ecosystem.
  Experiments on state-of-the-art (SOTA) LLMs reveal significant performance variations: models achieve a 65.8% average success rate on stabilized APIs but only 38.0% on behavioral changes, highlighting difficulties in detecting semantic shifts without signature alterations. Knowledge cutoff dates strongly influence performance, with models scoring 56.1% on before-cutoff APIs versus 32.5% on after-cutoff tasks. Retrieval-Augmented Generation (RAG) mitigates this gap, improving success rates by 13.5% on average for APIs released after model training. Our findings underscore the necessity of our evolution-aware benchmarks to advance the adaptability of LLMs in fast-paced software ecosystems. The framework and the benchmarks are publicly released at https://github.com/SYSUSELab/RustEvo.

[Arxiv](https://arxiv.org/abs/2503.16922)