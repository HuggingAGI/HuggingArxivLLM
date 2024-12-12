# 针对视听分割中时间错位的协作式混合传播器

发布时间：2024年12月11日

`LLM应用` `音频 - 视觉` `视频分割`

> Collaborative Hybrid Propagator for Temporal Misalignment in Audio-Visual Segmentation

# 摘要

> 音频 - 视觉视频分割（AVVS）旨在生成与对应音频精准对齐的发声物体的像素级映射。然而，现有方法常面临时间失配的问题，即音频线索与分割结果在时间上无法协同。音频提供了两大关键信息：其一为目标对象层级的细节，其二是物体发声的起止时间。当下的方法多聚焦于对象层级的信息，却忽视了音频语义变化的边界，从而导致时间失配。为解决此问题，我们提出了协作混合传播器框架（Co-Prop）。该框架涵盖两个主要步骤：初步的音频边界锚定和逐帧音频插入传播。为锚定音频边界，我们借助带有 Qwen 大型语言模型的检索辅助提示来识别音频语义变化的控制点。这些控制点将音频分割为语义一致的部分。获取控制点列表后，我们提出音频插入传播器，通过逐帧音频插入传播和匹配的方式处理每个音频部分。我们精心整理了一个包含多种源转换案例的紧凑数据集，并设计了评估对齐率的指标。相较于传统的同步处理方法，我们的方法降低了内存需求，有利于帧对齐。实验结果显示，我们的方法在三个数据集和两个骨干网络上成效显著。此外，我们的方法能与现有的 AVVS 方法相融合，具备即插即用的功能，可提升其性能。

> Audio-visual video segmentation (AVVS) aims to generate pixel-level maps of sound-producing objects that accurately align with the corresponding audio. However, existing methods often face temporal misalignment, where audio cues and segmentation results are not temporally coordinated. Audio provides two critical pieces of information: i) target object-level details and ii) the timing of when objects start and stop producing sounds. Current methods focus more on object-level information but neglect the boundaries of audio semantic changes, leading to temporal misalignment. To address this issue, we propose a Collaborative Hybrid Propagator Framework~(Co-Prop). This framework includes two main steps: Preliminary Audio Boundary Anchoring and Frame-by-Frame Audio-Insert Propagation. To Anchor the audio boundary, we employ retrieval-assist prompts with Qwen large language models to identify control points of audio semantic changes. These control points split the audio into semantically consistent audio portions. After obtaining the control point lists, we propose the Audio Insertion Propagator to process each audio portion using a frame-by-frame audio insertion propagation and matching approach. We curated a compact dataset comprising diverse source conversion cases and devised a metric to assess alignment rates. Compared to traditional simultaneous processing methods, our approach reduces memory requirements and facilitates frame alignment. Experimental results demonstrate the effectiveness of our approach across three datasets and two backbones. Furthermore, our method can be integrated with existing AVVS approaches, offering plug-and-play functionality to enhance their performance.

[Arxiv](https://arxiv.org/abs/2412.08161)