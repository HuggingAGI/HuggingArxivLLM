# 可证明安全的检索增强生成方法

发布时间：2025年08月01日

`RAG` `人工智能` `信息安全`

> Provably Secure Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）系统在实际应用中虽然表现优异，但其潜在的隐私与安全风险（如数据泄露和数据投毒）仍未得到系统性解决。目前的防御策略主要依赖启发式过滤或增强检索器的鲁棒性，但这些方法存在可解释性不足、缺乏正式安全保证以及易受自适应攻击等局限性。为突破这些技术瓶颈，本文提出首个可证明安全的RAG系统框架（SAG）。我们的框架创新性地采用预存储全加密方案，实现对检索内容与向量嵌入的双重保护，确保仅授权实体能够访问数据。通过严格的正式安全证明，我们在计算安全模型下验证了该方案的机密性和完整性。在多个基准数据集上的大量实验表明，我们的框架能够有效抵御多种前沿攻击。这项研究不仅为可验证安全的RAG系统奠定了坚实的理论基础，还提供了实用的实践范式，推动了AI驱动服务向形式化安全保证迈进。

> Although Retrieval-Augmented Generation (RAG) systems have been widely applied, the privacy and security risks they face, such as data leakage and data poisoning, have not been systematically addressed yet. Existing defense strategies primarily rely on heuristic filtering or enhancing retriever robustness, which suffer from limited interpretability, lack of formal security guarantees, and vulnerability to adaptive attacks. To address these challenges, this paper proposes the first provably secure framework for RAG systems(SAG). Our framework employs a pre-storage full-encryption scheme to ensure dual protection of both retrieved content and vector embeddings, guaranteeing that only authorized entities can access the data. Through formal security proofs, we rigorously verify the scheme's confidentiality and integrity under a computational security model. Extensive experiments across multiple benchmark datasets demonstrate that our framework effectively resists a range of state-of-the-art attacks. This work establishes a theoretical foundation and practical paradigm for verifiably secure RAG systems, advancing AI-powered services toward formally guaranteed security.

[Arxiv](https://arxiv.org/abs/2508.01084)