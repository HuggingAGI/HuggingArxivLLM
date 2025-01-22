# 基于LLM-Agents的小型无人航空系统自动化模拟测试与分析

发布时间：2025年01月20日

`Agent

理由：这篇论文描述了一个由大型语言模型（LLM）驱动的框架（AutoSimTest），其中多个LLM代理协作支持小型无人驾驶航空系统（sUAS）的模拟测试。这些代理负责创建测试场景、准备模拟环境、生成任务以及分析结果。因此，论文的核心内容涉及多个LLM代理的协作和任务执行，符合“Agent”分类的定义。` `无人驾驶航空系统` `模拟测试`

> LLM-Agents Driven Automated Simulation Testing and Analysis of small Uncrewed Aerial Systems

# 摘要

> # 摘要
全面的模拟测试对于验证小型无人驾驶航空系统（sUAS）在多种场景下的正确行为至关重要，包括恶劣天气（如风、雾）、多样化环境（如丘陵或城市）以及不同任务（如监视、跟踪）。尽管已有多种sUAS模拟工具，但创建、执行和分析测试的过程仍以手动为主，繁琐且耗时。开发者需识别测试场景、设置环境、集成测试系统（SuT）、制定任务计划并分析结果，这些繁重任务限制了广泛场景下的详尽测试。为此，我们提出了AutoSimTest，一个由大型语言模型（LLM）驱动的框架，多个LLM代理协作支持sUAS模拟测试。该框架包括：（1）创建独特环境下的测试场景；（2）根据场景准备模拟环境；（3）生成多样化任务；（4）分析结果并提供交互式界面。此外，框架设计灵活，适用于多种sUAS用例、模拟工具和SuT需求。我们通过（a）对PX4和ArduPilot飞行控制器的SuT进行模拟测试，（b）分析代理性能，（c）收集开发者反馈来评估方法。结果表明，AutoSimTest显著提升了测试效率和范围，支持更全面、多样化的场景评估，同时减少了手动工作量。

> Thorough simulation testing is crucial for validating the correct behavior of small Uncrewed Aerial Systems (sUAS) across multiple scenarios, including adverse weather conditions (such as wind, and fog), diverse settings (hilly terrain, or urban areas), and varying mission profiles (surveillance, tracking). While various sUAS simulation tools exist to support developers, the entire process of creating, executing, and analyzing simulation tests remains a largely manual and cumbersome task. Developers must identify test scenarios, set up the simulation environment, integrate the System under Test (SuT) with simulation tools, formulate mission plans, and collect and analyze results. These labor-intensive tasks limit the ability of developers to conduct exhaustive testing across a wide range of scenarios. To alleviate this problem, in this paper, we propose AutoSimTest, a Large Language Model (LLM)-driven framework, where multiple LLM agents collaborate to support the sUAS simulation testing process. This includes: (1) creating test scenarios that subject the SuT to unique environmental contexts; (2) preparing the simulation environment as per the test scenario; (3) generating diverse sUAS missions for the SuT to execute; and (4) analyzing simulation results and providing an interactive analytics interface. Further, the design of the framework is flexible for creating and testing scenarios for a variety of sUAS use cases, simulation tools, and SuT input requirements. We evaluated our approach by (a) conducting simulation testing of PX4 and ArduPilot flight-controller-based SuTs, (b) analyzing the performance of each agent, and (c) gathering feedback from sUAS developers. Our findings indicate that AutoSimTest significantly improves the efficiency and scope of the sUAS testing process, allowing for more comprehensive and varied scenario evaluations while reducing the manual effort.

[Arxiv](https://arxiv.org/abs/2501.11864)