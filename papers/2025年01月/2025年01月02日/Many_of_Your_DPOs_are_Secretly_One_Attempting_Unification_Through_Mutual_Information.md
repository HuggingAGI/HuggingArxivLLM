# 您的许多DPO其实是一回事：通过互信息实现统一

发布时间：2025年01月02日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的后对齐问题，特别是直接偏好优化（DPO）算法的变体及其统一框架。论文的核心内容涉及如何通过引入新的损失函数和灵活的先验来优化LLMs的对齐过程，并展示了如何从该框架中推导出多种现有算法。这些内容属于LLM的理论研究范畴，旨在提升LLMs的实用性和安全性，因此应归类为“LLM理论”。` `人工智能`

> Many of Your DPOs are Secretly One: Attempting Unification Through Mutual Information

# 摘要

> # 摘要
大型语言模型（LLMs）的后对齐是提升其实用性、安全性和与人类意图一致性的关键。直接偏好优化（DPO）因其能直接基于人类反馈优化模型，已成为实现这一目标的主流算法。然而，文献中涌现的大量DPO变体让研究人员难以全面把握它们之间的联系。本文提出了一种受互信息启发的统一框架，并引入了一个具有灵活先验的新损失函数。通过精心设定这些先验，我们展示了如何从该框架中推导出SimPO、TDPO、SparsePO等现有算法。这一统一框架为研究人员提供了更清晰、结构化的视角，帮助他们更好地理解不同DPO变体之间的关系。我们希望通过简化DPO算法的复杂性，推动LLM对齐领域的进一步发展，并为开发更强大、可解释的对齐技术奠定基础。

> Post-alignment of large language models (LLMs) is critical in improving their utility, safety, and alignment with human intentions. Direct preference optimisation (DPO) has become one of the most widely used algorithms for achieving this alignment, given its ability to optimise models based on human feedback directly. However, the vast number of DPO variants in the literature has made it increasingly difficult for researchers to navigate and fully grasp the connections between these approaches. This paper introduces a unifying framework inspired by mutual information, which proposes a new loss function with flexible priors. By carefully specifying these priors, we demonstrate that many existing algorithms, such as SimPO, TDPO, SparsePO, and others, can be derived from our framework. This unification offers a clearer and more structured approach, allowing researchers to understand the relationships between different DPO variants better. We aim to simplify the landscape of DPO algorithms, making it easier for the research community to gain insights and foster further advancements in LLM alignment. Ultimately, we hope our framework can be a foundation for developing more robust and interpretable alignment techniques.

[Arxiv](https://arxiv.org/abs/2501.01544)