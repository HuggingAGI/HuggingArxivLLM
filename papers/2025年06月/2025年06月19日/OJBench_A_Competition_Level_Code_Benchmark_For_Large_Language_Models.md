# OJBench：专为大型语言模型打造的竞赛级代码基准测试

发布时间：2025年06月19日

`LLM应用

理由：这篇论文主要讨论了大型语言模型在代码推理任务中的应用和评估，特别是通过新设计的基准测试OJBench来评估模型在竞争级别的表现。研究集中在模型的应用场景和性能评估，属于LLM的应用领域。` `编程竞赛`

> OJBench: A Competition Level Code Benchmark For Large Language Models

# 摘要

> 大型语言模型（LLMs）近期在数学和代码推理领域取得了显著突破。然而，现有代码基准测试在全面评估这些能力，特别是在竞争级别上，仍显不足。为解决这一问题，我们推出了OJBench——一个全新且极具挑战性的基准测试，专为评估LLMs在竞争级别的代码推理能力而设计。OJBench精选了来自NOI和ICPC的232个编程竞赛问题，为模型推理能力提供了更严格的考验。我们对包括闭源与开源、推理导向与非推理导向在内的37个模型进行了全面评估。结果显示，即使是当前最先进的推理导向模型，如o4-mini和Gemini-2.5-pro-exp，在面对极具挑战性的竞赛级别问题时也表现挣扎。这表明，模型在竞争级别代码推理方面仍面临重大挑战。

> Recent advancements in large language models (LLMs) have demonstrated significant progress in math and code reasoning capabilities. However, existing code benchmark are limited in their ability to evaluate the full spectrum of these capabilities, particularly at the competitive level. To bridge this gap, we introduce OJBench, a novel and challenging benchmark designed to assess the competitive-level code reasoning abilities of LLMs. OJBench comprises 232 programming competition problems from NOI and ICPC, providing a more rigorous test of models' reasoning skills. We conducted a comprehensive evaluation using OJBench on 37 models, including both closed-source and open-source models, reasoning-oriented and non-reasoning-oriented models. Our results indicate that even state-of-the-art reasoning-oriented models, such as o4-mini and Gemini-2.5-pro-exp, struggle with highly challenging competition-level problems. This highlights the significant challenges that models face in competitive-level code reasoning.

[Arxiv](https://arxiv.org/abs/2506.16395)