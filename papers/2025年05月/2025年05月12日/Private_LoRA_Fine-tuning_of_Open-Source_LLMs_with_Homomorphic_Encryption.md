# 基于同态加密的开源LLMs私有LoRA微调方法研究

发布时间：2025年05月12日

`LLM应用

论文摘要主要探讨了在开源大语言模型的微调过程中如何保护数据机密性，特别是针对敏感应用场景。他们提出了一种基于低秩适配（LoRA）技术的交互协议，结合同态加密（HE）来保护训练数据和梯度的机密性。该方法通过减少对昂贵客户端GPU的依赖，使得数据所有者可以在资源有限的情况下进行私有微调。论文还展示了该方法在多个实际应用中的可行性，如机密知识库问答、AI代码助手的私有代码库微调、基于公司邮件存档的AI代理邮件草拟，以及适应分析敏感法律或医疗文档的模型。这些内容都属于大语言模型的实际应用领域，因此分类为LLM应用。` `知识库问答` `代码助手`

> Private LoRA Fine-tuning of Open-Source LLMs with Homomorphic Encryption

# 摘要

> 在开源大语言模型的微调过程中，数据机密性的保护至关重要，尤其对于敏感应用场景。本研究提出了一种基于低秩适配 (LoRA) 技术的交互协议，用于实现私有微调。通过同态加密 (HE)，远程工作节点在处理基础模型权重相关计算时，能够保护训练数据和梯度的机密性。数据所有者负责协调整个训练流程，仅需极少量的本地计算资源和内存，从而大幅降低了对昂贵客户端 GPU 的依赖。我们通过微调 Llama-3.2-1B 模型验证了该方法的可行性，展示了在与 HE 兼容的量化方法下的收敛结果，并提供了 GPU 硬件上 HE 计算的性能基准。该方法可广泛应用于多个领域，包括机密知识库问答、AI 代码助手的私有代码库微调、基于公司邮件存档的 AI 代理邮件草拟，以及适应分析敏感法律或医疗文档的模型。

> Preserving data confidentiality during the fine-tuning of open-source Large Language Models (LLMs) is crucial for sensitive applications. This work introduces an interactive protocol adapting the Low-Rank Adaptation (LoRA) technique for private fine-tuning. Homomorphic Encryption (HE) protects the confidentiality of training data and gradients handled by remote worker nodes performing the bulk of computations involving the base model weights. The data owner orchestrates training, requiring minimal local computing power and memory, thus alleviating the need for expensive client-side GPUs. We demonstrate feasibility by fine-tuning a Llama-3.2-1B model, presenting convergence results using HE-compatible quantization and performance benchmarks for HE computations on GPU hardware. This approach enables applications such as confidential knowledge base question answering, private codebase fine-tuning for AI code assistants, AI agents for drafting emails based on a company's email archive, and adapting models to analyze sensitive legal or healthcare documents.

[Arxiv](https://arxiv.org/abs/2505.07329)