# CreAgent：探索平台与创作者信息差下的推荐系统长期评估

发布时间：2025年02月11日

`Agent

理由：这篇论文主要讨论了推荐系统中的长期可持续性问题，并提出了一个基于LLM的创作者模拟代理（CreAgent），该代理结合了博弈论的信念机制和快慢思维框架，并通过PPO进行微调。研究的核心是模拟创作者行为及其对推荐系统的长期影响，而不是直接研究LLM本身或其应用。因此，这篇论文应归类为“Agent”。` `推荐系统` `创作者模拟`

> CreAgent: Towards Long-Term Evaluation of Recommender System under Platform-Creator Information Asymmetry

# 摘要

> 推荐系统 (RS) 的长期可持续性已成为关键议题。传统 RS 评估方法侧重于即时用户反馈（如点击），却忽视了内容创作者的长期影响。现实中，创作者基于用户反馈和偏好趋势策略性地生产和上传内容。尽管此前研究尝试建模创作者行为，但常忽视信息不对称的作用——创作者仅能获取自身作品的反馈，而平台掌握整体用户反馈数据。现有 RS 模拟器未能考虑这一不对称性，导致长期评估失准。为此，我们提出 CreAgent，一个基于 LLM 的创作者模拟代理。通过融合博弈论的信念机制与快慢思维框架，CreAgent 能在信息不对称环境下精准模拟创作者行为。借助近端策略优化 (PPO) 微调，进一步提升了 CreAgent 的模拟能力。我们的可信度验证实验表明，CreAgent 与现实平台和创作者行为高度契合，显著提升了长期 RS 评估的可靠性。此外，通过模拟 CreAgent 参与的 RS，我们可探究公平性与多样性感知算法如何助力各利益相关者实现更优长期表现。CreAgent 及模拟平台现已开源，访问地址：https://github.com/shawnye2000/CreAgent。

> Ensuring the long-term sustainability of recommender systems (RS) emerges as a crucial issue. Traditional offline evaluation methods for RS typically focus on immediate user feedback, such as clicks, but they often neglect the long-term impact of content creators. On real-world content platforms, creators can strategically produce and upload new items based on user feedback and preference trends. While previous studies have attempted to model creator behavior, they often overlook the role of information asymmetry. This asymmetry arises because creators primarily have access to feedback on the items they produce, while platforms possess data on the entire spectrum of user feedback. Current RS simulators, however, fail to account for this asymmetry, leading to inaccurate long-term evaluations. To address this gap, we propose CreAgent, a Large Language Model (LLM)-empowered creator simulation agent. By incorporating game theory's belief mechanism and the fast-and-slow thinking framework, CreAgent effectively simulates creator behavior under conditions of information asymmetry. Additionally, we enhance CreAgent's simulation ability by fine-tuning it using Proximal Policy Optimization (PPO). Our credibility validation experiments show that CreAgent aligns well with the behaviors between real-world platform and creator, thus improving the reliability of long-term RS evaluations. Moreover, through the simulation of RS involving CreAgents, we can explore how fairness- and diversity-aware RS algorithms contribute to better long-term performance for various stakeholders. CreAgent and the simulation platform are publicly available at https://github.com/shawnye2000/CreAgent.

[Arxiv](https://arxiv.org/abs/2502.07307)