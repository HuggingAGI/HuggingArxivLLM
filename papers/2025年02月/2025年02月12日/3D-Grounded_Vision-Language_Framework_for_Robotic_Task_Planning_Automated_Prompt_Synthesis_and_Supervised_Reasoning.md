# 3D-Grounded Vision-Language Framework for Robotic Task Planning: Automated Prompt Synthesis and Supervised Reasoning
基于三维的视觉语言框架在机器人任务规划中的应用：自动提示合成与监督推理

发布时间：2025年02月12日

`LLM应用

LLM应用` `机器人` `计算机视觉`

> 3D-Grounded Vision-Language Framework for Robotic Task Planning: Automated Prompt Synthesis and Supervised Reasoning

# 摘要

> 视觉语言模型（VLMs）在场景理解与感知任务中取得了显著的成功，使机器人能够自适应地规划和执行动作，应对动态环境的挑战。然而，现有模型在3D场景定位能力上的不足，限制了其在精细机器人操作中的应用。此外，识别精度、效率、迁移能力和可靠性方面的不足，也阻碍了其在高精度任务中的广泛应用。为了解决这些问题，我们提出了一种创新性框架，通过将2D图像映射到点云，引入了2D提示合成模块，并结合小型语言模型（SLM）来监督VLM的输出。2D提示合成模块使仅基于2D图像和文本训练的VLM能够自主提取精确的3D空间信息，无需人工干预，从而显著提升了3D场景理解能力。同时，SLM对VLM的输出进行监督，减少了幻觉现象，确保生成的机器人控制代码可靠且可执行。我们的框架无需在新环境中重新训练，从而提高了成本效率和运行稳健性。实验结果表明，所提出的框架实现了96.0%的任务成功率（TSR），优于其他方法。消融实验表明，2D提示合成模块和输出监督模块都起到了关键作用（当移除这些模块时，TSR下降了67%）。这些结果验证了该框架在提升3D识别、任务规划和机器人任务执行方面的有效性。

> Vision-language models (VLMs) have achieved remarkable success in scene understanding and perception tasks, enabling robots to plan and execute actions adaptively in dynamic environments. However, most multimodal large language models lack robust 3D scene localization capabilities, limiting their effectiveness in fine-grained robotic operations. Additionally, challenges such as low recognition accuracy, inefficiency, poor transferability, and reliability hinder their use in precision tasks. To address these limitations, we propose a novel framework that integrates a 2D prompt synthesis module by mapping 2D images to point clouds, and incorporates a small language model (SLM) for supervising VLM outputs. The 2D prompt synthesis module enables VLMs, trained on 2D images and text, to autonomously extract precise 3D spatial information without manual intervention, significantly enhancing 3D scene understanding. Meanwhile, the SLM supervises VLM outputs, mitigating hallucinations and ensuring reliable, executable robotic control code generation. Our framework eliminates the need for retraining in new environments, thereby improving cost efficiency and operational robustness. Experimental results that the proposed framework achieved a 96.0\% Task Success Rate (TSR), outperforming other methods. Ablation studies demonstrated the critical role of both the 2D prompt synthesis module and the output supervision module (which, when removed, caused a 67\% TSR drop). These findings validate the framework's effectiveness in improving 3D recognition, task planning, and robotic task execution.

[Arxiv](https://arxiv.org/abs/2502.08903)