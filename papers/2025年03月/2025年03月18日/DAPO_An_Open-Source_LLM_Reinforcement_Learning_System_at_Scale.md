# DAPO: 开源大规模LLM强化学习系统

发布时间：2025年03月18日

`LLM应用` `人工智能`

> DAPO: An Open-Source LLM Reinforcement Learning System at Scale

# 摘要

> 推理扩展赋予了大型语言模型（LLMs）前所未有的推理能力，其中强化学习是激发复杂推理的核心技术。然而，当前最先进的推理型LLMs的关键技术细节仍被隐藏（如OpenAI o1博客和DeepSeek R1技术报告所示），因此社区在复现实验结果时仍面临困难。我们提出了【数学公式】算法，并完全开源了一个先进的大规模RL系统，该系统基于Qwen2.5-32B基础模型，在AIME 2024上实现了50分的成绩。与之前的工作不同，我们公开了算法的四个关键技术，这些技术使得大规模LLM RL取得成功。此外，我们开源了我们的训练代码，该代码基于verl框架，并附带了一个精心整理和处理的数据集。我们开源系统中的这些组件增强了结果的可复现性，并为未来的大规模LLM RL研究提供了支持。

> Inference scaling empowers LLMs with unprecedented reasoning ability, with reinforcement learning as the core technique to elicit complex reasoning. However, key technical details of state-of-the-art reasoning LLMs are concealed (such as in OpenAI o1 blog and DeepSeek R1 technical report), thus the community still struggles to reproduce their RL training results. We propose the $\textbf{D}$ecoupled Clip and $\textbf{D}$ynamic s$\textbf{A}$mpling $\textbf{P}$olicy $\textbf{O}$ptimization ($\textbf{DAPO}$) algorithm, and fully open-source a state-of-the-art large-scale RL system that achieves 50 points on AIME 2024 using Qwen2.5-32B base model. Unlike previous works that withhold training details, we introduce four key techniques of our algorithm that make large-scale LLM RL a success. In addition, we open-source our training code, which is built on the verl framework, along with a carefully curated and processed dataset. These components of our open-source system enhance reproducibility and support future research in large-scale LLM RL.

[Arxiv](https://arxiv.org/abs/2503.14476)