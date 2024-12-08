# 利用大型语言模型提供的弱监督反馈来训练智能体

发布时间：2024年11月29日

`Agent` `代码生成`

> Training Agents with Weakly Supervised Feedback from Large Language Models

# 摘要

> 大型语言模型（LLMs）为创建能通过迭代环境交互处理复杂任务的代理奠定了充满希望的基础。现有的方法，要么要求这些代理模仿专家提供的轨迹，要么依赖明确的环境反馈来进行强化学习，这就限制了它们在诸如游戏或代码生成等特定场景中的应用。本文引入了一种针对基于LLM的代理的全新训练方法，借助来自评论者LLM的弱监督信号，无需专家轨迹或明确反馈。我们的代理以迭代的方式训练，起初它们通过与环境交互生成轨迹。接着，评论者LLM选出一部分良好的轨迹，然后用于更新代理，让它们在下次迭代中生成更优的轨迹。在API-bank数据集上的大量测试显示，我们的代理能力不断提升，且与GPT-4性能相当，尽管使用的是参数少得多的开源模型。

> Large Language Models (LLMs) offer a promising basis for creating agents that can tackle complex tasks through iterative environmental interaction. Existing methods either require these agents to mimic expert-provided trajectories or rely on definitive environmental feedback for reinforcement learning which limits their application to specific scenarios like gaming or code generation. This paper introduces a novel training method for LLM-based agents using weakly supervised signals from a critic LLM, bypassing the need for expert trajectories or definitive feedback. Our agents are trained in iterative manner, where they initially generate trajectories through environmental interaction. Subsequently, a critic LLM selects a subset of good trajectories, which are then used to update the agents, enabling them to generate improved trajectories in the next iteration. Extensive tests on the API-bank dataset show consistent improvement in our agents' capabilities and comparable performance to GPT-4, despite using open-source models with much fewer parameters.

[Arxiv](https://arxiv.org/abs/2411.19547)