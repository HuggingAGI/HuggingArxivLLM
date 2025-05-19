# PoE-World：程序化专家乘积驱动的组合式世界建模

发布时间：2025年05月15日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在程序合成领域的应用，提出了一种新的方法来构建世界模型，并将其应用于AI代理中。论文的重点在于展示LLMs在特定任务中的应用和效果，因此归类为LLM应用。`

> PoE-World: Compositional World Modeling with Products of Programmatic Experts

# 摘要

> 理解世界运行机制是构建适应复杂环境的AI代理的核心。传统基于深度学习的世界模型不仅需要大量训练数据，还难以从少量观察中灵活更新知识。得益于大型语言模型（LLMs）在程序合成领域的最新进展，我们提出了一种以源代码形式学习世界模型的新方法，能够实现从少量数据中进行强泛化。目前，程序结构化世界模型的应用主要局限于自然语言和网格世界领域。

我们创新性地提出了一种新型程序合成方法，通过将世界模型表示为大型语言模型合成的程序化专家的指数加权乘积（PoE-World），从而有效建模复杂的非网格世界领域。实验表明，该方法能够仅凭少量观察即可学习复杂且随机的世界模型。通过将学习到的世界模型嵌入到基于模型的规划代理中进行评估，我们展示了在Atari经典游戏Pong和蒙特祖马复仇中实现高效性能和对未见级别的泛化能力。我们的代码、学习到的世界模型以及代理游戏视频已发布在https://topwasu.github.io/poe-world，欢迎访问查看。


> Learning how the world works is central to building AI agents that can adapt to complex environments. Traditional world models based on deep learning demand vast amounts of training data, and do not flexibly update their knowledge from sparse observations. Recent advances in program synthesis using Large Language Models (LLMs) give an alternate approach which learns world models represented as source code, supporting strong generalization from little data. To date, application of program-structured world models remains limited to natural language and grid-world domains. We introduce a novel program synthesis method for effectively modeling complex, non-gridworld domains by representing a world model as an exponentially-weighted product of programmatic experts (PoE-World) synthesized by LLMs. We show that this approach can learn complex, stochastic world models from just a few observations. We evaluate the learned world models by embedding them in a model-based planning agent, demonstrating efficient performance and generalization to unseen levels on Atari's Pong and Montezuma's Revenge. We release our code and display the learned world models and videos of the agent's gameplay at https://topwasu.github.io/poe-world.

[Arxiv](https://arxiv.org/abs/2505.10819)