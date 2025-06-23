# # 语义数字孪生赋能语言模型，助力机器人规划
通过将语言模型与语义数字孪生相结合，为机器人规划提供强大支持。

发布时间：2025年06月19日

`Agent` `机器人` `自动化`

> Grounding Language Models with Semantic Digital Twins for Robotic Planning

# 摘要

> 我们提出了一种将语义数字孪生（SDTs）与大型语言模型（LLMs）相结合的创新框架，旨在实现动态环境下自适应且目标导向的机器人任务执行。该系统将自然语言指令分解为结构化的动作三元组，并基于SDT提供的上下文环境数据进行语义接地。这种接地机制使机器人能够理解物体的使用可能性和交互规则，从而实现动作规划和实时适应。当执行失败时，LLM通过分析错误反馈和SDT提供的见解，生成恢复策略并迭代调整动作计划。我们在ALFRED基准任务上进行了评估，结果显示该框架在各种家庭场景中表现优异。该框架成功整合了高级推理与语义环境理解，在不确定性和故障情况下仍能可靠完成任务。

> We introduce a novel framework that integrates Semantic Digital Twins (SDTs) with Large Language Models (LLMs) to enable adaptive and goal-driven robotic task execution in dynamic environments. The system decomposes natural language instructions into structured action triplets, which are grounded in contextual environmental data provided by the SDT. This semantic grounding allows the robot to interpret object affordances and interaction rules, enabling action planning and real-time adaptability. In case of execution failures, the LLM utilizes error feedback and SDT insights to generate recovery strategies and iteratively revise the action plan. We evaluate our approach using tasks from the ALFRED benchmark, demonstrating robust performance across various household scenarios. The proposed framework effectively combines high-level reasoning with semantic environment understanding, achieving reliable task completion in the face of uncertainty and failure.

[Arxiv](https://arxiv.org/abs/2506.16493)