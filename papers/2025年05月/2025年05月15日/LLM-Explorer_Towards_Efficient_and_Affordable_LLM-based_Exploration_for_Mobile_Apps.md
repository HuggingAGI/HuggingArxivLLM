# LLM探索者：高效且经济的移动应用LLM探索方法

发布时间：2025年05月15日

`LLM应用` `移动应用` `自动化探索`

> LLM-Explorer: Towards Efficient and Affordable LLM-based Exploration for Mobile Apps

# 摘要

> 大型语言模型（LLMs）为自动化的移动应用探索带来了新机遇，这一重要且具挑战性的问题曾因难以生成有意义的用户界面交互而备受困扰。然而，现有基于LLMs的探索方法在几乎每一步都严重依赖LLMs生成动作，导致高昂的token费用和计算资源消耗。我们发现，这种对LLMs的过度使用不仅不必要，而且效果不佳，因为许多探索动作并不需要LLMs的能力，甚至可能受到其偏见的影响。基于精确且简洁的知识在探索中发挥核心作用的见解，我们提出了LLM-Explorer，一种专为高效和经济设计的新探索代理。LLM-Explorer主要利用LLMs维护知识，而非生成动作，知识则以无需LLMs的方式指导动作生成。在与5个强大基线的对比中，LLM-Explorer在20个典型应用上实现了所有自动化探索器中最快的速度和最高的覆盖率，与最先进的基于LLMs方法相比，成本降低了148倍以上。

> Large language models (LLMs) have opened new opportunities for automated mobile app exploration, an important and challenging problem that used to suffer from the difficulty of generating meaningful UI interactions. However, existing LLM-based exploration approaches rely heavily on LLMs to generate actions in almost every step, leading to a huge cost of token fees and computational resources. We argue that such extensive usage of LLMs is neither necessary nor effective, since many actions during exploration do not require, or may even be biased by the abilities of LLMs. Further, based on the insight that a precise and compact knowledge plays the central role for effective exploration, we introduce LLM-Explorer, a new exploration agent designed for efficiency and affordability. LLM-Explorer uses LLMs primarily for maintaining the knowledge instead of generating actions, and knowledge is used to guide action generation in a LLM-less manner. Based on a comparison with 5 strong baselines on 20 typical apps, LLM-Explorer was able to achieve the fastest and highest coverage among all automated app explorers, with over 148x lower cost than the state-of-the-art LLM-based approach.

[Arxiv](https://arxiv.org/abs/2505.10593)