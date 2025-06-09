# OPeRA: 面向大型语言模型评估的人类在线购物行为模拟数据集，包含观察、角色设定、动机和行为四个维度。

发布时间：2025年06月05日

`LLM应用` `电子商务`

> OPeRA: A Dataset of Observation, Persona, Rationale, and Action for Evaluating LLMs on Human Online Shopping Behavior Simulation

# 摘要

> 大型语言模型（LLMs）能否精准模拟特定用户的下一个网络行为？尽管LLMs在生成“可信”的人类行为方面展现出巨大潜力，但评估其模仿真实用户行为的能力仍是一个开放性挑战。这主要源于缺乏高质量的公开数据集，这些数据集能够同时捕捉真实人类用户的可观测行为和内部推理过程。为了解决这一问题，我们引入了OPERA，这是一个从真实人类参与者在线购物过程中收集的 Observation（观察）、Persona（用户画像）、Rationale（理由）和 Action（行为）的新型数据集。OPERA是首个公开的数据集，全面涵盖了：用户画像、浏览器观察结果、细粒度的网络行为以及即时报告的理由。我们开发了一个在线问卷和一个定制的浏览器插件，以高保真度收集此数据集。借助OPERA，我们建立了首个基准测试，用于评估当前LLMs在给定用户画像和<观察、行为、理由>历史的情况下，预测特定用户下一个行为和理由的能力。该数据集为未来研究旨在成为个性化数字孪生的LLM代理奠定了基础。

> Can large language models (LLMs) accurately simulate the next web action of a specific user? While LLMs have shown promising capabilities in generating ``believable'' human behaviors, evaluating their ability to mimic real user behaviors remains an open challenge, largely due to the lack of high-quality, publicly available datasets that capture both the observable actions and the internal reasoning of an actual human user. To address this gap, we introduce OPERA, a novel dataset of Observation, Persona, Rationale, and Action collected from real human participants during online shopping sessions. OPERA is the first public dataset that comprehensively captures: user personas, browser observations, fine-grained web actions, and self-reported just-in-time rationales. We developed both an online questionnaire and a custom browser plugin to gather this dataset with high fidelity. Using OPERA, we establish the first benchmark to evaluate how well current LLMs can predict a specific user's next action and rationale with a given persona and <observation, action, rationale> history. This dataset lays the groundwork for future research into LLM agents that aim to act as personalized digital twins for human.

[Arxiv](https://arxiv.org/abs/2506.05606)