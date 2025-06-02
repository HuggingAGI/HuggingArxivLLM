# CoMaPOI: 协作式多智能体框架，用于下一个POI预测，弥合轨迹与语言之间的鸿沟

发布时间：2025年05月28日

`LLM应用

理由：论文探讨了大型语言模型（LLMs）在兴趣点（POI）预测任务中的应用，并提出了一种协作多智能体框架来解决LLMs在时空数据理解和候选空间约束上的问题。虽然提到了多智能体，但主要焦点是LLMs的应用，因此归类为LLM应用。` `地理信息系统` `位置服务`

> CoMaPOI: A Collaborative Multi-Agent Framework for Next POI Prediction Bridging the Gap Between Trajectory and Language

# 摘要

> 大型语言模型（LLMs）为兴趣点（POI）预测任务带来了新的可能性，但现有方法未能充分应对其中的关键挑战。我们提出了一种名为CoMaPOI的协作多智能体框架，通过三个智能体的协同工作，有效解决了LLMs在时空数据理解和候选空间约束上的两大难题。实验结果表明，CoMaPOI在多个数据集上显著优于现有方法，为LLMs在复杂时空任务中的应用提供了新思路。

> Large Language Models (LLMs) offer new opportunities for the next Point-Of-Interest (POI) prediction task, leveraging their capabilities in semantic understanding of POI trajectories. However, previous LLM-based methods, which are superficially adapted to next POI prediction, largely overlook critical challenges associated with applying LLMs to this task. Specifically, LLMs encounter two critical challenges: (1) a lack of intrinsic understanding of numeric spatiotemporal data, which hinders accurate modeling of users' spatiotemporal distributions and preferences; and (2) an excessively large and unconstrained candidate POI space, which often results in random or irrelevant predictions. To address these issues, we propose a Collaborative Multi Agent Framework for Next POI Prediction, named CoMaPOI. Through the close interaction of three specialized agents (Profiler, Forecaster, and Predictor), CoMaPOI collaboratively addresses the two critical challenges. The Profiler agent is responsible for converting numeric data into language descriptions, enhancing semantic understanding. The Forecaster agent focuses on dynamically constraining and refining the candidate POI space. The Predictor agent integrates this information to generate high-precision predictions. Extensive experiments on three benchmark datasets (NYC, TKY, and CA) demonstrate that CoMaPOI achieves state of the art performance, improving all metrics by 5% to 10% compared to SOTA baselines. This work pioneers the investigation of challenges associated with applying LLMs to complex spatiotemporal tasks by leveraging tailored collaborative agents.

[Arxiv](https://arxiv.org/abs/2505.23837)