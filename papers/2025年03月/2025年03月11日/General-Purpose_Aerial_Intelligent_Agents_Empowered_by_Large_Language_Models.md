# 大型语言模型赋能的通用型空中智能体

发布时间：2025年03月11日

`LLM应用` `无人机` `工业自动化`

> General-Purpose Aerial Intelligent Agents Empowered by Large Language Models

# 摘要

> 大型语言模型 (LLMs) 的问世为无人机 (UAV) 带来了前所未有的发展机遇，但现有系统仍受限于硬件-软件协同设计的挑战，难以突破预定义任务的限制。本文首次提出了一种通过 LLM 推理与机器人自主性紧密结合的空中智能体，实现了开放世界任务的自主执行。我们的软硬件协同设计系统突破了两大关键限制：(1) 基于边缘优化计算平台实现机载 LLM 推理，峰值功耗仅 220W 时即可支持 140 亿参数模型以 5-6 token/秒的速度进行推理；(2) 一种创新的双向认知架构，实现了缓慢的深思熟虑规划（LLM 任务规划）与快速的反应式控制（状态估计、建图、避障及运动规划）的有机协同。通过初步实验结果验证，该系统在通信受限环境下展现出卓越的任务规划和场景理解能力，典型应用场景包括甘蔗监测、电网巡检、矿井隧道勘探和生物观测等。这项研究为具身化空中人工智能奠定了全新框架，成功填补了开放环境下任务规划与机器人自主性之间的鸿沟，为未来智能无人机的发展指明了方向。

> The emergence of large language models (LLMs) opens new frontiers for unmanned aerial vehicle (UAVs), yet existing systems remain confined to predefined tasks due to hardware-software co-design challenges. This paper presents the first aerial intelligent agent capable of open-world task execution through tight integration of LLM-based reasoning and robotic autonomy. Our hardware-software co-designed system addresses two fundamental limitations: (1) Onboard LLM operation via an edge-optimized computing platform, achieving 5-6 tokens/sec inference for 14B-parameter models at 220W peak power; (2) A bidirectional cognitive architecture that synergizes slow deliberative planning (LLM task planning) with fast reactive control (state estimation, mapping, obstacle avoidance, and motion planning). Validated through preliminary results using our prototype, the system demonstrates reliable task planning and scene understanding in communication-constrained environments, such as sugarcane monitoring, power grid inspection, mine tunnel exploration, and biological observation applications. This work establishes a novel framework for embodied aerial artificial intelligence, bridging the gap between task planning and robotic autonomy in open environments.

[Arxiv](https://arxiv.org/abs/2503.08302)