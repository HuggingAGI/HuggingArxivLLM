# SCBench：专为视频大型语言模型设立的体育评论基准

发布时间：2024年12月23日

`LLM应用` `视频处理`

> SCBench: A Sports Commentary Benchmark for Video LLMs

# 摘要

> 近来，在学术和工业领域，视频大型语言模型（Video LLMs）均取得了重大进展。然而，评估和衡量不同视频大型语言模型性能的方法，尤其是其细粒度、时间性的视觉能力方面，仍极为有限。一方面，当前的基准测试采用相对简单的视频（如带字幕的电影片段），模型仅处理几个帧就能理解整个视频。另一方面，其数据集在任务格式上缺乏多样性，仅包含问答或多项选择问答，忽略了模型生成深入且精确文本的能力。具有复杂视觉信息、连续事件和饱含情感评论的体育视频，给视频大型语言模型带来了关键挑战，使体育评论成为理想的基准测试任务。受这些挑战启发，我们提出了新任务：体育视频评论生成，并为视频大型语言模型开发了$	extbf{SCBench}$。为构建此基准，我们引入了（1）$	extbf{SCORES}$，一个专为该任务设计的六维指标，在此基础上提出了基于 GPT 的评估方法，以及（2）$	extbf{CommentarySet}$，一个由 5775 个带注释的视频片段和针对该指标的真实标签组成的数据集。基于 SCBench，我们对多个视频大型语言模型（如 VILA、Video-LLaVA 等）和思维链基线方法进行了全面评估。结果发现，InternVL-Chat-2 以 5.44 的成绩表现最佳，比第二名高出 1.04。我们的工作为未来研究提供了新视角，旨在提升模型在复杂视觉理解任务中的整体能力。我们的数据集即将发布。

> Recently, significant advances have been made in Video Large Language Models (Video LLMs) in both academia and industry. However, methods to evaluate and benchmark the performance of different Video LLMs, especially their fine-grained, temporal visual capabilities, remain very limited. On one hand, current benchmarks use relatively simple videos (e.g., subtitled movie clips) where the model can understand the entire video by processing just a few frames. On the other hand, their datasets lack diversity in task format, comprising only QA or multi-choice QA, which overlooks the models' capacity for generating in-depth and precise texts. Sports videos, which feature intricate visual information, sequential events, and emotionally charged commentary, present a critical challenge for Video LLMs, making sports commentary an ideal benchmarking task. Inspired by these challenges, we propose a novel task: sports video commentary generation, developed $\textbf{SCBench}$ for Video LLMs. To construct such a benchmark, we introduce (1) $\textbf{SCORES}$, a six-dimensional metric specifically designed for our task, upon which we propose a GPT-based evaluation method, and (2) $\textbf{CommentarySet}$, a dataset consisting of 5,775 annotated video clips and ground-truth labels tailored to our metric. Based on SCBench, we conduct comprehensive evaluations on multiple Video LLMs (e.g. VILA, Video-LLaVA, etc.) and chain-of-thought baseline methods. Our results found that InternVL-Chat-2 achieves the best performance with 5.44, surpassing the second-best by 1.04. Our work provides a fresh perspective for future research, aiming to enhance models' overall capabilities in complex visual understanding tasks. Our dataset will be released soon.

[Arxiv](https://arxiv.org/abs/2412.17637)