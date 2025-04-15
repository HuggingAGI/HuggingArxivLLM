# AGENT：一款基于大型语言模型的飞行器生成与设计工具

发布时间：2025年04月11日

`LLM应用` `航空航天`

> AGENT: An Aerial Vehicle Generation and Design Tool Using Large Language Models

# 摘要

> 计算机辅助设计（CAD）是新兴人工智能方法的热门应用领域。传统的网络物理系统工作流创建详细数字模型，通过物理仿真器评估以缩小原型制作前的搜索空间。然而，仿真器计算成本高且速度慢，成为主要瓶颈。近期人工智能方法的进展为加速这些流程提供了新可能。

我们采用最近发布的AircraftVerse数据集，该数据集专为开发和评估设计领域的大语言模型而设计。它包含一系列通过文本设计树表示的无人机设计，附带详细物理仿真结果。借鉴大型语言模型（LLMs）的成功，我们提出AGENT（Aircraft GENeraTor），这是一个基于CodeT5+ LLM的综合设计工具，直接从JSON文件学习飞机文本设计的强大表示。

我们开发了训练任务课程，赋予单个模型多种实用功能。AGENT可根据飞行动力学属性（悬停时间、最大速度等）生成设计，并能对设计进行评估，从而作为AircraftVerse数据集物理仿真的代理模型。实验结果展示了系统的能力。我们使用CodeT5+家族最小成员（220M参数）实现了强大性能，使其成为灵活强大的系统，在单GPU上即可运行，为未来部署提供了清晰路径。

> Computer-aided design (CAD) is a promising application area for emerging artificial intelligence methods. Traditional workflows for cyberphysical systems create detailed digital models which can be evaluated by physics simulators in order to narrow the search space before creating physical prototypes. A major bottleneck of this approach is that the simulators are often computationally expensive and slow. Recent advancements in AI methods offer the possibility to accelerate these pipelines. We use the recently released AircraftVerse dataset, which is especially suited for developing and evaluating large language models for designs. AircraftVerse contains a diverse set of UAV designs represented via textual design trees together with detailed physics simulation results. Following the recent success of large language models (LLMs), we propose AGENT (Aircraft GENeraTor). AGENT is a comprehensive design tool built on the CodeT5+ LLM which learns powerful representations of aircraft textual designs directly from JSON files. We develop a curriculum of training tasks which imbues a single model with a suite of useful features. AGENT is able to generate designs conditioned on properties of flight dynamics (hover time, maximum speed, etc.). Additionally, AGENT can issue evaluations of designs allowing it to act as a surrogate model of the physics simulation that underlies the AircraftVerse dataset. We present a series of experiments which demonstrate our system's abilities. We are able to achieve strong performance using the smallest member of the CodeT5+ family (220M parameters). This allows for a flexible and powerful system which can be executed on a single GPU enabling a clear path toward future deployment.

[Arxiv](https://arxiv.org/abs/2504.08981)