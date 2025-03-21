# 隐私感知的RAG：安全、隔离的知识检索

发布时间：2025年03月17日

`RAG` `人工智能` `信息安全`

> Privacy-Aware RAG: Secure and Isolated Knowledge Retrieval

# 摘要

> 检索增强生成（RAG）系统的广泛应用引发了对专有知识库保密性和完整性的担忧。这些知识库在提升大型语言模型（LLMs）生成能力方面起着关键作用，但它们越来越容易受到破坏，可能泄露敏感信息。为应对这些挑战，本文提出了一种先进的加密方法，旨在保护RAG系统免受未经授权的访问和数据泄露。我们的方法对文本内容及其对应的向量表示进行加密存储，确保所有数据始终安全加密。此机制仅限授权方访问，从而大幅降低数据意外泄露的风险。此外，我们证明了我们的加密策略保留了RAG流水线的性能和功能，确保其在不同领域和应用中的兼容性。为了验证我们方法的健壮性，我们提供了全面的安全证明，突显其抵御潜在威胁和漏洞的能力。这些证明还揭示了现有方法的局限性，它们通常缺乏稳健性、适应性或依赖开源模型。我们的研究结果表明，将高级加密技术整合到RAG系统的设计和部署中可以有效增强隐私保护。这项研究为提升AI驱动服务的安全措施的讨论做出了贡献，并呼吁在RAG架构中实施更严格的数据保护标准。

> The widespread adoption of Retrieval-Augmented Generation (RAG) systems in real-world applications has heightened concerns about the confidentiality and integrity of their proprietary knowledge bases. These knowledge bases, which play a critical role in enhancing the generative capabilities of Large Language Models (LLMs), are increasingly vulnerable to breaches that could compromise sensitive information. To address these challenges, this paper proposes an advanced encryption methodology designed to protect RAG systems from unauthorized access and data leakage. Our approach encrypts both textual content and its corresponding embeddings prior to storage, ensuring that all data remains securely encrypted. This mechanism restricts access to authorized entities with the appropriate decryption keys, thereby significantly reducing the risk of unintended data exposure. Furthermore, we demonstrate that our encryption strategy preserves the performance and functionality of RAG pipelines, ensuring compatibility across diverse domains and applications. To validate the robustness of our method, we provide comprehensive security proofs that highlight its resilience against potential threats and vulnerabilities. These proofs also reveal limitations in existing approaches, which often lack robustness, adaptability, or reliance on open-source models. Our findings suggest that integrating advanced encryption techniques into the design and deployment of RAG systems can effectively enhance privacy safeguards. This research contributes to the ongoing discourse on improving security measures for AI-driven services and advocates for stricter data protection standards within RAG architectures.

[Arxiv](https://arxiv.org/abs/2503.15548)