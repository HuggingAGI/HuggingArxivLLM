# **Leanabell-Prover-V2：通过强化学习实现形式定理证明中的验证器集成推理**

发布时间：2025年07月11日

`LLM应用` `形式化验证`

> Leanabell-Prover-V2: Verifier-integrated Reasoning for Formal Theorem Proving via Reinforcement Learning

# 摘要

> 我们很高兴推出我们的Leanabell-Prover-V2！这是一个70亿参数的大型语言模型，能够生成Lean 4中的正式定理证明，并集成了验证器的长链式思维（Long Chain-of-Thoughts，CoT）。延续前期工作Leanabell-Prover-V1的思路，我们继续对现有的强大证明模型进行微调，以进一步提升性能。在V2版本中，我们主要通过Lean 4验证器提供的反馈来优化强化学习（Reinforcement Learning，RL）。通过验证器的反馈，如指示成功或详细说明特定错误，LLM能够“自我感知”其推理过程的正确性，并学会反射性地纠正错误。Leanabell-Prover-V2通过多轮验证器交互直接优化LLM的推理轨迹，同时结合反馈令牌遮蔽以实现稳定的RL训练，并采用简单的奖励策略。实验结果显示，在MiniF2F测试集上，相较于Kimina-Prover-Preview-Distill-7B和DeepSeek-Prover-V2-7B，性能分别提升了3.2%（pass@128）和2.0%（pass@128）。源代码、整理好的数据和模型可在以下链接获取：https://github.com/Leanabell-LM/Leanabell-Prover-V2。

> We introduce our Leanabell-Prover-V2, a 7B large language models (LLMs) that can produce formal theorem proofs in Lean 4, with verifier-integrated Long Chain-of-Thoughts (CoT). Following our previous work Leanabell-Prover-V1, we continual to choose to posttrain existing strong prover models for further performance improvement. In our V2 version, we mainly upgrade the Reinforcement Learning (RL) with feedback provided by the Lean 4 verifier. Crucially, verifier feedback, such as indicating success or detailing specific errors, allows the LLM to become ``self-aware'' of the correctness of its own reasoning process and learn to reflexively correct errors. Leanabell-Prover-V2 directly optimizes LLM reasoning trajectories with multi-turn verifier interactions, together with feedback token masking for stable RL training and a simple reward strategy. Experiments show that Leanabell-Prover-V2 improves performance by 3.2% (pass@128) with Kimina-Prover-Preview-Distill-7B and 2.0% (pass@128) with DeepSeek-Prover-V2-7B on the MiniF2F test set. The source codes, curated data and models are available at: https://github.com/Leanabell-LM/Leanabell-Prover-V2.

[Arxiv](https://arxiv.org/abs/2507.08649)