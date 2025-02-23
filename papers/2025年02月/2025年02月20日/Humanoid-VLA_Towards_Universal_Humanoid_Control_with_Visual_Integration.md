# 人形-VLA：迈向通用人形控制，结合视觉整合

发布时间：2025年02月20日

`Agent` `机器人` `人工智能`

> Humanoid-VLA: Towards Universal Humanoid Control with Visual Integration

# 摘要

> 本文针对现有依赖反应机制且受限于数据稀缺性而缺乏自主交互能力的人形机器人控制框架的局限性，提出了一种名为Humanoid-VLA的创新框架。该框架集成了语言理解、以自我为中心的场景感知和运动控制，实现了通用的人形机器人控制。Humanoid-VLA通过非以自我为中心的人类运动数据集与文本描述的配对，进行语言-运动预对齐，使模型掌握通用运动模式和动作语义。随后，借助高效的参数化视频条件微调，引入以自我为中心的视觉上下文，实现上下文感知的运动生成。此外，我们还提出了一种自监督数据增强策略，能够直接从运动数据中生成伪标注，将原始运动序列转化为信息丰富的问答对，从而有效利用大规模无标签视频数据。基于全身控制架构的大量实验证明，Humanoid-VLA在物体交互和环境探索任务中表现出增强的上下文感知能力，展现出更加类人化的能力，能够进行适应性和智能的互动。

> This paper addresses the limitations of current humanoid robot control frameworks, which primarily rely on reactive mechanisms and lack autonomous interaction capabilities due to data scarcity. We propose Humanoid-VLA, a novel framework that integrates language understanding, egocentric scene perception, and motion control, enabling universal humanoid control. Humanoid-VLA begins with language-motion pre-alignment using non-egocentric human motion datasets paired with textual descriptions, allowing the model to learn universal motion patterns and action semantics. We then incorporate egocentric visual context through a parameter efficient video-conditioned fine-tuning, enabling context-aware motion generation. Furthermore, we introduce a self-supervised data augmentation strategy that automatically generates pseudoannotations directly derived from motion data. This process converts raw motion sequences into informative question-answer pairs, facilitating the effective use of large-scale unlabeled video data. Built upon whole-body control architectures, extensive experiments show that Humanoid-VLA achieves object interaction and environment exploration tasks with enhanced contextual awareness, demonstrating a more human-like capacity for adaptive and intelligent engagement.

[Arxiv](https://arxiv.org/abs/2502.14795)