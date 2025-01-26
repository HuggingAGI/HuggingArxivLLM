# 大型语言模型是否真正理解几何结构？

发布时间：2025年01月23日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLMs）在几何理解能力上的表现，并提出了一个新的数据集（GeomRel）和一种新的方法（几何思维链，GeoCoT）来评估和提升LLMs的几何理解能力。这涉及到对LLMs的理论理解和改进，因此属于LLM理论分类。` `人工智能`

> Do Large Language Models Truly Understand Geometric Structures?

# 摘要

> 几何能力是LLMs的一大挑战，因为它需要高级的空间理解和抽象思维。现有数据集主要评估LLMs的最终答案，但无法真正衡量其对几何结构的理解，因为LLMs可能通过巧合得出正确答案。为此，我们推出了GeomRel数据集，通过隔离几何关系识别的核心步骤来评估LLMs的几何理解能力。基于这一基准，我们对多种LLMs进行了全面评估，并发现了其在理解几何结构上的关键局限。我们还提出了几何思维链（GeoCoT）方法，显著提升了LLMs识别几何关系的能力，从而大幅提高了性能。

> Geometric ability is a significant challenge for large language models (LLMs) due to the need for advanced spatial comprehension and abstract thinking. Existing datasets primarily evaluate LLMs on their final answers, but they cannot truly measure their true understanding of geometric structures, as LLMs can arrive at correct answers by coincidence. To fill this gap, we introduce the GeomRel dataset, designed to evaluate LLMs' understanding of geometric structures by isolating the core step of geometric relationship identification in problem-solving. Using this benchmark, we conduct thorough evaluations of diverse LLMs and identify key limitations in understanding geometric structures. We further propose the Geometry Chain-of-Thought (GeoCoT) method, which enhances LLMs' ability to identify geometric relationships, resulting in significant performance improvements.

[Arxiv](https://arxiv.org/abs/2501.13773)