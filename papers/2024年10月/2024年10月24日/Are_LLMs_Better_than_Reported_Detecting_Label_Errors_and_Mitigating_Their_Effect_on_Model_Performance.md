# LLMs 的表现是否被低估？检测标签错误并减少其对模型性能的影响

发布时间：2024年10月24日

`LLM应用

解释：这篇论文主要讨论了如何利用大型语言模型（LLMs）来增强注释过程，特别是在检测现有数据集中的标签错误方面。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `基准测试`

> Are LLMs Better than Reported? Detecting Label Errors and Mitigating Their Effect on Model Performance

# 摘要

> NLP 基准测试依赖标准化数据集来训练和评估模型，这对推动领域发展至关重要。传统上，专家注释确保了高质量的标签，但其成本难以应对现代模型对更大数据集的需求。众包虽提供了更具扩展性的解决方案，但往往以牺牲注释精度和一致性为代价。最近，大型语言模型（LLMs）的进展为增强注释过程提供了新机遇，特别是在检测现有数据集中的标签错误方面。本研究采用 LLM-as-a-judge 方法，利用一组 LLMs 标记可能错误的示例。通过对 TRUE 基准测试中四个数据集的案例研究，我们实证分析了现有数据集的标签质量，并比较了专家、众包和基于 LLM 的注释在一致性、标签质量和效率上的表现，揭示了每种方法的优劣。研究发现，大量标签错误被纠正后，模型性能显著提升，表明许多所谓的 LLM 错误实为标签错误而非模型失败。此外，我们探讨了错误标记数据的影响，并提出了在训练中减轻这些错误以提升模型性能的方法。

> NLP benchmarks rely on standardized datasets for training and evaluating models and are crucial for advancing the field. Traditionally, expert annotations ensure high-quality labels; however, the cost of expert annotation does not scale well with the growing demand for larger datasets required by modern models. While crowd-sourcing provides a more scalable solution, it often comes at the expense of annotation precision and consistency. Recent advancements in large language models (LLMs) offer new opportunities to enhance the annotation process, particularly for detecting label errors in existing datasets. In this work, we consider the recent approach of LLM-as-a-judge, leveraging an ensemble of LLMs to flag potentially mislabeled examples. Through a case study of four datasets from the TRUE benchmark, covering different tasks and domains, we empirically analyze the labeling quality of existing datasets, and compare expert, crowd-sourced, and our LLM-based annotations in terms of agreement, label quality, and efficiency, demonstrating the strengths and limitations of each annotation method. Our findings reveal a substantial number of label errors, which, when corrected, induce a significant upward shift in reported model performance. This suggests that many of the LLMs so-called mistakes are due to label errors rather than genuine model failures. Additionally, we discuss the implications of mislabeled data and propose methods to mitigate them in training to improve model performance.

[Arxiv](https://arxiv.org/abs/2410.18889)