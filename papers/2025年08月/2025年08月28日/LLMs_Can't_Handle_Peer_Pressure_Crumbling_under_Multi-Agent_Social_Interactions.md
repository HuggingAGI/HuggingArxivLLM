# LLMs 扛不住同伴压力：在多智能体社交互动中败下阵来

发布时间：2025年08月28日

`Agent` `基础理论`

> LLMs Can't Handle Peer Pressure: Crumbling under Multi-Agent Social Interactions

# 摘要

> 大型语言模型（LLMs）正越来越多地作为协作智能的核心组件，部署于多智能体系统（MAS）中——在这类系统里，同伴间的交互会动态塑造个体决策。尽管已有研究主要关注从众偏差，我们进一步扩展分析范围，探究LLMs如何基于过往印象建立信任、抵制错误信息，并在交互中整合同伴意见——这些正是复杂社会动态下实现集体智能的关键要素。我们提出了KAIROS基准，它模拟了具有不同可靠性同伴智能体的问答竞赛场景，并能对专家-新手角色、嘈杂群体及对抗性同伴等条件进行精细化控制。LLMs会接收历史交互记录与当前同伴响应，以便系统探究信任、同伴行为及自信心对决策的影响机制。在缓解策略方面，我们在多个模型上评估了提示工程、监督微调及强化学习方法——群体相对策略优化（GRPO）。研究结果显示，结合多智能体上下文、基于结果的奖励与无约束推理的GRPO策略，虽能实现最佳整体性能，但与基础模型相比，其对社会影响的鲁棒性有所下降。相关代码与数据集已开源，地址为：https://github.com/declare-lab/KAIROS。

> Large language models (LLMs) are increasingly deployed in multi-agent systems (MAS) as components of collaborative intelligence, where peer interactions dynamically shape individual decision-making. Although prior work has focused on conformity bias, we extend the analysis to examine how LLMs form trust from previous impressions, resist misinformation, and integrate peer input during interaction, key factors for achieving collective intelligence under complex social dynamics. We present KAIROS, a benchmark simulating quiz contests with peer agents of varying reliability, offering fine-grained control over conditions such as expert-novice roles, noisy crowds, and adversarial peers. LLMs receive both historical interactions and current peer responses, allowing systematic investigation into how trust, peer action, and self-confidence influence decisions. As for mitigation strategies, we evaluate prompting, supervised fine-tuning, and reinforcement learning, Group Relative Policy Optimisation (GRPO), across multiple models. Our results reveal that GRPO with multi-agent context combined with outcome-based rewards and unconstrained reasoning achieves the best overall performance, but also decreases the robustness to social influence compared to Base models. The code and datasets are available at: https://github.com/declare-lab/KAIROS.

[Arxiv](https://arxiv.org/abs/2508.18321)