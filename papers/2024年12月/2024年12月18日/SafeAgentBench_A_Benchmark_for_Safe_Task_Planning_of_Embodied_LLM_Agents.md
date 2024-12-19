# SafeAgentBench：用于具身 LLM 智能体安全任务规划的基准

发布时间：2024年12月18日

`Agent` `机器人` `具身智能`

> SafeAgentBench: A Benchmark for Safe Task Planning of Embodied LLM Agents

# 摘要

> 随着大型语言模型（LLMs）的融入，具身智能体拥有了用自然语言执行复杂指令的强大能力，为具身机器人的潜在应用铺平了道路。然而，一个可预见的问题是，这些具身智能体还能出色地执行某些危险任务，可能会在现实世界中造成危害。为研究此问题，我们推出了 SafeAgentBench——一个针对具身 LLM 智能体安全感知任务规划的新基准。SafeAgentBench 涵盖：（1）包含 750 个任务的新数据集，涵盖 10 种潜在危险和 3 种任务类型；（2）SafeAgentEnv，一个带有低级控制器的通用具身环境，支持多智能体执行，具备 17 种高级动作，适用于 8 种先进基线；（3）从执行和语义两方面出发的可靠评估方法。实验结果显示，表现最佳的基线在安全任务上的成功率为 69%，但在危险任务上的拒绝率仅为 5%，这表明存在显著的安全风险。更多详情和代码可在 https://github.com/shengyin1224/SafeAgentBench 查看。

> With the integration of large language models (LLMs), embodied agents have strong capabilities to execute complicated instructions in natural language, paving a way for the potential deployment of embodied robots. However, a foreseeable issue is that those embodied agents can also flawlessly execute some hazardous tasks, potentially causing damages in real world. To study this issue, we present SafeAgentBench -- a new benchmark for safety-aware task planning of embodied LLM agents. SafeAgentBench includes: (1) a new dataset with 750 tasks, covering 10 potential hazards and 3 task types; (2) SafeAgentEnv, a universal embodied environment with a low-level controller, supporting multi-agent execution with 17 high-level actions for 8 state-of-the-art baselines; and (3) reliable evaluation methods from both execution and semantic perspectives. Experimental results show that the best-performing baseline gets 69% success rate for safe tasks, but only 5% rejection rate for hazardous tasks, indicating significant safety risks. More details and codes are available at https://github.com/shengyin1224/SafeAgentBench.

[Arxiv](https://arxiv.org/abs/2412.13178)