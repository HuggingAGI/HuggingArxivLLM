# LLM360 K2: 360度开源大型语言模型的扩展

发布时间：2025年01月13日

`LLM理论

理由：这篇论文主要讨论了LLM360 K2-65B模型的训练过程，特别是如何实现透明度和可重复性。它详细介绍了模型的训练步骤、资源使用情况以及性能分析，这些都是关于大型语言模型（LLM）的理论和实践方面的内容。因此，这篇论文更适合归类为LLM理论。` `人工智能` `开源技术`

> LLM360 K2: Scaling Up 360-Open-Source Large Language Models

# 摘要

> 我们详细介绍了LLM360 K2-65B模型的训练过程，将360度开源方法扩展到LLM360项目下最大、最强大的模型。尽管开源LLM不断进步，但社区内对于“最大的LLM是如何训练的？”这一问题仍无定论。由于高成本相关的商业考虑，这些高容量模型的实现细节通常保密。这种透明度的缺乏阻碍了LLM研究人员从以往经验中获取有价值的见解，例如“解决损失峰值的最佳实践是什么？”LLM360 K2项目通过提供完全的透明度和访问大规模LLM训练过程中积累的资源，填补了这一空白。本报告重点介绍了K2项目的关键要素，包括我们的第一个模型K2 DIAMOND，这是一个拥有650亿参数的LLM，超越了LLaMA-65B，并与LLaMA2-70B相媲美，同时需要更少的FLOPs和tokens。我们详细介绍了实现步骤，并展示了K2 DIAMOND在整个训练过程中的能力纵向分析。我们还概述了正在进行中的项目，如TXT360，为系列中的未来模型奠定了基础。通过提供以前无法获得的资源，K2项目也符合360度开源原则的透明度、可重复性和可访问性，我们认为这些原则在资源密集型AI研究时代至关重要。

> We detail the training of the LLM360 K2-65B model, scaling up our 360-degree OPEN SOURCE approach to the largest and most powerful models under project LLM360. While open-source LLMs continue to advance, the answer to "How are the largest LLMs trained?" remains unclear within the community. The implementation details for such high-capacity models are often protected due to business considerations associated with their high cost. This lack of transparency prevents LLM researchers from leveraging valuable insights from prior experience, e.g., "What are the best practices for addressing loss spikes?" The LLM360 K2 project addresses this gap by providing full transparency and access to resources accumulated during the training of LLMs at the largest scale. This report highlights key elements of the K2 project, including our first model, K2 DIAMOND, a 65 billion-parameter LLM that surpasses LLaMA-65B and rivals LLaMA2-70B, while requiring fewer FLOPs and tokens. We detail the implementation steps and present a longitudinal analysis of K2 DIAMOND's capabilities throughout its training process. We also outline ongoing projects such as TXT360, setting the stage for future models in the series. By offering previously unavailable resources, the K2 project also resonates with the 360-degree OPEN SOURCE principles of transparency, reproducibility, and accessibility, which we believe are vital in the era of resource-intensive AI research.

[Arxiv](https://arxiv.org/abs/2501.07124)