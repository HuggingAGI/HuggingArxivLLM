# LeCoPCR: 法律概念驱动的欧洲人权法院先例检索

发布时间：2025年01月23日

`LLM应用

理由：这篇论文讨论了如何通过生成法律概念来增强查询，以提升模型对语义意图的理解。这涉及到使用大型语言模型（LLM）来生成和处理法律概念，属于LLM在法律领域的应用。` `信息检索`

> LeCoPCR: Legal Concept-guided Prior Case Retrieval for European Court of Human Rights cases

# 摘要

> 先例检索（PCR）对法律从业者至关重要，它帮助他们在给定查询案件事实的情况下找到相关先例。现有方法在确定相关性时往往忽略了语义意图。我们提出的LeCoPCR方法，通过从查询案件事实中生成法律概念形式的意图，并用这些概念增强查询，从而提升模型对语义意图的理解。为了解决缺乏注释法律概念的问题，我们采用弱监督方法，使用行列式点过程（DPP）从推理部分提取关键法律概念，平衡质量与多样性。ECtHR-PCR数据集的实验结果验证了利用法律概念和DPP提取关键概念的有效性。

> Prior case retrieval (PCR) is crucial for legal practitioners to find relevant precedent cases given the facts of a query case. Existing approaches often overlook the underlying semantic intent in determining relevance with respect to the query case. In this work, we propose LeCoPCR, a novel approach that explicitly generate intents in the form of legal concepts from a given query case facts and then augments the query with these concepts to enhance models understanding of semantic intent that dictates relavance. To overcome the unavailability of annotated legal concepts, we employ a weak supervision approach to extract key legal concepts from the reasoning section using Determinantal Point Process (DPP) to balance quality and diversity. Experimental results on the ECtHR-PCR dataset demonstrate the effectiveness of leveraging legal concepts and DPP-based key concept extraction.

[Arxiv](https://arxiv.org/abs/2501.14114)