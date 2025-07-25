# GrAInS：基于梯度的归因方法，用于LLMs和VLMs推理时的引导

发布时间：2025年07月23日

`LLM应用` `视觉语言模型` `语言模型`

> GrAInS: Gradient-based Attribution for Inference-Time Steering of LLMs and VLMs

# 摘要

> 推理时的引导方法提供了一种轻量级的替代方案，通过在测试时修改模型的内部激活而不更新权重，避免了传统微调大型语言模型（LLMs）和视觉语言模型（VLMs）的复杂性。然而，现有方法存在三个主要问题：依赖固定全局干预向量、忽视单个输入令牌的因果影响、未能充分利用模型 logits 提供的有用梯度信息，尤其在视觉和文本输入贡献不均衡的多模态场景中表现突出。为了解决这些挑战，我们提出了 GrAInS，这是一种跨语言和视觉语言模型及任务的新型推理时引导方法。GrAInS 创新性地采用集成梯度的对比梯度归因技术，能够识别出对输出结果影响最大的 top-k 令牌，这些令牌根据其对期望与非期望输出的贡献，可以被正向或负向归因。通过这些关键令牌，GrAInS 构建方向引导向量，捕捉从不良行为到期望行为的语义转变。在推理过程中，GrAInS 根据令牌级归因信号动态调整 transformer 层的隐藏激活，并对激活进行归一化处理，以保持表征的尺度一致性。这种设计使得 GrAInS 在不重新训练模型或引入辅助监督的情况下，实现了对模型行为的细粒度、可解释且模块化的精准控制。实验结果充分证明了 GrAInS 的优越性：在 Llama-3.1-8B 上，TruthfulQA 的准确率显著提升了 13.22%；使用 LLaVA-1.6-7B，MMHal-Bench 的幻觉率从 0.624 降至 0.514；在 SPA-VL 上，对齐胜率提高了 8.11%。所有这些提升均在保持模型流畅性和通用能力的前提下实现，充分展示了 GrAInS 的强大性能和广泛应用潜力。

> Inference-time steering methods offer a lightweight alternative to fine-tuning large language models (LLMs) and vision-language models (VLMs) by modifying internal activations at test time without updating model weights. However, most existing approaches rely on fixed, global intervention vectors, overlook the causal influence of individual input tokens, and fail to leverage informative gradients from the model's logits, particularly in multimodal settings where visual and textual inputs contribute unevenly. To address these limitations, we introduce GrAInS, an inference-time steering approach that operates across both language-only and vision-language models and tasks. GrAInS uses contrastive, gradient-based attribution via Integrated Gradients to identify the top-k most influential tokens, both positively and negatively attributed based on their contribution to preferred versus dispreferred outputs. These tokens are then used to construct directional steering vectors that capture semantic shifts from undesirable to desirable behavior. During inference, GrAInS adjusts hidden activations at transformer layers guided by token-level attribution signals, and normalizes activations to preserve representational scale. This enables fine-grained, interpretable, and modular control over model behavior, without retraining or auxiliary supervision. Empirically, GrAInS consistently outperforms both fine-tuning and existing steering baselines: it achieves a 13.22% accuracy gain on TruthfulQA using Llama-3.1-8B, reduces hallucination rates on MMHal-Bench from 0.624 to 0.514 with LLaVA-1.6-7B, and improves alignment win rates on SPA-VL by 8.11%, all while preserving the model's fluency and general capabilities.

[Arxiv](https://arxiv.org/abs/2507.18043)