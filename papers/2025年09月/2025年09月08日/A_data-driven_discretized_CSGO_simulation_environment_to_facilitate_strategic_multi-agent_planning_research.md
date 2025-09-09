# 数据驱动的离散式CS:GO模拟环境：助力战略性多智能体规划研究

发布时间：2025年09月08日

`Agent` `媒体与娱乐`

> A data-driven discretized CS:GO simulation environment to facilitate strategic multi-agent planning research

# 摘要

> 用于复杂多智能体交互的现代仿真环境，必须在高保真细节与计算效率之间找到平衡。我们提出了DECOY——一种新型多智能体模拟器，它能将3D地形中的战略性长期规划抽象为高层离散化仿真，同时保留底层环境的保真度。以《反恐精英：全球攻势》（CS:GO）为测试平台，我们的框架仅通过移动决策实现战术定位，就能准确模拟游戏过程——无需对瞄准、射击等底层机制进行显式建模。我们方法的核心是一个航点系统，它能简化并离散化连续的状态与动作，并结合基于真实CS:GO锦标赛数据训练的神经预测与生成模型，用于重建事件结果。大量评估结果显示，DECOY基于人类数据生成的回放与原始游戏中的实际回放高度吻合。我们公开的仿真环境为战略性多智能体规划与行为生成研究的推进提供了宝贵工具。

> Modern simulation environments for complex multi-agent interactions must balance high-fidelity detail with computational efficiency. We present DECOY, a novel multi-agent simulator that abstracts strategic, long-horizon planning in 3D terrains into high-level discretized simulation while preserving low-level environmental fidelity. Using Counter-Strike: Global Offensive (CS:GO) as a testbed, our framework accurately simulates gameplay using only movement decisions as tactical positioning -- without explicitly modeling low-level mechanics such as aiming and shooting. Central to our approach is a waypoint system that simplifies and discretizes continuous states and actions, paired with neural predictive and generative models trained on real CS:GO tournament data to reconstruct event outcomes. Extensive evaluations show that replays generated from human data in DECOY closely match those observed in the original game. Our publicly available simulation environment provides a valuable tool for advancing research in strategic multi-agent planning and behavior generation.

[Arxiv](https://arxiv.org/abs/2509.06355)