# 用于基于检索的多图像问答的多模态假设摘要

发布时间：2024年12月19日

`LLM应用` `图像问答` `多模态`

> Multimodal Hypothetical Summary for Retrieval-based Multi-image Question Answering

# 摘要

> 基于检索的多图像问答（QA）任务，需要检索多个与问题相关的图像，并对这些图像进行综合从而生成答案。传统的“先检索后回答”流程，往往由于问答的训练目标无法对检索阶段进行优化，从而出现级联错误。为解决这一问题，我们提出了一种新方法，能有效地将检索到的信息引入并参考到问答中。对于给定的待检索图像集，我们运用多模态大型语言模型（从视觉角度）和大型语言模型（从文本角度），获取问题形式和描述形式的多模态假设摘要。通过融合视觉和文本视角，MHyS 能更精准地捕捉图像内容，并在检索中替代真实图像，将其转化为文本到文本的检索，消除了模态差距，有助于提升检索效果。为了更好地将检索与问答相结合，我们采用对比学习使查询（问题）与 MHyS 对齐。此外，我们还提出了一种由粗到细的策略，用于计算句子级和单词级的相似度得分，进一步增强检索能力并过滤掉不相关的细节。我们的方法在 RETVQA 上比现有最先进的方法绝对提升了 3.7%，比 CLIP 提升了 14.5%。全面的实验和详细的消融研究都证明了我们方法的优越性。

> Retrieval-based multi-image question answering (QA) task involves retrieving multiple question-related images and synthesizing these images to generate an answer. Conventional "retrieve-then-answer" pipelines often suffer from cascading errors because the training objective of QA fails to optimize the retrieval stage. To address this issue, we propose a novel method to effectively introduce and reference retrieved information into the QA. Given the image set to be retrieved, we employ a multimodal large language model (visual perspective) and a large language model (textual perspective) to obtain multimodal hypothetical summary in question-form and description-form. By combining visual and textual perspectives, MHyS captures image content more specifically and replaces real images in retrieval, which eliminates the modality gap by transforming into text-to-text retrieval and helps improve retrieval. To more advantageously introduce retrieval with QA, we employ contrastive learning to align queries (questions) with MHyS. Moreover, we propose a coarse-to-fine strategy for calculating both sentence-level and word-level similarity scores, to further enhance retrieval and filter out irrelevant details. Our approach achieves a 3.7% absolute improvement over state-of-the-art methods on RETVQA and a 14.5% improvement over CLIP. Comprehensive experiments and detailed ablation studies demonstrate the superiority of our method.

[Arxiv](https://arxiv.org/abs/2412.14880)