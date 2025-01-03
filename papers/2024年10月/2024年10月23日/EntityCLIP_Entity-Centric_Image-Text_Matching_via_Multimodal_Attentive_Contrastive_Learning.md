# EntityCLIP：基于多模态注意力对比学习的实体中心图像-文本匹配

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）生成解释性文本，以帮助解决以实体为中心的图像-文本匹配（EITM）任务。论文的核心在于使用LLMs生成解释性文本作为桥梁线索，并将其与图像和文本一起输入到多模态注意力专家（MMAE）模块中，以缩小实体相关文本和图像之间的语义鸿沟。这表明论文的重点是利用LLMs的能力来增强图像-文本匹配任务的效果，属于LLM在实际应用中的使用，因此分类为“LLM应用”。` `社交媒体` `图像处理`

> EntityCLIP: Entity-Centric Image-Text Matching via Multimodal Attentive Contrastive Learning

# 摘要

> # 摘要
近年来，图像-文本匹配领域取得了显著进展，但主流模型主要服务于广泛查询，难以适应细粒度的查询意图。本文致力于解决以实体为中心的图像-文本匹配（EITM）任务，该任务中文本和图像涉及特定实体相关信息。与一般的图像-文本匹配问题相比，该任务的挑战主要在于实体关联建模中的语义鸿沟更大。为了缩小以实体为中心的文本与图像之间的巨大语义鸿沟，我们以基础的CLIP模型为骨干，设计了一个多模态注意力对比学习框架，以调整CLIP适应EITM问题，开发了一个名为EntityCLIP的模型。我们的多模态注意力对比学习的关键在于使用大型语言模型（LLMs）生成解释性文本作为桥梁线索。具体来说，我们从现成的LLMs中提取解释性文本。这些解释性文本与图像和文本一起输入到我们专门设计的多模态注意力专家（MMAE）模块中，该模块有效地整合了解释性文本，以缩小实体相关文本和图像在共享语义空间中的差距。基于MMAE生成的丰富特征，我们进一步设计了一种有效的门控集成图像-文本匹配（GI-ITM）策略。GI-ITM采用自适应门控机制来聚合MMAE的特征，随后应用图像-文本匹配约束来引导文本与图像的对齐。我们在三个社交媒体新闻基准（包括N24News、VisualNews和GoodNews）上进行了大量实验，结果表明我们的方法明显优于竞争方法。

> Recent advancements in image-text matching have been notable, yet prevailing models predominantly cater to broad queries and struggle with accommodating fine-grained query intention. In this paper, we work towards the \textbf{E}ntity-centric \textbf{I}mage-\textbf{T}ext \textbf{M}atching (EITM), a task that the text and image involve specific entity-related information. The challenge of this task mainly lies in the larger semantic gap in entity association modeling, comparing with the general image-text matching problem.To narrow the huge semantic gap between the entity-centric text and the images, we take the fundamental CLIP as the backbone and devise a multimodal attentive contrastive learning framework to tam CLIP to adapt EITM problem, developing a model named EntityCLIP. The key of our multimodal attentive contrastive learning is to generate interpretive explanation text using Large Language Models (LLMs) as the bridge clues. In specific, we proceed by extracting explanatory text from off-the-shelf LLMs. This explanation text, coupled with the image and text, is then input into our specially crafted Multimodal Attentive Experts (MMAE) module, which effectively integrates explanation texts to narrow the gap of the entity-related text and image in a shared semantic space. Building on the enriched features derived from MMAE, we further design an effective Gated Integrative Image-text Matching (GI-ITM) strategy. The GI-ITM employs an adaptive gating mechanism to aggregate MMAE's features, subsequently applying image-text matching constraints to steer the alignment between the text and the image. Extensive experiments are conducted on three social media news benchmarks including N24News, VisualNews, and GoodNews, the results shows that our method surpasses the competition methods with a clear margin.

[Arxiv](https://arxiv.org/abs/2410.17810)