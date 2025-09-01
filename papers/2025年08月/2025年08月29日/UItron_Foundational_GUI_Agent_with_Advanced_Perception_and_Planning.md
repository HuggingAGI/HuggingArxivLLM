# UItron：基础GUI智能体——具备先进感知与规划能力

发布时间：2025年08月29日

`Agent` `基础理论`

> UItron: Foundational GUI Agent with Advanced Perception and Planning

# 摘要

> GUI智能体旨在实现移动/PC设备的自动化操作，是通用人工智能发展的关键课题。视觉语言模型（VLMs）凭借强大的视觉理解与任务规划能力，极大加速了GUI智能体的研发进程。但构建GUI智能体仍面临三大挑战：操作轨迹数据匮乏、交互基础设施缺失，以及基础模型初始能力受限。本研究推出UItron——一款开源的GUI智能体基础模型，具备先进的GUI感知、元素定位与任务规划能力。UItron核心创新在于：将系统性数据工程与交互基础设施确立为推动GUI智能体发展的底层支柱。它不仅系统探索了多类数据工程策略以提升训练效果，还搭建了贯通移动与PC设备的交互环境。训练阶段，UItron先通过监督微调在多场景GUI任务中优化感知与规划能力，再引入课程强化学习框架，实现对在线环境的复杂推理与探索。最终，UItron在GUI感知、定位及规划基准测试中表现卓越。特别值得关注的是，针对当前主流方案普遍缺乏中文能力的痛点，UItron在中文移动应用交互上展现出突出优势。为此，我们手动采集了Top 100热门应用的超百万步操作轨迹，并构建了离线与在线智能体评估环境。实验结果显示，UItron在中文应用场景中取得突破性进展，让GUI智能体向落地应用更近一步。

> GUI agent aims to enable automated operations on Mobile/PC devices, which is an important task toward achieving artificial general intelligence. The rapid advancement of VLMs accelerates the development of GUI agents, owing to their powerful capabilities in visual understanding and task planning. However, building a GUI agent remains a challenging task due to the scarcity of operation trajectories, the availability of interactive infrastructure, and the limitation of initial capabilities in foundation models. In this work, we introduce UItron, an open-source foundational model for automatic GUI agents, featuring advanced GUI perception, grounding, and planning capabilities. UItron highlights the necessity of systemic data engineering and interactive infrastructure as foundational components for advancing GUI agent development. It not only systematically studies a series of data engineering strategies to enhance training effects, but also establishes an interactive environment connecting both Mobile and PC devices. In training, UItron adopts supervised finetuning over perception and planning tasks in various GUI scenarios, and then develop a curriculum reinforcement learning framework to enable complex reasoning and exploration for online environments. As a result, UItron achieves superior performance in benchmarks of GUI perception, grounding, and planning. In particular, UItron highlights the interaction proficiency with top-tier Chinese mobile APPs, as we identified a general lack of Chinese capabilities even in state-of-the-art solutions. To this end, we manually collect over one million steps of operation trajectories across the top 100 most popular apps, and build the offline and online agent evaluation environments. Experimental results demonstrate that UItron achieves significant progress in Chinese app scenarios, propelling GUI agents one step closer to real-world application.

[Arxiv](https://arxiv.org/abs/2508.21767)