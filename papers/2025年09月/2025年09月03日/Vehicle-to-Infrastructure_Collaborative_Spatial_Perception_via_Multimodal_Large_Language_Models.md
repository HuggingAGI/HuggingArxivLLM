# 基于多模态大型语言模型的车路协同空间感知

发布时间：2025年09月03日

`LLM应用` `交通运输`

> Vehicle-to-Infrastructure Collaborative Spatial Perception via Multimodal Large Language Models

# 摘要

> 准确预测通信链路质量指标对车-基础设施（V2I）系统至关重要，是实现平滑切换、高效波束管理与可靠低延迟通信的核心。随着现代车辆传感器数据日益丰富，多模态大型语言模型（MLLMs）凭借跨任务适应性强、推理能力突出等优势得以广泛应用。然而，MLLMs本身缺乏三维空间理解能力。为此，本文提出一种轻量级、即插即用的鸟瞰图（BEV）注入连接器，以弥补这一不足。该框架通过收集周边车辆的感知数据，构建出环境的BEV；随后将此BEV表示与自车输入融合，为大型语言模型补充空间上下文信息。为支持真实场景下的多模态学习，本文构建了联合仿真环境，融合CARLA模拟器与基于MATLAB的射线追踪技术，可在多种场景下生成RGB、LiDAR、GPS及无线信号数据，指令与真值响应则通过程序从射线追踪输出中自动提取。实验在三个V2I链路预测任务上展开：视距（LoS）与非视距（NLoS）分类、链路可用性及阻塞预测。结果显示，所提BEV注入框架在所有任务中均能稳定提升性能：与仅基于自车数据的基线模型相比，准确率指标的宏平均提升13.9%；尤其在雨天、夜间等复杂场景下，性能提升幅度可达32.7%，充分证明了该框架在恶劣环境中的鲁棒性。

> Accurate prediction of communication link quality metrics is essential for vehicle-to-infrastructure (V2I) systems, enabling smooth handovers, efficient beam management, and reliable low-latency communication. The increasing availability of sensor data from modern vehicles motivates the use of multimodal large language models (MLLMs) because of their adaptability across tasks and reasoning capabilities. However, MLLMs inherently lack three-dimensional spatial understanding. To overcome this limitation, a lightweight, plug-and-play bird's-eye view (BEV) injection connector is proposed. In this framework, a BEV of the environment is constructed by collecting sensing data from neighboring vehicles. This BEV representation is then fused with the ego vehicle's input to provide spatial context for the large language model. To support realistic multimodal learning, a co-simulation environment combining CARLA simulator and MATLAB-based ray tracing is developed to generate RGB, LiDAR, GPS, and wireless signal data across varied scenarios. Instructions and ground-truth responses are programmatically extracted from the ray-tracing outputs. Extensive experiments are conducted across three V2I link prediction tasks: line-of-sight (LoS) versus non-line-of-sight (NLoS) classification, link availability, and blockage prediction. Simulation results show that the proposed BEV injection framework consistently improved performance across all tasks. The results indicate that, compared to an ego-only baseline, the proposed approach improves the macro-average of the accuracy metrics by up to 13.9%. The results also show that this performance gain increases by up to 32.7% under challenging rainy and nighttime conditions, confirming the robustness of the framework in adverse settings.

[Arxiv](https://arxiv.org/abs/2509.03837)