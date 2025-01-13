# VideoAuteur: 探索长篇叙事视频生成

发布时间：2025年01月10日

`其他

理由：这篇论文主要讨论的是视频生成模型和视觉-语言模型在烹饪视频生成中的应用，特别是长篇叙述生成的问题。虽然涉及到了视觉-语言模型（VLMs），但主要内容集中在视频生成和视觉嵌入的微调技术上，与Agent、RAG、LLM应用、LLM理论等分类关系不大。因此，将其归类为其他更为合适。` `视频生成`

> VideoAuteur: Towards Long Narrative Video Generation

# 摘要

> # 摘要
近期视频生成模型在生成几秒钟的高质量视频片段上表现亮眼，但在生成长序列以传达清晰且信息丰富的事件方面仍面临挑战，难以支持连贯的叙述。本文提出一个大规模烹饪视频数据集，旨在推动烹饪领域的长篇叙述生成。我们分别使用最先进的视觉-语言模型（VLMs）和视频生成模型验证了数据集在视觉保真度和文本字幕准确性上的质量。此外，我们引入了一个长篇叙述视频导演，以增强生成视频的视觉和语义连贯性，并强调对齐视觉嵌入对提升整体视频质量的重要性。通过整合文本和图像嵌入的微调技术，我们的方法在生成视觉细节丰富且语义对齐的关键帧方面取得了显著改进。项目页面：https://videoauteur.github.io/

> Recent video generation models have shown promising results in producing high-quality video clips lasting several seconds. However, these models face challenges in generating long sequences that convey clear and informative events, limiting their ability to support coherent narrations. In this paper, we present a large-scale cooking video dataset designed to advance long-form narrative generation in the cooking domain. We validate the quality of our proposed dataset in terms of visual fidelity and textual caption accuracy using state-of-the-art Vision-Language Models (VLMs) and video generation models, respectively. We further introduce a Long Narrative Video Director to enhance both visual and semantic coherence in generated videos and emphasize the role of aligning visual embeddings to achieve improved overall video quality. Our method demonstrates substantial improvements in generating visually detailed and semantically aligned keyframes, supported by finetuning techniques that integrate text and image embeddings within the video generation process. Project page: https://videoauteur.github.io/

[Arxiv](https://arxiv.org/abs/2501.06173)