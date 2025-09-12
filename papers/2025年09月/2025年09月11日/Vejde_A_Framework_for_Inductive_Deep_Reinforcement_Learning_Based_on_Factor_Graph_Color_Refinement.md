# Vejde：基于因子图颜色精化的归纳式深度强化学习框架

发布时间：2025年09月11日

`其他` `（由于论文摘要翻译失败` `无法获取内容以判断应用的行业领域` `因此无法生成标签。）`

> Vejde: A Framework for Inductive Deep Reinforcement Learning Based on Factor Graph Color Refinement

# 摘要

> <翻译失败>

> We present and evaluate Vejde; a framework which combines data abstraction, graph neural networks and reinforcement learning to produce inductive policy functions for decision problems with richly structured states, such as object classes and relations. MDP states are represented as data bases of facts about entities, and Vejde converts each state to a bipartite graph, which is mapped to latent states through neural message passing. The factored representation of both states and actions allows Vejde agents to handle problems of varying size and structure. We tested Vejde agents on eight problem domains defined in RDDL, with ten problem instances each, where policies were trained using both supervised and reinforcement learning. To test policy generalization, we separate problem instances in two sets, one for training and the other solely for testing. Test results on unseen instances for the Vejde agents were compared to MLP agents trained on each problem instance, as well as the online planning algorithm Prost. Our results show that Vejde policies in average generalize to the test instances without a significant loss in score. Additionally, the inductive agents received scores on unseen test instances that on average were close to the instance-specific MLP agents.

[Arxiv](https://arxiv.org/abs/2509.09219)