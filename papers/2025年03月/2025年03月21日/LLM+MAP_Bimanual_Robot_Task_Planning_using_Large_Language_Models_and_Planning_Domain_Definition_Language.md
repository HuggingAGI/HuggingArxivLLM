# LLM+MAP：基于大型语言模型与规划领域定义语言的双臂机器人任务规划

发布时间：2025年03月21日

`LLM应用` `机器人` `任务规划`

> LLM+MAP: Bimanual Robot Task Planning using Large Language Models and Planning Domain Definition Language

# 摘要

> 双臂机器人操作虽然灵活，但两臂的空间与时间协调复杂性带来了固有挑战。当前研究多聚焦于提升机器人手的操作技能，却忽视了长期任务规划的重要性。尽管大型语言模型（LLMs）凭借其强大的上下文学习和零样本生成能力，在机器人任务规划中展现出潜力，但其在长期推理和复杂任务中仍存在错误和幻觉问题，无法保证生成计划的逻辑正确性。此前的LLM+P等方法通过引入符号规划器扩展了LLMs的功能，但尚未成功应用于双臂机器人。双臂操作带来了新的挑战，不仅需要有效的任务分解，还要求高效的资源分配。为此，我们提出了LLM+MAP，一个结合LLM推理与多智能体规划的双臂规划框架，实现高效且有效的双臂任务规划。我们在不同复杂度的长期操作任务上进行了模拟实验，基于GPT-4o作为后端，将其性能与直接由LLMs生成的计划进行了对比，包括GPT-4o、V3以及近期强大的推理模型o1和R1。通过分析规划时间、成功率、分组扣款和规划步骤减少率等指标，我们展示了LLM+MAP的优越性能，同时也为机器人推理提供了新的见解。代码可在https://github.com/Kchu/LLM-MAP获取。

> Bimanual robotic manipulation provides significant versatility, but also presents an inherent challenge due to the complexity involved in the spatial and temporal coordination between two hands. Existing works predominantly focus on attaining human-level manipulation skills for robotic hands, yet little attention has been paid to task planning on long-horizon timescales. With their outstanding in-context learning and zero-shot generation abilities, Large Language Models (LLMs) have been applied and grounded in diverse robotic embodiments to facilitate task planning. However, LLMs still suffer from errors in long-horizon reasoning and from hallucinations in complex robotic tasks, lacking a guarantee of logical correctness when generating the plan. Previous works, such as LLM+P, extended LLMs with symbolic planners. However, none have been successfully applied to bimanual robots. New challenges inevitably arise in bimanual manipulation, necessitating not only effective task decomposition but also efficient task allocation. To address these challenges, this paper introduces LLM+MAP, a bimanual planning framework that integrates LLM reasoning and multi-agent planning, automating effective and efficient bimanual task planning. We conduct simulated experiments on various long-horizon manipulation tasks of differing complexity. Our method is built using GPT-4o as the backend, and we compare its performance against plans generated directly by LLMs, including GPT-4o, V3 and also recent strong reasoning models o1 and R1. By analyzing metrics such as planning time, success rate, group debits, and planning-step reduction rate, we demonstrate the superior performance of LLM+MAP, while also providing insights into robotic reasoning. Code is available at https://github.com/Kchu/LLM-MAP.

[Arxiv](https://arxiv.org/abs/2503.17309)