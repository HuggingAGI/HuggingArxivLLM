# 个性化工具包：免训练的大型视觉语言模型个性化

发布时间：2025年02月04日

`RAG

理由：这篇论文主要讨论了如何通过检索增强生成（RAG）技术来实现大型视觉语言模型（LVLMs）的个性化，而无需进行耗时的训练。RAG技术是论文的核心方法之一，因此将其分类为RAG是合适的。` `计算机视觉` `个性化服务`

> Personalization Toolkit: Training Free Personalization of Large Vision Language Models

# 摘要

> # 摘要
大型视觉语言模型（LVLMs）在适应用户独特需求和偏好方面展现出巨大潜力，能够提供个性化帮助。LVLMs的个性化是一个新兴领域，旨在定制模型以识别特定对象实例并提供定制化响应。然而，现有方法需要为每个用户和对象进行耗时的测试时训练，实用性较低。本文提出了一种无需训练的新方法，通过预训练视觉基础模型提取特征、检索增强生成（RAG）技术识别视觉输入中的实例，以及视觉提示方法，实现LVLM的个性化。我们的模型无关视觉工具包无需大量重新训练，即可实现灵活高效的个性化。实验结果表明，该方法优于传统基于训练的方法，为LVLM个性化树立了新标杆。

> Large Vision Language Models (LVLMs) have significant potential to deliver personalized assistance by adapting to individual users' unique needs and preferences. Personalization of LVLMs is an emerging area that involves customizing models to recognize specific object instances and provide tailored responses. However, existing approaches rely on time-consuming test-time training for each user and object, rendering them impractical. This paper proposes a novel, training-free approach to LVLM personalization by leveraging pre-trained vision foundation models to extract distinct features, retrieval-augmented generation (RAG) techniques to recognize instances in the visual input, and visual prompting methods. Our model-agnostic vision toolkit enables flexible and efficient personalization without extensive retraining. We demonstrate state-of-the-art results, outperforming conventional training-based approaches and establish a new standard for LVLM personalization.

[Arxiv](https://arxiv.org/abs/2502.02452)