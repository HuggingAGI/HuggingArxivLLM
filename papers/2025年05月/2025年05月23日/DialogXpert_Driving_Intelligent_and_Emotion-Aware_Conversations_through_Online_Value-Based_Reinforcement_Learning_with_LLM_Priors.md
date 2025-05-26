# DialogXpert: 结合大型语言模型（LLM）先验知识，通过在线基于价值的强化学习，推动智能且情感感知的对话

发布时间：2025年05月23日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLM）在对话中的应用，特别是在主动且目标导向的互动中。它提出了一种名为DialogXpert的模型，通过结合冻结的LLM和紧凑型Q网络来优化对话中的行动选择，并实时追踪用户情绪以提升对话效果。这些方法和应用都属于LLM在实际场景中的具体应用，因此归类为LLM应用。` `对话系统` `情感计算`

> DialogXpert: Driving Intelligent and Emotion-Aware Conversations through Online Value-Based Reinforcement Learning with LLM Priors

# 摘要

> 大型语言模型（LLM）代理在响应式对话方面表现出色，但在主动且目标导向的互动中表现欠佳，主要源于短视的解码机制和昂贵的规划成本。我们推出DialogXpert，该模型利用冻结的LLM每轮生成少量高质量候选动作，并通过基于固定BERT嵌入的紧凑型Q网络（经时差学习训练）在精简空间内选择最优行动。通过实时追踪用户情绪，DialogXpert能够量身定制每一步决策，既推动任务进展，又建立真实且富有同理心的连接。在谈判、情感支持和辅导等多个基准测试中，DialogXpert将对话轮数压缩至低于3轮，成功率超过94%，搭配更大规模的LLM先验模型，更可将成功率提升至97%以上，同时显著优化谈判结果。这一框架实现了大规模、实时、战略性和情感智能的对话规划。代码已开源：https://github.com/declare-lab/dialogxpert/

> Large-language-model (LLM) agents excel at reactive dialogue but struggle with proactive, goal-driven interactions due to myopic decoding and costly planning. We introduce DialogXpert, which leverages a frozen LLM to propose a small, high-quality set of candidate actions per turn and employs a compact Q-network over fixed BERT embeddings trained via temporal-difference learning to select optimal moves within this reduced space. By tracking the user's emotions, DialogXpert tailors each decision to advance the task while nurturing a genuine, empathetic connection. Across negotiation, emotional support, and tutoring benchmarks, DialogXpert drives conversations to under $3$ turns with success rates exceeding 94\% and, with a larger LLM prior, pushes success above 97\% while markedly improving negotiation outcomes. This framework delivers real-time, strategic, and emotionally intelligent dialogue planning at scale. Code available at https://github.com/declare-lab/dialogxpert/

[Arxiv](https://arxiv.org/abs/2505.17795)