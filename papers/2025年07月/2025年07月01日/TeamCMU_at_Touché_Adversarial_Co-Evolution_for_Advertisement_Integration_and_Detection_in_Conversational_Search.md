# # CMU团队在Touché比赛中的对抗协同进化方法：对话式搜索中的广告整合与检测

发布时间：2025年07月01日

`RAG`

> TeamCMU at Touché: Adversarial Co-Evolution for Advertisement Integration and Detection in Conversational Search

# 摘要

> 对话式搜索引擎正越来越多地采用由大型语言模型（LLM）和检索增强生成（RAG）驱动的生成式范式。在这一背景下，广告与生成回复的结合既带来了商业机遇，也对用户体验提出了挑战。与传统搜索不同，传统搜索中广告界限分明，而生成系统模糊了信息内容与推广材料之间的界限，引发了关于透明度和信任的担忧。本研究针对基于 RAG 的对话系统，提出了一种模块化的广告管理流水线，其中包括一个用于无缝集成广告的广告改写器和一个强大的广告分类器用于检测。我们利用合成数据训练高性能分类器，并将其用于指导两种互补的广告集成策略：监督微调广告改写器和一种最佳 N 采样方法，该方法在多个候选回复中选择广告集成最不易察觉的回复。我们的研究重点在于：广告分类器在检测多种广告集成策略方面的有效性，以及支持连贯且最小干扰广告插入的最佳训练方法。实验结果表明，我们的广告分类器在基于营销策略的合成广告数据上进行训练，并通过课程学习增强，实现了强大的检测性能。此外，通过微调和最佳 N 采样两种方式，分类器引导的优化显著提高了广告的隐蔽性，从而实现了更无缝的集成。这些发现为开发更复杂的广告感知生成式搜索系统和强大的广告分类器提供了一个对抗性协同进化框架。

> As conversational search engines increasingly adopt generation-based paradigms powered by Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG), the integration of advertisements into generated responses presents both commercial opportunities and challenges for user experience. Unlike traditional search, where advertisements are clearly delineated, generative systems blur the boundary between informational content and promotional material, raising concerns around transparency and trust. In this work, we propose a modular pipeline for advertisement management in RAG-based conversational systems, consisting of an ad-rewriter for seamless ad integration and a robust ad-classifier for detection. We leverage synthetic data to train high-performing classifiers, which are then used to guide two complementary ad-integration strategies: supervised fine-tuning of the ad-rewriter and a best-of-N sampling approach that selects the least detectable ad-integrated response among multiple candidates. Our evaluation focuses on two core questions: the effectiveness of ad classifiers in detecting diverse ad integration strategies, and the training methods that best support coherent, minimally intrusive ad insertion. Experimental results show that our ad-classifier, trained on synthetic advertisement data inspired by marketing strategies and enhanced through curriculum learning, achieves robust detection performance. Additionally, we demonstrate that classifier-guided optimization, through both fine-tuning and best-of-N sampling, significantly improves ad stealth, enabling more seamless integration. These findings contribute an adversarial co-evolution framework for developing more sophisticated ad-aware generative search systems and robust ad classifiers.

[Arxiv](https://arxiv.org/abs/2507.00509)