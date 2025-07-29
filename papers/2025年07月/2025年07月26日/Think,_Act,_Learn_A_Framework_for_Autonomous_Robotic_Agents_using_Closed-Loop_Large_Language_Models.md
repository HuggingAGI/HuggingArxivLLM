# 思考、行动、学习：面向自主机器人代理的闭环大型语言模型框架

发布时间：2025年07月26日

`LLM应用` `机器人技术` `人工智能`

> Think, Act, Learn: A Framework for Autonomous Robotic Agents using Closed-Loop Large Language Models

# 摘要

> 大型语言模型（LLMs）与机器人技术的结合，为高层任务规划开辟了全新可能。但目前多数系统仍以开环方式运行，LLMs仅作为一次性规划器，使其在动态环境中的适应性大打折扣。为突破这一局限，我们提出了“思考、行动、学习”（T-A-L）框架，这是一种创新架构，让机器人通过持续交互自主优化策略。在T-A-L框架中，LLM首先“思考”并分解高层指令为具体计划，机器人随后“行动”并收集多模态反馈。关键的“学习”模块则通过处理反馈，帮助智能体进行自我反思与策略优化，将经验存储为未来参考。实验表明，T-A-L智能体在复杂任务中表现卓越，成功率高达97%，仅需9次试验即可稳定，且具备出色的泛化能力。这为打造更 robust、自主的智能机器人奠定了重要基础。

> The integration of Large Language Models (LLMs) into robotics has unlocked unprecedented capabilities in high-level task planning. However, most current systems operate in an open-loop fashion, where LLMs act as one-shot planners, rendering them brittle and unable to adapt to unforeseen circumstances in dynamic physical environments. To overcome this limitation, this paper introduces the "Think, Act, Learn" (T-A-L) framework, a novel architecture that enables an embodied agent to autonomously learn and refine its policies through continuous interaction. Our framework establishes a closed-loop cycle where an LLM first "thinks" by decomposing high-level commands into actionable plans. The robot then "acts" by executing these plans while gathering rich, multimodal sensory feedback. Critically, the "learn" module processes this feedback to facilitate LLM-driven self-reflection, allowing the agent to perform causal analysis on its failures and generate corrective strategies. These insights are stored in an experiential memory to guide future planning cycles. We demonstrate through extensive experiments in both simulation and the real world that our T-A-L agent significantly outperforms baseline methods, including open-loop LLMs, Behavioral Cloning, and traditional Reinforcement Learning. Our framework achieves over a 97% success rate on complex, long-horizon tasks, converges to a stable policy in an average of just 9 trials, and exhibits remarkable generalization to unseen tasks. This work presents a significant step towards developing more robust, adaptive, and truly autonomous robotic agents.

[Arxiv](https://arxiv.org/abs/2507.19854)