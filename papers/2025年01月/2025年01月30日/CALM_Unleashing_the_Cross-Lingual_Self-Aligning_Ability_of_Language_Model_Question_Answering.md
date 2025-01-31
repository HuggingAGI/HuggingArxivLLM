# CALM: 解锁语言模型问答的跨语言自对齐潜能

发布时间：2025年01月30日

`LLM应用

**理由**：这篇论文主要讨论了如何通过跨语言自对齐能力（CALM）来提升大型语言模型（LLMs）在跨语言知识问答中的表现。具体来说，论文提出了一个方法，通过直接偏好优化（DPO）来对齐模型的多语言知识，并在多个数据集上进行了实验验证。这些内容属于如何应用和改进大型语言模型的具体技术和方法，因此归类为LLM应用。` `跨文化研究`

> CALM: Unleashing the Cross-Lingual Self-Aligning Ability of Language Model Question Answering

# 摘要

> 大型语言模型（LLMs）通过预训练广泛的多语言语料库，掌握了特定语言的文化知识和通用知识。理想情况下，LLMs 应对跨文化的通用问题提供一致的回答，但实际表现却存在显著差异。为此，我们提出了语言模型的跨语言自对齐能力（CALM），旨在对齐不同语言间的知识。具体而言，对于给定问题，我们从不同语言中采样多个回答，选择最自洽的作为目标，其余则作为负例。随后，我们采用直接偏好优化（DPO）来对齐模型的多语言知识。在 MEDQA 和 X-CSQA 数据集上的实验表明，CALM 在零-shot 和检索增强场景下均能有效提升跨语言知识问答的表现。此外，增加 CALM 训练中的语言数量还能进一步提升模型的准确性和一致性。我们通过定性分析探讨了跨语言一致性如何促进知识对齐，并验证了该方法的通用性。本文的源代码和数据已开源在 GitHub 上。

> Large Language Models (LLMs) are pretrained on extensive multilingual corpora to acquire both language-specific cultural knowledge and general knowledge. Ideally, while LLMs should provide consistent responses to culture-independent questions across languages, we observe significant performance disparities. To address this, we explore the Cross-Lingual Self-Aligning ability of Language Models (CALM) to align knowledge across languages. Specifically, for a given question, we sample multiple responses across different languages, and select the most self-consistent response as the target, leaving the remaining responses as negative examples. We then employ direct preference optimization (DPO) to align the model's knowledge across different languages. Evaluations on the MEDQA and X-CSQA datasets demonstrate CALM's effectiveness in enhancing cross-lingual knowledge question answering, both in zero-shot and retrieval augmented settings. We also found that increasing the number of languages involved in CALM training leads to even higher accuracy and consistency. We offer a qualitative analysis of how cross-lingual consistency can enhance knowledge alignment and explore the method's generalizability. The source code and data of this paper are available on GitHub.

[Arxiv](https://arxiv.org/abs/2501.18457)