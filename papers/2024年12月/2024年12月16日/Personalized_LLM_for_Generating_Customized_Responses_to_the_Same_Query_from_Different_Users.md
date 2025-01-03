# 个性化LLM：为不同用户生成定制化响应

发布时间：2024年12月16日

`LLM应用

理由：这篇论文主要关注的是如何通过提问者感知的方法来个性化LLM的响应生成，这属于LLM在实际应用中的个性化定制问题。论文提出的双塔模型架构和多视图增强的对比学习策略都是为了提升LLM在个性化响应生成中的应用效果。因此，这篇论文应被归类为LLM应用。` `个性化推荐`

> Personalized LLM for Generating Customized Responses to the Same Query from Different Users

# 摘要

> 现有LLM个性化研究为模型分配了不同的响应角色，但忽略了提问者的多样性。本文提出了一种新的提问者感知LLM个性化方法，能够针对不同提问者的相同问题生成差异化响应。我们设计了双塔模型架构，包含通用编码器和提问者特定编码器，并采用多视图增强的对比学习策略，拉近同一提问者的对话表示，同时拉开不同提问者的对话表示。为降低问题多样性对对比学习的影响，我们基于问题相似性进行对话聚类，并在每个聚类内进行对比学习。此外，我们从英文和中文剧本及微信记录中构建了包含173个提问者和12个响应者的MQDialog数据集。实验结果表明，该方法显著提升了个性化响应生成的质量。

> Existing work on large language model (LLM) personalization assigned different responding roles to LLM, but overlooked the diversity of questioners. In this work, we propose a new form of questioner-aware LLM personalization, generating different responses even for the same query from different questioners. We design a dual-tower model architecture with a cross-questioner general encoder and a questioner-specific encoder. We further apply contrastive learning with multi-view augmentation, pulling close the dialogue representations of the same questioner, while pulling apart those of different questioners. To mitigate the impact of question diversity on questioner-contrastive learning, we cluster the dialogues based on question similarity and restrict the scope of contrastive learning within each cluster. We also build a multi-questioner dataset from English and Chinese scripts and WeChat records, called MQDialog, containing 173 questioners and 12 responders. Extensive evaluation with different metrics shows a significant improvement in the quality of personalized response generation.

[Arxiv](https://arxiv.org/abs/2412.11736)