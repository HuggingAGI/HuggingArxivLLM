# ProVox：实现情境化人机协作的个性化与主动性规划

发布时间：2025年06月13日

`LLM应用` `协作机器人` `机器人`

> ProVox: Personalization and Proactive Planning for Situated Human-Robot Collaboration

# 摘要

> 协作机器人需要快速适应人类伙伴的意图和偏好，特别是在需要人类不断教授新行为的环境中。我们提出，机器人应能从早期互动中推断出伙伴的目标，并在此基础上主动规划行为。基于大型语言模型的强大能力，我们开发了ProVox框架，使机器人能够高效适应个体伙伴。通过元提示协议，用户可提前传达偏好和期望，ProVox利用这些信息主动预测用户需求并建议行动，从而显著减轻用户负担。实验表明，ProVox使任务完成速度提升38.7%，用户负担降低31.9%。更多详情请访问https://provox-2025.github.io。

> Collaborative robots must quickly adapt to their partner's intent and preferences to proactively identify helpful actions. This is especially true in situated settings where human partners can continually teach robots new high-level behaviors, visual concepts, and physical skills (e.g., through demonstration), growing the robot's capabilities as the human-robot pair work together to accomplish diverse tasks. In this work, we argue that robots should be able to infer their partner's goals from early interactions and use this information to proactively plan behaviors ahead of explicit instructions from the user. Building from the strong commonsense priors and steerability of large language models, we introduce ProVox ("Proactive Voice"), a novel framework that enables robots to efficiently personalize and adapt to individual collaborators. We design a meta-prompting protocol that empowers users to communicate their distinct preferences, intent, and expected robot behaviors ahead of starting a physical interaction. ProVox then uses the personalized prompt to condition a proactive language model task planner that anticipates a user's intent from the current interaction context and robot capabilities to suggest helpful actions; in doing so, we alleviate user burden, minimizing the amount of time partners spend explicitly instructing and supervising the robot. We evaluate ProVox through user studies grounded in household manipulation tasks (e.g., assembling lunch bags) that measure the efficiency of the collaboration, as well as features such as perceived helpfulness, ease of use, and reliability. Our analysis suggests that both meta-prompting and proactivity are critical, resulting in 38.7% faster task completion times and 31.9% less user burden relative to non-active baselines. Supplementary material, code, and videos can be found at https://provox-2025.github.io.

[Arxiv](https://arxiv.org/abs/2506.12248)