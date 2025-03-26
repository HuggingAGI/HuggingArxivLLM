# GeoBenchX：多步骤地理空间任务的LLMs基准测试

发布时间：2025年03月23日

`LLM应用

摘要中提到的论文评估了大型语言模型在地理空间任务中的应用，探讨了模型的表现和基准测试，属于LLM的应用领域。` `地理信息`

> GeoBenchX: Benchmarking LLMs for Multistep Geospatial Tasks

# 摘要

> 本文建立了一个基准测试，用于评估大型语言模型（LLMs）在与商业GIS从业者相关的多步骤地理空间任务中的表现。我们使用一个配备23个地理空间函数的工具调用代理，对七款主流商业LLM（包括Sonnet 3.5和3.7、Haiku 3.5、Gemini 2.0、GPT-4o、GPT-4o mini以及o3-mini）进行了评估。基准测试任务分为四个复杂度递增的类别，包含可解决和故意不可解决的任务，以测试模型的幻觉抑制能力。我们开发了一个LLM-as-Judge评估框架，用于比较代理解决方案与参考实现。结果显示，Sonnet 3.5和GPT-4o在整体性能上表现最佳，Claude模型在可解决任务上表现出色，而OpenAI模型在识别不可解决场景方面更为出色。我们观察到代币使用量存在显著差异，其中Anthropic模型的代币消耗量远高于其他模型。常见错误包括几何关系理解错误、依赖过时知识以及数据操作效率低下。此次基准测试集、评估框架和数据生成管道已作为开源资源发布，为持续评估LLMs在GeoAI领域的应用提供了又一标准化方法。

> In this paper, we establish a benchmark for evaluating large language models (LLMs) on multi-step geospatial tasks relevant to commercial GIS practitioners. We assess seven leading commercial LLMs (Sonnet 3.5 and 3.7, Haiku 3.5, Gemini 2.0, GPT-4o, GPT-4o mini, and o3-mini) using a simple tool-calling agent equipped with 23 geospatial functions. Our benchmark comprises tasks across four categories of increasing complexity, with both solvable and intentionally unsolvable tasks to test hallucination rejection. We develop an LLM-as-Judge evaluation framework to compare agent solutions against reference implementations. Results show Sonnet 3.5 and GPT-4o achieve the best overall performance, with Claude models excelling on solvable tasks while OpenAI models better identify unsolvable scenarios. We observe significant differences in token usage, with Anthropic models consuming substantially more tokens than competitors. Common errors include misunderstanding geometrical relationships, relying on outdated knowledge, and inefficient data manipulation. The resulting benchmark set, evaluation framework, and data generation pipeline are released as open-source resources, providing one more standardized method for ongoing evaluation of LLMs for GeoAI.

[Arxiv](https://arxiv.org/abs/2503.18129)