# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年07月11日

`Agent` `工程设计` `系统设计`

> Agentic Large Language Models for Conceptual Systems Engineering and Design

# 摘要

> # 摘要
早期工程设计通常涉及复杂且迭代的推理过程，现有大型语言模型（LLM）工作流程在保持任务连续性和生成可执行模型方面仍面临挑战。我们研究了一种结构化的多智能体系统（MAS）是否能比更简单的两智能体系统（2AS）更有效地管理需求提取、功能分解以及模拟器代码生成。目标应用是一个太阳能净水系统，其设计要求在技术规格书中有所描述。

我们引入了设计状态图（DSG），这是一种可JSON序列化的表示方法，将需求、物理实现以及基于Python的物理模型打包为图节点。一个包含九个角色的MAS系统通过迭代构建和优化DSG，而2AS则将该过程简化为一个生成器-反思器循环。两个系统均运行了总共60次实验（2种LLM - Llama 3.3 70B vs经过推理蒸馏的DeepSeek R1 70B x 2种代理配置 x 3种温度设置 x 5种随机种子）。

实验结果表明：在所有运行中，MAS和2AS均保持了完美的JSON完整性和实现标记。需求覆盖率始终保持在较低水平（低于20%）。代码兼容性在特定2AS设置下达到100%峰值，但MAS的平均值低于50%。只有经过推理蒸馏的模型能够可靠地标记工作流完成状态。由DeepSeek R1 70B驱动的MAS生成了更细致的DSGs（平均5-6个节点），而2AS则模式化地简化了结构。结构化的多智能体编排增强了设计细节。经过推理蒸馏的LLM提高了完成率，但需求覆盖不足和编码保真度差距的问题仍然存在。


> Early-stage engineering design involves complex, iterative reasoning, yet existing large language model (LLM) workflows struggle to maintain task continuity and generate executable models. We evaluate whether a structured multi-agent system (MAS) can more effectively manage requirements extraction, functional decomposition, and simulator code generation than a simpler two-agent system (2AS). The target application is a solar-powered water filtration system as described in a cahier des charges. We introduce the Design-State Graph (DSG), a JSON-serializable representation that bundles requirements, physical embodiments, and Python-based physics models into graph nodes. A nine-role MAS iteratively builds and refines the DSG, while the 2AS collapses the process to a Generator-Reflector loop. Both systems run a total of 60 experiments (2 LLMs - Llama 3.3 70B vs reasoning-distilled DeepSeek R1 70B x 2 agent configurations x 3 temperatures x 5 seeds). We report a JSON validity, requirement coverage, embodiment presence, code compatibility, workflow completion, runtime, and graph size. Across all runs, both MAS and 2AS maintained perfect JSON integrity and embodiment tagging. Requirement coverage remained minimal (less than 20\%). Code compatibility peaked at 100\% under specific 2AS settings but averaged below 50\% for MAS. Only the reasoning-distilled model reliably flagged workflow completion. Powered by DeepSeek R1 70B, the MAS generated more granular DSGs (average 5-6 nodes) whereas 2AS mode-collapsed. Structured multi-agent orchestration enhanced design detail. Reasoning-distilled LLM improved completion rates, yet low requirements and fidelity gaps in coding persisted.

[Arxiv](https://arxiv.org/abs/2507.08619)