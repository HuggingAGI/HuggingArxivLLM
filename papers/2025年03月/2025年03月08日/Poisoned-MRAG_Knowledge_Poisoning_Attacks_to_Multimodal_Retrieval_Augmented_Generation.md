# Poisoned-MRAG：针对多模态检索增强生成的投毒攻击

发布时间：2025年03月08日

`RAG` `网络安全` `人工智能`

> Poisoned-MRAG: Knowledge Poisoning Attacks to Multimodal Retrieval Augmented Generation

# 摘要

> 多模态检索增强生成（RAG）通过动态调用外部知识库，显著提升了视觉语言模型（VLMs）的视觉推理能力。本研究首次提出	extit{Poisoned-MRAG}——一种针对多模态RAG系统的知识投毒攻击方法。该方法通过向知识库注入少量精良设计的图像-文本对，成功操控VLMs，使其对特定查询输出攻击者预设的响应。我们从优化问题的角度建模此次攻击，并根据攻击目标与资源，提出了两种跨模态攻击策略：脏标签与干净标签。实验结果显示，Poisoned-MRAG在多个知识库和VLMs上的表现均优于现有方法，仅需向InfoSeek数据库注入5个恶意样本，即可实现高达98%的攻击成功率。此外，我们对文本改写、重复内容删除、结构驱动缓解和净化四种防御策略进行了全面评估，结果表明这些方法对Poisoned-MRAG的防御效果有限且存在明显权衡。研究结果充分证明了Poisoned-MRAG的高效性与可扩展性，凸显了其作为多模态RAG系统潜在重大威胁的现实意义。

> Multimodal retrieval-augmented generation (RAG) enhances the visual reasoning capability of vision-language models (VLMs) by dynamically accessing information from external knowledge bases. In this work, we introduce \textit{Poisoned-MRAG}, the first knowledge poisoning attack on multimodal RAG systems. Poisoned-MRAG injects a few carefully crafted image-text pairs into the multimodal knowledge database, manipulating VLMs to generate the attacker-desired response to a target query. Specifically, we formalize the attack as an optimization problem and propose two cross-modal attack strategies, dirty-label and clean-label, tailored to the attacker's knowledge and goals. Our extensive experiments across multiple knowledge databases and VLMs show that Poisoned-MRAG outperforms existing methods, achieving up to 98\% attack success rate with just five malicious image-text pairs injected into the InfoSeek database (481,782 pairs). Additionally, We evaluate 4 different defense strategies, including paraphrasing, duplicate removal, structure-driven mitigation, and purification, demonstrating their limited effectiveness and trade-offs against Poisoned-MRAG. Our results highlight the effectiveness and scalability of Poisoned-MRAG, underscoring its potential as a significant threat to multimodal RAG systems.

[Arxiv](https://arxiv.org/abs/2503.06254)