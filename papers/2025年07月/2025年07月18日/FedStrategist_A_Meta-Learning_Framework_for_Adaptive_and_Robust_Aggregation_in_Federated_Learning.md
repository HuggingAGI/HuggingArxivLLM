# FedStrategist：联邦学习中自适应且鲁棒聚合的元学习框架。

发布时间：2025年07月18日

`LLM应用` `问答系统`

> FedStrategist: A Meta-Learning Framework for Adaptive and Robust Aggregation in Federated Learning

# 摘要

> <翻译失败>

> Federated Learning (FL) offers a paradigm for privacy-preserving collaborative AI, but its decentralized nature creates significant vulnerabilities to model poisoning attacks. While numerous static defenses exist, their effectiveness is highly context-dependent, often failing against adaptive adversaries or in heterogeneous data environments. This paper introduces FedStrategist, a novel meta-learning framework that reframes robust aggregation as a real-time, cost-aware control problem. We design a lightweight contextual bandit agent that dynamically selects the optimal aggregation rule from an arsenal of defenses based on real-time diagnostic metrics. Through comprehensive experiments, we demonstrate that no single static rule is universally optimal. We show that our adaptive agent successfully learns superior policies across diverse scenarios, including a ``Krum-favorable" environment and against a sophisticated "stealth" adversary designed to neutralize specific diagnostic signals. Critically, we analyze the paradoxical scenario where a non-robust baseline achieves high but compromised accuracy, and demonstrate that our agent learns a conservative policy to prioritize model integrity. Furthermore, we prove the agent's policy is controllable via a single "risk tolerance" parameter, allowing practitioners to explicitly manage the trade-off between performance and security. Our work provides a new, practical, and analyzable approach to creating resilient and intelligent decentralized AI systems.

[Arxiv](https://arxiv.org/abs/2507.14322)