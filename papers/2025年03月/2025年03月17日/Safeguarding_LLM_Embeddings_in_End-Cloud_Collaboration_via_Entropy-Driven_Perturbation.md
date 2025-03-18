# # 熵驱动扰动保护端云协作中的LLM嵌入

发布时间：2025年03月17日

`RAG` `端云协作` `隐私保护`

> Safeguarding LLM Embeddings in End-Cloud Collaboration via Entropy-Driven Perturbation

# 摘要

> 近期研究通过端云协作显著提升了设备端语言模型的推理能力。具体而言，端设备通过检索云端数据库中的有用信息来增强本地处理，这一过程被称为检索增强生成 (RAG)。通常情况下，为了在保护隐私的同时从云端获取信息，端设备会利用本地嵌入模型将原始数据转换为嵌入向量。然而，新兴的嵌入反转攻击 (EIAs) 却能从文本嵌入中恢复原始数据（例如，通过训练恢复模型将嵌入映射回原始文本），这对用户隐私构成了严重威胁。

为应对这一挑战，我们提出了 EntroGuard，这是一种基于熵驱动的扰动式嵌入隐私保护方法。它能在端云协作过程中有效保护文本嵌入的隐私，同时保持检索准确性。具体来说，为了抵御各种嵌入反转攻击，我们通过增加恢复文本在恢复模型通用结构中的熵来扰动嵌入，从而在恢复过程中引导嵌入指向无意义文本，而非原始敏感文本。

为了确保云端的检索性能，我们将扰动控制在一个合理范围内，并采取“冗余处减小扰动、稀疏处增大扰动”的策略。此外，EntroGuard 的优势还体现在无需对现有嵌入模型进行任何修改，即可直接集成到端设备中。

大量实验结果表明，与现有隐私保护方法相比，EntroGuard 最多可将隐私泄露风险降低 8 倍，且对检索性能的影响微乎其微。

> Recent studies improve on-device language model (LM) inference through end-cloud collaboration, where the end device retrieves useful information from cloud databases to enhance local processing, known as Retrieval-Augmented Generation (RAG). Typically, to retrieve information from the cloud while safeguarding privacy, the end device transforms original data into embeddings with a local embedding model. However, the recently emerging Embedding Inversion Attacks (EIAs) can still recover the original data from text embeddings (e.g., training a recovery model to map embeddings back to original texts), posing a significant threat to user privacy. To address this risk, we propose EntroGuard, an entropy-driven perturbation-based embedding privacy protection method, which can protect the privacy of text embeddings while maintaining retrieval accuracy during the end-cloud collaboration. Specifically, to defeat various EIAs, we perturb the embeddings to increase the entropy of the recovered text in the common structure of recovery models, thus steering the embeddings toward meaningless texts rather than original sensitive texts during the recovery process. To maintain retrieval performance in the cloud, we constrain the perturbations within a bound, applying the strategy of reducing them where redundant and increasing them where sparse. Moreover, EntroGuard can be directly integrated into end devices without requiring any modifications to the embedding model. Extensive experimental results demonstrate that EntroGuard can reduce the risk of privacy leakage by up to 8 times at most with negligible loss of retrieval performance compared to existing privacy-preserving methods.

[Arxiv](https://arxiv.org/abs/2503.12896)