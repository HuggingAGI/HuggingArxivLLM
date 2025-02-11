# # **赫菲斯托斯：借助持续预训练提升大型语言模型的基础能力**

发布时间：2025年02月10日

`LLM应用` `人工智能` `代理系统`

> Hephaestus: Improving Fundamental Agent Capabilities of Large Language Models through Continual Pre-Training

# 摘要

> 由于缺乏面向代理的预训练数据，基于LLM的自主代理通常需要复杂的提示或大量微调，但这种方法往往难以在保持强泛化能力的同时引入新能力。为此，我们推出了Hephaestus-Forge——首个专注于提升LLM代理能力的大型预训练语料库。它包含1030亿条代理专用数据，涵盖76,537个API，包括工具文档以介绍API功能，以及函数调用轨迹以强化内在推理能力。通过研究缩放定律，我们确定了最佳数据混合比例，以探索有效的训练协议。经过Hephaestus-Forge的持续预训练，Hephaestus在小型到中型开源LLM中表现更优，并在三个代理基准测试中与商业LLM相媲美。这充分证明了Hephaestus-Forge在增强LLM的基础代理能力和泛化到新任务或环境中的有效性。

> Due to the scarcity of agent-oriented pre-training data, LLM-based autonomous agents typically rely on complex prompting or extensive fine-tuning, which often fails to introduce new capabilities while preserving strong generalizability. We introduce Hephaestus-Forge, the first large-scale pre-training corpus designed to enhance the fundamental capabilities of LLM agents in API function calling, intrinsic reasoning and planning, and adapting to environmental feedback. Hephaestus-Forge comprises 103B agent-specific data encompassing 76,537 APIs, including both tool documentation to introduce knowledge of API functions and function calling trajectories to strengthen intrinsic reasoning. To explore effective training protocols, we investigate scaling laws to identify the optimal recipe in data mixing ratios. By continual pre-training on Hephaestus-Forge, Hephaestus outperforms small- to medium-scale open-source LLMs and rivals commercial LLMs on three agent benchmarks, demonstrating the effectiveness of our pre-training corpus in enhancing fundamental agentic capabilities and generalization of LLMs to new tasks or environments.

[Arxiv](https://arxiv.org/abs/2502.06589)