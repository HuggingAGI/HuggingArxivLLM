# 黑盒模型合并：面向大规模模型仓库的语言模型即服务

发布时间：2025年09月16日

`LLM应用` `基础理论`

> Black-box Model Merging for Language-Model-as-a-Service with Massive Model Repositories

# 摘要

> 模型合并是指将多个不同模型整合为一个统一模型的过程，这个统一模型能保留并融合各模型的优势与能力。现有多数方法依赖任务向量来组合模型，其前提通常是模型参数可访问。但对于GPT-4这类超大型语言模型（LLMs），它们常仅通过API接口以黑盒服务形式提供（即语言模型即服务），模型权重对终端用户而言无法获取。这带来了一大挑战，我们将其命名为超大型LLMs的黑盒模型合并（BMM）。为应对这一挑战，我们提出了一种基于进化算法的无导数优化框架（Evo-Merging），该框架仅通过推理时的API查询就能实现高效的模型合并。我们的方法包含两个核心组件：（1）基于稀疏性的去噪模块，用于识别并滤除跨模型的无关或冗余信息；（2）符号感知缩放模块，能根据相关模型的性能动态计算其最优组合权重。我们还为非对称稀疏化提供了严谨的理论证明与分析。大量实验评估显示，我们的方法在多项任务上均达到了最先进水平，性能显著优于现有的强基线模型。

> Model merging refers to the process of integrating multiple distinct models into a unified model that preserves and combines the strengths and capabilities of the individual models. Most existing approaches rely on task vectors to combine models, typically under the assumption that model parameters are accessible. However, for extremely large language models (LLMs) such as GPT-4, which are often provided solely as black-box services through API interfaces (Language-Model-as-a-Service), model weights are not available to end users. This presents a significant challenge, which we refer to as black-box model merging (BMM) with massive LLMs. To address this challenge, we propose a derivative-free optimization framework based on the evolutionary algorithm (Evo-Merging) that enables effective model merging using only inference-time API queries. Our method consists of two key components: (1) sparsity-based denoising, designed to identify and filter out irrelevant or redundant information across models, and (2) sign-aware scaling, which dynamically computes optimal combination weights for the relevant models based on their performance. We also provide a formal justification, along with a theoretical analysis, for our asymmetric sparsification. Extensive experimental evaluations demonstrate that our approach achieves state-of-the-art results on a range of tasks, significantly outperforming existing strong baselines.

[Arxiv](https://arxiv.org/abs/2509.12951)