# SeriesBench：评估叙事驱动电视剧理解能力的基准测试

发布时间：2025年04月30日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）在视频叙事理解中的应用，提出了新的基准测试和框架，属于LLM的应用研究。` `视频理解` `叙事理解`

> SeriesBench: A Benchmark for Narrative-Driven Drama Series Understanding

# 摘要

> 多模态大型语言模型（MLLMs）的快速发展催生了许多评估视频理解能力的基准测试。然而，这些测试主要针对独立视频片段，侧重于评估视觉元素，如人类动作和物体状态。现实中，当代视频往往以系列形式呈现，包含复杂且连续的叙事。为此，我们提出了**SeriesBench**，一个包含105个叙事驱动系列的基准测试，涵盖28个需要深入理解叙事的任务。我们从多种类型的剧集中精选了一系列剧集，并采用创新的长跨度叙事标注方法，结合全信息转换技术，将人工标注转化为多样化的任务格式。为了提升模型对系列中情节结构和角色关系的分析能力，我们开发了**PC-DCoT**叙事推理框架。实验结果表明，现有MLLMs在理解叙事驱动系列方面仍具挑战，而**PC-DCoT**能够显著提升其性能。我们的**SeriesBench**和**PC-DCoT**凸显了提升模型叙事理解能力的重要性，为MLLMs的未来发展提供了方向。**SeriesBench**现已公开，访问地址为https://github.com/zackhxn/SeriesBench-CVPR2025。

> With the rapid development of Multi-modal Large Language Models (MLLMs), an increasing number of benchmarks have been established to evaluate the video understanding capabilities of these models. However, these benchmarks focus on \textbf{standalone} videos and mainly assess ``visual elements'' like human actions and object states. In reality, contemporary videos often encompass complex and continuous narratives, typically presented as a \textbf{series}. To address this challenge, we propose \textbf{SeriesBench}, a benchmark consisting of 105 carefully curated narrative-driven series, covering 28 specialized tasks that require deep narrative understanding. Specifically, we first select a diverse set of drama series spanning various genres. Then, we introduce a novel long-span narrative annotation method, combined with a full-information transformation approach to convert manual annotations into diverse task formats. To further enhance model capacity for detailed analysis of plot structures and character relationships within series, we propose a novel narrative reasoning framework, \textbf{PC-DCoT}. Extensive results on \textbf{SeriesBench} indicate that existing MLLMs still face significant challenges in understanding narrative-driven series, while \textbf{PC-DCoT} enables these MLLMs to achieve performance improvements. Overall, our \textbf{SeriesBench} and \textbf{PC-DCoT} highlight the critical necessity of advancing model capabilities to understand narrative-driven series, guiding the future development of MLLMs. SeriesBench is publicly available at https://github.com/zackhxn/SeriesBench-CVPR2025.

[Arxiv](https://arxiv.org/abs/2504.21435)