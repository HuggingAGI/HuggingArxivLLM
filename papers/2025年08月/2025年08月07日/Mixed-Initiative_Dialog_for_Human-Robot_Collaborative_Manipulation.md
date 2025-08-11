# # 人机协作操作中的交互对话

发布时间：2025年08月07日

`Agent` `机器人` `协作系统`

> Mixed-Initiative Dialog for Human-Robot Collaborative Manipulation

# 摘要

> 面向长期人机协作的机器人系统需要适应各种人类合作伙伴，这些人的行为、协助意愿和对机器人能力的理解会随时间变化。为此，我们需要一个紧密的通信环路，让双方能够灵活地提出、接受或拒绝请求，从而高效完成任务。我们采用混合主动对话范式，提出MICoBot系统，用于处理双方使用自然语言主动建议、接受或拒绝任务分配的场景。为了优化任务导向对话并减少人类努力，MICoBot从三个层级做出决策：(1) 元规划器根据对话制定高层协作策略，(2) 规划器基于机器人能力（通过模拟预训练模型评估）和人类可用性，优化任务分配，(3) 执行器决定具体动作或对话内容。我们的模拟和实验证明，MICoBot显著提升了任务成功率和用户体验。更多信息请访问https://robin-lab.cs.utexas.edu/MicoBot/。

> Effective robotic systems for long-horizon human-robot collaboration must adapt to a wide range of human partners, whose physical behavior, willingness to assist, and understanding of the robot's capabilities may change over time. This demands a tightly coupled communication loop that grants both agents the flexibility to propose, accept, or decline requests as they coordinate toward completing the task effectively. We apply a Mixed-Initiative dialog paradigm to Collaborative human-roBot teaming and propose MICoBot, a system that handles the common scenario where both agents, using natural language, take initiative in formulating, accepting, or rejecting proposals on who can best complete different steps of a task. To handle diverse, task-directed dialog, and find successful collaborative strategies that minimize human effort, MICoBot makes decisions at three levels: (1) a meta-planner considers human dialog to formulate and code a high-level collaboration strategy, (2) a planner optimally allocates the remaining steps to either agent based on the robot's capabilities (measured by a simulation-pretrained affordance model) and the human's estimated availability to help, and (3) an action executor decides the low-level actions to perform or words to say to the human. Our extensive evaluations in simulation and real-world -- on a physical robot with 18 unique human participants over 27 hours -- demonstrate the ability of our method to effectively collaborate with diverse human users, yielding significantly improved task success and user experience than a pure LLM baseline and other agent allocation models. See additional videos and materials at https://robin-lab.cs.utexas.edu/MicoBot/.

[Arxiv](https://arxiv.org/abs/2508.05535)