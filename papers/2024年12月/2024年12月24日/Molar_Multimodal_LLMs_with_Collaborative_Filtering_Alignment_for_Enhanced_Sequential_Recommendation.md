# 摩尔：通过协同过滤对齐的多模态大型语言模型来强化顺序推荐

发布时间：2024年12月24日

`LLM应用` `推荐系统` `多模态`

> Molar: Multimodal LLMs with Collaborative Filtering Alignment for Enhanced Sequential Recommendation

# 摘要

> 顺序推荐（SR）系统在过去十年间发展迅猛，从传统的协同过滤发展到深度学习方法，近来又转向了大型语言模型（LLMs）。尽管LLMs的应用带来了巨大进步，但这些模型天生缺少协同过滤信息，主要依赖文本内容数据，忽略了其他模式，所以无法达到最优的推荐效果。为克服这一局限，我们提出了Molar，这是一个多模态大型语言顺序推荐框架，它将多种内容模式与ID信息相结合，能有效地捕捉协同信号。Molar运用MLLM从文本和非文本数据生成统一的项目表征，有利于全面的多模态建模和丰富项目嵌入。此外，它通过一种后对齐机制融入协同过滤信号，该机制能对齐基于内容和基于ID的模型中的用户表征，确保精准的个性化和强大的性能。通过将多模态内容与协同过滤的见解无缝结合，Molar既能捕捉用户兴趣，又能把握上下文语义，从而实现出色的推荐准确性。大量实验表明，Molar明显优于传统的和基于LLM的基线，突显了它在利用多模态数据和协同信号进行顺序推荐任务方面的强大能力。其源代码可在https://anonymous.4open.science/r/Molar-8B06/获取。

> Sequential recommendation (SR) systems have evolved significantly over the past decade, transitioning from traditional collaborative filtering to deep learning approaches and, more recently, to large language models (LLMs). While the adoption of LLMs has driven substantial advancements, these models inherently lack collaborative filtering information, relying primarily on textual content data neglecting other modalities and thus failing to achieve optimal recommendation performance. To address this limitation, we propose Molar, a Multimodal large language sequential recommendation framework that integrates multiple content modalities with ID information to capture collaborative signals effectively. Molar employs an MLLM to generate unified item representations from both textual and non-textual data, facilitating comprehensive multimodal modeling and enriching item embeddings. Additionally, it incorporates collaborative filtering signals through a post-alignment mechanism, which aligns user representations from content-based and ID-based models, ensuring precise personalization and robust performance. By seamlessly combining multimodal content with collaborative filtering insights, Molar captures both user interests and contextual semantics, leading to superior recommendation accuracy. Extensive experiments validate that Molar significantly outperforms traditional and LLM-based baselines, highlighting its strength in utilizing multimodal data and collaborative signals for sequential recommendation tasks. The source code is available at https://anonymous.4open.science/r/Molar-8B06/.

[Arxiv](https://arxiv.org/abs/2412.18176)