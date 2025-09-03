# <翻译失败>

发布时间：2025年08月29日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> Mechanistic interpretability for steering vision-language-action models

# 摘要

> <翻译失败>

> Vision-Language-Action (VLA) models are a promising path to realizing generalist embodied agents that can quickly adapt to new tasks, modalities, and environments. However, methods for interpreting and steering VLAs fall far short of classical robotics pipelines, which are grounded in explicit models of kinematics, dynamics, and control. This lack of mechanistic insight is a central challenge for deploying learned policies in real-world robotics, where robustness and explainability are critical. Motivated by advances in mechanistic interpretability for large language models, we introduce the first framework for interpreting and steering VLAs via their internal representations, enabling direct intervention in model behavior at inference time. We project feedforward activations within transformer layers onto the token embedding basis, identifying sparse semantic directions - such as speed and direction - that are causally linked to action selection. Leveraging these findings, we introduce a general-purpose activation steering method that modulates behavior in real time, without fine-tuning, reward signals, or environment interaction. We evaluate this method on two recent open-source VLAs, Pi0 and OpenVLA, and demonstrate zero-shot behavioral control in simulation (LIBERO) and on a physical robot (UR5). This work demonstrates that interpretable components of embodied VLAs can be systematically harnessed for control - establishing a new paradigm for transparent and steerable foundation models in robotics.

[Arxiv](https://arxiv.org/abs/2509.00328)