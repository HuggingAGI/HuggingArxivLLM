# # 大型语言模型能否预估并行代码性能表现？

发布时间：2025年05月06日

`LLM应用` `高性能计算` `人工智能`

> Can Large Language Models Predict Parallel Code Performance?

# 摘要

> 准确评估并行GPU代码的性能通常需要在目标硬件上进行执行时间分析，但受限于高端GPU资源的获取难度，这一过程变得日益困难。本文探讨了大型语言模型（LLMs）能否提供一种无需依赖硬件的GPU性能预测新方法。我们将问题定义为一个 Roofline 模型分类任务：给定一个GPU内核的源代码和目标GPU的硬件规格，LLM能否预测该GPU内核是计算密集型还是带宽密集型？

    为此研究，我们构建了一个包含340个GPU内核的平衡数据集，这些内核来自HeCBench基准测试，采用CUDA和OpenMP编写，并通过实测GPU分析获得了其真实标签。我们从四个场景评估LLMs的表现：(1) 访问内核源代码的分析数据，(2) 仅基于源代码的零样本预测，(3) 基于代码和标签对的少样本学习，(4) 在小型定制数据集上进行微调。

    我们的结果表明，最先进的LLMs对Roofline模型有着深刻理解，在提供明确分析数据时可实现100%的分类准确率。我们还发现，具备推理能力的LLMs在零样本和少样本场景下显著优于标准LLMs，对GPU源代码的预测准确率最高可达64%，且无需分析数据。最后，我们发现LLM微调需要远超当前可用规模的数据量。

    本研究是首批尝试通过分类方法利用LLMs进行源代码级Roofline性能预测的工作之一，展示了其在运行时分析不可行时指导优化工作的潜力。我们的发现表明，借助更优质的数据集和提示策略，LLMs有望成为高性能计算性能分析和性能移植的实用工具。
    

> Accurate determination of the performance of parallel GPU code typically requires execution-time profiling on target hardware -- an increasingly prohibitive step due to limited access to high-end GPUs. This paper explores whether Large Language Models (LLMs) can offer an alternative approach for GPU performance prediction without relying on hardware. We frame the problem as a roofline classification task: given the source code of a GPU kernel and the hardware specifications of a target GPU, can an LLM predict whether the GPU kernel is compute-bound or bandwidth-bound?
  For this study, we build a balanced dataset of 340 GPU kernels, obtained from HeCBench benchmark and written in CUDA and OpenMP, along with their ground-truth labels obtained via empirical GPU profiling. We evaluate LLMs across four scenarios: (1) with access to profiling data of the kernel source, (2) zero-shot with source code only, (3) few-shot with code and label pairs, and (4) fine-tuned on a small custom dataset.
  Our results show that state-of-the-art LLMs have a strong understanding of the Roofline model, achieving 100% classification accuracy when provided with explicit profiling data. We also find that reasoning-capable LLMs significantly outperform standard LLMs in zero- and few-shot settings, achieving up to 64% accuracy on GPU source codes, without profiling information. Lastly, we find that LLM fine-tuning will require much more data than what we currently have available.
  This work is among the first to use LLMs for source-level roofline performance prediction via classification, and illustrates their potential to guide optimization efforts when runtime profiling is infeasible. Our findings suggest that with better datasets and prompt strategies, LLMs could become practical tools for HPC performance analysis and performance portability.

[Arxiv](https://arxiv.org/abs/2505.03988)