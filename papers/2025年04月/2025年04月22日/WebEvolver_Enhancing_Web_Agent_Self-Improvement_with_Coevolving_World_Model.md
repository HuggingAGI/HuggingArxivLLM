# WebEvolver：利用协同进化的世界模型提升网络代理的自我改进能力

发布时间：2025年04月22日

`Agent` `智能体` `人工智能`

> WebEvolver: Enhancing Web Agent Self-Improvement with Coevolving World Model

# 摘要

> 智能体自我改进通过基于自身策略自主采样的轨迹训练其大型语言模型（LLM）主干，展现出巨大潜力。然而，近期在Web环境中的进展面临一个关键限制：智能体在自主学习周期中会达到性能停滞点，阻碍进一步提升。我们认为，这是由于对Web环境探索不足以及大型语言模型中预训练Web知识的利用不够充分所致。为了改善自我改进的效果，我们提出了一种引入协同演化的世界模型大型语言模型的新型框架。该世界模型基于Web环境中的当前观察和动作预测下一步的观察结果。通过利用大型语言模型对丰富网络内容的预训练知识，世界模型承担双重角色：(1) 作为虚拟Web服务器，生成自我指令的训练数据，持续优化智能体的策略；(2) 在推理过程中作为想象引擎，实现向前模拟，指导智能体大型语言模型的动作选择。在真实Web环境（Mind2Web-Live、WebVoyager 和 GAIA-web）中的实验表明，与现有自我演化的智能体相比，我们的方法性能提升了10%，证明了该方法的有效性和通用性，且无需从更强大的闭源模型中进行蒸馏。我们的研究表明，将世界模型集成到自主智能体框架中是实现持续适应性的必要条件。

> Agent self-improvement, where the backbone Large Language Model (LLM) of the agent are trained on trajectories sampled autonomously based on their own policies, has emerged as a promising approach for enhancing performance. Recent advancements, particularly in web environments, face a critical limitation: their performance will reach a stagnation point during autonomous learning cycles, hindering further improvement. We argue that this stems from limited exploration of the web environment and insufficient exploitation of pre-trained web knowledge in LLMs. To improve the performance of self-improvement, we propose a novel framework that introduces a co-evolving World Model LLM. This world model predicts the next observation based on the current observation and action within the web environment. Leveraging LLMs' pretrained knowledge of abundant web content, the World Model serves dual roles: (1) as a virtual web server generating self-instructed training data to continuously refine the agent's policy, and (2) as an imagination engine during inference, enabling look-ahead simulation to guide action selection for the agent LLM. Experiments in real-world web environments (Mind2Web-Live, WebVoyager, and GAIA-web) show a 10% performance gain over existing self-evolving agents, demonstrating the efficacy and generalizability of our approach, without using any distillation from more powerful close-sourced models. Our work establishes the necessity of integrating world models into autonomous agent frameworks to unlock sustained adaptability.

[Arxiv](https://arxiv.org/abs/2504.21024)