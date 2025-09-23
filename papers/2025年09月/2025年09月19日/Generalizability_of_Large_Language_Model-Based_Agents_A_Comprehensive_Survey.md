# 大语言模型智能体的泛化能力：全面综述

发布时间：2025年09月19日

`Agent` `基础理论`

> Generalizability of Large Language Model-Based Agents: A Comprehensive Survey

# 摘要

> 基于大型语言模型（LLM）的智能体已成为一种新范式，将LLM的能力从文本生成拓展至与外部环境的动态交互。通过融合推理、感知、记忆与工具使用能力，这类智能体已被广泛应用于网页导航、家庭机器人等多元领域。然而，其核心挑战在于确保智能体的泛化性——即在多样指令、任务、环境及领域（尤其是超出智能体微调数据范围的场景）中保持稳定性能的能力。尽管相关研究热度渐增，但LLM智能体的泛化性概念尚未明确，亦缺乏系统性的测量与改进方法。本综述首次全面梳理了LLM智能体的泛化性研究：首先，我们从利益相关者视角强调泛化性的重要意义，并借助层级领域-任务本体框架厘清其边界；接着，综述现有数据集、评估维度与指标，并指出其局限性；随后，将泛化性改进方法分为三类：针对骨干LLM的优化、针对智能体组件的增强，以及针对组件交互的调控；此外，还区分了泛化框架与泛化智能体，阐述了如何将泛化框架转化为智能体层面的泛化能力。最后，明确关键挑战与未来方向，包括构建标准化框架、设计基于方差和成本的指标，以及探索方法创新与架构设计融合的路径。通过整合现有进展并聚焦未来机遇，本综述力求为构建可在多元应用中稳定泛化的LLM智能体奠定系统性研究基础。

> Large Language Model (LLM)-based agents have emerged as a new paradigm that extends LLMs' capabilities beyond text generation to dynamic interaction with external environments. By integrating reasoning with perception, memory, and tool use, agents are increasingly deployed in diverse domains like web navigation and household robotics. A critical challenge, however, lies in ensuring agent generalizability - the ability to maintain consistent performance across varied instructions, tasks, environments, and domains, especially those beyond agents' fine-tuning data. Despite growing interest, the concept of generalizability in LLM-based agents remains underdefined, and systematic approaches to measure and improve it are lacking. In this survey, we provide the first comprehensive review of generalizability in LLM-based agents. We begin by emphasizing agent generalizability's importance by appealing to stakeholders and clarifying the boundaries of agent generalizability by situating it within a hierarchical domain-task ontology. We then review datasets, evaluation dimensions, and metrics, highlighting their limitations. Next, we categorize methods for improving generalizability into three groups: methods for the backbone LLM, for agent components, and for their interactions. Moreover, we introduce the distinction between generalizable frameworks and generalizable agents and outline how generalizable frameworks can be translated into agent-level generalizability. Finally, we identify critical challenges and future directions, including developing standardized frameworks, variance- and cost-based metrics, and approaches that integrate methodological innovations with architecture-level designs. By synthesizing progress and highlighting opportunities, this survey aims to establish a foundation for principled research on building LLM-based agents that generalize reliably across diverse applications.

[Arxiv](https://arxiv.org/abs/2509.16330)