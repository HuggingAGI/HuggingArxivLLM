# 智能体无人机：LLM驱动的自主系统——集成工具调用与认知推理

发布时间：2025年09月14日

`Agent` `交通运输`

> Agentic UAVs: LLM-Driven Autonomy with Integrated Tool-Calling and Cognitive Reasoning

# 摘要

> 无人机（UAVs）在国防、监控和灾害响应中的应用日益广泛，但多数系统仍停留在SAE 2-3级自动驾驶水平。由于依赖基于规则的控制和窄AI，它们在动态多变、充满不确定性的任务中适应性受限。现有的无人机框架缺乏上下文感知推理、自主决策能力和生态系统级集成，更关键的是，尚无任何框架利用具备工具调用功能的大型语言模型（LLM）代理实现实时知识访问。本文提出智能体无人机框架（Agentic UAVs framework），这是一种包含感知层（Perception）、推理层（Reasoning）、行动层（Action）、集成层（Integration）和学习层（Learning）的五层架构，为无人机赋予了LLM驱动的推理能力、数据库查询功能及第三方系统交互能力。基于ROS2和Gazebo构建的原型系统整合了YOLOv11目标检测、GPT-4推理及本地Gemma-3部署。在模拟搜救场景中，智能体无人机的检测置信度（0.79 vs. 0.72）、人员检测率（91% vs. 75%）和行动推荐率（92% vs. 4.5%）均显著提升。这些结果表明，仅需适度的计算开销，就能实现无人机自主水平和生态系统集成的质的飞跃。

> Unmanned Aerial Vehicles (UAVs) are increasingly deployed in defense, surveillance, and disaster response, yet most systems remain confined to SAE Level 2--3 autonomy. Their reliance on rule-based control and narrow AI restricts adaptability in dynamic, uncertain missions. Existing UAV frameworks lack context-aware reasoning, autonomous decision-making, and ecosystem-level integration; critically, none leverage Large Language Model (LLM) agents with tool-calling for real-time knowledge access. This paper introduces the Agentic UAVs framework, a five-layer architecture (Perception, Reasoning, Action, Integration, Learning) that augments UAVs with LLM-driven reasoning, database querying, and third-party system interaction. A ROS2 and Gazebo-based prototype integrates YOLOv11 object detection with GPT-4 reasoning and local Gemma-3 deployment. In simulated search-and-rescue scenarios, agentic UAVs achieved higher detection confidence (0.79 vs. 0.72), improved person detection rates (91% vs. 75%), and markedly increased action recommendation (92% vs. 4.5%). These results confirm that modest computational overhead enables qualitatively new levels of autonomy and ecosystem integration.

[Arxiv](https://arxiv.org/abs/2509.13352)