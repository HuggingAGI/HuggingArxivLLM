# 缺失的奖励：经验时代下的主动推理

发布时间：2025年08月07日

`Agent

这篇论文探讨了如何利用主动推断（AIF）来开发能够自主学习和适应目标的AI代理，属于智能体（Agent）领域。` `人工智能` `机器学习`

> The Missing Reward: Active Inference in the Era of Experience

# 摘要

> 本文认为，主动推断（AIF）为开发能够无需持续人工奖励工程即可从经验中学习的自主AI代理提供了关键基础。随着AI系统开始耗尽高质量训练数据，并依赖日益庞大的人工团队进行奖励设计，当前范式正面临重大可扩展性挑战，这可能阻碍真正自主智能的进步。

提出“经验时代”，即代理从自生成数据中学习，是一个有希望的进展。然而，这一愿景仍然依赖于对奖励函数的广泛人工设计，实质上将瓶颈从数据整理转移到奖励整理。这凸显了我们所识别的	extbf{扎根-主体性鸿沟}：当代AI系统无法自主地制定、适应并追求目标以应对不断变化的情况。

我们提出，AIF可以通过将外部奖励信号替换为最小化自由能的内在驱动力来弥合这一鸿沟，使代理能够通过统一的贝叶斯目标自然平衡探索与利用。通过将大型语言模型作为生成世界模型与AIF的原则性决策框架相结合，我们可以创建既能高效从经验中学习又与人类价值观保持一致的代理。这种结合为开发既能自主发展又遵守计算和物理约束的AI系统提供了一条引人注目的道路。

> This paper argues that Active Inference (AIF) provides a crucial foundation for developing autonomous AI agents capable of learning from experience without continuous human reward engineering. As AI systems begin to exhaust high-quality training data and rely on increasingly large human workforces for reward design, the current paradigm faces significant scalability challenges that could impede progress toward genuinely autonomous intelligence. The proposal for an ``Era of Experience,'' where agents learn from self-generated data, is a promising step forward. However, this vision still depends on extensive human engineering of reward functions, effectively shifting the bottleneck from data curation to reward curation. This highlights what we identify as the \textbf{grounded-agency gap}: the inability of contemporary AI systems to autonomously formulate, adapt, and pursue objectives in response to changing circumstances. We propose that AIF can bridge this gap by replacing external reward signals with an intrinsic drive to minimize free energy, allowing agents to naturally balance exploration and exploitation through a unified Bayesian objective. By integrating Large Language Models as generative world models with AIF's principled decision-making framework, we can create agents that learn efficiently from experience while remaining aligned with human values. This synthesis offers a compelling path toward AI systems that can develop autonomously while adhering to both computational and physical constraints.

[Arxiv](https://arxiv.org/abs/2508.05619)