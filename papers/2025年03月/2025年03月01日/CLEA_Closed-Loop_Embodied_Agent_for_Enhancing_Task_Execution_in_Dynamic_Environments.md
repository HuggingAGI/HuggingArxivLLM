# # CLEA: Closed-Loop Embodied Agent for Enhancing Task Execution in Dynamic Environments
# CLEA：闭环具身智能体，助力动态环境下的任务执行优化

发布时间：2025年03月01日

`Agent` `机器人` `任务规划`

> CLEA: Closed-Loop Embodied Agent for Enhancing Task Execution in Dynamic Environments

# 摘要

> 大型语言模型（LLMs）在复杂任务的层次分解方面表现出色，但将其应用于具身系统时，仍面临可靠执行子任务序列和一次性完成长期任务的挑战。为应对动态环境中的这些限制，我们提出了闭环具身代理（Closed-Loop Embodied Agent，CLEA），一种整合四个功能独立开源LLMs的新型架构，用于闭环任务管理。该框架的两大核心创新为：(1) 交互式任务规划器，根据环境记忆动态生成可执行子任务；(2) 多模态执行评估器，通过评估框架对动作可行性进行概率评估，当环境干扰超出预设阈值时触发层次化重新规划机制。我们在真实环境中使用两种异构机器人进行了实验，涵盖物体搜索、操作及搜索-操作集成任务。在12次任务试验中，CLEA的表现优于基线模型，成功率达到67.3%的提升，任务完成率增加了52.8%。这些结果证明，CLEA显著增强了动态环境中任务规划与执行的鲁棒性。

> Large Language Models (LLMs) exhibit remarkable capabilities in the hierarchical decomposition of complex tasks through semantic reasoning. However, their application in embodied systems faces challenges in ensuring reliable execution of subtask sequences and achieving one-shot success in long-term task completion. To address these limitations in dynamic environments, we propose Closed-Loop Embodied Agent (CLEA) -- a novel architecture incorporating four specialized open-source LLMs with functional decoupling for closed-loop task management. The framework features two core innovations: (1) Interactive task planner that dynamically generates executable subtasks based on the environmental memory, and (2) Multimodal execution critic employing an evaluation framework to conduct a probabilistic assessment of action feasibility, triggering hierarchical re-planning mechanisms when environmental perturbations exceed preset thresholds. To validate CLEA's effectiveness, we conduct experiments in a real environment with manipulable objects, using two heterogeneous robots for object search, manipulation, and search-manipulation integration tasks. Across 12 task trials, CLEA outperforms the baseline model, achieving a 67.3% improvement in success rate and a 52.8% increase in task completion rate. These results demonstrate that CLEA significantly enhances the robustness of task planning and execution in dynamic environments.

[Arxiv](https://arxiv.org/abs/2503.00729)