# LLMs 的密集法则

发布时间：2024年12月05日

`LLM理论` `人工智能` `语言模型`

> Densing Law of LLMs

# 摘要

> 大型语言模型（LLMs）已然成为人工智能领域的一座里程碑，其性能会随着模型规模的增大而提升。然而，这种规模的扩张给训练和推理效率带来巨大挑战，尤其是在资源受限的环境中部署 LLMs 时，而且这种扩张趋势愈发难以持续。本文引入“容量密度”这一概念作为新的衡量指标，用于评估不同规模的 LLMs 的质量，并从有效性和效率方面阐述 LLMs 的发展趋势。为计算给定目标 LLMs 的容量密度，我们先引入一组参考模型，并制定一种缩放定律，依据其参数大小预测这些参考模型的下游性能。接着，我们把目标 LLMs 的“有效参数大小”定义为参考模型达成同等性能所需的参数大小，并将容量密度定义为目标 LLMs 的有效参数大小与实际参数大小的比值。容量密度为评估模型的有效性和效率提供了统一框架。我们对近期开源基础 LLMs 的进一步分析揭示出一条经验定律（密集定律），即 LLMs 的容量密度随时间呈指数增长。更确切地说，通过一些广泛使用的基准进行评估，LLMs 的容量密度大约每三个月就会翻倍。该定律为未来 LLMs 的发展提供了新的视角，强调了提高容量密度以用最少的计算开销实现最佳结果的重要性。

> Large Language Models (LLMs) have emerged as a milestone in artificial intelligence, and their performance can improve as the model size increases. However, this scaling brings great challenges to training and inference efficiency, particularly for deploying LLMs in resource-constrained environments, and the scaling trend is becoming increasingly unsustainable. This paper introduces the concept of ``\textit{capacity density}'' as a new metric to evaluate the quality of the LLMs across different scales and describes the trend of LLMs in terms of both effectiveness and efficiency. To calculate the capacity density of a given target LLM, we first introduce a set of reference models and develop a scaling law to predict the downstream performance of these reference models based on their parameter sizes. We then define the \textit{effective parameter size} of the target LLM as the parameter size required by a reference model to achieve equivalent performance, and formalize the capacity density as the ratio of the effective parameter size to the actual parameter size of the target LLM. Capacity density provides a unified framework for assessing both model effectiveness and efficiency. Our further analysis of recent open-source base LLMs reveals an empirical law (the densing law)that the capacity density of LLMs grows exponentially over time. More specifically, using some widely used benchmarks for evaluation, the capacity density of LLMs doubles approximately every three months. The law provides new perspectives to guide future LLM development, emphasizing the importance of improving capacity density to achieve optimal results with minimal computational overhead.

[Arxiv](https://arxiv.org/abs/2412.04315)