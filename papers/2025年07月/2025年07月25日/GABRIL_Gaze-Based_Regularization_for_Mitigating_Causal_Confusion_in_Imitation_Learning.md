# GABRIL: 基于注视的正则化方法，解决模仿学习中的因果混淆问题

发布时间：2025年07月25日

`Agent` `自动驾驶`

> GABRIL: Gaze-Based Regularization for Mitigating Causal Confusion in Imitation Learning

# 摘要

> 模仿学习（IL）是一种广泛应用的方法，它通过将任务视为监督学习问题，使智能体能够从人类专家演示中学习。然而，IL常常受到因果混淆的影响，即智能体将虚假相关性误认为因果关系，导致在测试环境中的分布偏移时表现不佳。为了解决这一问题，我们引入了基于注视的模仿学习正则化方法（GABRIL），这是一种利用数据收集阶段收集的人类注视数据来指导IL中表示学习的新方法。GABRIL采用了一种正则化损失，鼓励模型关注通过专家注视识别出的因果相关特征，从而减轻了混杂变量的影响。我们在Atari环境和CARLA平台的Bench2Drive基准测试中验证了我们的方法，通过收集人类注视数据并在两个领域应用我们的方法。实验结果表明，与行为克隆相比，GABRIL在Atari环境中的提升幅度比其他基线方法高出约179%，在CARLA设置中高出76%。最后，我们展示了与常规IL智能体相比，我们的方法提供了额外的可解释性。

> Imitation Learning (IL) is a widely adopted approach which enables agents to learn from human expert demonstrations by framing the task as a supervised learning problem. However, IL often suffers from causal confusion, where agents misinterpret spurious correlations as causal relationships, leading to poor performance in testing environments with distribution shift. To address this issue, we introduce GAze-Based Regularization in Imitation Learning (GABRIL), a novel method that leverages the human gaze data gathered during the data collection phase to guide the representation learning in IL. GABRIL utilizes a regularization loss which encourages the model to focus on causally relevant features identified through expert gaze and consequently mitigates the effects of confounding variables. We validate our approach in Atari environments and the Bench2Drive benchmark in CARLA by collecting human gaze datasets and applying our method in both domains. Experimental results show that the improvement of GABRIL over behavior cloning is around 179% more than the same number for other baselines in the Atari and 76% in the CARLA setup. Finally, we show that our method provides extra explainability when compared to regular IL agents.

[Arxiv](https://arxiv.org/abs/2507.19647)