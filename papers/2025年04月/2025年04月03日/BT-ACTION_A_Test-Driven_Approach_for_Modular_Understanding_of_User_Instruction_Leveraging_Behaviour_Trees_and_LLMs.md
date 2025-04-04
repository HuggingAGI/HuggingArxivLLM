# BT-ACTION: 一种利用行为树和大型语言模型（LLMs）实现模块化用户指令理解的测试驱动方法

发布时间：2025年04月03日

`LLM应用` `机器人` `厨房辅助`

> BT-ACTION: A Test-Driven Approach for Modular Understanding of User Instruction Leveraging Behaviour Trees and LLMs

# 摘要

> 自然语言指令往往抽象复杂，即使是简单的请求，也需机器人完成多项子任务。例如，用户让机器人准备牛油果吐司，涉及多个连续步骤。此外，这类指令可能对机器人含糊不清或无法执行，甚至超出机器人现有知识范围。虽然大型语言模型（LLMs）具备强大的语言推理能力，但如何有效融入机器人系统仍是关键挑战。

为解决这一难题，我们提出BT-ACTION，一种结合行为树（BT）模块化结构与LLMs的测试驱动方法，旨在生成机器人执行复杂用户指令（尤其在厨房辅助场景下准备食谱）的连贯动作序列。我们通过一项涵盖45名参与者的全面用户研究评估了BT-ACTION，并将其表现与直接LLM提示进行了对比。结果显示，BT-ACTION的模块化设计显著减少了机器人错误，提升了用户信任度，且参与者对机器人运用BT-ACTION表现出明显偏好。项目代码已开源，详情请访问https://github.com/1Eggbert7/BT_LLM。

> Natural language instructions are often abstract and complex, requiring robots to execute multiple subtasks even for seemingly simple queries. For example, when a user asks a robot to prepare avocado toast, the task involves several sequential steps. Moreover, such instructions can be ambiguous or infeasible for the robot or may exceed the robot's existing knowledge. While Large Language Models (LLMs) offer strong language reasoning capabilities to handle these challenges, effectively integrating them into robotic systems remains a key challenge. To address this, we propose BT-ACTION, a test-driven approach that combines the modular structure of Behavior Trees (BT) with LLMs to generate coherent sequences of robot actions for following complex user instructions, specifically in the context of preparing recipes in a kitchen-assistance setting. We evaluated BT-ACTION in a comprehensive user study with 45 participants, comparing its performance to direct LLM prompting. Results demonstrate that the modular design of BT-ACTION helped the robot make fewer mistakes and increased user trust, and participants showed a significant preference for the robot leveraging BT-ACTION. The code is publicly available at https://github.com/1Eggbert7/BT_LLM.

[Arxiv](https://arxiv.org/abs/2504.02779)