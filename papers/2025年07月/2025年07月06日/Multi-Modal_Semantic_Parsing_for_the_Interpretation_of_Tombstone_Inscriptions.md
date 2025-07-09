# # 多模态语义解析助力墓碑文字解读

发布时间：2025年07月06日

`LLM应用` `文化遗产保护` `文化遗产数字化`

> Multi-Modal Semantic Parsing for the Interpretation of Tombstone Inscriptions

# 摘要

> 墓碑承载着丰富的历史与文化价值，记录着个体生命、社区记忆与艺术表达。然而，众多墓碑正面临风化、破坏与环境退化等严峻挑战。本文提出了一种创新的多模态墓碑数字化框架，旨在提升墓碑内容的解读与管理。我们的方法基于视觉语言模型（VLMs），将墓碑图像转化为结构化的意义表示（TMRs），整合图像与文字信息。通过检索增强生成（RAG）技术，我们进一步整合地名、职业编码及本体概念等外部信息。相较于传统OCR方法，我们的技术将解析准确度从36.1提升至89.5。我们还测试了模型在不同语言与文化铭文中的表现，并通过图像融合模拟退化，评估其在受损条件下的性能。这是首次利用大型视觉语言模型 formalize墓碑理解的研究，为文化遗产保护提供了重要启示。

> Tombstones are historically and culturally rich artifacts, encapsulating individual lives, community memory, historical narratives and artistic expression. Yet, many tombstones today face significant preservation challenges, including physical erosion, vandalism, environmental degradation, and political shifts. In this paper, we introduce a novel multi-modal framework for tombstones digitization, aiming to improve the interpretation, organization and retrieval of tombstone content. Our approach leverages vision-language models (VLMs) to translate tombstone images into structured Tombstone Meaning Representations (TMRs), capturing both image and text information. To further enrich semantic parsing, we incorporate retrieval-augmented generation (RAG) for integrate externally dependent elements such as toponyms, occupation codes, and ontological concepts. Compared to traditional OCR-based pipelines, our method improves parsing accuracy from an F1 score of 36.1 to 89.5. We additionally evaluate the model's robustness across diverse linguistic and cultural inscriptions, and simulate physical degradation through image fusion to assess performance under noisy or damaged conditions. Our work represents the first attempt to formalize tombstone understanding using large vision-language models, presenting implications for heritage preservation.

[Arxiv](https://arxiv.org/abs/2507.04377)