# 从建筑信息模型到机器人适用的现场数字孪生（BIM2RDT）：智能体AI安全优先框架

发布时间：2025年09月24日

`Agent` `工业与制造`

> Building Information Models to Robot-Ready Site Digital Twins (BIM2RDT): An Agentic AI Safety-First Framework

# 摘要

> 网络物理系统与工地智能的应用——通过连接设计模型、实时工地感知及自主现场作业——极大提升了建筑行业的数字化管理水平。本文提出BIM2RDT（建筑信息模型到机器人就绪工地数字孪生）框架，这是一种智能体人工智能（AI）架构，旨在将静态建筑信息模型（BIM）转化为动态、适配机器人的数字孪生（DTs），并在施工阶段优先保障安全性。该框架通过整合三大关键数据流，填补了既有BIM数据与实时工地状况间的鸿沟：BIM模型提供的几何与语义信息、物联网传感器网络采集的活动数据，以及机器人巡检时获取的视觉空间数据。方法上，本文提出语义重力ICP（SG-ICP）算法——一种融合大型语言模型（LLM）推理能力的点云配准技术。与传统方法不同，SG-ICP借助LLM基于BIM语义推断特定对象的合理方向先验，通过避免收敛于局部最小值提升配准精度。这形成反馈循环：机器人采集的数据更新数字孪生，数字孪生再优化任务路径。框架采用YOLOE目标检测与Shi-Tomasi角点检测技术识别并跟踪建筑构件，同时将BIM几何作为先验地图。此外，框架整合实时手臂振动（HAV）监测，依据IFC标准将传感器检测到的安全事件映射至数字孪生以实现干预。实验表明，SG-ICP性能优于标准ICP，在特征遮挡场景中配准均方根误差（RMSE）降低64.3%--88.3%，确保方向合理；HAV整合在暴露限值超标时触发警告，提升了对ISO 5349-1标准的合规性。

> The adoption of cyber-physical systems and jobsite intelligence that connects design models, real-time site sensing, and autonomous field operations can dramatically enhance digital management in the construction industry. This paper introduces BIM2RDT (Building Information Models to Robot-Ready Site Digital Twins), an agentic artificial intelligence (AI) framework designed to transform static Building Information Modeling (BIM) into dynamic, robot-ready digital twins (DTs) that prioritize safety during execution. The framework bridges the gap between pre-existing BIM data and real-time site conditions by integrating three key data streams: geometric and semantic information from BIM models, activity data from IoT sensor networks, and visual-spatial data collected by robots during site traversal. The methodology introduces Semantic-Gravity ICP (SG-ICP), a point cloud registration algorithm that leverages large language model (LLM) reasoning. Unlike traditional methods, SG-ICP utilizes an LLM to infer object-specific, plausible orientation priors based on BIM semantics, improving alignment accuracy by avoiding convergence on local minima. This creates a feedback loop where robot-collected data updates the DT, which in turn optimizes paths for missions. The framework employs YOLOE object detection and Shi-Tomasi corner detection to identify and track construction elements while using BIM geometry as a priori maps. The framework also integrates real-time Hand-Arm Vibration (HAV) monitoring, mapping sensor-detected safety events to the digital twin using IFC standards for intervention. Experiments demonstrate SG-ICP's superiority over standard ICP, achieving RMSE reductions of 64.3%--88.3% in alignment across scenarios with occluded features, ensuring plausible orientations. HAV integration triggers warnings upon exceeding exposure limits, enhancing compliance with ISO 5349-1.

[Arxiv](https://arxiv.org/abs/2509.20705)