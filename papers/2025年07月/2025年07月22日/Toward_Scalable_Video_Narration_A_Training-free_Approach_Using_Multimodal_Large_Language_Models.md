# # 摘要
迈向可扩展视频叙述：无需训练的多模态大语言模型方法

发布时间：2025年07月22日

`LLM应用` `视频处理` `视频分析`

> Toward Scalable Video Narration: A Training-free Approach Using Multimodal Large Language Models

# 摘要

> 本文介绍了一种创新的无训练管道——VideoNarrator，它专为生成密集视频字幕而设计，能够提供视频内容的结构化快照。这些字幕不仅包含详细叙述，还带有精确时间戳，精准捕捉视频每个片段的细微差别。尽管多模态大型语言模型（MLLMs）在视频理解方面取得了显著进展，但它们在时间对齐叙述方面仍存在不足，尤其是在不熟悉的情景下容易产生幻觉。VideoNarrator通过灵活的管道设计解决了这一难题，其中现成的MLLMs和视觉语言模型（VLMs）可作为字幕生成器、上下文提供者或验证器。实验结果表明，这些组件的协同作用显著提升了视频叙述的质量和准确性，有效减少了幻觉现象并优化了时间对齐效果。这种结构化方法不仅提升了视频理解能力，还为视频摘要和问答等下游任务提供了有力支持，未来甚至有望拓展至广告和营销领域。

> In this paper, we introduce VideoNarrator, a novel training-free pipeline designed to generate dense video captions that offer a structured snapshot of video content. These captions offer detailed narrations with precise timestamps, capturing the nuances present in each segment of the video. Despite advancements in multimodal large language models (MLLMs) for video comprehension, these models often struggle with temporally aligned narrations and tend to hallucinate, particularly in unfamiliar scenarios. VideoNarrator addresses these challenges by leveraging a flexible pipeline where off-the-shelf MLLMs and visual-language models (VLMs) can function as caption generators, context providers, or caption verifiers. Our experimental results demonstrate that the synergistic interaction of these components significantly enhances the quality and accuracy of video narrations, effectively reducing hallucinations and improving temporal alignment. This structured approach not only enhances video understanding but also facilitates downstream tasks such as video summarization and video question answering, and can be potentially extended for advertising and marketing applications.

[Arxiv](https://arxiv.org/abs/2507.17050)