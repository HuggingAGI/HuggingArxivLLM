# # **无限指令**：大规模优化指令选择与合成，助力提升语言模型性能

发布时间：2025年06月09日

`LLM应用` `人工智能` `数据集`

> Infinity Instruct: Scaling Instruction Selection and Synthesis to Enhance Language Models

# 摘要

> 大型语言模型（LLMs）在实际应用中表现出色，但现有的开源指令数据集往往局限于狭窄领域，如数学或编程，这限制了模型的泛化能力，并与专有模型的差距进一步拉大。为了解决这一问题，我们推出了Infinity-Instruct，一个高质量的指令数据集，通过两阶段的流水线设计，全面提升LLMs的基础和对话能力。第一阶段，我们从1亿多样本中精选出740万个高质量的基础指令（InfInstruct-F-7.4M），采用混合数据筛选技术。第二阶段，通过指令选择、优化和诊断过滤的两步流程，生成150万个高质量的对话指令（InfInstruct-G-1.5M）。我们对多个开源模型（包括Mistral、LLaMA、Qwen和Yi）进行微调测试，结果显示在基础任务和指令遵循基准上均有显著提升，超越官方微调版本。值得注意的是，InfInstruct-LLaMA3.1-70B在指令遵循任务上比GPT-4-0314高出8.6%，同时保持了相当的基础性能。这些成果凸显了基础与对话训练的协同效应，为全面优化LLM开发提供了新思路。我们的数据集ootnote{https://huggingface.co/datasets/BAAI/Infinity-Instruct}和代码ootnote{https://gitee.com/li-touch/infinity-instruct}已公开发布。

> Large Language Models (LLMs) demonstrate strong performance in real-world applications, yet existing open-source instruction datasets often concentrate on narrow domains, such as mathematics or coding, limiting generalization and widening the gap with proprietary models. To bridge this gap, we introduce Infinity-Instruct, a high-quality instruction dataset designed to enhance both foundational and chat capabilities of LLMs through a two-phase pipeline. In Phase 1, we curate 7.4M high-quality foundational instructions (InfInstruct-F-7.4M) from over 100M samples using hybrid data selection techniques. In Phase 2, we synthesize 1.5M high-quality chat instructions (InfInstruct-G-1.5M) through a two-stage process involving instruction selection, evolution, and diagnostic filtering. We empirically evaluate Infinity-Instruct by fine-tuning several open-source models, including Mistral, LLaMA, Qwen, and Yi, and observe substantial performance gains across both foundational and instruction following benchmarks, consistently surpassing official instruction-tuned counterparts. Notably, InfInstruct-LLaMA3.1-70B outperforms GPT-4-0314 by 8.6\% on instruction following tasks while achieving comparable foundational performance. These results underscore the synergy between foundational and chat training and offer new insights into holistic LLM development. Our dataset\footnote{https://huggingface.co/datasets/BAAI/Infinity-Instruct} and codes\footnote{https://gitee.com/li-touch/infinity-instruct} have been publicly released.

[Arxiv](https://arxiv.org/abs/2506.11116)