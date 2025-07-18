# MCoT-RE: 通过多维度链式推理与重排序实现无训练零样本合成图像检索

发布时间：2025年07月17日

`LLM应用` `图像检索` `计算机视觉`

> MCoT-RE: Multi-Faceted Chain-of-Thought and Re-Ranking for Training-Free Zero-Shot Composed Image Retrieval

# 摘要

> 组合图像检索（CIR）是一项利用包含参考图像和修改文本的合成查询，从图像库中检索目标图像的任务。在众多CIR方法中，基于预训练模型的无训练零样本方法虽然成本效益高，但仍存在显著的局限性。例如，串行的VLM-LLM流水线独立处理每种模态，这通常导致信息丢失并限制跨模态交互。相比之下，基于多模态大型语言模型（MLLMs）的方法往往仅专注于应用文本指示的修改，而未能充分利用参考图像中的上下文视觉信息。为了解决这些问题，我们提出了一种无训练零样本的CIR框架——多维度思考链与重新排序（MCoT-RE）。MCoT-RE利用多维度思考链引导MLLM平衡显式修改和上下文视觉线索，生成两个不同的描述：一个专注于修改，另一个整合全面的视觉-文本上下文。第一个描述用于过滤候选图像。随后，我们将这两个描述与参考图像结合，进行多粒度的重新排序。这种两阶段的方法通过与文本修改指令对齐，同时保留参考图像的视觉上下文，从而促进精确检索。通过广泛的实验，MCoT-RE在无训练方法中实现了最先进的结果，在FashionIQ上的Recall@10提高了6.24%，在CIRR上的Recall@1提高了8.58%。

> Composed Image Retrieval (CIR) is the task of retrieving a target image from a gallery using a composed query consisting of a reference image and a modification text. Among various CIR approaches, training-free zero-shot methods based on pre-trained models are cost-effective but still face notable limitations. For example, sequential VLM-LLM pipelines process each modality independently, which often results in information loss and limits cross-modal interaction. In contrast, methods based on multimodal large language models (MLLMs) often focus exclusively on applying changes indicated by the text, without fully utilizing the contextual visual information from the reference image. To address these issues, we propose multi-faceted Chain-of-Thought with re-ranking (MCoT-RE), a training-free zero-shot CIR framework. MCoT-RE utilizes multi-faceted Chain-of-Thought to guide the MLLM to balance explicit modifications and contextual visual cues, generating two distinct captions: one focused on modification and the other integrating comprehensive visual-textual context. The first caption is used to filter candidate images. Subsequently, we combine these two captions and the reference image to perform multi-grained re-ranking. This two-stage approach facilitates precise retrieval by aligning with the textual modification instructions while preserving the visual context of the reference image. Through extensive experiments, MCoT-RE achieves state-of-the-art results among training-free methods, yielding improvements of up to 6.24% in Recall@10 on FashionIQ and 8.58% in Recall@1 on CIRR.

[Arxiv](https://arxiv.org/abs/2507.12819)