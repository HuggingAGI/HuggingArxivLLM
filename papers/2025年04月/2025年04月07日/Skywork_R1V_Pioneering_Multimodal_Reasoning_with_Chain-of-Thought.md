# Skywork R1V：以链式思维引领多模态推理新潮流

发布时间：2025年04月07日

`LLM应用

摘要：论文介绍了Skywork R1V，一个通过多模态迁移方法扩展大型语言模型到视觉领域的推理模型。重点在于模型的应用和优化，属于LLM的实际应用。` `人工智能`

> Skywork R1V: Pioneering Multimodal Reasoning with Chain-of-Thought

# 摘要

> 我们推出Skywork R1V，一款通过高效多模态迁移方法将R1系列大型语言模型（LLM）扩展至视觉领域的多模态推理模型。借助轻量级视觉投影器，Skywork R1V实现了多模态的无缝适配，无需对基础语言模型或视觉编码器进行重新训练。为了加强视觉与文本的对齐，我们提出了一种结合迭代监督微调（SFT）与组相对策略优化（GRPO）的混合优化策略，显著提升了跨模态整合效率。此外，我们引入了一种自适应长度的链式思考蒸馏方法，用于推理数据生成。该方法动态优化推理链的长度，从而提升推理效率，避免过度思考。实证评估显示，Skywork R1V仅凭380亿参数便展现出强劲性能，在MMMU基准测试中获得69.0分，在MathVista中达到67.5分。同时，它在文本推理方面表现稳健，分别在AIME和MATH500中取得了72.0和94.0的优异成绩。Skywork R1V模型权重已公开发布，以推动开放与可重复性研究。

> We introduce Skywork R1V, a multimodal reasoning model extending the an R1-series Large language models (LLM) to visual modalities via an efficient multimodal transfer method. Leveraging a lightweight visual projector, Skywork R1V facilitates seamless multimodal adaptation without necessitating retraining of either the foundational language model or the vision encoder. To strengthen visual-text alignment, we propose a hybrid optimization strategy that combines Iterative Supervised Fine-Tuning (SFT) with Group Relative Policy Optimization (GRPO), significantly enhancing cross-modal integration efficiency. Additionally, we introduce an adaptive-length Chain-of-Thought distillation approach for reasoning data generation. This approach dynamically optimizes reasoning chain lengths, thereby enhancing inference efficiency and preventing excessive reasoning overthinking. Empirical evaluations demonstrate that Skywork R1V, with only 38B parameters, delivers competitive performance, achieving a score of 69.0 on the MMMU benchmark and 67.5 on MathVista. Meanwhile, it maintains robust textual reasoning performance, evidenced by impressive scores of 72.0 on AIME and 94.0 on MATH500. The Skywork R1V model weights have been publicly released to promote openness and reproducibility.

[Arxiv](https://arxiv.org/abs/2504.05599)