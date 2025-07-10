# SkyVLN：基于视觉-语言导航与非线性模型预测控制的城市环境中无人机导航系统

发布时间：2025年07月09日

`LLM应用` `无人机` `城市环境`

> SkyVLN: Vision-and-Language Navigation and NMPC Control for UAVs in Urban Environments

# 摘要

> # 摘要
近年来，无人机因其出色的机动性和适应性，在各领域中已成为不可或缺的多功能工具。本文提出了一种全新的SkyVLN框架，将视觉语言导航（VLN）与非线性模型预测控制（NMPC）相结合，致力于提升无人机在复杂城市环境中的自主导航能力。与传统导航方法不同，SkyVLN创新性地运用大型语言模型（LLMs）来解析自然语言指令和视觉观测信息，从而实现无人机在动态三维空间中更精准、更稳健的导航。我们设计了一种多模态导航代理，配备精细的空间描述器和历史路径记忆机制，使其能够准确解析空间上下文、处理模糊指令，并在必要时灵活回溯。此外，SkyVLN框架还集成了一个动态障碍物避障的NMPC模块，确保无人机能够实现精准的轨迹跟踪和可靠的碰撞预防。为了验证我们的方法，我们利用AirSim打造了一个高保真的三维城市仿真环境，其中包含逼真的图像和丰富的动态城市元素。通过大量实验验证，SkyVLN在全新的未知环境中表现出色，显著提升了导航的成功率和效率。


> Unmanned Aerial Vehicles (UAVs) have emerged as versatile tools across various sectors, driven by their mobility and adaptability. This paper introduces SkyVLN, a novel framework integrating vision-and-language navigation (VLN) with Nonlinear Model Predictive Control (NMPC) to enhance UAV autonomy in complex urban environments. Unlike traditional navigation methods, SkyVLN leverages Large Language Models (LLMs) to interpret natural language instructions and visual observations, enabling UAVs to navigate through dynamic 3D spaces with improved accuracy and robustness. We present a multimodal navigation agent equipped with a fine-grained spatial verbalizer and a history path memory mechanism. These components allow the UAV to disambiguate spatial contexts, handle ambiguous instructions, and backtrack when necessary. The framework also incorporates an NMPC module for dynamic obstacle avoidance, ensuring precise trajectory tracking and collision prevention. To validate our approach, we developed a high-fidelity 3D urban simulation environment using AirSim, featuring realistic imagery and dynamic urban elements. Extensive experiments demonstrate that SkyVLN significantly improves navigation success rates and efficiency, particularly in new and unseen environments.

[Arxiv](https://arxiv.org/abs/2507.06564)