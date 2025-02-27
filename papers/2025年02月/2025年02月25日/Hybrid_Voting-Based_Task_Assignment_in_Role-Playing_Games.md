# 角色扮演游戏中的一种混合投票任务分配方法

发布时间：2025年02月25日

`Agent` `角色扮演类游戏`

> Hybrid Voting-Based Task Assignment in Role-Playing Games

# 摘要

> 在角色扮演类游戏（RPG）中，沉浸感是关键，特别是在游戏代理向玩家传达任务、提示或想法时。要让代理准确理解玩家的情绪和上下文细节，需要基础的理解能力，这可以通过大型语言模型（LLM）实现。然而，要在多个上下文变化中保持LLM的专注，需要更强大的方法，如将其与专用的任务分配模型结合，以在整个游戏过程中指导其表现。为此，我们推出了基于投票的任务分配（VBTA），一个受人类任务分配推理启发的框架。VBTA为代理分配能力概况，并为任务分配描述，生成一个衡量能力与需求匹配度的 suitability matrix。通过结合六种投票方法、预训练LLM以及基于冲突的搜索（CBS）进行路径规划，VBTA高效识别并分配最适合的代理到每个任务。现有方法多专注于生成单一任务或战斗遭遇，而我们的方法凭借其通用性，在生成独特战斗遭遇和叙述方面更具潜力。

> In role-playing games (RPGs), the level of immersion is critical-especially when an in-game agent conveys tasks, hints, or ideas to the player. For an agent to accurately interpret the player's emotional state and contextual nuances, a foundational level of understanding is required, which can be achieved using a Large Language Model (LLM). Maintaining the LLM's focus across multiple context changes, however, necessitates a more robust approach, such as integrating the LLM with a dedicated task allocation model to guide its performance throughout gameplay. In response to this need, we introduce Voting-Based Task Assignment (VBTA), a framework inspired by human reasoning in task allocation and completion. VBTA assigns capability profiles to agents and task descriptions to tasks, then generates a suitability matrix that quantifies the alignment between an agent's abilities and a task's requirements. Leveraging six distinct voting methods, a pre-trained LLM, and integrating conflict-based search (CBS) for path planning, VBTA efficiently identifies and assigns the most suitable agent to each task. While existing approaches focus on generating individual aspects of gameplay, such as single quests, or combat encounters, our method shows promise when generating both unique combat encounters and narratives because of its generalizable nature.

[Arxiv](https://arxiv.org/abs/2502.18690)