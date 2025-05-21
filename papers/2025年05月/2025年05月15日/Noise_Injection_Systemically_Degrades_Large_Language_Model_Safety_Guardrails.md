# 噪声注入系统性降级大型语言模型安全防护机制

发布时间：2025年05月15日

`LLM理论` `人工智能`

> Noise Injection Systemically Degrades Large Language Model Safety Guardrails

# 摘要

> 大型语言模型（LLMs）中的安全护栏是防止产生有害输出的关键组件。然而，它们在受到扰动时的鲁棒性仍然知之甚少。本文中，我们通过系统性地向模型激活中注入高斯噪声，研究了LLMs中安全微调的稳健性。通过在多个开源模型中进行实验，我们发现：（1）高斯噪声使有害输出率显著增加，最高可达27%（p < 0.001）；（2）更深层次的安全微调并未提供额外的保护效果；（3）链式思维推理能力基本保持完整。这些发现揭示了当前安全对齐技术中的关键漏洞，并突显了基于推理和强化学习的方法在开发更稳健AI安全系统方面的潜力。这些结果对LLMs在安全关键应用中的实际部署具有重要意义，因为它们表明，即使没有对抗性提示，广泛使用的安全调优方法也可能失效。


> Safety guardrails in large language models (LLMs) are a critical component in preventing harmful outputs. Yet, their resilience under perturbation remains poorly understood. In this paper, we investigate the robustness of safety fine-tuning in LLMs by systematically injecting Gaussian noise into model activations. We show across multiple open-weight models that (1) Gaussian noise raises harmful-output rates (p < 0.001) by up to 27%, (2) that deeper safety fine-tuning affords no extra protection, and (3) that chain-of-thought reasoning remains largely intact. The findings reveal critical vulnerabilities in current safety alignment techniques and highlight the potential of reasoning-based and reinforcement learning approaches as promising direction for developing more robust AI safety systems. These results have important implications for real-world deployment of LLMs in safety-critical applications as these results imply that widely-deployed safety tuning methods can fail even without adversarial prompts.

[Arxiv](https://arxiv.org/abs/2505.13500)