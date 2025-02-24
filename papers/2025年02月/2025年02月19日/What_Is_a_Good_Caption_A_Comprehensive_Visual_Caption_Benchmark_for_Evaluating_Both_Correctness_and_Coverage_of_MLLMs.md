# 什么样的图像描述才算好？一个综合性的视觉描述基准，用于衡量多模态大语言模型的正确性和覆盖范围

发布时间：2025年02月19日

`LLM应用

理由：这篇论文讨论了多模态大语言模型（MLLMs）在视觉描述任务中的应用，介绍了新的基准测试框架CV-CapBench，并评估了模型在不同维度的表现。这属于大语言模型在具体任务中的应用和评估，因此归类为LLM应用。` `计算机视觉`

> What Is a Good Caption? A Comprehensive Visual Caption Benchmark for Evaluating Both Correctness and Coverage of MLLMs

# 摘要

> 多模态大语言模型（MLLMs）的最新进展使传统视觉描述基准相形见绌，因为它们主要依赖过时指标评估简短描述。尽管近期基准通过分解视觉元素并采用模型评估方法改进了评估，但它们仍不完整——忽视关键方面，提供模糊且无解释的评分。为此，我们推出CV-CapBench，这是一个全面的视觉描述基准，从6个视角和13个维度系统性评估描述质量。CV-CapBench为每个维度引入精确率、召回率和命中率指标，独特地评估描述的准确性和覆盖范围。在领先MLLMs上的实验揭示了显著能力差距，特别是在动态和知识密集型维度。这些发现为未来研究提供了可操作的见解。代码和数据即将开放。

> Recent advancements in Multimodal Large Language Models (MLLMs) have rendered traditional visual captioning benchmarks obsolete, as they primarily evaluate short descriptions with outdated metrics. While recent benchmarks address these limitations by decomposing captions into visual elements and adopting model-based evaluation, they remain incomplete-overlooking critical aspects, while providing vague, non-explanatory scores. To bridge this gap, we propose CV-CapBench, a Comprehensive Visual Caption Benchmark that systematically evaluates caption quality across 6 views and 13 dimensions. CV-CapBench introduces precision, recall, and hit rate metrics for each dimension, uniquely assessing both correctness and coverage. Experiments on leading MLLMs reveal significant capability gaps, particularly in dynamic and knowledge-intensive dimensions. These findings provide actionable insights for future research. The code and data will be released.

[Arxiv](https://arxiv.org/abs/2502.14914)