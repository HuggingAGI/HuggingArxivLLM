# VeriOS：面向可信操作系统智能体的查询驱动式主动人机-智能体-图形界面交互

发布时间：2025年09月09日

`Agent` `基础理论`

> VeriOS: Query-Driven Proactive Human-Agent-GUI Interaction for Trustworthy OS Agents

# 摘要

> 随着多模态大型语言模型的飞速发展，操作系统（OS）智能体借助设备端图形用户界面（GUIs）实现任务自动化的能力越来越强。但大多数现有OS智能体均面向理想化场景设计，现实环境却常出现不可信状况。为降低此类场景中的过度执行风险，我们提出了一种查询驱动的人-智能体-GUI交互框架，让OS智能体可自主判断何时向人类发起查询，从而确保任务更可靠地完成。基于该框架，我们开发了VeriOS-Agent——一种可信的OS智能体，它通过两阶段学习范式训练，能够有效解耦并利用元知识。具体来说，VeriOS-Agent在正常场景中可自主执行操作，遇到不可信场景时则会主动向人类咨询。实验结果显示，在不可信场景中，VeriOS-Agent相较于现有最优方法，平均分步成功率提升了20.64%，且不会降低正常场景下的性能。分析结果表明，VeriOS-Agent具备良好的合理性、泛化性和可扩展性。相关代码、数据集及模型已开源，地址为https://github.com/Wuzheng02/VeriOS。

> With the rapid progress of multimodal large language models, operating system (OS) agents become increasingly capable of automating tasks through on-device graphical user interfaces (GUIs). However, most existing OS agents are designed for idealized settings, whereas real-world environments often present untrustworthy conditions. To mitigate risks of over-execution in such scenarios, we propose a query-driven human-agent-GUI interaction framework that enables OS agents to decide when to query humans for more reliable task completion. Built upon this framework, we introduce VeriOS-Agent, a trustworthy OS agent trained with a two-stage learning paradigm that falicitate the decoupling and utilization of meta-knowledge. Concretely, VeriOS-Agent autonomously executes actions in normal conditions while proactively querying humans in untrustworthy scenarios. Experiments show that VeriOS-Agent improves the average step-wise success rate by 20.64\% in untrustworthy scenarios over the state-of-the-art, without compromising normal performance. Analysis highlights VeriOS-Agent's rationality, generalizability, and scalability. The codes, datasets and models are available at https://github.com/Wuzheng02/VeriOS.

[Arxiv](https://arxiv.org/abs/2509.07553)