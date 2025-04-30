# # 内存受限条件下强化学习在LLM推理中的应用

发布时间：2025年04月29日

`LLM应用` `计算资源优化`

> Reinforcement Learning for LLM Reasoning Under Memory Constraints

# 摘要

> 我们研究了强化学习技术，旨在优化大型语言模型在特定问题空间中的推理能力，同时应对内存和计算资源的限制。我们的重点是与LoRA微调兼容的无批评者方法，这些方法能在单个40GB GPU上运行，这是学术研究中的常见限制。我们提出了S-GRPO（Group Relative Policy Optimization的内存高效变体）和T-SPMO（一种基于token级别的前缀匹配策略，用于细粒度信用分配）。尽管资源有限，使用LoRA训练对Qwen2-1.5B进行微调时，两种方法均显著提升了SVAMP基准测试的准确性，从46%提升至70%以上。T-SPMO在多位数乘法任务中表现尤为突出，这表明在硬件约束下进行RL微调具有巨大潜力。此外，我们的全token GRPO基线在LoRA微调下未提升模型性能（与基础模型相比），这表明我们的内存高效方法可能通过仅更新参数子集起到稳定训练的正则化作用。

> We explore reinforcement learning (RL) techniques to enhance reasoning within targeted problem spaces in large language models (LLMs) under memory and compute constraints. Our focus is on critic-free methods compatible with LoRA fine-tuning on a single 40GB GPU, a common limitation in academic settings. We introduce S-GRPO, a memory-efficient variant of Group Relative Policy Optimization, and T-SPMO, a token-level prefix matching strategy for fine-grained credit assignment. Despite limited resources, when used to fine-tune Qwen2-1.5B both methods significantly improve SVAMP benchmark accuracy from 46% to above 70% using LoRA training. T-SPMO also excels in multi-digit multiplication tasks, underscoring the potential of RL fine-tuning under hardware constraints. Additionally, we find that our full-token GRPO baseline under LoRA fine-tuning did not improve model performance (compared to base model) on either task, suggesting that our memory-efficient methods may act as a form of regularization that stabilizes training when only a small subset of parameters are updated.

[Arxiv](https://arxiv.org/abs/2504.20834)