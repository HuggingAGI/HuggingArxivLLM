# ReVeal：通过迭代生成与验证实现代码代理的自我演进

发布时间：2025年06月12日

`LLM应用` `AI推理` `代码生成`

> ReVeal: Self-Evolving Code Agents via Iterative Generation-Verification

# 摘要

> 近期，强化学习（RL）领域取得突破性进展，特别是在结合多轮工具交互时，显著提升了大型语言模型（LLMs）的推理能力。然而，现有方法在验证环节存在两大局限：缺乏真实环境中的有效验证信号，以及缺乏对验证过程的显式优化，导致自我验证的可靠性不足。为解决这些问题，我们提出了ReVeal——一个创新的多轮强化学习框架，通过将代码生成与显式的自我验证和工具化评估相结合，实现了模型能力的全面提升。ReVeal赋予LLMs自主生成测试用例的能力，能够调用外部工具获取精准反馈，并通过定制化的强化学习算法，借助密集的每轮奖励机制持续优化性能。通过这种设计，ReVeal实现了模型生成能力和验证能力的共同进化，显著拓展了基础模型的推理边界。实验证明，在LiveCodeBench基准测试中，ReVeal的Pass@k指标取得了显著提升。此外，ReVeal还支持推理过程的深度扩展，随着推理轮数的增加，代码持续优化，最终性能超越了DeepSeek-R1-Zero-Qwen-32B模型。这些成果充分展现了ReVeal作为构建更强大、更自主AI代理的可扩展且有效范式的巨大潜力。

> Recent advances in reinforcement learning (RL) with verifiable outcome rewards have significantly improved the reasoning capabilities of large language models (LLMs), especially when combined with multi-turn tool interactions. However, existing methods lack both meaningful verification signals from realistic environments and explicit optimization for verification, leading to unreliable self-verification. To address these limitations, we propose ReVeal, a multi-turn reinforcement learning framework that interleaves code generation with explicit self-verification and tool-based evaluation. ReVeal enables LLMs to autonomously generate test cases, invoke external tools for precise feedback, and improves performance via a customized RL algorithm with dense, per-turn rewards. As a result, ReVeal fosters the co-evolution of a model's generation and verification capabilities through RL training, expanding the reasoning boundaries of the base model, demonstrated by significant gains in Pass@k on LiveCodeBench. It also enables test-time scaling into deeper inference regimes, with code consistently evolving as the number of turns increases during inference, ultimately surpassing DeepSeek-R1-Zero-Qwen-32B. These findings highlight the promise of ReVeal as a scalable and effective paradigm for building more robust and autonomous AI agents.

[Arxiv](https://arxiv.org/abs/2506.11442)