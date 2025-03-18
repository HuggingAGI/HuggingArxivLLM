# TFHE-Coder：评测 LLM 驱动的全同态加密代码生成能力

发布时间：2025年03月15日

`LLM应用` `数据安全`

> TFHE-Coder: Evaluating LLM-agentic Fully Homomorphic Encryption Code Generation

# 摘要

> 环上的全同态加密（TFHE）能在不解密的情况下对加密数据进行计算，是安全与 confidential 计算的核心技术。尽管它在隐私保护机器学习、安全多方计算、私人区块链交易及安全医疗诊断等领域潜力巨大，但加密复杂性及使用上的挑战限制了其广泛应用。尽管已有多种 TFHE 库和编译器，但实际代码生成仍面临难题。我们提出一个集成编译器的框架，专注于评估 LLM 推理与智能体优化在 TFHE 代码生成中的效果，特别是在逻辑门和 ReLU 激活方面的表现。我们的方法从开源与闭源 LLM 的角度，评估了错误率、可编译性及结构相似性。结果显示，现成的模型存在明显局限，但通过检索增强生成（RAG）与少量样本提示等智能体优化手段，可有效降低错误率并提升代码保真度。这项研究首次为 TFHE 代码生成设立了基准，展示了 LLM 在特定领域反馈的助力下，如何有效弥补 FHE 代码生成中的专业鸿沟。

> Fully Homomorphic Encryption over the torus (TFHE) enables computation on encrypted data without decryption, making it a cornerstone of secure and confidential computing. Despite its potential in privacy preserving machine learning, secure multi party computation, private blockchain transactions, and secure medical diagnostics, its adoption remains limited due to cryptographic complexity and usability challenges. While various TFHE libraries and compilers exist, practical code generation remains a hurdle. We propose a compiler integrated framework to evaluate LLM inference and agentic optimization for TFHE code generation, focusing on logic gates and ReLU activation. Our methodology assesses error rates, compilability, and structural similarity across open and closedsource LLMs. Results highlight significant limitations in off-the-shelf models, while agentic optimizations such as retrieval augmented generation (RAG) and few-shot prompting reduce errors and enhance code fidelity. This work establishes the first benchmark for TFHE code generation, demonstrating how LLMs, when augmented with domain-specific feedback, can bridge the expertise gap in FHE code generation.

[Arxiv](https://arxiv.org/abs/2503.12217)