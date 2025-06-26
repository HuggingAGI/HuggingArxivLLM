# 更少数据，更少标记：面向大语言模型高效测试时推理的多语言统一学习方案

发布时间：2025年06月23日

`LLM理论` `多语言学习`

> Less Data Less Tokens: Multilingual Unification Learning for Efficient Test-Time Reasoning in LLMs

# 摘要

> 本文探讨了大型语言模型在测试时扩展的挑战，涉及数据和推理效率两个方面。我们揭示了基于试点研究的多语言推理的多样性，并提出了一种创新方法——\(L^2\)多语言统一学习，结合解码干预策略，深入研究这一问题。\(L^2\)的核心思想是，不同语言的推理过程存在差异，这种差异可能相互促进，从而提升模型性能和效率。具体来说，我们区分了两种类型的多语言数据：一种是不同语言中完整的长链式思考标注，另一种是分步混合的语言。通过基于这些数据进行进一步微调，我们发现，即使少量的数据也能显著提升推理能力。研究结果表明，多语言学习在保持可比性能的同时，减少了所需的数据量和推理标记数量。此外，\(L^2\)与其他数据高效方法正交，因此，我们强调了多样化数据选择的重要性。\(L^2\)方法为大型语言模型在数据收集和测试时计算效率方面面临的挑战提供了一个有前途的解决方案。

> This paper explores the challenges of test-time scaling of large language models (LLMs), regarding both the data and inference efficiency. We highlight the diversity of multi-lingual reasoning based on our pilot studies, and then introduce a novel approach, \(L^2\) multi-lingual unification learning with a decoding intervention strategy for further investigation. The basic idea of \(L^2\) is that the reasoning process varies across different languages, which may be mutually beneficial to enhance both model performance and efficiency. In specific, there are two types of multi-lingual data: the entire long chain-of-thought annotations in different languages and the step-wise mixture of languages. By further tuning based on them, we show that even small amounts of data can significantly improve reasoning capabilities. Our findings suggest that multilingual learning reduces both the required data and the number of inference tokens while maintaining a comparable performance. Furthermore, \(L^2\) is orthogonal to other data efficient methods. Thus, we also emphasize the importance of diverse data selection. The \(L^2\) method offers a promising solution to the challenges of data collection and test-time compute efficiency in LLMs.

[Arxiv](https://arxiv.org/abs/2506.18341)