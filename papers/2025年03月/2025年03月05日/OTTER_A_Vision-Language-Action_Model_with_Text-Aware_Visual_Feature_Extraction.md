# OTTER：一款视觉-语言-动作模型，具备基于文本感知的视觉特征提取能力

发布时间：2025年03月05日

`Agent` `机器人` `人工智能`

> OTTER: A Vision-Language-Action Model with Text-Aware Visual Feature Extraction

# 摘要

> 视觉-语言-动作（VLA）模型旨在根据视觉观察和语言指令预测机器人的动作。现有方法需要对预训练的视觉语言模型（VLMs）进行微调，因为视觉和语言特征是独立输入到下游策略中，这会降低预训练的语义对齐效果。我们提出了一种新颖的VLA架构OTTER，它通过显式的、文本感知的视觉特征提取来利用现有的语义对齐。与处理所有视觉特征不同，OTTER选择性地提取并仅传递与语言指令在语义上对齐的任务相关视觉特征到策略转换器。这样可以让OTTER保持预训练的视觉语言编码器不变。因此，OTTER保留并利用了大规模预训练中学习到的丰富语义理解，从而具备强大的零样本泛化能力。在模拟和真实世界实验中，OTTER显著优于现有的VLA模型，展示了对新物体和环境的强大零样本泛化能力。相关资源请访问：https://ottervla.github.io.

> Vision-Language-Action (VLA) models aim to predict robotic actions based on visual observations and language instructions. Existing approaches require fine-tuning pre-trained visionlanguage models (VLMs) as visual and language features are independently fed into downstream policies, degrading the pre-trained semantic alignments. We propose OTTER, a novel VLA architecture that leverages these existing alignments through explicit, text-aware visual feature extraction. Instead of processing all visual features, OTTER selectively extracts and passes only task-relevant visual features that are semantically aligned with the language instruction to the policy transformer. This allows OTTER to keep the pre-trained vision-language encoders frozen. Thereby, OTTER preserves and utilizes the rich semantic understanding learned from large-scale pre-training, enabling strong zero-shot generalization capabilities. In simulation and real-world experiments, OTTER significantly outperforms existing VLA models, demonstrating strong zeroshot generalization to novel objects and environments. Video, code, checkpoints, and dataset: https://ottervla.github.io/.

[Arxiv](https://arxiv.org/abs/2503.03734)