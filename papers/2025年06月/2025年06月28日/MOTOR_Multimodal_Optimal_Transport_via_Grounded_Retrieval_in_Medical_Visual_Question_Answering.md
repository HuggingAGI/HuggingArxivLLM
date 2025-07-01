# MOTOR：多模态最优传输基于 grounding 检索应用于医学视觉问答

发布时间：2025年06月28日

`RAG` `视觉问答系统`

> MOTOR: Multimodal Optimal Transport via Grounded Retrieval in Medical Visual Question Answering

# 摘要

> 医学视觉问答（MedVQA）在临床决策中发挥着关键作用，它通过提供富含上下文的答案来解答基于图像的查询。尽管视觉-语言模型（VLMs）在这一领域得到了广泛应用，但它们常常输出事实性错误的回答。为了解决这一问题，检索增强生成技术通过引入外部信息源来提供支持，然而这种做法也带来了检索到无关上下文的风险，从而可能削弱VLM的推理能力。现有方法中，通过重排序检索来提高相关性是一种常见策略，这些方法主要关注查询与文本的对齐度。然而，这些方法忽视了视觉或跨模态上下文的重要性，这对于医学诊断来说至关重要。我们提出了一种全新的多模态检索与重排序方法——MOTOR，该方法巧妙结合了基于图像描述的文本和最优运输理论。MOTOR能够基于文本和视觉信息，深入挖掘查询与检索到的上下文之间的潜在关系。因此，我们的方法能够识别出更具临床相关性的上下文，从而有效增强VLM的输入。实证分析和人类专家评估结果表明，MOTOR在MedVQA数据集上表现优异，平均超越现有最优方法6.45%。代码已开源，地址为https://github.com/BioMedIA-MBZUAI/MOTOR。

> Medical visual question answering (MedVQA) plays a vital role in clinical decision-making by providing contextually rich answers to image-based queries. Although vision-language models (VLMs) are widely used for this task, they often generate factually incorrect answers. Retrieval-augmented generation addresses this challenge by providing information from external sources, but risks retrieving irrelevant context, which can degrade the reasoning capabilities of VLMs. Re-ranking retrievals, as introduced in existing approaches, enhances retrieval relevance by focusing on query-text alignment. However, these approaches neglect the visual or multimodal context, which is particularly crucial for medical diagnosis. We propose MOTOR, a novel multimodal retrieval and re-ranking approach that leverages grounded captions and optimal transport. It captures the underlying relationships between the query and the retrieved context based on textual and visual information. Consequently, our approach identifies more clinically relevant contexts to augment the VLM input. Empirical analysis and human expert evaluation demonstrate that MOTOR achieves higher accuracy on MedVQA datasets, outperforming state-of-the-art methods by an average of 6.45%. Code is available at https://github.com/BioMedIA-MBZUAI/MOTOR.

[Arxiv](https://arxiv.org/abs/2506.22900)