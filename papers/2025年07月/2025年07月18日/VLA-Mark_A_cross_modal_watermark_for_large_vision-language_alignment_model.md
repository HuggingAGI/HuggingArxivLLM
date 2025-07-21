# VLA-Mark: 用于大规模视觉-语言对齐模型的跨模态水印

发布时间：2025年07月18日

`LLM应用` `人工智能` `知识产权保护`

> VLA-Mark: A cross modal watermark for large vision-language alignment model

# 摘要

> 视觉-语言模型的知识产权保护需要创新的水印方案，同时确保多模态一致性。现有文本水印技术因有偏标记选择和静态策略导致视觉-文本对齐失效，使语义关键概念易受攻击。为此，我们提出了VLA-Mark——一种视觉对齐框架，通过跨模态协调机制，在保持语义准确性的前提下实现水印嵌入。

该框架整合多尺度视觉-文本对齐度量，结合局部补丁亲和力、全局语义连贯性和上下文注意力模式，实现无需模型重训的水印注入。创新的熵敏感机制动态平衡水印强度与语义保护，在低不确定性生成阶段优先确保视觉定位。

实验结果显示，VLA-Mark在保持文本-视觉一致性的同时，实现了比传统方法低7.4%的困惑度（PPL）和高26.6%的BLEU值，检测准确率高达98.8%。面对改写和同义词替换等攻击时，该框架展现出96.1%的鲁棒性，为质量保留的多模态水印技术树立了新标杆。


> Vision-language models demand watermarking solutions that protect intellectual property without compromising multimodal coherence. Existing text watermarking methods disrupt visual-textual alignment through biased token selection and static strategies, leaving semantic-critical concepts vulnerable. We propose VLA-Mark, a vision-aligned framework that embeds detectable watermarks while preserving semantic fidelity through cross-modal coordination. Our approach integrates multiscale visual-textual alignment metrics, combining localized patch affinity, global semantic coherence, and contextual attention patterns, to guide watermark injection without model retraining. An entropy-sensitive mechanism dynamically balances watermark strength and semantic preservation, prioritizing visual grounding during low-uncertainty generation phases. Experiments show 7.4% lower PPL and 26.6% higher BLEU than conventional methods, with near-perfect detection (98.8% AUC). The framework demonstrates 96.1\% attack resilience against attacks such as paraphrasing and synonym substitution, while maintaining text-visual consistency, establishing new standards for quality-preserving multimodal watermarking

[Arxiv](https://arxiv.org/abs/2507.14067)