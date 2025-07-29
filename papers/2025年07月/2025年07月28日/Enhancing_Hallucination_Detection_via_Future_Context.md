# 利用未来上下文提升幻觉检测能力

发布时间：2025年07月28日

`LLM应用

理由：这篇论文专注于开发针对黑箱生成器的幻觉检测框架，探讨如何检测大型语言模型生成的幻觉内容，属于大型语言模型的实际应用研究。` `信息安全`

> Enhancing Hallucination Detection via Future Context

# 摘要

> 大型语言模型（LLMs）在在线平台上被广泛用于生成看似合理的文本，而其生成过程却如同黑箱般不透明。随着用户越来越多地接触这种黑箱输出，如何识别其中的幻觉内容已成为一项重要挑战。为应对这一挑战，我们专注于开发针对黑箱生成器的幻觉检测框架。受幻觉一旦引入往往持续存在的观察启发，我们对未来的上下文进行采样。这些采样的未来上下文为幻觉检测提供了有价值线索，并能与各种基于采样的方法有效结合。通过我们提出的采样方法，在多种方法上都展示了显著的性能提升。

> Large Language Models (LLMs) are widely used to generate plausible text on online platforms, without revealing the generation process. As users increasingly encounter such black-box outputs, detecting hallucinations has become a critical challenge. To address this challenge, we focus on developing a hallucination detection framework for black-box generators. Motivated by the observation that hallucinations, once introduced, tend to persist, we sample future contexts. The sampled future contexts provide valuable clues for hallucination detection and can be effectively integrated with various sampling-based methods. We extensively demonstrate performance improvements across multiple methods using our proposed sampling approach.

[Arxiv](https://arxiv.org/abs/2507.20546)