# DEMONSTRATE：通过多任务演示学习实现零样本语言到机器人控制

发布时间：2025年07月17日

`LLM应用

摘要中详细讨论了大型语言模型（LLMs）在控制系统中的应用，特别是在机械臂任务中的应用。论文提出了DEMONSTRATE方法，利用任务描述的嵌入表示和逆向最优控制工具，结合多任务学习，以减少对专业工程师的依赖，并在任务执行前评估幻觉。这些内容都属于LLM的实际应用，因此归类为LLM应用。` `机器人` `自动化`

> DEMONSTRATE: Zero-shot Language to Robotic Control via Multi-task Demonstration Learning

# 摘要

> 大型语言模型（LLMs）与控制系统的结合在多个场景中展现出了巨大潜力，例如利用机械臂完成任务。这一成功的关键在于LLMs的上下文学习能力，但这种能力高度依赖于与目标任务密切相关的设计良好的任务示例。因此，使用LLMs构建最优控制问题通常需要专业工程师设计包含明确数学表达的任务示例。此外，目前在任务执行前缺乏有效评估幻觉的方法。为了解决这些挑战，我们提出了DEMONSTRATE，一种全新的方法，无需使用LLMs生成复杂的优化问题，而是仅依赖于任务描述的嵌入表示。为此，我们借助逆向最优控制工具，用任务演示替代上下文提示示例，并引入多任务学习的概念，通过构造确保目标任务与示例任务的相似性。由于硬件演示可以通过遥操作或机器人引导轻松收集，我们的方法显著减少了设计上下文示例所需的专业工程师依赖。此外，强制的多任务结构使我们能够从少量演示中学习，并在任务执行前评估幻觉。我们通过模拟和硬件实验展示了我们方法的有效性，实验中使用了一只负责桌面操作的机械臂。

> The integration of large language models (LLMs) with control systems has demonstrated significant potential in various settings, such as task completion with a robotic manipulator. A main reason for this success is the ability of LLMs to perform in-context learning, which, however, strongly relies on the design of task examples, closely related to the target tasks. Consequently, employing LLMs to formulate optimal control problems often requires task examples that contain explicit mathematical expressions, designed by trained engineers. Furthermore, there is often no principled way to evaluate for hallucination before task execution. To address these challenges, we propose DEMONSTRATE, a novel methodology that avoids the use of LLMs for complex optimization problem generations, and instead only relies on the embedding representations of task descriptions. To do this, we leverage tools from inverse optimal control to replace in-context prompt examples with task demonstrations, as well as the concept of multitask learning, which ensures target and example task similarity by construction. Given the fact that hardware demonstrations can easily be collected using teleoperation or guidance of the robot, our approach significantly reduces the reliance on engineering expertise for designing in-context examples. Furthermore, the enforced multitask structure enables learning from few demonstrations and assessment of hallucinations prior to task execution. We demonstrate the effectiveness of our method through simulation and hardware experiments involving a robotic arm tasked with tabletop manipulation.

[Arxiv](https://arxiv.org/abs/2507.12855)