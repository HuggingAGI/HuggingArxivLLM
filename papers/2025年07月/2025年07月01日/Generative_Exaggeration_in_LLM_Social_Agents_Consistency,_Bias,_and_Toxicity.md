# 大型语言模型社交代理中的生成式夸大：一致性、偏见与毒性表现

发布时间：2025年07月01日

`LLM应用` `社交媒体` `内容审核`

> Generative Exaggeration in LLM Social Agents: Consistency, Bias, and Toxicity

# 摘要

> 我们深入研究了大型语言模型 (LLMs) 在模拟社交媒体政治讨论时的行为表现。基于2024年美国总统选举期间X平台上2100万次互动数据，我们构建了1186个基于真实用户的LLM智能体，通过控制条件下提示它们回复具有政治敏感性的推文。这些智能体的初始化方式分为两种：基于少量的意识形态线索（零样本）或基于近期推文历史（少样本），从而可以与人类回复进行一对一比较。我们从语言风格、意识形态一致性以及毒性内容三个方面评估了三个模型家族（Gemini、Mistral 和 DeepSeek）。研究发现，更丰富的上下文化提升了内部一致性，但也加剧了极化、风格化信号以及有害语言的出现。我们观察到一种新兴的扭曲现象，称之为“生成夸大”：即对显著特征的系统性放大，超越了实证基准。分析表明，LLMs 并非简单模仿用户，而是对用户行为进行了重构。它们的输出更多反映内部优化动态，而非实际观察到的行为，从而引入了影响其作为社会代理可靠性的结构性偏差。这一发现挑战了LLMs在内容审核、审议模拟以及政策建模中的应用前景。

> We investigate how Large Language Models (LLMs) behave when simulating political discourse on social media. Leveraging 21 million interactions on X during the 2024 U.S. presidential election, we construct LLM agents based on 1,186 real users, prompting them to reply to politically salient tweets under controlled conditions. Agents are initialized either with minimal ideological cues (Zero Shot) or recent tweet history (Few Shot), allowing one-to-one comparisons with human replies. We evaluate three model families (Gemini, Mistral, and DeepSeek) across linguistic style, ideological consistency, and toxicity. We find that richer contextualization improves internal consistency but also amplifies polarization, stylized signals, and harmful language. We observe an emergent distortion that we call "generation exaggeration": a systematic amplification of salient traits beyond empirical baselines. Our analysis shows that LLMs do not emulate users, they reconstruct them. Their outputs, indeed, reflect internal optimization dynamics more than observed behavior, introducing structural biases that compromise their reliability as social proxies. This challenges their use in content moderation, deliberative simulations, and policy modeling.

[Arxiv](https://arxiv.org/abs/2507.00657)