# 警惕你的Po！深入探讨LLMs角色扮演微调中的AI安全风险测量与缓解策略

发布时间：2025年02月28日

`LLM应用

摘要主要探讨了角色扮演在大型语言模型中的应用及其带来的安全问题，并提出了一种新的微调方法来平衡角色适应性和安全性。这属于LLM的应用层面，特别是涉及模型在特定任务中的应用和优化。` `人工智能` `模型安全`

> Beware of Your Po! Measuring and Mitigating AI Safety Risks in Role-Play Fine-Tuning of LLMs

# 摘要

> 角色扮演让大型语言模型 (LLMs) 与用户的互动更沉浸、更个性化，但同时也带来了显著的安全隐患。现有的角色扮演微调技术虽然提升了角色适应性，却可能削弱安全性能，尤其在处理反派角色时表现明显。我们通过 RoleBench 训练了 95 个特定角色的 LLM，进行了首次全面的角色扮演微调风险评估。实验结果表明，角色扮演微调会导致安全性能明显下降，且安全风险因角色特质而异。

为应对这一挑战，我们提出了 Safety-Aware Role-Play Fine-Tuning (SaRFT)，这是一种平衡角色扮演能力和安全性的创新方法。在 LLaMA-3-8B-Instruct、Gemma-2-9B-it 和 Qwen2.5-7B-Instruct 等模型上的大量实验表明，SaRFT 在 LoRA 和全参数微调设置下均优于现有最佳基线。我们的研究结果强调了角色自适应安全措施的必要性，并为缓解角色扮演 LLM 中特定角色的安全风险提供了重要见解。

> Role-playing enables large language models (LLMs) to engage users in immersive and personalized interactions, but it also introduces significant safety risks. Existing role-play fine-tuning techniques improve role adaptability but may degrade safety performance, particularly for villainous characters. In this work, we conduct the first comprehensive assessment of role-play fine-tuning risks by training 95 role-specific LLMs using RoleBench. Our experiments reveal that role-play fine-tuning leads to a noticeable decline in safety performance, with safety risks varying based on character traits. To tackle this challenge, we propose Safety-Aware Role-Play Fine-Tuning (SaRFT), a novel method designed to balance role-playing capabilities and safety. Extensive experiments on LLaMA-3-8B-Instruct, Gemma-2-9B-it, and Qwen2.5-7B-Instruct demonstrate that SaRFT consistently outperforms state-of-the-art baselines under both LoRA and full-parameter fine-tuning settings. Our findings highlight the necessity of role-adaptive safety measures and provide insights into mitigating role-specific safety risks in role-playing LLMs.

[Arxiv](https://arxiv.org/abs/2502.20968)