# 一种面向基于意图的方法与零接触网络的新颖集成架构

发布时间：2025年09月25日

`RAG` `基础理论`

> A Novel Integrated Architecture for Intent Based Approach and Zero Touch Networks

# 摘要

> 向第六代（6G）网络转型面临诸多挑战，包括管理多样化应用的服务质量（QoS），以及在动态网络条件下实现服务等级协议（SLAs）。因此，必须借助机器学习（ML）和人工智能（AI）实现网络管理自动化，以满足实时需求。零接触网络（ZTN）是实现网络管理自动化的框架之一，它通过闭环控制等机制确保目标持续达成。基于意图的网络（IBN）用于明确用户的多样化网络需求或目标，并将其转化为具体的网络配置和操作。本文提出一种新型架构，通过整合IBN与ZTN来实现意图目标。用户以自然语言（如英语）形式输入意图，随后通过自然语言处理（NLP）技术（如检索增强生成（RAG））将其转换为网络意图语言（Nile）。接着，Nile意图作为目标被传递至基于双向长短期记忆网络（BiLSTM）和Q学习的ZTN闭环框架，该框架在动态网络条件下维持意图的实现。因此，所提架构可自主运行，用户只需用英语表述意图，即可确保网络性能目标的达成。该整合架构还在基于开放空中接口（OAI）的测试床上完成了部署。此外，为评估该架构，本文构建了优化问题，并通过蒙特卡洛模拟进行评估。结果表明，ZTN能够自主实现用户意图设定的带宽目标。模拟结果与测试床结果对比显示，二者趋势一致。同时，本文还测量了体验质量（QoE）的平均意见得分（MOS），以反映用户对意图实现的满意度。

> The transition to Sixth Generation (6G) networks presents challenges in managing quality of service (QoS) of diverse applications and achieving Service Level Agreements (SLAs) under varying network conditions. Hence, network management must be automated with the help of Machine Learning (ML) and Artificial Intelligence (AI) to achieve real-time requirements. Zero touch network (ZTN) is one of the frameworks to automate network management with mechanisms such as closed loop control to ensure that the goals are met perpetually. Intent- Based Networking (IBN) specifies the user intents with diverse network requirements or goals which are then translated into specific network configurations and actions. This paper presents a novel architecture for integrating IBN and ZTN to serve the intent goals. Users provides the intent in the form of natural language, e.g., English, which is then translated using natural language processing (NLP) techniques (e.g., retrieval augmented generation (RAG)) into Network Intent LanguagE (Nile). The Nile intent is then passed on to the BiLSTM and Q-learning based ZTN closed loop framework as a goal which maintains the intent under varying network conditions. Thus, the proposed architecture can work autonomously to ensure the network performance goal is met by just specifying the user intent in English. The integrated architecture is also implemented on a testbed using OpenAirInterface (OAI). Additionally, to evaluate the architecture, an optimization problem is formulated which evaluated with Monte Carlo simulations. Results demonstrate how ZTN can help achieve the bandwidth goals autonomously set by user intent. The simulation and the testbed results are compared and they show similar trend. Mean Opinion Score (MOS) for Quality of Experience (QoE) is also measured to indicate the user satisfaction of the intent.

[Arxiv](https://arxiv.org/abs/2509.21026)