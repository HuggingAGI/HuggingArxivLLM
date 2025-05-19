# LARGO：利用梯度优化实现潜在对抗性反思，实现LLM越狱

发布时间：2025年05月16日

`LLM理论

摘要讨论了通过优化潜在向量来攻击大型语言模型的方法，涉及模型的内部机制和优化策略，属于理论层面的研究。` `人工智能安全` `人工智能`

> LARGO: Latent Adversarial Reflection through Gradient Optimization for Jailbreaking LLMs

# 摘要

> 发现大型语言模型 (LLMs) 漏洞的高效红队攻击方法至关重要。尽管近期攻击常将LLMs作为优化器，但离散语言空间使基于梯度的方法难以施展。我们引入LARGO（通过梯度优化实现的潜在对抗性反思），这是一种新颖的潜在自我反思攻击方法，重新确立了基于梯度优化生成流畅越狱提示的能力。通过在LLM的连续潜在空间中运行，LARGO首先优化一个对抗性的潜在向量，然后递归调用同一LLM将潜在向量解码为自然语言。这一方法生成了一种快速、有效且可迁移的攻击手段，能够产生流畅且隐蔽的提示。在AdvBench和JailbreakBench等标准基准测试中，LARGO在攻击成功率上超越了包括AutoDAN在内的领先越狱技术，高出44个百分点。我们的研究结果展示了一种强大的替代方法，用于提示具有能动性的LLMs，突显了通过梯度优化解读和攻击LLM内部机制的有效性。

> Efficient red-teaming method to uncover vulnerabilities in Large Language Models (LLMs) is crucial. While recent attacks often use LLMs as optimizers, the discrete language space make gradient-based methods struggle. We introduce LARGO (Latent Adversarial Reflection through Gradient Optimization), a novel latent self-reflection attack that reasserts the power of gradient-based optimization for generating fluent jailbreaking prompts. By operating within the LLM's continuous latent space, LARGO first optimizes an adversarial latent vector and then recursively call the same LLM to decode the latent into natural language. This methodology yields a fast, effective, and transferable attack that produces fluent and stealthy prompts. On standard benchmarks like AdvBench and JailbreakBench, LARGO surpasses leading jailbreaking techniques, including AutoDAN, by 44 points in attack success rate. Our findings demonstrate a potent alternative to agentic LLM prompting, highlighting the efficacy of interpreting and attacking LLM internals through gradient optimization.

[Arxiv](https://arxiv.org/abs/2505.10838)