# ACCESS：用于评估抽象因果事件发现与推理能力的基准测试

发布时间：2025年02月12日

`LLM应用` `因果推理`

> ACCESS : A Benchmark for Abstract Causal Event Discovery and Reasoning

# 摘要

> 因果关系的识别是理解现实世界动态和因果推理的关键。现有的NLP因果事件识别方法，包括基于大型语言模型（LLMs）的方法，在处理分布外场景时都面临困难，这主要是因为现有基准的规模有限且高度依赖词汇线索。受概率因果推断启发，现代基准试图通过构建事件因果图来表示稳健的因果知识，其中	exttt{CRAB} \citep{romanou2023crab}是沿此方向的近期基准之一。本文中，我们介绍了	exttt{ACCESS}，这是一个专注于发现和推理抽象因果事件的基准。与现有资源不同，	exttt{ACCESS}聚焦于日常生活事件的抽象层面因果关系。我们提出了一种从大规模隐式常识因果知识数据集	exttt{GLUCOSE} \citep{mostafazadeh-etal-2020-glucose}中识别事件泛化抽象的流水线，并从中提取了【数学公式】因果对。我们的实验凸显了在NLP中使用统计方法和/或LLMs进行自动抽象识别和因果发现的持续挑战。尽管如此，我们证明	exttt{ACCESS}中提供的抽象因果知识可用于提升LLMs的问答推理性能。

> Identifying cause-and-effect relationships is critical to understanding real-world dynamics and ultimately causal reasoning. Existing methods for identifying event causality in NLP, including those based on Large Language Models (LLMs), exhibit difficulties in out-of-distribution settings due to the limited scale and heavy reliance on lexical cues within available benchmarks. Modern benchmarks, inspired by probabilistic causal inference, have attempted to construct causal graphs of events as a robust representation of causal knowledge, where \texttt{CRAB} \citep{romanou2023crab} is one such recent benchmark along this line. In this paper, we introduce \texttt{ACCESS}, a benchmark designed for discovery and reasoning over abstract causal events. Unlike existing resources, \texttt{ACCESS} focuses on causality of everyday life events on the abstraction level. We propose a pipeline for identifying abstractions for event generalizations from \texttt{GLUCOSE} \citep{mostafazadeh-etal-2020-glucose}, a large-scale dataset of implicit commonsense causal knowledge, from which we subsequently extract $1,4$K causal pairs. Our experiments highlight the ongoing challenges of using statistical methods and/or LLMs for automatic abstraction identification and causal discovery in NLP. Nonetheless, we demonstrate that the abstract causal knowledge provided in \texttt{ACCESS} can be leveraged for enhancing QA reasoning performance in LLMs.

[Arxiv](https://arxiv.org/abs/2502.08148)