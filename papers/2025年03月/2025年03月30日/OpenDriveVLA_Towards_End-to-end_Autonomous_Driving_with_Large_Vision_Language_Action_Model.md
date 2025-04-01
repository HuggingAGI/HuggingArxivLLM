# <翻译失败>

发布时间：2025年03月30日

`LLM应用` `自动驾驶` `智能驾驶`

> OpenDriveVLA: Towards End-to-end Autonomous Driving with Large Vision Language Action Model

# 摘要

> 我们推出了一款专为端到端自动驾驶设计的视觉语言动作模型——OpenDriveVLA。该模型基于开源预训练的大型视觉语言模型（VLMs），通过三维环境感知、自车状态和驾驶员指令生成可靠的驾驶动作。为了解决驾驶视觉表示与语言嵌入之间的模态差异，我们创新性地提出了一种层次化视觉语言对齐流程，将二维和三维结构化视觉令牌映射到统一的语义空间中。此外，OpenDriveVLA 采用自回归的 Agent-Env-Ego 交互机制，捕捉自车、周围目标与静态道路元素的动态关系，实现空间与行为双重信息驱动的轨迹规划。在 nuScenes 数据集上的广泛实验表明，OpenDriveVLA 在开放环路轨迹规划和驾驶问答任务中均达到了行业领先的水准。通过定性分析，我们进一步发现 OpenDriveVLA 在执行高级驾驶指令和应对复杂场景时展现出色的轨迹生成能力，充分彰显了其在下一代端到端自动驾驶中的巨大潜力。我们计划开源代码，助力该领域的持续探索与创新。

> We present OpenDriveVLA, a Vision-Language Action (VLA) model designed for end-to-end autonomous driving. OpenDriveVLA builds upon open-source pre-trained large Vision-Language Models (VLMs) to generate reliable driving actions, conditioned on 3D environmental perception, ego vehicle states, and driver commands. To bridge the modality gap between driving visual representations and language embeddings, we propose a hierarchical vision-language alignment process, projecting both 2D and 3D structured visual tokens into a unified semantic space. Besides, OpenDriveVLA models the dynamic relationships between the ego vehicle, surrounding agents, and static road elements through an autoregressive agent-env-ego interaction process, ensuring both spatially and behaviorally informed trajectory planning. Extensive experiments on the nuScenes dataset demonstrate that OpenDriveVLA achieves state-of-the-art results across open-loop trajectory planning and driving-related question-answering tasks. Qualitative analyses further illustrate OpenDriveVLA's superior capability to follow high-level driving commands and robustly generate trajectories under challenging scenarios, highlighting its potential for next-generation end-to-end autonomous driving. We will release our code to facilitate further research in this domain.

[Arxiv](https://arxiv.org/abs/2503.23463)