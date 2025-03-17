# 桌面视觉：大规模桌面区域描述，助力高级 GUI 代理

发布时间：2025年03月14日

`其他` `软件工程` `用户体验`

> DeskVision: Large Scale Desktop Region Captioning for Advanced GUI Agents

# 摘要

> 图形用户界面（GUI）数据的局限性一直是 GUI 代理开发的重要障碍，尤其是在桌面场景中。为解决这一难题，我们提出了自动化 GUI 数据生成管道 AutoCaptioner，它能够高效生成具有丰富描述的数据，大幅减少人工 effort。利用 AutoCaptioner，我们创建了新型大规模桌面 GUI 数据集 DeskVision，以及涵盖多种系统和 UI 元素的桌面测试基准 DeskVision-Eval，每个元素都配有详尽描述，真实反映日常使用场景。基于 DeskVision，我们开发了全新 GUI 理解模型 GUIExplorer，该模型在理解视觉元素方面无需复杂架构设计即可达到最先进性能。我们通过在多种大型视觉语言模型上的消融研究，进一步验证了 DeskVision 数据集的显著价值。我们相信，AutoCaptioner 和 DeskVision 将为 GUI 代理领域带来重要突破，并计划将其开源，助力社区共同进步。

> The limitation of graphical user interface (GUI) data has been a significant barrier to the development of GUI agents today, especially for the desktop / computer use scenarios. To address this, we propose an automated GUI data generation pipeline, AutoCaptioner, which generates data with rich descriptions while minimizing human effort. Using AutoCaptioner, we created a novel large-scale desktop GUI dataset, DeskVision, along with the largest desktop test benchmark, DeskVision-Eval, which reflects daily usage and covers diverse systems and UI elements, each with rich descriptions. With DeskVision, we train a new GUI understanding model, GUIExplorer. Results show that GUIExplorer achieves state-of-the-art (SOTA) performance in understanding/grounding visual elements without the need for complex architectural designs. We further validated the effectiveness of the DeskVision dataset through ablation studies on various large visual language models (LVLMs). We believe that AutoCaptioner and DeskVision will significantly advance the development of GUI agents, and will open-source them for the community.

[Arxiv](https://arxiv.org/abs/2503.11170)