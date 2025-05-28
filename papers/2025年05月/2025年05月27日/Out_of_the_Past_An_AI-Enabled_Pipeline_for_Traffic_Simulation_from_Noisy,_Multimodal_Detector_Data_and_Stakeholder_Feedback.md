# 走出过去：基于AI的交通模拟管道，从杂乱的多源数据和多方反馈中构建

发布时间：2025年05月27日

`LLM应用`

> Out of the Past: An AI-Enabled Pipeline for Traffic Simulation from Noisy, Multimodal Detector Data and Stakeholder Feedback

# 摘要

> 如何设计交通模拟，才能真实反映现实中的交通状况？过去基于数据的交通模拟方法往往依赖不切实际或次优的启发式规则，也无法充分考虑数据中的不确定性和多模态性对模拟结果的影响。我们整合了人工智能领域的最新进展，构建了一个三步式的端到端管道，从检测器数据生成交通模拟：使用计算机视觉从摄像头画面中进行车辆计数，利用组合优化从多模态数据中生成车辆路线，以及借助大型语言模型根据自然语言反馈进行迭代模拟优化。以俄亥俄州斯特rongsville市的路网作为试验平台，我们证明了我们的管道能够准确捕捉该市的交通模式，在细致的模拟中再现真实的交通状况。除了斯特rongsville，我们的交通模拟框架还可以推广到其他城市，适应不同数据和基础设施可用性的需求。

> How can a traffic simulation be designed to faithfully reflect real-world traffic conditions? Past data-driven approaches to traffic simulation in the literature have relied on unrealistic or suboptimal heuristics. They also fail to adequately account for the effects of uncertainty and multimodality in the data on simulation outcomes. In this work, we integrate advances in AI to construct a three-step, end-to-end pipeline for generating a traffic simulation from detector data: computer vision for vehicle counting from camera footage, combinatorial optimization for vehicle route generation from multimodal data, and large language models for iterative simulation refinement from natural language feedback. Using a road network from Strongsville, Ohio as a testbed, we demonstrate that our pipeline can accurately capture the city's traffic patterns in a granular simulation. Beyond Strongsville, our traffic simulation framework can be generalized to other municipalities with different levels of data and infrastructure availability.

[Arxiv](https://arxiv.org/abs/2505.21349)