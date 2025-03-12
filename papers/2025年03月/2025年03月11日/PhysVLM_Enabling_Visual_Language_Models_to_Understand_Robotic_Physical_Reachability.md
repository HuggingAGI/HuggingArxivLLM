# PhysVLM：赋能视觉语言模型实现机器人物理可达性理解

发布时间：2025年03月11日

`Agent` `机器人` `计算机视觉`

> PhysVLM: Enabling Visual Language Models to Understand Robotic Physical Reachability

# 摘要

> 理解环境和机器人的物理可达性是任务执行的关键。尽管目前的视觉-语言模型（VLMs）在环境感知方面表现出色，但在涉及机器人物理可达性的任务中，它们常常产生不准确或不切实际的推理结果。为了解决这一问题，我们提出了一个适用于多种机器人的统一物理可达性表示——空间-物理可达性图（S-P图），以及一种整合了该可达性信息的视觉-语言模型PhysVLM。具体而言，S-P图将机器人的物理可达性抽象为一种通用的空间表示形式，不依赖于特定的机器人配置，从而使模型能够专注于可达性特征而非机器人特定参数。随后，PhysVLM通过扩展传统VLM架构，加入了一个额外的功能编码器来处理S-P图，使模型能够在不损害其通用视觉-语言能力的前提下推理物理可达性。为了训练和评估PhysVLM，我们构建了一个大规模多机器人数据集Phys100K，以及一个具有挑战性的基准测试EQA-phys，其中包含六种不同机器人在模拟和真实世界环境中的任务。实验结果表明，PhysVLM优于现有模型，在EQA-phys上比GPT-4o高出14%的性能，并在RoboVQA-val和OpenEQA基准测试中超越了先进的具身VLM模型如RoboMamba和SpatialVLM。此外，S-P图与多种VLM具有良好的兼容性，将其整合到GPT-4o-mini中可获得7.1%的性能提升。

> Understanding the environment and a robot's physical reachability is crucial for task execution. While state-of-the-art vision-language models (VLMs) excel in environmental perception, they often generate inaccurate or impractical responses in embodied visual reasoning tasks due to a lack of understanding of robotic physical reachability. To address this issue, we propose a unified representation of physical reachability across diverse robots, i.e., Space-Physical Reachability Map (S-P Map), and PhysVLM, a vision-language model that integrates this reachability information into visual reasoning. Specifically, the S-P Map abstracts a robot's physical reachability into a generalized spatial representation, independent of specific robot configurations, allowing the model to focus on reachability features rather than robot-specific parameters. Subsequently, PhysVLM extends traditional VLM architectures by incorporating an additional feature encoder to process the S-P Map, enabling the model to reason about physical reachability without compromising its general vision-language capabilities. To train and evaluate PhysVLM, we constructed a large-scale multi-robot dataset, Phys100K, and a challenging benchmark, EQA-phys, which includes tasks for six different robots in both simulated and real-world environments. Experimental results demonstrate that PhysVLM outperforms existing models, achieving a 14\% improvement over GPT-4o on EQA-phys and surpassing advanced embodied VLMs such as RoboMamba and SpatialVLM on the RoboVQA-val and OpenEQA benchmarks. Additionally, the S-P Map shows strong compatibility with various VLMs, and its integration into GPT-4o-mini yields a 7.1\% performance improvement.

[Arxiv](https://arxiv.org/abs/2503.08481)