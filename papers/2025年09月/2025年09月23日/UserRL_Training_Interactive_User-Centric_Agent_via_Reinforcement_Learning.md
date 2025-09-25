# UserRL：基于强化学习训练交互式用户中心智能体

发布时间：2025年09月23日

`强化学习` `基础理论`

> UserRL: Training Interactive User-Centric Agent via Reinforcement Learning

# 摘要

> 强化学习（RL）在训练智能体模型上展现出巨大潜力，这类模型突破静态基准限制，可实现动态多轮交互。然而，智能体的核心价值在于协助用户的能力，而用户交互的多样性与动态性为此带来了不小挑战。为此，我们提出UserRL——一个通过标准化gym环境与模拟用户协同工作，来训练和评估以用户为中心能力的统一框架。我们通过系统调整轮次级奖励分配与轨迹级分数计算方式，分析了不同设计在GRPO算法下对学习过程的影响。在Qwen3模型上的实验揭示三个关键发现：（i）监督微调（SFT）冷启动是解锁初始交互能力、实现RL持续优化的关键；（ii）审慎的轨迹评分可显著提升多轮交互的效率与效果；（iii）尽管更强的模拟用户（如GPT-4o）能加速训练，但开源模拟器（如Qwen3-32B）仍是经济高效且具备迁移性的替代方案。综上，研究结果表明：奖励塑造与用户模拟选择的精心设计同模型规模同等关键，而UserRL则为开发稳健的用户中心智能体模型提供了切实可行的路径。所有代码与数据已公开，供后续研究参考。

> Reinforcement learning (RL) has shown promise in training agentic models that move beyond static benchmarks to engage in dynamic, multi-turn interactions. Yet, the ultimate value of such agents lies in their ability to assist users, a setting where diversity and dynamics of user interaction pose challenges. In this work, we propose UserRL, a unified framework for training and evaluating user-centric abilities through standardized gym environments paired with simulated users. We systematically vary turn-level reward assignment and trajectory-level score calculation to analyze how different formulations affect learning under the GRPO algorithm. Our experiments across Qwen3 models reveal three key findings: (i) SFT cold start is critical for unlocking initial interaction ability and enabling sustained RL improvements; (ii) deliberate trajectory scoring yields more efficient and effective multi-turn interactions; and (iii) while stronger simulated users (e.g., GPT-4o) facilitates training, open-source simulators (e.g., Qwen3-32B) remain a cost-effective and transferable option. Together, these results highlight that careful design of reward shaping and user simulation choice is as crucial as model scale, and establish UserRL as a practical pathway for developing robust user-centric agentic models. All codes and data are public for future research.

[Arxiv](https://arxiv.org/abs/2509.19736)