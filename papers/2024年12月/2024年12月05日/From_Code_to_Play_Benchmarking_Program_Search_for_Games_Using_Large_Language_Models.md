# 从代码走向游戏：利用大型语言模型为游戏的程序搜索设立基准

发布时间：2024年12月05日

`LLM应用` `程序合成`

> From Code to Play: Benchmarking Program Search for Games Using Large Language Models

# 摘要

> 大型语言模型（LLMs）在生成程序代码方面表现出色，为程序合成在游戏中的应用带来了令人欣喜的机遇。在本研究中，我们探究了 LLMs 直接为各类游戏应用合成可用代码的潜力，重点聚焦于 Python 和 Java 这两种编程语言。我们采用了一种进化爬山算法，其中初始程序的变异和种子由 LLMs 掌控。就 Python 而言，该框架涵盖了多种游戏相关任务，比如五个雅达利游戏的迷你版、十个关卡的《Baba is You》、一个受《Asteroids》启发的环境以及一个迷宫生成任务。对于 Java，该框架包含了来自 TAG 桌面游戏框架的 12 个游戏。在 29 个任务中，我们对 12 个 Python 语言模型和 8 个 Java 语言模型进行了评估。我们的研究结果表明，LLMs 的性能更多取决于任务，而非模型规模。虽然较大的模型能生成更多可执行程序，但这些并不总能带来更高质量的解决方案，而且成本更高。没有哪个模型具有明显优势，不过在任何特定任务中，可能某一个模型表现更好。在一个问题上尝试多个模型，并采用其中的最佳结果，要比仅使用一个模型更可靠。

> Large language models (LLMs) have shown impressive capabilities in generating program code, opening exciting opportunities for applying program synthesis to games. In this work, we explore the potential of LLMs to directly synthesize usable code for a wide range of gaming applications, focusing on two programming languages, Python and Java. We use an evolutionary hill-climbing algorithm, where the mutations and seeds of the initial programs are controlled by LLMs. For Python, the framework covers various game-related tasks, including five miniature versions of Atari games, ten levels of Baba is You, an environment inspired by Asteroids, and a maze generation task. For Java, the framework contains 12 games from the TAG tabletop games framework. Across 29 tasks, we evaluated 12 language models for Python and 8 for Java. Our findings suggest that the performance of LLMs depends more on the task than on model size. While larger models generate more executable programs, these do not always result in higher-quality solutions but are much more expensive. No model has a clear advantage, although on any specific task, one model may be better. Trying many models on a problem and using the best results across them is more reliable than using just one.

[Arxiv](https://arxiv.org/abs/2412.04057)