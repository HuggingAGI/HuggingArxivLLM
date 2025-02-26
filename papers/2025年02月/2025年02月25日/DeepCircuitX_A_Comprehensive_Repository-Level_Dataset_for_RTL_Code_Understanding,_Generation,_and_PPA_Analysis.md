# DeepCircuitX：面向RTL代码理解、生成及PPA分析的全面代码仓库级数据集

发布时间：2025年02月25日

`LLM应用` `电子设计自动化` `硬件设计自动化`

> DeepCircuitX: A Comprehensive Repository-Level Dataset for RTL Code Understanding, Generation, and PPA Analysis

# 摘要

> 本文推出DeepCircuitX，一个专注于提升RTL代码理解、生成和PPA分析的全面仓库级数据集。与现有局限于文件级RTL代码或物理布局数据的数据集不同，DeepCircuitX构建了一个跨仓库、文件、模块和块级的多层次资源体系。这种创新结构使大型语言模型（LLMs）在RTL相关任务上的训练和评估更加精准。DeepCircuitX特别配备了链式思考（CoT）注释，对RTL代码的功能和结构进行了多层次的详细解析，使其在代码理解、生成和补全等任务中更具应用价值。此外，数据集还包含综合网表和PPA指标，为早期设计探索提供了有力支持，并实现了从RTL代码直接进行精确PPA预测的功能。通过在多种LLMs上进行微调实验，我们验证了DeepCircuitX的有效性，并通过人工评估确保了其高质量。实验结果表明，DeepCircuitX是推动硬件设计自动化中RTL相关机器学习应用不可或缺的资源。数据获取链接：https://zeju.gitbook.io/lcm-team。

> This paper introduces DeepCircuitX, a comprehensive repository-level dataset designed to advance RTL (Register Transfer Level) code understanding, generation, and power-performance-area (PPA) analysis. Unlike existing datasets that are limited to either file-level RTL code or physical layout data, DeepCircuitX provides a holistic, multilevel resource that spans repository, file, module, and block-level RTL code. This structure enables more nuanced training and evaluation of large language models (LLMs) for RTL-specific tasks. DeepCircuitX is enriched with Chain of Thought (CoT) annotations, offering detailed descriptions of functionality and structure at multiple levels. These annotations enhance its utility for a wide range of tasks, including RTL code understanding, generation, and completion. Additionally, the dataset includes synthesized netlists and PPA metrics, facilitating early-stage design exploration and enabling accurate PPA prediction directly from RTL code. We demonstrate the dataset's effectiveness on various LLMs finetuned with our dataset and confirm the quality with human evaluations. Our results highlight DeepCircuitX as a critical resource for advancing RTL-focused machine learning applications in hardware design automation.Our data is available at https://zeju.gitbook.io/lcm-team.

[Arxiv](https://arxiv.org/abs/2502.18297)