# # 大型语言模型评估的第三种范式：基于对话游戏的评估方法
大型语言模型（LLM）的评估方法迎来了第三种范式，我们采用 clembench 这一工具，通过对话游戏的方式进行评估，为模型能力的衡量提供了全新的视角。

发布时间：2025年07月11日

`LLM应用` `模型评估`

> A Third Paradigm for LLM Evaluation: Dialogue Game-Based Evaluation using clembench

# 摘要

> 目前，评估大型语言模型（LLMs）主要有两种范式：基于参考的评估和基于偏好的评估。前者源自通用机器学习模型的评估方法，依赖于预定义的任务实例，这些实例有现成的参考执行结果。后者以LM-arena为代表，依赖于用户将自己的意图带到一个网站，该网站将这些意图同时路由到多个模型，用户随后从这些模型的响应中选择自己最偏好的一个。因此，前一种范式在控制测试内容方面更为出色，而后一种范式则具有更高的生态效度，能够通过交互式测试实际使用案例。最近，一种新的补充范式出现了，它结合了前两种方法的一些优势，提供了对多轮、无参考、可重复交互的控制，同时强调目标导向性：基于对话游戏的评估。尽管已有多个项目展示了这种方法的实用性，但由于缺乏成熟且易于重用的实现，其采用受到了限制。在本文中，我们介绍了clembench，它自2023年以来一直在持续开发中，其最新版本已针对易于一般使用进行了优化。我们描述了如何使用它来基准测试自己的模型（使用一组提供的英语基准游戏实例），以及如何轻松地将基准本身扩展为新的、量身定制的目标测试。

> There are currently two main paradigms for evaluating large language models (LLMs), reference-based evaluation and preference-based evaluation. The first, carried over from the evaluation of machine learning models in general, relies on pre-defined task instances, for which reference task executions are available. The second, best exemplified by the LM-arena, relies on (often self-selected) users bringing their own intents to a site that routes these to several models in parallel, among whose responses the user then selects their most preferred one. The former paradigm hence excels at control over what is tested, while the latter comes with higher ecological validity, testing actual use cases interactively. Recently, a third complementary paradigm has emerged that combines some of the strengths of these approaches, offering control over multi-turn, reference-free, repeatable interactions, while stressing goal-directedness: dialogue game based evaluation. While the utility of this approach has been shown by several projects, its adoption has been held back by the lack of a mature, easily re-usable implementation. In this paper, we present clembench, which has been in continuous development since 2023 and has in its latest release been optimized for ease of general use. We describe how it can be used to benchmark one's own models (using a provided set of benchmark game instances in English), as well as how easily the benchmark itself can be extended with new, tailor-made targeted tests.

[Arxiv](https://arxiv.org/abs/2507.08491)