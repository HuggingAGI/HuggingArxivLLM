# # 前缀微调+：通过独立注意力前缀数据改进前缀微调方法
前缀微调（Prefix-Tuning）是一种在自然语言处理任务中微调预训练语言模型的有效方法。通过在输入序列前添加特定的前缀提示（prefix prompt），模型能够更好地理解和处理目标任务。然而，传统的前缀微调方法通常需要为每个任务单独设计和优化前缀提示，这在实际应用中可能带来一定的挑战和限制。

发布时间：2025年06月16日

`LLM理论` `模型微调`

> Prefix-Tuning+: Modernizing Prefix-Tuning through Attention Independent Prefix Data

# 摘要

> 参数高效微调（PEFT）方法已成为快速将大型语言模型（LLMs）适应下游任务的关键。作为一种早期且有效的PEFT技术，前缀调优展示了在显著降低计算和内存开销的同时，达到与全参数微调相当性能的能力。然而，尽管它在早期取得了成功，但在训练现代最先进的LLMs时，其有效性却非常有限。本研究通过实证表明，前缀调优在LLMs上表现不佳，原因在于注意力头中输入与前缀重要性之间存在固有的权衡。这促使我们引入了前缀调优+（Prefix-Tuning+），这是一种新型架构，它在继承前缀调优核心原则的同时，通过将前缀模块移出注意力头本身来弥补其不足。我们还概述了构建过程，以指导未来用户在开发自己的基于上下文的方法时参考。实验结果表明，Prefix-Tuning+在各类基准测试中均显著优于现有前缀调优方法。值得注意的是，在多个通用基准测试中，其性能可与广泛采用的LoRA方法相媲美，凸显了前缀调优方法现代化扩展的潜力。我们的研究发现表明，通过克服其固有局限性，前缀调优仍可作为参数高效LLM适配领域中具有竞争力和相关性的研究方向。

> Parameter-Efficient Fine-Tuning (PEFT) methods have become crucial for rapidly adapting large language models (LLMs) to downstream tasks. Prefix-Tuning, an early and effective PEFT technique, demonstrated the ability to achieve performance comparable to full fine-tuning with significantly reduced computational and memory overhead. However, despite its earlier success, its effectiveness in training modern state-of-the-art LLMs has been very limited. In this work, we demonstrate empirically that Prefix-Tuning underperforms on LLMs because of an inherent tradeoff between input and prefix significance within the attention head. This motivates us to introduce Prefix-Tuning+, a novel architecture that generalizes the principles of Prefix-Tuning while addressing its shortcomings by shifting the prefix module out of the attention head itself. We further provide an overview of our construction process to guide future users when constructing their own context-based methods. Our experiments show that, across a diverse set of benchmarks, Prefix-Tuning+ consistently outperforms existing Prefix-Tuning methods. Notably, it achieves performance on par with the widely adopted LoRA method on several general benchmarks, highlighting the potential modern extension of Prefix-Tuning approaches. Our findings suggest that by overcoming its inherent limitations, Prefix-Tuning can remain a competitive and relevant research direction in the landscape of parameter-efficient LLM adaptation.

[Arxiv](https://arxiv.org/abs/2506.13674)