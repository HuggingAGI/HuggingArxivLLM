# # 基于上下文的开放词汇方法在自动驾驶中的运动检索

发布时间：2025年08月01日

`其他` `自动驾驶` `计算机视觉`

> Context-based Motion Retrieval using Open Vocabulary Methods for Autonomous Driving

# 摘要

> 自动驾驶系统在安全关键场景下必须可靠运行，尤其是在涉及弱势道路使用者（VRUs）的异常或复杂行为时。识别驾驶数据集中的这些边缘案例对于稳健的评估和泛化至关重要，但在大规模数据集的长尾部分检索如此罕见的人类行为场景颇具挑战性。为了支持在多样化、以人为中心的场景中对自动驾驶系统进行有针对性的评估，我们提出了一种新型的上下文感知运动检索框架。我们的方法结合了基于SMPL（Skinned Multi-Person Linear）模型的运动序列及其对应的视频帧，在编码到与自然语言对齐的共享多模态嵌入空间之前。通过文本查询，我们的方法实现了对人类行为及其上下文的可扩展检索。这项工作还介绍了我们的数据集WayMoCo，它是Waymo开放数据集的扩展。它包含从生成的伪真实SMPL序列和相应的图像数据中自动标注的运动和场景上下文描述。在WayMoCo数据集上的评估表明，我们的方法在运动-上下文检索方面比现有最先进的模型提高了高达27.5%的准确率。

> Autonomous driving systems must operate reliably in safety-critical scenarios, particularly those involving unusual or complex behavior by Vulnerable Road Users (VRUs). Identifying these edge cases in driving datasets is essential for robust evaluation and generalization, but retrieving such rare human behavior scenarios within the long tail of large-scale datasets is challenging. To support targeted evaluation of autonomous driving systems in diverse, human-centered scenarios, we propose a novel context-aware motion retrieval framework. Our method combines Skinned Multi-Person Linear (SMPL)-based motion sequences and corresponding video frames before encoding them into a shared multimodal embedding space aligned with natural language. Our approach enables the scalable retrieval of human behavior and their context through text queries. This work also introduces our dataset WayMoCo, an extension of the Waymo Open Dataset. It contains automatically labeled motion and scene context descriptions derived from generated pseudo-ground-truth SMPL sequences and corresponding image data. Our approach outperforms state-of-the-art models by up to 27.5% accuracy in motion-context retrieval, when evaluated on the WayMoCo dataset.

[Arxiv](https://arxiv.org/abs/2508.00589)