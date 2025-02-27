# 重新审视 LLM 遗忘目标：从梯度视角出发，探索更广阔的研究领域

发布时间：2025年02月26日

`LLM理论` `模型治理` `模型优化`

> Rethinking LLM Unlearning Objectives: A Gradient Perspective and Go Beyond

# 摘要

> 大型语言模型（LLMs）需经过严格审核，以识别潜在风险，例如版权和隐私问题。一旦风险出现，及时更新至关重要，移除不良响应，确保模型合法安全使用。这激发了近期关于LLMs无学习的研究，专注于在不损害其他非目标响应的情况下擦除特定不良知识。现有研究提出了多种无学习目标，无需完整重新训练即可实现无学习。然而，每个目标都有独特性质，目前尚无统一框架全面理解它们。为此，我们提出基于梯度效应（G-effect）的工具包，从梯度视角量化无学习目标对模型性能的影响。其显著优势在于广泛适用性，能从实例、更新步骤和LLM层等多个方面详细分析无学习影响。因此，G-effect为识别现有无学习目标的缺点提供了新见解，并激励我们探索缓解和改进的新方案。最后，我们概述了值得进一步研究的有前景方向，旨在为社区做出贡献，推动这一重要领域的发展。

> Large language models (LLMs) should undergo rigorous audits to identify potential risks, such as copyright and privacy infringements. Once these risks emerge, timely updates are crucial to remove undesirable responses, ensuring legal and safe model usage. It has spurred recent research into LLM unlearning, focusing on erasing targeted undesirable knowledge without compromising the integrity of other, non-targeted responses. Existing studies have introduced various unlearning objectives to pursue LLM unlearning without necessitating complete retraining. However, each of these objectives has unique properties, and no unified framework is currently available to comprehend them thoroughly. To fill the gap, we propose a toolkit of the gradient effect (G-effect), quantifying the impacts of unlearning objectives on model performance from a gradient perspective. A notable advantage is its broad ability to detail the unlearning impacts from various aspects across instances, updating steps, and LLM layers. Accordingly, the G-effect offers new insights into identifying drawbacks of existing unlearning objectives, further motivating us to explore a series of new solutions for their mitigation and improvements. Finally, we outline promising directions that merit further studies, aiming at contributing to the community to advance this important field.

[Arxiv](https://arxiv.org/abs/2502.19301)