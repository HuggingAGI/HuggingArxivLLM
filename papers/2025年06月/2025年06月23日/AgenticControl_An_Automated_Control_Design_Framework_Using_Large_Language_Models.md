# AgenticControl：基于大型语言模型的自动化控制设计框架

发布时间：2025年06月23日

`LLM应用` `控制系统` `自动化`

> AgenticControl: An Automated Control Design Framework Using Large Language Models

# 摘要

> 传统的控制系统设计依赖于专家知识和精确的模型，难以应对复杂、非线性或不确定的动力学问题。本文提出了一种全新的多智能体框架——AgenticControl，该框架利用协同工作的大型语言模型（LLM）代理实现控制器设计的自动化。通过结构化的JSON通信，这些代理能够处理控制器选择、场景设计、参数优化、性能评估和决策制定等任务。基于演员-评论家优化方法，该系统在逐步增加复杂性的场景中迭代改进性能，确保在名义条件、测量噪声、执行器扰动和参数不确定性下具备鲁棒性。其关键创新包括结构化的多智能体协作、鲁棒优化机制以及通过上下文学习实现的实时适应能力。在直流电机位置控制、球与梁、倒摆和双倒摆等四个不同控制系统上的验证表明，该框架在与经典方法的竞争中表现出色。其全状态反馈解决方案与线性二次调节器（LQR）结果相当，而设计的PID控制器显著优于MATLAB的PIDTuner，通过激进的参数探索将PID跟踪误差降低了55%。对五个LLM模型的比较研究揭示了不同的优化特性，其中DeepSeek实现了最快的收敛速度。这项工作展示了LLM驱动控制设计的潜力，为模型预测控制和强化学习等高级技术铺平了道路。

> Traditional control system design, reliant on expert knowledge and precise models, struggles with complex, nonlinear, or uncertain dynamics. This paper introduces AgenticControl, a novel multi-agent framework that automates controller design using coordinated Large Language Model (LLM) agents. Through structured JSON communication, these agents handle tasks including controller selection, scenario design, parameter optimization, performance evaluation, and decision-making. Through an actor-critic optimization approach, the system iteratively improves performance while progressing through scenarios of increasing complexity to ensure robustness under nominal conditions, measurement noise, actuator disturbances, and parametric uncertainties. Key innovations include structured multi-agent collaboration, robust optimization mechanisms, and real-time adaptability via in-context learning. Validated across four diverse control systems, namely, DC Motor Position control, Ball and Beam, Inverted Pendulum, and Double Inverted Pendulum, the framework achieves competitive performance against classical methods. Its Full State Feedback solution closely matches Linear Quadratic Regulator (LQR) results, while the designed PID controller significantly outperforming MATLAB's PIDTuner, reducing PID tracking error by 55% through adaptive parameter exploration. A comparative study of five LLM models reveals distinct optimization profiles, with DeepSeek achieving the fastest convergence. This work demonstrates the potential of LLM-driven control design, paving the way for advanced techniques like model predictive control and reinforcement learning.

[Arxiv](https://arxiv.org/abs/2506.19160)