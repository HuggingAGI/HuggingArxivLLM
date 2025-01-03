# 通过观察物体运动实现基于指令的图像操作

发布时间：2024年12月16日

`LLM应用

**理由**：该论文主要讨论了利用多模态大型语言模型（MLLMs）生成编辑指令，并构建数据集用于训练基于指令的图像处理模型。这属于将大型语言模型应用于具体任务（图像处理）的范畴，因此分类为LLM应用。` `计算机视觉` `图像处理`

> Instruction-based Image Manipulation by Watching How Things Move

# 摘要

> 本文提出了一种创新的数据集构建方法，通过从视频中提取帧对，并利用多模态大型语言模型（MLLMs）生成编辑指令，用于训练基于指令的图像处理模型。视频帧天然保留了主体和场景的完整性，确保编辑过程中的内容一致性。此外，视频数据捕捉了丰富的自然动态，如非刚性主体运动和复杂相机运动，这些动态难以通过其他方式模拟，因此成为构建可扩展数据集的理想选择。基于此方法，我们构建了一个新数据集，用于训练InstructMove模型，该模型能够执行基于指令的复杂操作，这些操作在合成数据集中难以实现。我们的模型在调整主体姿态、重新排列元素和改变相机视角等任务中表现出色，达到了业界领先水平。

> This paper introduces a novel dataset construction pipeline that samples pairs of frames from videos and uses multimodal large language models (MLLMs) to generate editing instructions for training instruction-based image manipulation models. Video frames inherently preserve the identity of subjects and scenes, ensuring consistent content preservation during editing. Additionally, video data captures diverse, natural dynamics-such as non-rigid subject motion and complex camera movements-that are difficult to model otherwise, making it an ideal source for scalable dataset construction. Using this approach, we create a new dataset to train InstructMove, a model capable of instruction-based complex manipulations that are difficult to achieve with synthetically generated datasets. Our model demonstrates state-of-the-art performance in tasks such as adjusting subject poses, rearranging elements, and altering camera perspectives.

[Arxiv](https://arxiv.org/abs/2412.12087)