# 利用预训练大型语言模型与精细提示实现在线任务与运动规划

发布时间：2025年04月30日

`LLM应用` `智能机器人` `人工智能`

> Leveraging Pre-trained Large Language Models with Refined Prompting for Online Task and Motion Planning

# 摘要

> 随着人工智能技术的飞速发展，智能机器人在日常任务和复杂操作中的需求与日俱增。这些机器人不仅需要具备任务规划能力，还需确保任务执行的稳定性和鲁棒性。本文提出了一种由预训练大型语言模型（LLM）辅助的闭环任务规划与执行系统——LLM-PAS。该系统在规划长周期任务时采用了与传统任务和运动规划器相似的方法，但更注重任务的执行阶段。通过将部分约束检查过程从规划阶段转移至执行阶段，LLM-PAS实现了对约束空间的探索，并在执行过程中提供了更精准的环境异常反馈。LLM的推理能力使其能够处理那些稳健执行器无法解决的异常情况。为了进一步提升系统在重新规划过程中对规划器的辅助能力，我们提出了首次审视提示方法（FLP），该方法引导LLM生成有效的PDDL目标。通过比较性提示实验和系统性实验，我们验证了LLM-PAS在任务执行过程中应对异常条件的有效性和鲁棒性。

> With the rapid advancement of artificial intelligence, there is an increasing demand for intelligent robots capable of assisting humans in daily tasks and performing complex operations. Such robots not only require task planning capabilities but must also execute tasks with stability and robustness. In this paper, we present a closed-loop task planning and acting system, LLM-PAS, which is assisted by a pre-trained Large Language Model (LLM). While LLM-PAS plans long-horizon tasks in a manner similar to traditional task and motion planners, it also emphasizes the execution phase of the task. By transferring part of the constraint-checking process from the planning phase to the execution phase, LLM-PAS enables exploration of the constraint space and delivers more accurate feedback on environmental anomalies during execution. The reasoning capabilities of the LLM allow it to handle anomalies that cannot be addressed by the robust executor. To further enhance the system's ability to assist the planner during replanning, we propose the First Look Prompting (FLP) method, which induces LLM to generate effective PDDL goals. Through comparative prompting experiments and systematic experiments, we demonstrate the effectiveness and robustness of LLM-PAS in handling anomalous conditions during task execution.

[Arxiv](https://arxiv.org/abs/2504.21596)