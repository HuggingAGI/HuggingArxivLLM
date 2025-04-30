# ReCIT：从梯度中重构完整的私有数据，实现大语言模型的参数高效微调

发布时间：2025年04月29日

`LLM应用` `联邦学习` `数据隐私`

> ReCIT: Reconstructing Full Private Data from Gradient in Parameter-Efficient Fine-Tuning of Large Language Models

# 摘要

> 参数高效的微调（PEFT）作为一种实用的解决方案，能够以显著降低的计算成本，将大型语言模型（LLMs）适应到自定义数据集。在协作学习场景（如联邦学习）中实施PEFT时，通常需要在各方之间交换模型更新（或梯度）。这些梯度，即使维度有限，也可能导致严重的数据隐私泄露。近期研究表明，上下文前缀和可识别个人身份的信息（PII）都可能通过梯度被泄露。然而，由于以下挑战，从同一训练实例中同时且准确地恢复这两个组件仍然不可行：1）PEFT参数数量有限；2）高维token空间；3）大批次规模。我们提出了ReCIT，一种新颖的隐私攻击方法，解决了所有这些挑战，并实现了从PEFT梯度中高保真恢复完整的私人数据。具体而言，ReCIT通过恶意微调并结合个人笔记来增强预训练模型的记忆能力；ReCIT还提出了一种新型的基于过滤的token提取技术以及token配对机制，以从大批次规模的训练序列中准确重构token。广泛的评估表明，ReCIT在不同的PEFT范式下始终优于最先进的梯度反转和记忆基础攻击。它实现了高达10倍的PII恢复率，并且在不同批次规模下均保持有效性，尤其是在传统方法难以进行前缀重构的设置下。这些发现凸显了重新评估PEFT的隐私保证的紧迫性，特别是在去中心化或共享训练环境中。

> Parameter-efficient fine-tuning (PEFT) has emerged as a practical solution for adapting large language models (LLMs) to custom datasets with significantly reduced computational cost. When carrying out PEFT under collaborative learning scenarios (e.g., federated learning), it is often required to exchange model updates (or gradients) across parties. These gradients, even with limited dimensions, can cause severe breach of data privacy. Recent works have shown that both contextual prefixes and personally identifiable information (PII) can be exposed through gradients. However, \emph{simultaneously} and \emph{accurately} recovering both components from the same training instance remains infeasible due to the following challenges: 1) limited number of PEFT parameters; 2) high-dimensional token spaces; and 3) large batch sizes. We propose ReCIT, a novel privacy attack that addresses all challenges, and achieves recovery of \emph{full} private data from PEFT gradients with high fidelity. Specifically, ReCIT proposes to enhance the memorization capability of the pre-trained model through malicious fine-tuning with Personal Notes; ReCIT also proposes a novel filter-based token extraction technique and a token pairing mechanism, to accurately reconstruct tokens from the training sequences with large batch sizes. Extensive evaluations show that ReCIT consistently outperforms state-of-the-art gradient inversion and memorization-based attacks across different PEFT paradigms. It achieves up to 10$\times$ higher PII recovery rates and remains effective across varying batch sizes, especially in settings where prefix reconstruction is intractable for conventional approaches. These findings highlight an urgent need to reassess the privacy guarantees of PEFT, especially in decentralized or shared training environments.

[Arxiv](https://arxiv.org/abs/2504.20570)