# Florence-VL：利用生成式视觉编码器和深度-广度融合来强化视觉语言模型

发布时间：2024年12月05日

`LLM应用` `多模态` `语言模型`

> Florence-VL: Enhancing Vision-Language Models with Generative Vision Encoder and Depth-Breadth Fusion

# 摘要

> 我们带来了 Florence-VL，这一全新的多模态大型语言模型（MLLMs）家族，其丰富的视觉表征由生成式视觉基础模型 Florence-2 造就。和通过对比学习训练的常见 CLIP 风格视觉转换器不同，Florence-2 能够抓取视觉特征的不同层级和方面，通用性更强，能适配各类下游任务。我们给出了一种新颖的特征融合架构和创新的训练方案，能有效地把 Florence-2 的视觉特征融入预训练的大型语言模型（比如 Phi 3.5 和 LLama 3）中。特别地，我们提出了“深度-广度融合（DBFusion）”，用于融合从不同深度和多重提示下提取的视觉特征。我们的模型训练包含整个模型的端到端预训练，以及投影层和大型语言模型的微调，基于精心设计的涵盖高质量图像标题和指令调整对的各类开源数据集的方案。我们对 Florence-VL 视觉特征的定量分析和可视化表明，在视觉语言对齐方面，它比流行的视觉编码器更具优势，其中丰富的深度和广度发挥了重要作用。Florence-VL 在涵盖一般 VQA、感知、幻觉、OCR、图表、知识密集型理解等的各种多模态和以视觉为中心的基准测试中，相比现有的最先进的 MLLMs 有显著提升。为助力未来研究，我们的模型和完整的训练方案已开源。https://github.com/JiuhaiChen/Florence-VL

> We present Florence-VL, a new family of multimodal large language models (MLLMs) with enriched visual representations produced by Florence-2, a generative vision foundation model. Unlike the widely used CLIP-style vision transformer trained by contrastive learning, Florence-2 can capture different levels and aspects of visual features, which are more versatile to be adapted to diverse downstream tasks. We propose a novel feature-fusion architecture and an innovative training recipe that effectively integrates Florence-2's visual features into pretrained LLMs, such as Phi 3.5 and LLama 3. In particular, we propose "depth-breath fusion (DBFusion)" to fuse the visual features extracted from different depths and under multiple prompts. Our model training is composed of end-to-end pretraining of the whole model followed by finetuning of the projection layer and the LLM, on a carefully designed recipe of diverse open-source datasets that include high-quality image captions and instruction-tuning pairs. Our quantitative analysis and visualization of Florence-VL's visual features show its advantages over popular vision encoders on vision-language alignment, where the enriched depth and breath play important roles. Florence-VL achieves significant improvements over existing state-of-the-art MLLMs across various multi-modal and vision-centric benchmarks covering general VQA, perception, hallucination, OCR, Chart, knowledge-intensive understanding, etc. To facilitate future research, our models and the complete training recipe are open-sourced. https://github.com/JiuhaiChen/Florence-VL

[Arxiv](https://arxiv.org/abs/2412.04424)