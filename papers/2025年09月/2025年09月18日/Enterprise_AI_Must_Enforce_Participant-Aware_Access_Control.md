# 企业AI必须实施参与者感知的访问控制

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Enterprise AI Must Enforce Participant-Aware Access Control

# 摘要

> 大型语言模型（LLMs）如今在企业场景中应用日益广泛，它们与多用户交互，并基于敏感内部数据进行训练或微调。尽管微调能通过内化领域知识提升性能，却也带来了严重的安全隐患——机密训练数据可能被泄露给未授权用户。而当LLMs与检索增强生成（RAG）管道结合时，这些风险会进一步加剧——RAG管道会在推理阶段动态获取上下文文档。
  我们演示了针对AI助手的数据泄露攻击：攻击者可利用当前微调与RAG架构的访问控制缺陷，实现敏感信息的泄露。研究发现，现有的防御手段（如提示词清理、输出过滤、系统隔离及训练级隐私机制）本质上都是概率性的，难以有效抵御此类攻击。
  我们认为，唯有在微调与基于RAG的推理阶段严格执行确定性的细粒度访问控制，才能可靠地防止敏感数据泄露给未授权用户。
  我们提出了一个核心框架，其原则为：LLM在训练、检索或生成过程中使用的任何内容，都必须明确授权给\emph{交互所涉及的所有用户}。我们的方法为构建安全的多用户LLM系统带来了简洁而高效的范式革新——它以经典访问控制为基础，同时适配了现代AI工作流的独特挑战。该方案已在Microsoft Copilot Tuning中落地应用，这是一款支持企业利用自有特定数据微调模型的产品。

> Large language models (LLMs) are increasingly deployed in enterprise settings where they interact with multiple users and are trained or fine-tuned on sensitive internal data. While fine-tuning enhances performance by internalizing domain knowledge, it also introduces a critical security risk: leakage of confidential training data to unauthorized users. These risks are exacerbated when LLMs are combined with Retrieval-Augmented Generation (RAG) pipelines that dynamically fetch contextual documents at inference time.
  We demonstrate data exfiltration attacks on AI assistants where adversaries can exploit current fine-tuning and RAG architectures to leak sensitive information by leveraging the lack of access control enforcement. We show that existing defenses, including prompt sanitization, output filtering, system isolation, and training-level privacy mechanisms, are fundamentally probabilistic and fail to offer robust protection against such attacks.
  We take the position that only a deterministic and rigorous enforcement of fine-grained access control during both fine-tuning and RAG-based inference can reliably prevent the leakage of sensitive data to unauthorized recipients.
  We introduce a framework centered on the principle that any content used in training, retrieval, or generation by an LLM is explicitly authorized for \emph{all users involved in the interaction}. Our approach offers a simple yet powerful paradigm shift for building secure multi-user LLM systems that are grounded in classical access control but adapted to the unique challenges of modern AI workflows. Our solution has been deployed in Microsoft Copilot Tuning, a product offering that enables organizations to fine-tune models using their own enterprise-specific data.

[Arxiv](https://arxiv.org/abs/2509.14608)