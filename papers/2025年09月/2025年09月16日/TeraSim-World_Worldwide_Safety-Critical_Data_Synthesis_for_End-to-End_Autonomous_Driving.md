# TeraSim-World：面向端到端自动驾驶的全球安全关键型数据合成

发布时间：2025年09月16日

`其他` `交通运输`

> TeraSim-World: Worldwide Safety-Critical Data Synthesis for End-to-End Autonomous Driving

# 摘要

> 端到端（E2E）自动驾驶的安全规模化部署离不开海量多样的数据支撑，其中安全关键事件数据尤为重要。现有数据要么来自模拟器（存在明显的“仿真-现实”鸿沟），要么通过道路测试采集（成本高且风险大）。本文提出TeraSim-World——一个自动化数据合成管道，能够为全球任意地点的端到端自动驾驶系统生成真实且地理多样性丰富的安全关键数据。以任意地点为起点，TeraSim-World从地理空间数据源调取真实世界地图与交通需求数据；接着，它借鉴自然驾驶数据集模拟智能体行为，并通过设置多样化的不利条件构建极端场景；结合该地点的街景数据，TeraSim-World利用前沿视频生成模型Cosmos-Drive，实现了照片级真实感的地理锚定传感器渲染。通过融合智能体仿真与传感器仿真，TeraSim-World为端到端自动驾驶系统的训练与评估提供了可扩展的关键数据合成方案。

> Safe and scalable deployment of end-to-end (E2E) autonomous driving requires extensive and diverse data, particularly safety-critical events. Existing data are mostly generated from simulators with a significant sim-to-real gap or collected from on-road testing that is costly and unsafe. This paper presents TeraSim-World, an automated pipeline that synthesizes realistic and geographically diverse safety-critical data for E2E autonomous driving at anywhere in the world. Starting from an arbitrary location, TeraSim-World retrieves real-world maps and traffic demand from geospatial data sources. Then, it simulates agent behaviors from naturalistic driving datasets, and orchestrates diverse adversities to create corner cases. Informed by street views of the same location, it achieves photorealistic, geographically grounded sensor rendering via the frontier video generation model Cosmos-Drive. By bridging agent and sensor simulations, TeraSim-World provides a scalable and critical~data synthesis framework for training and evaluation of E2E autonomous driving systems.

[Arxiv](https://arxiv.org/abs/2509.13164)