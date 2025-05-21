# BAR：专为复杂Minecraft任务设计的基于逆向推理的智能体

发布时间：2025年05月20日

`Agent` `机器人`

> BAR: A Backward Reasoning based Agent for Complex Minecraft Tasks

# 摘要

> 基于大型语言模型（LLM）的智能体在遵循人类指令并自动完成各种任务方面展现出巨大潜力。完成任务时，智能体需要通过规划将其分解为易于执行的步骤。现有研究主要从智能体的初始状态出发，推断下一步应执行的步骤。然而，这种前向推理范式在处理复杂任务时效果不佳。我们建议在Minecraft这一虚拟环境中研究这一问题，它能够基于现实场景模拟复杂任务。我们发现，前向推理的失败源于智能体初始状态与任务目标之间的巨大认知差距。为此，我们采用反向推理方法，使规划从终止状态开始，从而在一步内直接实现任务目标。具体来说，我们设计了一个基于反向推理的智能体（BAR）。它配备了递归目标分解模块、状态一致性维护模块和阶段记忆模块，以实现从终止状态出发的稳健、一致和高效的规划。实验结果表明，BAR在现有方法上具有显著优势，且所提出的模块设计非常有效。

> Large language model (LLM) based agents have shown great potential in following human instructions and automatically completing various tasks. To complete a task, the agent needs to decompose it into easily executed steps by planning. Existing studies mainly conduct the planning by inferring what steps should be executed next starting from the agent's initial state. However, this forward reasoning paradigm doesn't work well for complex tasks. We propose to study this issue in Minecraft, a virtual environment that simulates complex tasks based on real-world scenarios. We believe that the failure of forward reasoning is caused by the big perception gap between the agent's initial state and task goal. To this end, we leverage backward reasoning and make the planning starting from the terminal state, which can directly achieve the task goal in one step. Specifically, we design a BAckward Reasoning based agent (BAR). It is equipped with a recursive goal decomposition module, a state consistency maintaining module and a stage memory module to make robust, consistent, and efficient planning starting from the terminal state. Experimental results demonstrate the superiority of BAR over existing methods and the effectiveness of proposed modules.

[Arxiv](https://arxiv.org/abs/2505.14079)