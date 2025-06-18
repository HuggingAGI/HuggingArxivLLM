# 别瞎编，LLM微调中保持不知则不知的态度

发布时间：2025年06月17日

`LLM理论` `人工智能`

> Don't Make It Up: Preserving Ignorance Awareness in LLM Fine-Tuning

# 摘要

> 目前关于大型语言模型（LLM）微调中缓解灾难性遗忘的研究，主要聚焦于保留特定数据或任务，但这一研究方向却忽视了一个关键问题：通过安全对齐注入的基本能力，特别是模型忠实表达无知的能力，会受到严重影响。在本研究中，我们发现这些能力在常规微调过程中会遭受显著退化，导致出现幻觉等不良行为。为了解决这一新颖但极具实用价值的问题，我们提出了SEAT，这是一种简单而有效的微调方法，能够在保持微调性能的同时，保留模型本应具备的承认无知的能力。SEAT整合了两个关键组件：(1) 通过约束激活漂移实现的稀疏训练，以及 (2) 一种结合KL散度正则化的新型实体扰动方法，旨在应对知识纠缠问题。实验结果表明，与现有方法相比，SEAT在保持微调性能的同时，显著提升了模型对无知的认知能力，为LLM微调提供了一种更 robust 的解决方案。

> Existing work on mitigating catastrophic forgetting in large language model (LLM) fine-tuning has primarily focused on preserving specific data or tasks, while critically overlooking the degradation of essential capabilities instilled through safety alignment, particularly the model's ability to faithfully express ignorance. In this work, we show that this capability is significantly degraded during conventional fine-tuning, leading to undesired behaviors such as hallucinations. To address this novel but highly practical problem, we propose SEAT, a simple and effective fine-tuning approach that preserves both fine-tuning performance and the model's inherent ability to acknowledge its ignorance. SEAT integrates two key components: (1) sparse training that constrains activation drift, and (2) a novel entity perturbation method with KL-divergence regularization, designed to counter knowledge entanglement. Experimental results demonstrate that SEAT significantly outperforms baselines in preserving ignorance awareness while retaining fine-tuning performance, offering a more robust solution for LLM fine-tuning.

[Arxiv](https://arxiv.org/abs/2506.14387)