# LLMs赋能自主控制：下一代工业自动化的智能体框架

发布时间：2025年07月03日

`Agent` `自动化`

> Autonomous Control Leveraging LLMs: An Agentic Framework for Next-Generation Industrial Automation

# 摘要

> 面对现代化工流程的复杂性、劳动力短缺以及复杂故障场景，本研究提出了一种融合符号推理与自适应控制的新型自动化范式。我们开发了一种统一的智能体框架，利用大型语言模型（LLMs）在同一架构中实现离散故障恢复规划与连续过程控制。采用有限状态机（FSMs）作为可解释的操作边界：LLM驱动的规划智能体通过FSM提出恢复序列，仿真智能体执行并验证每一步转换，而验证-重提示循环则迭代优化无效方案。在案例研究1中，针对180个随机生成的FSM（4-25个状态，4-300个转换），GPT-4o和GPT-4o-mini在五次重提示内均实现100%有效路径成功率，其准确性和延迟表现均优于开源LLMs。案例研究2中，同一框架在实验室TCLab平台（及其数字孪生）上调节双加热器输入，在持续不对称扰动下维持目标平均温度。相较于经典PID控制，我们的LLM控制器达到相似性能，而对提示循环的消融实验凸显了其在处理非线性动态中的关键作用。我们分析了主要失效模式，包括指令遵循失误和粗略ODE近似。研究结果表明，借助结构化反馈和模块化智能体，LLMs能够统一高层次符号规划与低层次连续控制，为化工领域实现稳健的语言驱动型自动化铺平道路。

> The increasing complexity of modern chemical processes, coupled with workforce shortages and intricate fault scenarios, demands novel automation paradigms that blend symbolic reasoning with adaptive control. In this work, we introduce a unified agentic framework that leverages large language models (LLMs) for both discrete fault-recovery planning and continuous process control within a single architecture. We adopt Finite State Machines (FSMs) as interpretable operating envelopes: an LLM-driven planning agent proposes recovery sequences through the FSM, a Simulation Agent executes and checks each transition, and a Validator-Reprompting loop iteratively refines invalid plans. In Case Study 1, across 180 randomly generated FSMs of varying sizes (4-25 states, 4-300 transitions), GPT-4o and GPT-4o-mini achieve 100% valid-path success within five reprompts-outperforming open-source LLMs in both accuracy and latency. In Case Study 2, the same framework modulates dual-heater inputs on a laboratory TCLab platform (and its digital twin) to maintain a target average temperature under persistent asymmetric disturbances. Compared to classical PID control, our LLM-based controller attains similar performance, while ablation of the prompting loop reveals its critical role in handling nonlinear dynamics. We analyze key failure modes-such as instruction following lapses and coarse ODE approximations. Our results demonstrate that, with structured feedback and modular agents, LLMs can unify high-level symbolic planningand low-level continuous control, paving the way towards resilient, language-driven automation in chemical engineering.

[Arxiv](https://arxiv.org/abs/2507.07115)