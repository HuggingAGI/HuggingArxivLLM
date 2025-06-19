# # 基于结构化指令的图表转代码生成迭代优化方法

发布时间：2025年06月15日

`LLM应用` `软件开发` `数据可视化`

> Improved Iterative Refinement for Chart-to-Code Generation via Structured Instruction

# 摘要

> 近年来，多模态大型语言模型（MLLMs）因其强大的视觉理解能力，吸引了越来越多的研究关注。尽管它们在各类视觉任务中表现优异，但在图表转代码生成任务上仍有提升空间。该任务要求MLLMs生成可执行代码以复现给定图表，不仅需要精准的视觉理解，还需将视觉元素准确转化为结构化代码。直接指示MLLMs完成这一复杂任务往往效果不佳。为应对这一挑战，我们提出了{ChartIR}，一种基于结构化指令的迭代优化方法。首先，我们将任务分为两部分：视觉理解和代码转换。为完成视觉理解部分，我们设计了两类结构化指令：描述和差异。描述指令捕捉参考图表的视觉元素，而差异指令则刻画参考图表与生成图表之间的差异。这些指令有效将视觉特征转化为语言表示，从而促进后续代码转换过程。其次，我们将整体图表生成流程分解为两个阶段：初始代码生成和迭代优化，从而逐步提升最终输出质量。实验结果表明，与其它方法相比，我们的方法在开源模型Qwen2-VL和闭源模型GPT-4o上均实现了更优性能。

> Recently, multimodal large language models (MLLMs) have attracted increasing research attention due to their powerful visual understanding capabilities. While they have achieved impressive results on various vision tasks, their performance on chart-to-code generation remains suboptimal. This task requires MLLMs to generate executable code that can reproduce a given chart, demanding not only precise visual understanding but also accurate translation of visual elements into structured code. Directly prompting MLLMs to perform this complex task often yields unsatisfactory results. To address this challenge, we propose {ChartIR}, an iterative refinement method based on structured instruction. First, we distinguish two tasks: visual understanding and code translation. To accomplish the visual understanding component, we design two types of structured instructions: description and difference. The description instruction captures the visual elements of the reference chart, while the difference instruction characterizes the discrepancies between the reference chart and the generated chart. These instructions effectively transform visual features into language representations, thereby facilitating the subsequent code translation process. Second, we decompose the overall chart generation pipeline into two stages: initial code generation and iterative refinement, enabling progressive enhancement of the final output. Experimental results show that, compared to other method, our method achieves superior performance on both the open-source model Qwen2-VL and the closed-source model GPT-4o.

[Arxiv](https://arxiv.org/abs/2506.14837)