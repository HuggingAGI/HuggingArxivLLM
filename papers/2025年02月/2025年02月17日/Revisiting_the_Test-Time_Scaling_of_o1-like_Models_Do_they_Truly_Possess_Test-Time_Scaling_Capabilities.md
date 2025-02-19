# 再探 o1 类模型的测试时缩放：它们真的具备这一能力吗？

发布时间：2025年02月17日

`LLM理论` `人工智能` `模型优化`

> Revisiting the Test-Time Scaling of o1-like Models: Do they Truly Possess Test-Time Scaling Capabilities?

# 摘要

> 大型语言模型（LLMs）中的测试时间缩放技术，以OpenAI的o1系列为代表，通过在推理过程中动态调整计算资源分配，显著增强了模型的推理能力。尽管后续模型如QwQ、Deepseek-R1（R1）和LIMO也继承了这些改进，但这些模型是否真正具备测试时间缩放能力仍是一个开放问题。研究发现，这些类o1模型的长思维链推理并不总是提高准确性；事实上，对于同一问题，正确解答往往比错误解答更短。深入分析表明，这一现象与模型的自我修订能力密切相关：长思维链中包含更多自我修订，而这通常会导致性能下降。随后，我们对QwQ、R1和LIMO模型的串行与并行缩放策略进行了比较，发现并行缩放在覆盖范围和扩展性方面表现更优。基于这些发现，我们提出了一种结合并行缩放策略与思维链长度特性的最短多数投票方法，相较于传统的多数投票方法，显著提升了模型的测试时间可扩展性。

> The advent of test-time scaling in large language models (LLMs), exemplified by OpenAI's o1 series, has advanced reasoning capabilities by scaling computational resource allocation during inference. While successors like QwQ, Deepseek-R1 (R1) and LIMO replicate these advancements, whether these models truly possess test-time scaling capabilities remains underexplored. This study found that longer CoTs of these o1-like models do not consistently enhance accuracy; in fact, correct solutions are often shorter than incorrect ones for the same questions. Further investigation shows this phenomenon is closely related to models' self-revision capabilities - longer CoTs contain more self-revisions, which often lead to performance degradation. We then compare sequential and parallel scaling strategies on QwQ, R1 and LIMO, finding that parallel scaling achieves better coverage and scalability. Based on these insights, we propose Shortest Majority Vote, a method that combines parallel scaling strategies with CoT length characteristics, significantly improving models' test-time scalability compared to conventional majority voting approaches.

[Arxiv](https://arxiv.org/abs/2502.12215)