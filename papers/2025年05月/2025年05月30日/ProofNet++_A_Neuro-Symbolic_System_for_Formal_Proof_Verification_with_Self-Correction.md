# ProofNet++: 具备自我修正能力的神经符号系统，用于形式证明验证

发布时间：2025年05月30日

`LLM应用` `定理证明`

> ProofNet++: A Neuro-Symbolic System for Formal Proof Verification with Self-Correction

# 摘要

> 我们提出了ProofNet++——一种结合大型语言模型（LLMs）、正式证明验证和自我修正机制的神经符号框架，旨在提升自动定理证明的效果。当前基于LLMs的系统普遍存在生成虚假逻辑步骤和推理过程无法验证的问题。ProofNet++通过引入符号证明树监督、使用验证器作为奖励函数的强化学习循环以及迭代自我修正模块，有效解决了这些问题。我们的实验结果显示，在miniF2F、Lean的mathlib和HOL Light上，ProofNet++相较于以往模型，在证明的准确性、正确性和正式可验证性方面均实现了显著提升。此外，我们还对基于验证器引导的强化学习框架的收敛性和稳定性进行了理论分析，并公开了我们的数据集和代码库，以助力未来研究。

> We propose ProofNet++, a neuro-symbolic framework that enhances automated theorem proving by combining large language models (LLMs) with formal proof verification and self-correction mechanisms. Current LLM-based systems suffer from hallucinated logical steps and unverifiable reasoning. ProofNet++ mitigates these limitations by integrating symbolic proof tree supervision, a reinforcement learning loop using verifiers as reward functions, and an iterative self-correction module. Our experiments on miniF2F, Lean's mathlib, and HOL Light show that ProofNet++ significantly improves proof accuracy, correctness, and formal verifiability over prior models. We provide theoretical analysis of the convergence and stability of the verifier-guided RL framework and release our datasets and codebase for future research.

[Arxiv](https://arxiv.org/abs/2505.24230)