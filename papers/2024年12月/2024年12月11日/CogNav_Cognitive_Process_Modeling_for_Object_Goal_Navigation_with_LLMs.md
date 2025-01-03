# CogNav: 利用LLMs进行目标导航的认知过程建模

发布时间：2024年12月11日

`Agent

理由：这篇论文主要讨论的是物体目标导航（ObjectNav）任务，这是一个具身AI（Embodied AI）的核心任务，要求智能体在未知环境中定位目标物体。论文提出了一种名为CogNav的方法，利用大型语言模型（LLM）来模拟人类的认知过程，以提升导航效率。虽然论文中提到了大型语言模型的应用，但其核心关注点是智能体（Agent）在导航任务中的表现和决策过程，因此更适合归类为Agent。` `机器人` `人工智能`

> CogNav: Cognitive Process Modeling for Object Goal Navigation with LLMs

# 摘要

> # 摘要
物体目标导航（ObjectNav）是具身AI的核心任务，要求智能体在未知环境中定位目标物体。这一任务极具挑战性，因为它需要结合感知与认知能力来进行有效的决策。尽管感知领域在视觉基础模型的推动下取得了显著进展，但认知方面的研究仍主要依赖于从大量导航数据中隐式学习或显式使用预定义规则。受神经科学启发，人类在未知环境中搜索物体时会不断更新认知状态，我们提出了CogNav，利用大型语言模型模拟这一认知过程。具体而言，我们通过有限状态机建模认知过程，状态从探索到识别，状态间的转换由大型语言模型基于在线构建的异构认知图决定，该图包含场景的空间和语义信息。在合成和真实环境中的广泛实验表明，我们的认知建模显著提升了ObjectNav的效率，并展现出类人导航行为。在开放词汇和零-shot设置下，我们的方法将HM3D基准的SOTA从69.3%提升至87.2%。代码和数据将公开。

> Object goal navigation (ObjectNav) is a fundamental task of embodied AI that requires the agent to find a target object in unseen environments. This task is particularly challenging as it demands both perceptual and cognitive processes for effective perception and decision-making. While perception has gained significant progress powered by the rapidly developed visual foundation models, the progress on the cognitive side remains limited to either implicitly learning from massive navigation demonstrations or explicitly leveraging pre-defined heuristic rules. Inspired by neuroscientific evidence that humans consistently update their cognitive states while searching for objects in unseen environments, we present CogNav, which attempts to model this cognitive process with the help of large language models. Specifically, we model the cognitive process with a finite state machine composed of cognitive states ranging from exploration to identification. The transitions between the states are determined by a large language model based on an online built heterogeneous cognitive map containing spatial and semantic information of the scene being explored. Extensive experiments on both synthetic and real-world environments demonstrate that our cognitive modeling significantly improves ObjectNav efficiency, with human-like navigation behaviors. In an open-vocabulary and zero-shot setting, our method advances the SOTA of the HM3D benchmark from 69.3% to 87.2%. The code and data will be released.

[Arxiv](https://arxiv.org/abs/2412.10439)