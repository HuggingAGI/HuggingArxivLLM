# 时间迷航：多模态LLM中的时钟与日历理解难题

发布时间：2025年02月07日

`LLM应用

理由：这篇论文探讨了多模态大语言模型（MLLMs）在处理时间相关视觉数据时的能力，特别是通过模拟时钟和年度日历解析时间与日期。这属于大语言模型在实际应用中的表现和挑战，因此归类为“LLM应用”。` `计算机视觉` `时间解析`

> Lost in Time: Clock and Calendar Understanding Challenges in Multimodal LLMs

# 摘要

> 理解视觉中的时间是一项基本认知技能，但对多模态大语言模型（MLLMs）来说仍具挑战。本研究探讨了MLLMs通过模拟时钟和年度日历来解析时间与日期的能力。为此，我们构建了一个结构化数据集，包含两个子集：1）$	extit{ClockQA}$，涵盖多种时钟样式（如标准、黑盘、无秒针、罗马数字和箭头指针时钟）及其对应的时间相关问题；2）$	extit{CalendarQA}$，包含年度日历图像，问题从常见日期（如圣诞节、元旦）到计算日期（如一年中的第100天或第153天）。我们旨在分析MLLMs在处理时间相关视觉数据时的视觉识别、数值推理和时间推断能力。评估结果显示，尽管技术有所进步，MLLMs在可靠理解时间方面仍面临重大挑战。

> Understanding time from visual representations is a fundamental cognitive skill, yet it remains a challenge for multimodal large language models (MLLMs). In this work, we investigate the capabilities of MLLMs in interpreting time and date through analogue clocks and yearly calendars. To facilitate this, we curated a structured dataset comprising two subsets: 1) $\textit{ClockQA}$, which comprises various types of clock styles$-$standard, black-dial, no-second-hand, Roman numeral, and arrow-hand clocks$-$paired with time related questions; and 2) $\textit{CalendarQA}$, which consists of yearly calendar images with questions ranging from commonly known dates (e.g., Christmas, New Year's Day) to computationally derived ones (e.g., the 100th or 153rd day of the year). We aim to analyse how MLLMs can perform visual recognition, numerical reasoning, and temporal inference when presented with time-related visual data. Our evaluations show that despite recent advancements, reliably understanding time remains a significant challenge for MLLMs.

[Arxiv](https://arxiv.org/abs/2502.05092)