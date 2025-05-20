# TIME：一个多层级基准测试，针对大型语言模型在现实场景中的时间推理能力进行全面评估。

发布时间：2025年05月19日

`LLM应用

理由：这篇论文专注于大型语言模型的时间推理能力，提出了一个基准测试来评估和提升模型在时间推理方面的性能，属于LLM的应用研究。` `时间推理` `信息抽取`

> TIME: A Multi-level Benchmark for Temporal Reasoning of LLMs in Real-World Scenarios

# 摘要

> 时间推理对于大型语言模型理解现实世界至关重要，然而现有工作忽视了时间推理在现实世界中的三大挑战：强烈的时间信息、快速变化的事件动态以及社交互动中的复杂时间依赖关系。为填补这一空白，我们提出了一个多层级基准测试TIME，专为现实场景中的时间推理设计。TIME包含38,522个问答对，涵盖3个层次和11个细粒度子任务，并包含3个子数据集，分别对应不同的现实挑战：TIME-Wiki、TIME-News和TIME-Dial。我们在推理模型和非推理模型上进行了大量实验，深入分析了不同现实场景和任务中的时间推理性能，揭示了测试时间缩放对时间推理能力的影响。此外，我们发布了TIME-Lite，一个用于促进未来研究和标准化评估的时间推理人工标注子集。代码和数据集分别可在https://github.com/sylvain-wei/TIME和https://huggingface.co/datasets/SylvainWei/TIME获取。


> Temporal reasoning is pivotal for Large Language Models (LLMs) to comprehend the real world. However, existing works neglect the real-world challenges for temporal reasoning: (1) intensive temporal information, (2) fast-changing event dynamics, and (3) complex temporal dependencies in social interactions. To bridge this gap, we propose a multi-level benchmark TIME, designed for temporal reasoning in real-world scenarios. TIME consists of 38,522 QA pairs, covering 3 levels with 11 fine-grained sub-tasks. This benchmark encompasses 3 sub-datasets reflecting different real-world challenges: TIME-Wiki, TIME-News, and TIME-Dial. We conduct extensive experiments on reasoning models and non-reasoning models. And we conducted an in-depth analysis of temporal reasoning performance across diverse real-world scenarios and tasks, and summarized the impact of test-time scaling on temporal reasoning capabilities. Additionally, we release TIME-Lite, a human-annotated subset to foster future research and standardized evaluation in temporal reasoning. The code is available at https://github.com/sylvain-wei/TIME , and the dataset is available at https://huggingface.co/datasets/SylvainWei/TIME .

[Arxiv](https://arxiv.org/abs/2505.12891)