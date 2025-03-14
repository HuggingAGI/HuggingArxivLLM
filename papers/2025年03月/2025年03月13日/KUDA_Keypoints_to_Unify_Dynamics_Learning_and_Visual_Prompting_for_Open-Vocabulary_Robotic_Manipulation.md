# KUDA：关键点来统一动态学习与视觉提示，助力开放词汇的机器人操作

发布时间：2025年03月13日

`LLM应用` `机器人操作系统` `机器人操作`

> KUDA: Keypoints to Unify Dynamics Learning and Visual Prompting for Open-Vocabulary Robotic Manipulation

# 摘要

> 大型语言模型（LLMs）和视觉语言模型（VLMs）的快速发展推动了开放词汇机器人操作系统领域的显著进步。然而，现有方法往往忽视物体动力学的重要性，限制了其在复杂动态任务中的应用。为此，我们提出了KUDA——一个基于关键点整合动力学学习与视觉提示的开放词汇操作系统，充分利用VLMs和学习型神经动力学模型的优势。我们的核心发现是，基于关键点的目标规范不仅能被VLMs准确理解，还能高效转化为基于模型规划的成本函数。KUDA通过语言指令和视觉观察，首先在RGB图像上标注关键点，并利用VLM生成目标规范。这些基于关键点的抽象表示随后被转化为成本函数，结合学习到的动力学模型进行优化，从而生成机器人操作轨迹。我们在多种任务中验证了KUDA的效能，包括跨物体类别的自由形式语言指令、多物体交互以及对可变形或颗粒状物体的操作，充分证明了其框架的有效性。项目详情请访问http://kuda-dynamics.github.io。

> With the rapid advancement of large language models (LLMs) and vision-language models (VLMs), significant progress has been made in developing open-vocabulary robotic manipulation systems. However, many existing approaches overlook the importance of object dynamics, limiting their applicability to more complex, dynamic tasks. In this work, we introduce KUDA, an open-vocabulary manipulation system that integrates dynamics learning and visual prompting through keypoints, leveraging both VLMs and learning-based neural dynamics models. Our key insight is that a keypoint-based target specification is simultaneously interpretable by VLMs and can be efficiently translated into cost functions for model-based planning. Given language instructions and visual observations, KUDA first assigns keypoints to the RGB image and queries the VLM to generate target specifications. These abstract keypoint-based representations are then converted into cost functions, which are optimized using a learned dynamics model to produce robotic trajectories. We evaluate KUDA on a range of manipulation tasks, including free-form language instructions across diverse object categories, multi-object interactions, and deformable or granular objects, demonstrating the effectiveness of our framework. The project page is available at http://kuda-dynamics.github.io.

[Arxiv](https://arxiv.org/abs/2503.10546)