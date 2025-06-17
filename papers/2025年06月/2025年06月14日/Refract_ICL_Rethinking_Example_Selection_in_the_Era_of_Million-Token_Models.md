# Refract ICL：在百万令牌模型时代重新思考示例选择

发布时间：2025年06月14日

`LLM应用` `人工智能`

> Refract ICL: Rethinking Example Selection in the Era of Million-Token Models

# 摘要

> 长上下文大型语言模型的出现，使使用数百甚至数千个示例进行上下文学习成为可能，而这在以前是无法实现的。本文研究了传统ICL选择策略在大量演示中的有效性，这些策略通过平衡ICL示例与测试输入的相似性以及ICL集合内的多样性来优化性能。实验表明，虽然更长的上下文可以容纳更多示例，但单纯增加演示数量并不一定能提升性能。即使使用数千个演示，智能ICL选择仍然至关重要。为了进一步提升ICL的效果，我们提出了Refract ICL，这是一种新型的ICL选择算法，通过在上下文中战略性地重复困难示例，并将零样本预测作为错误信号，让模型更关注具有挑战性的例子。结果显示，Refract ICL显著提升了极长上下文模型（如Gemini 1.5 Pro）的性能，尤其是在输出类别较少的任务上。

> The emergence of long-context large language models (LLMs) has enabled the use of hundreds, or even thousands, of demonstrations for in-context learning (ICL) - a previously impractical regime. This paper investigates whether traditional ICL selection strategies, which balance the similarity of ICL examples to the test input (using a text retriever) with diversity within the ICL set, remain effective when utilizing a large number of demonstrations. Our experiments demonstrate that, while longer contexts can accommodate more examples, simply increasing the number of demonstrations does not guarantee improved performance. Smart ICL selection remains crucial, even with thousands of demonstrations. To further enhance ICL in this setting, we introduce Refract ICL, a novel ICL selection algorithm specifically designed to focus LLM attention on challenging examples by strategically repeating them within the context and incorporating zero-shot predictions as error signals. Our results show that Refract ICL significantly improves the performance of extremely long-context models such as Gemini 1.5 Pro, particularly on tasks with a smaller number of output classes.

[Arxiv](https://arxiv.org/abs/2506.12346)