# VideoRAG: 视频语料库的检索增强生成

发布时间：2025年01月10日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）方法，特别是针对视频这一多模态知识源的检索和生成过程。论文提出了VideoRAG框架，利用大型视频语言模型（LVLMs）动态检索相关视频并充分利用其视觉和文本信息。因此，这篇论文应归类为RAG。` `视频处理` `多模态生成`

> VideoRAG: Retrieval-Augmented Generation over Video Corpus

# 摘要

> 检索增强生成（RAG）通过检索与查询相关的外部知识并将其融入生成过程，有效解决了基础模型生成事实错误输出的问题。然而，现有RAG方法主要关注文本信息，少数近期研究开始涉及图像，却忽视了视频这一丰富的多模态知识源。视频能比其他模态更有效地呈现事件、过程和上下文细节。尽管有研究尝试在响应生成中整合视频，但它们要么预定义查询相关视频而不动态检索，要么将视频简化为文本描述，未能充分利用其多模态特性。为此，我们提出了VideoRAG，这一创新框架不仅根据查询动态检索相关视频，还在生成过程中充分利用视频的视觉和文本信息。我们的方法依托于最新的大型视频语言模型（LVLMs），这些模型能直接处理视频内容，实现视频检索并与查询无缝集成。实验证明，VideoRAG在性能上优于相关基线。

> Retrieval-Augmented Generation (RAG) is a powerful strategy to address the issue of generating factually incorrect outputs in foundation models by retrieving external knowledge relevant to queries and incorporating it into their generation process. However, existing RAG approaches have primarily focused on textual information, with some recent advancements beginning to consider images, and they largely overlook videos, a rich source of multimodal knowledge capable of representing events, processes, and contextual details more effectively than any other modality. While a few recent studies explore the integration of videos in the response generation process, they either predefine query-associated videos without retrieving them according to queries, or convert videos into the textual descriptions without harnessing their multimodal richness. To tackle these, we introduce VideoRAG, a novel framework that not only dynamically retrieves relevant videos based on their relevance with queries but also utilizes both visual and textual information of videos in the output generation. Further, to operationalize this, our method revolves around the recent advance of Large Video Language Models (LVLMs), which enable the direct processing of video content to represent it for retrieval and seamless integration of the retrieved videos jointly with queries. We experimentally validate the effectiveness of VideoRAG, showcasing that it is superior to relevant baselines.

[Arxiv](https://arxiv.org/abs/2501.05874)