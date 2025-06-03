# Jailbreak-R1：探索大型语言模型的越狱能力新方法——强化学习

发布时间：2025年05月31日

`LLM应用` `自动化红队`

> Jailbreak-R1: Exploring the Jailbreak Capabilities of LLMs via Reinforcement Learning

# 摘要

> 随着大型语言模型（LLMs）的影响力日益增强，确保其安全性并防止产生有害输出变得至关重要。自动化红队作为一种工具，能够在无需人工干预的情况下检测LLMs的安全漏洞。然而，现有方法大多难以在红队生成的攻击提示的有效性和多样性之间取得平衡。为了解决这一难题，我们提出了\ourapproach，这是一种全新的自动化红队训练框架，通过强化学习来探索并生成更有效的攻击提示，同时兼顾其多样性。具体而言，该框架包含三个训练阶段：(1) 冷启动阶段：红队模型基于通过模仿学习获得的越狱数据集进行监督微调。 (2) 预热探索阶段：模型在越狱指令遵循和探索中进行训练，将多样性和一致性作为奖励信号。 (3) 增强越狱阶段：引入渐进式越狱奖励，逐步提升红队模型的越狱性能。在多种LLMs上的广泛实验表明，与现有方法相比，\ourapproach在平衡越狱提示的多样性和有效性方面表现更为出色。我们的工作显著提高了红队探索的效率，并为自动化红队提供了全新的视角。

> As large language models (LLMs) grow in power and influence, ensuring their safety and preventing harmful output becomes critical. Automated red teaming serves as a tool to detect security vulnerabilities in LLMs without manual labor. However, most existing methods struggle to balance the effectiveness and diversity of red-team generated attack prompts. To address this challenge, we propose \ourapproach, a novel automated red teaming training framework that utilizes reinforcement learning to explore and generate more effective attack prompts while balancing their diversity. Specifically, it consists of three training stages: (1) Cold Start: The red team model is supervised and fine-tuned on a jailbreak dataset obtained through imitation learning. (2) Warm-up Exploration: The model is trained in jailbreak instruction following and exploration, using diversity and consistency as reward signals. (3) Enhanced Jailbreak: Progressive jailbreak rewards are introduced to gradually enhance the jailbreak performance of the red-team model. Extensive experiments on a variety of LLMs show that \ourapproach effectively balances the diversity and effectiveness of jailbreak prompts compared to existing methods. Our work significantly improves the efficiency of red team exploration and provides a new perspective on automated red teaming.

[Arxiv](https://arxiv.org/abs/2506.00782)