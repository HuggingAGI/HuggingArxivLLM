# 飞、试、调：基于强化学习与大型多模态模型的迭代式游戏修复方法

发布时间：2025年07月16日

`Agent

理由：这篇论文主要探讨了强化学习（RL）代理在游戏设计中的应用，结合大型多模态模型（LMM）来自动化设计迭代。虽然提到了大型模型，但核心在于代理的设计和应用，因此归类为Agent。` `游戏设计` `人工智能辅助设计`

> Fly, Fail, Fix: Iterative Game Repair with Reinforcement Learning and Large Multimodal Models

# 摘要

> 游戏设计的关键在于理解静态规则与内容如何转化为玩家的动态行为，而这一点正是现代仅凭代码或资产分析的生成系统难以捕捉的。我们提出了一种结合强化学习（RL）代理（用于游戏测试）与大型多模态模型（LMM）（根据代理行为修改游戏）的自动化设计迭代框架，成功填补了这一空白。在每个迭代循环中，RL玩家完成多个游戏回合，生成（i）数值玩法指标和/或（ii）一段简短的图像条，总结近期视频帧。LMM设计师接收游戏目标和当前游戏配置，分析玩法轨迹，并编辑配置以引导未来行为向目标靠拢。实验结果表明，LMM能够基于RL代理提供的行为轨迹进行推理，进而迭代优化游戏机制，为AI辅助游戏设计提供了实用且可扩展的工具。


> Game design hinges on understanding how static rules and content translate into dynamic player behavior - something modern generative systems that inspect only a game's code or assets struggle to capture. We present an automated design iteration framework that closes this gap by pairing a reinforcement learning (RL) agent, which playtests the game, with a large multimodal model (LMM), which revises the game based on what the agent does. In each loop the RL player completes several episodes, producing (i) numerical play metrics and/or (ii) a compact image strip summarising recent video frames. The LMM designer receives a gameplay goal and the current game configuration, analyses the play traces, and edits the configuration to steer future behaviour toward the goal. We demonstrate results that LMMs can reason over behavioral traces supplied by RL agents to iteratively refine game mechanics, pointing toward practical, scalable tools for AI-assisted game design.

[Arxiv](https://arxiv.org/abs/2507.12666)