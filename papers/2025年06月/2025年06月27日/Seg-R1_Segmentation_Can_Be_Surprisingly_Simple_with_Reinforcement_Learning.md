# Seg-R1：分割竟然可以如此简单，只需强化学习

发布时间：2025年06月27日

`LLM应用` `计算机视觉` `图像分割`

> Seg-R1: Segmentation Can Be Surprisingly Simple with Reinforcement Learning

# 摘要

> 我们提出了Seg-R1，这是一个利用强化学习（RL）提升大型多模态模型（LMMs）像素级理解和推理能力的初步探索。从伪装物体检测（COD）和显著物体检测（SOD）等前景分割任务入手，我们的方法使LMM能够以逐个token的方式生成点提示和边界框提示，这些提示随后用于指导SAM2生成分割掩膜。通过引入组相对策略优化（GRPO），我们设计了一种训练策略，赋予LMM像素级理解能力。值得注意的是，Seg-R1仅通过基于RL的训练就达到了显著的性能，在COD10K上实现了.873的S-measure，而无需复杂的模型修改。此外，我们发现纯RL训练在开放世界泛化方面表现强劲。尽管Seg-R1仅在带有图像-掩膜对的前景分割任务上进行训练，且没有文本监督，但它在零样本推理分割和推理分割任务上表现优异，在RefCOCOg测试中达到了71.4的cIoU，在ReasonSeg测试中达到了56.7的gIoU，超越了在这些数据集上完全监督训练的模型。

> We present Seg-R1, a preliminary exploration of using reinforcement learning (RL) to enhance the pixel-level understanding and reasoning capabilities of large multimodal models (LMMs). Starting with foreground segmentation tasks, specifically camouflaged object detection (COD) and salient object detection (SOD), our approach enables the LMM to generate point and bounding box prompts in the next-token fashion, which are then used to guide SAM2 in producing segmentation masks. We introduce Group Relative Policy Optimization (GRPO) into the segmentation domain, equipping the LMM with pixel-level comprehension through a carefully designed training strategy. Notably, Seg-R1 achieves remarkable performance with purely RL-based training, achieving .873 S-measure on COD10K without complex model modification. Moreover, we found that pure RL training demonstrates strong open-world generalization. Despite being trained solely on foreground segmentation image-mask pairs without text supervision, Seg-R1 achieves impressive zero-shot performance on referring segmentation and reasoning segmentation tasks, with 71.4 cIoU on RefCOCOg test and 56.7 gIoU on ReasonSeg test, outperforming models fully supervised on these datasets.

[Arxiv](https://arxiv.org/abs/2506.22624)