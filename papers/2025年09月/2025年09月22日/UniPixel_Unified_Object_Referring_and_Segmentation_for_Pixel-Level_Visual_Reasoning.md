# UniPixel：面向像素级视觉推理的统一目标指代与分割

发布时间：2025年09月22日

`LLM应用` `基础理论`

> UniPixel: Unified Object Referring and Segmentation for Pixel-Level Visual Reasoning

# 摘要

> 大型多模态模型（LMMs）的最新研究进展展现出它们作为通用多模态助手的卓越成效，尤其在整体图像和视频语言理解方面表现突出。然而，对于提升细粒度像素级理解能力的关注则相对不足——这类能力要求模型实现视觉信号与语言语义间的像素级对齐。已有研究将LMMs应用于区域级描述生成、指代表达式分割等相关任务，但这些模型往往只能独立完成指代或分割任务，未能将细粒度感知能力融入视觉推理过程。

针对这一不足，我们提出了UniPixel——一种能够灵活理解视觉提示输入并生成掩码接地响应的大型多模态模型。该模型的独特之处在于将像素级感知与通用视觉理解能力无缝融合：具体来说，UniPixel会处理视觉提示并按需生成相关掩码，然后在推理时以这些中间指针为条件进行后续推理，进而实现细粒度的像素级推理。

我们的方法在10个基准数据集上验证了有效性，涉及多种任务类型，包括像素级指代/分割以及图像/视频中的对象中心理解。为验证方法的灵活性，我们还构建了全新的PixelQA任务，该任务需同时完成指代、分割与问答。

> Recent advances in Large Multi-modal Models (LMMs) have demonstrated their remarkable success as general-purpose multi-modal assistants, with particular focuses on holistic image- and video-language understanding. Conversely, less attention has been given to scaling fine-grained pixel-level understanding capabilities, where the models are expected to realize pixel-level alignment between visual signals and language semantics. Some previous studies have applied LMMs to related tasks such as region-level captioning and referring expression segmentation. However, these models are limited to performing either referring or segmentation tasks independently and fail to integrate these fine-grained perception capabilities into visual reasoning. To bridge this gap, we propose UniPixel, a large multi-modal model capable of flexibly comprehending visual prompt inputs and generating mask-grounded responses. Our model distinguishes itself by seamlessly integrating pixel-level perception with general visual understanding capabilities. Specifically, UniPixel processes visual prompts and generates relevant masks on demand, and performs subsequent reasoning conditioning on these intermediate pointers during inference, thereby enabling fine-grained pixel-level reasoning. The effectiveness of our approach has been verified on 10 benchmarks across a diverse set of tasks, including pixel-level referring/segmentation and object-centric understanding in images/videos. A novel PixelQA task that jointly requires referring, segmentation, and question answering is also designed to verify the flexibility of our method.

[Arxiv](https://arxiv.org/abs/2509.18094)