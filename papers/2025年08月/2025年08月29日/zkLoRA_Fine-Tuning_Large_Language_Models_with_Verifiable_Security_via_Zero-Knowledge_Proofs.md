# zkLoRA：基于零知识证明的大型语言模型可验证安全微调

发布时间：2025年08月29日

`LLM应用` `基础理论`

> zkLoRA: Fine-Tuning Large Language Models with Verifiable Security via Zero-Knowledge Proofs

# 摘要

> 微调大型语言模型（LLMs）是使其适配特定任务的关键，但这一过程计算成本高昂，且在不可信环境中，其正确性与隐私问题尤为突出。尽管低秩适应（LoRA）等参数高效方法大幅降低了资源消耗，但在零知识约束下确保微调的安全性与可验证性仍是亟待解决的难题。为此，我们提出zkLoRA——首个将LoRA微调与零知识证明（ZKPs）相结合的框架，实现了可证明的安全性与正确性。zkLoRA运用查找参数、和校验协议及多项式承诺等先进密码学技术，验证基于Transformer架构中的算术与非算术运算。该框架为LoRA微调中的前向传播、反向传播及参数更新提供端到端可验证性，同时保障模型参数与训练数据的隐私安全。借助基于GPU的实现，zkLoRA在LLaMA等开源LLMs上通过实验验证，展现出实用性与效率，可扩展至130亿参数。zkLoRA将参数高效微调与ZKPs相结合，填补了关键空白，让LLMs得以在敏感或不可信环境中安全可靠地部署。

> Fine-tuning large language models (LLMs) is crucial for adapting them to specific tasks, yet it remains computationally demanding and raises concerns about correctness and privacy, particularly in untrusted environments. Although parameter-efficient methods like Low-Rank Adaptation (LoRA) significantly reduce resource requirements, ensuring the security and verifiability of fine-tuning under zero-knowledge constraints remains an unresolved challenge. To address this, we introduce zkLoRA, the first framework to integrate LoRA fine-tuning with zero-knowledge proofs (ZKPs), achieving provable security and correctness. zkLoRA employs advanced cryptographic techniques -- such as lookup arguments, sumcheck protocols, and polynomial commitments -- to verify both arithmetic and non-arithmetic operations in Transformer-based architectures. The framework provides end-to-end verifiability for forward propagation, backward propagation, and parameter updates during LoRA fine-tuning, while safeguarding the privacy of model parameters and training data. Leveraging GPU-based implementations, zkLoRA demonstrates practicality and efficiency through experimental validation on open-source LLMs like LLaMA, scaling up to 13 billion parameters. By combining parameter-efficient fine-tuning with ZKPs, zkLoRA bridges a critical gap, enabling secure and trustworthy deployment of LLMs in sensitive or untrusted environments.

[Arxiv](https://arxiv.org/abs/2508.21393)