# # 空地协作：在未知环境中实现特定语言任务的协作

发布时间：2025年05月13日

`LLM应用` `机器人` `无人机`

> Air-Ground Collaboration for Language-Specified Missions in Unknown Environments

# 摘要

> 随着自主机器人系统日趋成熟，用户将更倾向于通过意图而非繁琐的低级细节来定义任务。语言作为一种直观且高效的表达方式，成为任务指定的理想选择。然而，要实现语言引导的机器人团队协作，仍需突破诸多技术难关。理解并执行语言定义的任务需要强大的语义推理能力。在异构机器人团队中，成功的关键在于不同机器人间的高效协作与信息共享。此外，机器人间的通信往往是间歇性的，这就要求制定可靠的策略，充分利用每一次通信机会，确保团队协调并达成任务目标。

在本研究中，我们首次提出了一种创新系统，实现了无人机（UAV）与无人车（UGV）的协同作业。该系统能够通过自然语言完成任务定义，并实时响应任务规格的动态变化。我们采用基于大型语言模型（LLM）的智能规划器，实时构建并共享语义-度量地图，在空中与地面机器人之间进行推理。无论是城市还是乡村环境，我们的系统都能实现任务驱动的导航。系统通过语义映射主动获取与任务相关的环境信息。在地面和空地协同实验中，我们成功展示了系统在七种不同自然语言任务定义下的卓越性能，导航范围覆盖千米级别。


> As autonomous robotic systems become increasingly mature, users will want to specify missions at the level of intent rather than in low-level detail. Language is an expressive and intuitive medium for such mission specification. However, realizing language-guided robotic teams requires overcoming significant technical hurdles. Interpreting and realizing language-specified missions requires advanced semantic reasoning. Successful heterogeneous robots must effectively coordinate actions and share information across varying viewpoints. Additionally, communication between robots is typically intermittent, necessitating robust strategies that leverage communication opportunities to maintain coordination and achieve mission objectives. In this work, we present a first-of-its-kind system where an unmanned aerial vehicle (UAV) and an unmanned ground vehicle (UGV) are able to collaboratively accomplish missions specified in natural language while reacting to changes in specification on the fly. We leverage a Large Language Model (LLM)-enabled planner to reason over semantic-metric maps that are built online and opportunistically shared between an aerial and a ground robot. We consider task-driven navigation in urban and rural areas. Our system must infer mission-relevant semantics and actively acquire information via semantic mapping. In both ground and air-ground teaming experiments, we demonstrate our system on seven different natural-language specifications at up to kilometer-scale navigation.

[Arxiv](https://arxiv.org/abs/2505.09108)