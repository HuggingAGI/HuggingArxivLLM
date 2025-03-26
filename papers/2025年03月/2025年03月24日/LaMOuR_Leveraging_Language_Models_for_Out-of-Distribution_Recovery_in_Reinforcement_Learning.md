# LaMOuR：利用语言模型解决强化学习中的分布外问题

发布时间：2025年03月24日

`LLM应用

摘要中提到LaMOuR利用大语言模型的能力来生成奖励信号，帮助智能体从OOD状态恢复，属于将LLM应用于强化学习和机器人控制的场景，因此归类为LLM应用。` `机器人控制` `自动化`

> LaMOuR: Leveraging Language Models for Out-of-Distribution Recovery in Reinforcement Learning

# 摘要

> 深度强化学习（DRL）在机器人控制中表现优异，但面对分布外（OOD）状态时仍显脆弱，常引发不可靠动作甚至任务失败。尽管先前研究致力于减少或避免OOD的发生，却鲜少关注智能体陷入此类状态后的恢复机制。最新研究虽尝试通过引导智能体返回分布内状态来应对这一挑战，但其对不确定性估计的依赖限制了在复杂环境中的应用。为突破这一瓶颈，我们提出针对分布外恢复的语言模型（LaMOuR），它无需依赖不确定性估计即可实现高效恢复。LaMOuR通过生成密集奖励码，引导智能体回到能够成功执行原任务的状态，充分挖掘了大语言模型（LVLMs）在图像描述、逻辑推理和代码生成方面的潜力。实验结果表明，LaMOuR在各种 locomotion 任务中显著提升了恢复效率，并在复杂环境（如人形 locomotion 和移动操作）中展现出强大的泛化能力，而现有方法在这些场景下往往力不从心。代码和补充材料可在 https://lamour-rl.github.io/ 获取。

> Deep Reinforcement Learning (DRL) has demonstrated strong performance in robotic control but remains susceptible to out-of-distribution (OOD) states, often resulting in unreliable actions and task failure. While previous methods have focused on minimizing or preventing OOD occurrences, they largely neglect recovery once an agent encounters such states. Although the latest research has attempted to address this by guiding agents back to in-distribution states, their reliance on uncertainty estimation hinders scalability in complex environments. To overcome this limitation, we introduce Language Models for Out-of-Distribution Recovery (LaMOuR), which enables recovery learning without relying on uncertainty estimation. LaMOuR generates dense reward codes that guide the agent back to a state where it can successfully perform its original task, leveraging the capabilities of LVLMs in image description, logical reasoning, and code generation. Experimental results show that LaMOuR substantially enhances recovery efficiency across diverse locomotion tasks and even generalizes effectively to complex environments, including humanoid locomotion and mobile manipulation, where existing methods struggle. The code and supplementary materials are available at https://lamour-rl.github.io/.

[Arxiv](https://arxiv.org/abs/2503.17125)