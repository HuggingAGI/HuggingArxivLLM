# 从微小的失误到巨大的飞跃：基于LLM的假新闻演化模拟

发布时间：2024年10月24日

`Agent

理由：这篇论文主要讨论了利用大型语言模型（LLMs）作为代理来模拟社交网络中的个体行为，并定义了四种代理类型（传播者、评论者、验证者和旁观者）。论文的核心在于通过代理模拟假新闻的演变过程，属于多代理系统（Multi-Agent Systems）的应用，因此应归类为Agent。` `社交媒体` `信息安全`

> From a Tiny Slip to a Giant Leap: An LLM-Based Simulation for Fake News Evolution

# 摘要

> 随着网络虚假信息的泛滥，研究焦点逐渐转向假新闻的检测与追踪。然而，一个常被忽视的问题是，假新闻并非自然存在于社交网络中，而是源于事实的扭曲或恶意捏造。理解真实新闻如何演变为假新闻，对于早期检测和预防至关重要，能够有效减少其传播和影响。为此，本文首次提出基于大型语言模型（LLMs）的假新闻演变模拟框架（FUSE）。我们利用LLM作为代理，模拟社交网络中的个体行为，并定义了四种常见代理类型：传播者、评论者、验证者和旁观者。通过构建高聚类网络和无标度网络等模拟环境，我们还原了现实世界的网络动态。每天，代理们进行信念交流、反思思维过程，并重新发布新闻。由于该领域缺乏相关研究，我们开发了FUSE-EVAL评估框架，用于量化假新闻演变过程中与真实新闻的偏差。实验结果表明，FUSE成功捕捉了真实新闻向假新闻转变的潜在模式，并准确再现了已知的假新闻案例，与人类评估高度一致。此外，我们的研究强调，打击假新闻不应等到其完全演变后才行动，提前预防才是关键。

> With the growing spread of misinformation online, research has increasingly focused on detecting and tracking fake news. However, an overlooked issue is that fake news does not naturally exist in social networks -- it often originates from distorted facts or deliberate fabrication by malicious actors. Understanding how true news gradually evolves into fake news is critical for early detection and prevention, reducing its spread and impact. Hence, in this paper, we take the first step toward simulating and revealing this evolution, proposing a Fake News evolUtion Simulation framEwork (FUSE) based on large language models (LLMs). Specifically, we employ LLM as agents to represent individuals in a simulated social network. We define four types of agents commonly observed in daily interactions: spreaders, who propagate information; commentators, who provide opinions and interpretations; verifiers, who check the accuracy of information; and bystanders, who passively observe without engaging. For simulated environments, we model various social network structures, such as high-clustering networks and scale-free networks, to mirror real-world network dynamics. Each day, the agents engage in belief exchanges, reflect on their thought processes, and reintroduce the news accordingly. Given the lack of prior work in this area, we developed a FUSE-EVAL evaluation framework to measure the deviation from true news during the fake news evolution process. The results show that FUSE successfully captures the underlying patterns of how true news transforms into fake news and accurately reproduces previously discovered instances of fake news, aligning closely with human evaluations. Moreover, our work provides insights into the fact that combating fake news should not be delayed until it has fully evolved; instead, prevention in advance is key to achieving better outcomes.

[Arxiv](https://arxiv.org/abs/2410.19064)