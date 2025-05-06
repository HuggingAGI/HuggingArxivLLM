# DriveAgent：基于大型语言模型与多模态传感器融合的多智能体结构化推理系统，专为自动驾驶设计。

发布时间：2025年05月04日

`LLM应用` `自动驾驶` `汽车工业`

> DriveAgent: Multi-Agent Structured Reasoning with LLM and Multimodal Sensor Fusion for Autonomous Driving

# 摘要

> 我们推出 DriveAgent，一个创新的多智能体自动驾驶框架，结合大型语言模型推理与多模态传感器融合技术，以增强对复杂驾驶场景的理解和决策能力。DriveAgent 独特之处在于将多种传感器（摄像头、激光雷达、GPS 和惯性测量单元）与基于 LLM 的分析流程相结合，通过专门的智能体实现协同工作。该框架采用模块化的智能体流水线设计，包含四个核心组件：(i) 描述性分析智能体，基于时间戳筛选关键传感器数据；(ii) 激光雷达与视觉智能体协同进行车辆状态与运动分析；(iii) 环境推理与因果分析智能体，解析情境变化及其机制；(iv) 具备紧迫性感知的决策生成智能体，优先处理关键信息并提出及时操作建议。这种模块化设计使 LLM 能够高效协调各类感知与推理智能体，为复杂驾驶场景提供连贯且可解释的解决方案。在多个具有挑战性的自动驾驶数据集上进行的大量实验表明，DriveAgent 在多项指标上显著超越传统方法。这些结果充分证明了基于 LLM 的多智能体传感器融合框架的有效性，彰显了其在提升自动驾驶系统稳定性和可靠性方面的巨大潜力。

> We introduce DriveAgent, a novel multi-agent autonomous driving framework that leverages large language model (LLM) reasoning combined with multimodal sensor fusion to enhance situational understanding and decision-making. DriveAgent uniquely integrates diverse sensor modalities-including camera, LiDAR, GPS, and IMU-with LLM-driven analytical processes structured across specialized agents. The framework operates through a modular agent-based pipeline comprising four principal modules: (i) a descriptive analysis agent identifying critical sensor data events based on filtered timestamps, (ii) dedicated vehicle-level analysis conducted by LiDAR and vision agents that collaboratively assess vehicle conditions and movements, (iii) environmental reasoning and causal analysis agents explaining contextual changes and their underlying mechanisms, and (iv) an urgency-aware decision-generation agent prioritizing insights and proposing timely maneuvers. This modular design empowers the LLM to effectively coordinate specialized perception and reasoning agents, delivering cohesive, interpretable insights into complex autonomous driving scenarios. Extensive experiments on challenging autonomous driving datasets demonstrate that DriveAgent is achieving superior performance on multiple metrics against baseline methods. These results validate the efficacy of the proposed LLM-driven multi-agent sensor fusion framework, underscoring its potential to substantially enhance the robustness and reliability of autonomous driving systems.

[Arxiv](https://arxiv.org/abs/2505.02123)