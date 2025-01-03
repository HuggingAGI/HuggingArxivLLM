# 视觉文本至关重要：利用视觉文本实体知识感知的大型多模态助手提升文本-KVQA性能

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了如何利用大型多模态模型（LMMs）来改进基于知识的文本视觉问答（Text-KVQA），并提出了VisTEL和KaLMA两个具体的应用方法。这些方法通过结合视觉文本识别引擎和LMM的能力，提升了问答系统的性能。因此，这篇论文属于LLM应用类别。` `视觉问答` `知识库`

> Visual Text Matters: Improving Text-KVQA with Visual Text Entity Knowledge-aware Large Multimodal Assistant

# 摘要

> 我们结合大型多模态模型（LMMs）的最新进展，重新审视了基于知识的文本视觉问答（Text-KVQA），并做出了以下贡献：（i）提出了VisTEL——一种基于原则的视觉文本实体链接方法。VisTEL模块结合了先进的视觉文本识别引擎和LMM的强大能力，通过图像中的上下文线索进行联合推理，将视觉文本实体准确链接到知识库实体。（ii）推出了KaLMA——一个知识感知的大型多模态助手，通过增强LMM与图像中视觉文本实体相关的知识，生成更准确的答案。我们还进行了全面的实验分析，并与传统视觉问答、预LMM、LMM及之前的最佳方法进行了对比。在Text-KVQA的三个数据集上，我们的方法平均比之前的最佳方法高出23.3%，刷新了当前的最先进水平。我们的实现已公开提供。

> We revisit knowledge-aware text-based visual question answering, also known as Text-KVQA, in the light of modern advancements in large multimodal models (LMMs), and make the following contributions: (i) We propose VisTEL - a principled approach to perform visual text entity linking. The proposed VisTEL module harnesses a state-of-the-art visual text recognition engine and the power of a large multimodal model to jointly reason using textual and visual context obtained using surrounding cues in the image to link the visual text entity to the correct knowledge base entity. (ii) We present KaLMA - a knowledge-aware large multimodal assistant that augments an LMM with knowledge associated with visual text entity in the image to arrive at an accurate answer. Further, we provide a comprehensive experimental analysis and comparison of our approach with traditional visual question answering, pre-large multimodal models, and large multimodal models, as well as prior top-performing approaches. Averaging over three splits of Text-KVQA, our proposed approach surpasses the previous best approach by a substantial 23.3% on an absolute scale and establishes a new state of the art. We make our implementation publicly available.

[Arxiv](https://arxiv.org/abs/2410.19144)