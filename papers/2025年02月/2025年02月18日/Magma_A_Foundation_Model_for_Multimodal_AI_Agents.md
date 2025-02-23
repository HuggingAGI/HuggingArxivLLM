# Magma：专为多模态AI代理打造的基石模型

发布时间：2025年02月18日

`Agent` `机器人` `人工智能`

> Magma: A Foundation Model for Multimodal AI Agents

# 摘要

> 我们推出了一款名为 Magma 的基础模型，它能够服务于数字和物理世界中的多模态 AI 代理任务。作为视觉语言 (VL) 模型的重大扩展，Magma 不仅保留了 VL 理解能力（语言智能），还新增了在视觉-空间世界中规划和行动的能力（时空智能），能够完成从 UI 导航到机器人操作等多样化任务。为了赋予这些代理能力，Magma 在涵盖图像、视频和机器人数据的异构数据集上进行了预训练。其中，图像中的可操作对象（如 GUI 中的按钮）通过集合标记 (SoM) 进行标注以实现动作定位，而视频中的物体运动轨迹（如人手或机械臂）则通过轨迹标记 (ToM) 进行标注以实现动作规划。实验结果显示，SoM 和 ToM 的协同作用显著提升了 Magma 在时空智能方面的学习效果，而这正是众多任务的核心能力，如图 1 所示。特别地，Magma 在 UI 导航和机器人操作任务中达到了新的 state-of-the-art 水平，超越了专门为此类任务设计的先前模型。在图像和视频相关的多模态任务上，Magma 也优于那些基于更大数据集训练的流行多模态大模型。为了便于研究复现，我们已在 https://microsoft.github.io/Magma 上开源了模型和代码。

> We present Magma, a foundation model that serves multimodal AI agentic tasks in both the digital and physical worlds. Magma is a significant extension of vision-language (VL) models in that it not only retains the VL understanding ability (verbal intelligence) of the latter, but is also equipped with the ability to plan and act in the visual-spatial world (spatial-temporal intelligence) and complete agentic tasks ranging from UI navigation to robot manipulation. To endow the agentic capabilities, Magma is pretrained on large amounts of heterogeneous datasets spanning from images, videos to robotics data, where the actionable visual objects (e.g., clickable buttons in GUI) in images are labeled by Set-of-Mark (SoM) for action grounding, and the object movements (e.g., the trace of human hands or robotic arms) in videos are labeled by Trace-of-Mark (ToM) for action planning. Extensive experiments show that SoM and ToM reach great synergy and facilitate the acquisition of spatial-temporal intelligence for our Magma model, which is fundamental to a wide range of tasks as shown in Fig.1. In particular, Magma creates new state-of-the-art results on UI navigation and robotic manipulation tasks, outperforming previous models that are specifically tailored to these tasks. On image and video-related multimodal tasks, Magma also compares favorably to popular large multimodal models that are trained on much larger datasets. We make our model and code public for reproducibility at https://microsoft.github.io/Magma.

[Arxiv](https://arxiv.org/abs/2502.13130)