# # 加速大型语言模型推理：基于推测搜索的创新方法

发布时间：2025年05月03日

`LLM应用` `计算效率`

> Accelerating Large Language Model Reasoning via Speculative Search

# 摘要

> 基于树搜索的推理方法通过探索多个中间推理步骤（即思路）显著提升了大型语言模型（LLMs）的推理能力。然而，这些方法由于需要生成大量推理思路而面临显著的推理延迟问题，限制了LLM的应用范围。为了解决这一挑战，我们提出了一种新型的Speculative Search（SpecSearch）框架，通过优化思路生成过程显著加速LLM推理。具体来说，SpecSearch利用一个小模型在思路和标记级别与大模型进行战略性协作，从而高效生成高质量的推理思路。SpecSearch的核心支柱是一种新型的质量保持拒绝机制，能够有效过滤掉质量低于大模型输出的思路。实验结果表明，SpecSearch在Qwen和Llama模型上显著优于现有最优方法，实现了高达2.12倍的速度提升，同时保持了相当的推理质量。

> Tree-search-based reasoning methods have significantly enhanced the reasoning capability of large language models (LLMs) by facilitating the exploration of multiple intermediate reasoning steps, i.e., thoughts. However, these methods suffer from substantial inference latency, as they have to generate numerous reasoning thoughts, severely limiting LLM applicability. To address this challenge, we propose a novel Speculative Search (SpecSearch) framework that significantly accelerates LLM reasoning by optimizing thought generation. Specifically, SpecSearch utilizes a small model to strategically collaborate with a large model at both thought and token levels, efficiently generating high-quality reasoning thoughts. The major pillar of SpecSearch is a novel quality-preserving rejection mechanism, which effectively filters out thoughts whose quality falls below that of the large model's outputs. Moreover, we show that SpecSearch preserves comparable reasoning quality to the large model. Experiments on both the Qwen and Llama models demonstrate that SpecSearch significantly outperforms state-of-the-art approaches, achieving up to 2.12$\times$ speedup with comparable reasoning quality.

[Arxiv](https://arxiv.org/abs/2505.02865)