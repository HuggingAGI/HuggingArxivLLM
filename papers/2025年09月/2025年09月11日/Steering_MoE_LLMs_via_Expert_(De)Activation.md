# 通过专家（去）激活引导MoE大型语言模型

发布时间：2025年09月11日

`LLM应用` `基础理论`

> Steering MoE LLMs via Expert (De)Activation

# 摘要

> 大型语言模型（LLMs）中的混合专家模型（MoE）会将每个token路由至专门的前馈网络（FFN）子集，即所谓的“专家”。我们提出SteerMoE框架，它通过检测并控制与行为相关的专家来引导MoE模型。我们的检测方法能识别出在表现出对比行为的成对输入中具有独特激活模式的专家。在推理时，我们通过有选择地激活（或停用）这些专家，无需重新训练或修改权重，就能控制忠实度、安全性等行为。在11项基准测试和6个LLM上，我们的引导方法将安全性提升了最高+20%，忠实度提升了+27%。在对抗性攻击模式中，单独使用时安全性降低-41%；若与现有越狱方法结合，则安全性降低-100%，完全绕过所有安全护栏，同时揭示了隐藏在专家中的对齐伪造这一新维度。

> Mixture-of-Experts (MoE) in Large Language Models (LLMs) routes each token through a subset of specialized Feed-Forward Networks (FFN), known as experts. We present SteerMoE, a framework for steering MoE models by detecting and controlling behavior-linked experts. Our detection method identifies experts with distinct activation patterns across paired inputs exhibiting contrasting behaviors. By selectively (de)activating such experts during inference, we control behaviors like faithfulness and safety without retraining or modifying weights. Across 11 benchmarks and 6 LLMs, our steering raises safety by up to +20% and faithfulness by +27%. In adversarial attack mode, it drops safety by -41% alone, and -100% when combined with existing jailbreak methods, bypassing all safety guardrails and exposing a new dimension of alignment faking hidden within experts.

[Arxiv](https://arxiv.org/abs/2509.09660)