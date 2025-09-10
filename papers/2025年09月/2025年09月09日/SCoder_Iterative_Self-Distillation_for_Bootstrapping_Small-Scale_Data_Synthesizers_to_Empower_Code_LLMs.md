# SCoder：迭代式自蒸馏自举小规模数据合成器赋能代码LLMs

发布时间：2025年09月09日

`LLM应用` `基础理论`

> SCoder: Iterative Self-Distillation for Bootstrapping Small-Scale Data Synthesizers to Empower Code LLMs

# 摘要

> 现有代码大模型（LLMs）的微调往往依赖从专有LLMs蒸馏的大规模指令数据，成本高昂。本文探索了小规模开源LLMs（如7B模型）作为高质量代码指令数据合成器的潜力。研究发现，通过训练少量来自专有LLMs的优质合成样本，可显著提升小规模LLMs的数据合成能力。据此，我们提出一种新颖的迭代自蒸馏方法，引导小规模LLMs进化为强大合成器，从而减少对专有LLMs的依赖并降低成本。具体来说，在每次迭代中，为获取多样化、高质量的自蒸馏数据，我们设计了多检查点采样与多维度评分策略用于初始数据筛选；同时，引入基于梯度的影响估计方法，精准识别关键样本以完成最终数据过滤。基于这些小规模合成器生成的代码指令数据集，我们开发了SCoder——这是一系列基于DeepSeek-Coder微调的代码生成模型。实验表明，SCoder模型达到了当前最优的代码生成水平，充分验证了该方法的有效性。

> Existing code large language models (LLMs) often rely on large-scale instruction data distilled from proprietary LLMs for fine-tuning, which typically incurs high costs. In this paper, we explore the potential of small-scale open-source LLMs (e.g., 7B) as synthesizers for high-quality code instruction data construction. We first observe that the data synthesis capability of small-scale LLMs can be enhanced by training on a few superior data synthesis samples from proprietary LLMs. Building on this, we propose a novel iterative self-distillation approach to bootstrap small-scale LLMs, transforming them into powerful synthesizers that reduce reliance on proprietary LLMs and minimize costs. Concretely, in each iteration, to obtain diverse and high-quality self-distilled data, we design multi-checkpoint sampling and multi-aspect scoring strategies for initial data selection. Furthermore, to identify the most influential samples, we introduce a gradient-based influence estimation method for final data filtering. Based on the code instruction datasets from the small-scale synthesizers, we develop SCoder, a family of code generation models fine-tuned from DeepSeek-Coder. SCoder models achieve state-of-the-art code generation capabilities, demonstrating the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2509.07858)