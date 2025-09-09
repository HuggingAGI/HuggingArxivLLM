# 角色扮演：研究协作对话中的大型语言模型对齐

发布时间：2025年09月06日

`Agent` `基础理论`

> Let's Roleplay: Examining LLM Alignment in Collaborative Dialogues

# 摘要

> 随着大型语言模型（LLMs）融入各类工作流，它们正日益被视作人类的“协作者”。要让这类AI协作者具备可靠性，其在多轮交互中的行为必须在部署前实现可预测、可验证与可确认。然而，常见的对齐技术多在简化的单用户场景下开发，未能考虑长期多主体交互的动态特性。本文探讨了不同对齐方法如何影响LLM智能体在多轮多主体协作中的伙伴效能。我们从摩擦智能体的视角出发研究这一问题：此类智能体通过干预群体对话，促使协作群体放慢节奏，反思自身推理过程，进而支持审慎决策。借助角色扮演方法，我们评估了不同训练的摩擦智能体在协作任务对话中的干预效果，并提出一种新型反事实评估框架，以量化摩擦干预对群体协作轨迹及信念对齐的影响。结果显示，相较于常见对齐基线，摩擦感知方法在助力达成共识（即形成共同基础或商定任务相关命题）和提升任务结果准确性方面表现显著更优。

> As Large Language Models (LLMs) integrate into diverse workflows, they are increasingly being considered "collaborators" with humans. If such AI collaborators are to be reliable, their behavior over multiturn interactions must be predictable, validated and verified before deployment. Common alignment techniques are typically developed under simplified single-user settings and do not account for the dynamics of long-horizon multiparty interactions. This paper examines how different alignment methods affect LLM agents' effectiveness as partners in multiturn, multiparty collaborations. We study this question through the lens of friction agents that intervene in group dialogues to encourage the collaborative group to slow down and reflect upon their reasoning for deliberative decision-making. Using a roleplay methodology, we evaluate interventions from differently-trained friction agents in collaborative task conversations. We propose a novel counterfactual evaluation framework that quantifies how friction interventions change the trajectory of group collaboration and belief alignment. Our results show that a friction-aware approach significantly outperforms common alignment baselines in helping both convergence to a common ground, or agreed-upon task-relevant propositions, and correctness of task outcomes.

[Arxiv](https://arxiv.org/abs/2509.05882)