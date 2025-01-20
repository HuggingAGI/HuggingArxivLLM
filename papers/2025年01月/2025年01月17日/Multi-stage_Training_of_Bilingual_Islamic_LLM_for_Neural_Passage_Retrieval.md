# 双语伊斯兰大型语言模型的多阶段训练：神经段落检索应用

发布时间：2025年01月17日

`LLM应用

理由：这篇论文主要探讨了如何利用NLP技术（特别是XLM-R模型）来开发一个适用于伊斯兰领域的双语神经检索模型。研究涉及领域适应、多阶段训练和数据增强等技术，以提高在特定领域（伊斯兰领域）的检索性能。这些内容属于将大型语言模型（LLM）应用于特定领域的具体实践，因此归类为“LLM应用”。` `伊斯兰`

> Multi-stage Training of Bilingual Islamic LLM for Neural Passage Retrieval

# 摘要

> 本研究探索了NLP技术在伊斯兰领域的应用，专注于开发一种伊斯兰神经检索模型。通过强大的XLM-R模型，研究采用语言缩减技术构建了一个轻量级双语LLM。我们的领域适应方法解决了伊斯兰领域的独特挑战，即大量领域内语料库仅存在于阿拉伯语中，而其他语言（如英语）则相对匮乏。
    研究采用多阶段训练过程，结合大型检索数据集（如MS MARCO）和较小的领域内数据集，以提升检索性能。此外，通过数据增强技术和可靠的伊斯兰来源，我们构建了一个英语领域内检索数据集，进一步增强了领域特定数据集的性能。
    结果表明，结合领域适应和多阶段训练的双语伊斯兰神经检索模型在下游检索任务中表现优于单语模型。

> This study examines the use of Natural Language Processing (NLP) technology within the Islamic domain, focusing on developing an Islamic neural retrieval model. By leveraging the robust XLM-R model, the research employs a language reduction technique to create a lightweight bilingual large language model (LLM). Our approach for domain adaptation addresses the unique challenges faced in the Islamic domain, where substantial in-domain corpora exist only in Arabic while limited in other languages, including English.
  The work utilizes a multi-stage training process for retrieval models, incorporating large retrieval datasets, such as MS MARCO, and smaller, in-domain datasets to improve retrieval performance. Additionally, we have curated an in-domain retrieval dataset in English by employing data augmentation techniques and involving a reliable Islamic source. This approach enhances the domain-specific dataset for retrieval, leading to further performance gains.
  The findings suggest that combining domain adaptation and a multi-stage training method for the bilingual Islamic neural retrieval model enables it to outperform monolingual models on downstream retrieval tasks.

[Arxiv](https://arxiv.org/abs/2501.10175)