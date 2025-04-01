# 研究 GPT-4 在机器人代理策略中的能力，结合实时状态反馈与反应行为框架

发布时间：2025年03月30日

`LLM应用` `机器人` `机器人行为控制`

> Exploring GPT-4 for Robotic Agent Strategy with Real-Time State Feedback and a Reactive Behaviour Framework

# 摘要

> 我们通过在仿真和真实世界中部署 GPT-4 于人形机器人，验证了一种全新的 LLM 驱动行为方法的概念。LLMs 已经展现了执行各种任务的潜力，包括机器人行为控制。该方法通过提示 LLM 生成实现目标所需的子任务来工作。以往研究主要关注生成任务的可执行性和正确性。我们提出的方法成功解决了实际应用中的安全性、任务间过渡、任务时间范围以及状态反馈等关键问题。实验结果表明，我们的方法能够为所有可行请求生成可执行的输出，实现平滑的任务过渡。用户设定的目标在各种时间范围内大部分情况下都能达成。

> We explore the use of GPT-4 on a humanoid robot in simulation and the real world as proof of concept of a novel large language model (LLM) driven behaviour method. LLMs have shown the ability to perform various tasks, including robotic agent behaviour. The problem involves prompting the LLM with a goal, and the LLM outputs the sub-tasks to complete to achieve that goal. Previous works focus on the executability and correctness of the LLM's generated tasks. We propose a method that successfully addresses practical concerns around safety, transitions between tasks, time horizons of tasks and state feedback. In our experiments we have found that our approach produces output for feasible requests that can be executed every time, with smooth transitions. User requests are achieved most of the time across a range of goal time horizons.

[Arxiv](https://arxiv.org/abs/2503.23601)