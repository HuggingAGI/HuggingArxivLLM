# Hunyuan-TurboS：Mamba-Transformer 协同创新，自适应链式思维驱动大型语言模型突破

发布时间：2025年05月21日

`LLM理论` `对话系统`

> Hunyuan-TurboS: Advancing Large Language Models through Mamba-Transformer Synergy and Adaptive Chain-of-Thought

# 摘要

> 随着大型语言模型 (LLMs) 的快速发展，我们推出了 Hunyuan-TurboS——一款创新的大型混合 Transformer-Mamba 专家混合模型 (MoE)。它巧妙地结合了 Mamba 在长序列处理中的高效性与 Transformer 在上下文理解方面的优势。Hunyuan-TurboS 搭载了自适应长-短链式思考 (CoT) 机制，能够根据查询的复杂程度，在快速响应与深度“思考”模式之间智能切换，从而优化计算资源的使用。从架构上看，这一激活参数为 56B（总参数 560B）的模型采用了 128 层（Mamba2、Attention、FFN），并引入了创新的 AMF/MF 块模式。更快的 Mamba2 确保了线性复杂度，分组查询注意力减少了 KV 缓存的占用，而 FFN 则采用了 MoE 结构。经过 16T 高质量令牌的预训练，Hunyuan-TurboS 支持长达 256K 的上下文长度，并且是首个在行业中成功部署的大规模 Mamba 模型。我们的全面后训练策略包括监督微调（300 万指令）、新型自适应长-短 CoT 融合方法、多轮商讨学习以实现迭代改进，以及针对 STEM 和通用指令遵循的两阶段大规模强化学习过程，进一步提升了模型的能力。评估结果显示，Hunyuan-TurboS 表现优异：在 LMSYS Chatbot Arena 中总体排名第 7，得分为 1356，超越了 Gemini-2.0-Flash-001（1352）和 o4-mini-2025-04-16（1345）等领先模型。在 23 个自动化基准测试中，TurboS 也取得了 77.9% 的平均成绩。Hunyuan-TurboS 在高性能与效率之间实现了卓越的平衡，相较于许多推理模型，它在保持强大能力的同时，推理成本更低，从而为高效大规模预训练模型树立了新的范式。

> As Large Language Models (LLMs) rapidly advance, we introduce Hunyuan-TurboS, a novel large hybrid Transformer-Mamba Mixture of Experts (MoE) model. It synergistically combines Mamba's long-sequence processing efficiency with Transformer's superior contextual understanding. Hunyuan-TurboS features an adaptive long-short chain-of-thought (CoT) mechanism, dynamically switching between rapid responses for simple queries and deep "thinking" modes for complex problems, optimizing computational resources. Architecturally, this 56B activated (560B total) parameter model employs 128 layers (Mamba2, Attention, FFN) with an innovative AMF/MF block pattern. Faster Mamba2 ensures linear complexity, Grouped-Query Attention minimizes KV cache, and FFNs use an MoE structure. Pre-trained on 16T high-quality tokens, it supports a 256K context length and is the first industry-deployed large-scale Mamba model. Our comprehensive post-training strategy enhances capabilities via Supervised Fine-Tuning (3M instructions), a novel Adaptive Long-short CoT Fusion method, Multi-round Deliberation Learning for iterative improvement, and a two-stage Large-scale Reinforcement Learning process targeting STEM and general instruction-following. Evaluations show strong performance: overall top 7 rank on LMSYS Chatbot Arena with a score of 1356, outperforming leading models like Gemini-2.0-Flash-001 (1352) and o4-mini-2025-04-16 (1345). TurboS also achieves an average of 77.9% across 23 automated benchmarks. Hunyuan-TurboS balances high performance and efficiency, offering substantial capabilities at lower inference costs than many reasoning models, establishing a new paradigm for efficient large-scale pre-trained models.

[Arxiv](https://arxiv.org/abs/2505.15431)