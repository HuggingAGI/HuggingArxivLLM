# 小模型也不够：通过混合知识蒸馏打造高质量低资源面部动画模型

发布时间：2025年07月24日

`LLM应用` `游戏开发` `数字娱乐`

> Tiny is not small enough: High-quality, low-resource facial animation models through hybrid knowledge distillation

# 摘要

> 高质量且稳健的语音驱动3D面部动画模型训练，需要一个包含大量高质量音频-动画配对的多样化数据集。为了解决数据集缺乏的问题，近期研究引入了大型预训练语音编码器，这些编码器能够稳健处理输入音频的变化，使面部动画模型在不同说话人、音频质量和语言之间实现泛化。然而，这些模型过于庞大，仅适用于专用机器的离线推理。在本研究中，我们探索了游戏开发背景下实时、端侧的面部动画模型。通过混合知识蒸馏结合伪标签，我们克服了大型数据集的缺乏。给定一个大型音频数据集，我们采用高性能教师模型训练出非常小的学生模型。与预训练语音编码器不同，我们的学生模型仅由卷积层和全连接层组成，无需依赖注意力上下文或递归更新。在实验中，我们实现了内存占用减少至3.4 MB，所需未来音频上下文减少至81毫秒，同时保持高质量动画。这为端侧推理铺平了道路，是迈向现实的、基于模型的数字角色的重要一步。

> The training of high-quality, robust machine learning models for speech-driven 3D facial animation requires a large, diverse dataset of high-quality audio-animation pairs. To overcome the lack of such a dataset, recent work has introduced large pre-trained speech encoders that are robust to variations in the input audio and, therefore, enable the facial animation model to generalize across speakers, audio quality, and languages. However, the resulting facial animation models are prohibitively large and lend themselves only to offline inference on a dedicated machine. In this work, we explore on-device, real-time facial animation models in the context of game development. We overcome the lack of large datasets by using hybrid knowledge distillation with pseudo-labeling. Given a large audio dataset, we employ a high-performing teacher model to train very small student models. In contrast to the pre-trained speech encoders, our student models only consist of convolutional and fully-connected layers, removing the need for attention context or recurrent updates. In our experiments, we demonstrate that we can reduce the memory footprint to up to 3.4 MB and required future audio context to up to 81 ms while maintaining high-quality animations. This paves the way for on-device inference, an important step towards realistic, model-driven digital characters.

[Arxiv](https://arxiv.org/abs/2507.18352)