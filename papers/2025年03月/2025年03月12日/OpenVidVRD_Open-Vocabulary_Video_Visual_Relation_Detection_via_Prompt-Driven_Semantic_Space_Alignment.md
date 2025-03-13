# # OpenVidVRD：基于提示驱动语义空间对齐的开放词汇视频视觉关系检测

发布时间：2025年03月12日

`其他` `视频处理` `计算机视觉`

> OpenVidVRD: Open-Vocabulary Video Visual Relation Detection via Prompt-Driven Semantic Space Alignment

# 摘要

> 视频视觉关系检测（VidVRD）任务旨在识别视频中的物体及其关系，这一任务因动态内容、高昂的标注成本以及关系的长尾分布而颇具挑战性。视觉语言模型（VLMs）助力探索开放词汇表视觉关系检测任务，但往往忽视了不同视觉区域及其关系之间的联系。此外，直接使用VLMs进行视频中的视觉关系识别面临重大挑战，因为图像与视频之间的巨大差异。因此，我们提出了一种新颖的开放词汇表VidVRD框架，名为OpenVidVRD，该框架通过提示学习将VLMs的丰富知识和强大能力迁移至VidVRD任务中以提升其性能。具体来说，我们利用VLM从基于视频区域自动生成的区域描述中提取文本表示。接下来，我们开发了一个时空精炼模块，通过整合跨模态时空互补信息，从视频中推导出物体级别的关系表示。此外，我们采用一种基于提示的策略来对齐语义空间，以利用VLMs的语义理解能力，从而增强OpenVidVRD的整体泛化能力。在VidVRD和VidOR公开数据集上进行的大量实验表明，所提出的模型优于现有方法。

> The video visual relation detection (VidVRD) task is to identify objects and their relationships in videos, which is challenging due to the dynamic content, high annotation costs, and long-tailed distribution of relations. Visual language models (VLMs) help explore open-vocabulary visual relation detection tasks, yet often overlook the connections between various visual regions and their relations. Moreover, using VLMs to directly identify visual relations in videos poses significant challenges because of the large disparity between images and videos. Therefore, we propose a novel open-vocabulary VidVRD framework, termed OpenVidVRD, which transfers VLMs' rich knowledge and powerful capabilities to improve VidVRD tasks through prompt learning. Specificall y, We use VLM to extract text representations from automatically generated region captions based on the video's regions. Next, we develop a spatiotemporal refiner module to derive object-level relationship representations in the video by integrating cross-modal spatiotemporal complementary information. Furthermore, a prompt-driven strategy to align semantic spaces is employed to harness the semantic understanding of VLMs, enhancing the overall generalization ability of OpenVidVRD. Extensive experiments conducted on the VidVRD and VidOR public datasets show that the proposed model outperforms existing methods.

[Arxiv](https://arxiv.org/abs/2503.09416)