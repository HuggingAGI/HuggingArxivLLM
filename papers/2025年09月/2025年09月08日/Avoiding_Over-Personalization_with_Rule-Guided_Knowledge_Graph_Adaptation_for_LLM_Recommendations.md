# 规则引导的知识图谱适配：避免LLM推荐过度个性化

发布时间：2025年09月08日

`LLM应用` `零售与电商`

> Avoiding Over-Personalization with Rule-Guided Knowledge Graph Adaptation for LLM Recommendations

# 摘要

> 我们提出一种轻量级神经符号框架，通过在推理阶段适配用户侧知识图谱（KGs），有效缓解基于LLM的推荐系统中的过度个性化问题。该方法无需重新训练模型或依赖不透明的启发式规则，而是通过重构用户的个性化知识图谱（PKG），抑制强化个性化信息环境（PIEs）的特征共现模式——即算法催生的过滤气泡，这类气泡会限制内容多样性。这些适配后的PKG用于构建结构化提示，引导语言模型生成更多样化的Out-PIE推荐，同时确保主题相关性。我们提出一系列符号适配策略，包括软重加权、硬反转及针对性移除有偏三元组，并设计客户端学习算法，为每个用户优化策略的应用。在食谱推荐基准数据集上的实验显示，个性化PKG适配显著提升了内容新颖性，同时维持了推荐质量，性能优于全局适配和简单的基于提示的方法。

> We present a lightweight neuro-symbolic framework to mitigate over-personalization in LLM-based recommender systems by adapting user-side Knowledge Graphs (KGs) at inference time. Instead of retraining models or relying on opaque heuristics, our method restructures a user's Personalized Knowledge Graph (PKG) to suppress feature co-occurrence patterns that reinforce Personalized Information Environments (PIEs), i.e., algorithmically induced filter bubbles that constrain content diversity. These adapted PKGs are used to construct structured prompts that steer the language model toward more diverse, Out-PIE recommendations while preserving topical relevance. We introduce a family of symbolic adaptation strategies, including soft reweighting, hard inversion, and targeted removal of biased triples, and a client-side learning algorithm that optimizes their application per user. Experiments on a recipe recommendation benchmark show that personalized PKG adaptations significantly increase content novelty while maintaining recommendation quality, outperforming global adaptation and naive prompt-based methods.

[Arxiv](https://arxiv.org/abs/2509.07133)