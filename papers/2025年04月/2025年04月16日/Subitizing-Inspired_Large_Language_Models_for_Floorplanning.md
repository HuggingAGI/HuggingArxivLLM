# 受快速感知启发的大型语言模型在布局规划中的应用

发布时间：2025年04月16日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在布局规划问题中的应用，特别是在VLSI设计中的潜力。通过微调LLMs来模拟人类快速计数和排列物品的能力，展示了LLMs在实际优化任务中的有效性。因此，它属于LLM应用类别。` `电子设计自动化` `布局规划`

> Subitizing-Inspired_Large_Language_Models_for_Floorplanning

# 摘要

> 我们提出了一种利用微调后的大型语言模型（LLMs）解决布局规划问题的新方法。受人类“亚itize”能力——即快速准确计数少量物品的能力——的启发，我们推测LLMs也能像人类一样快速且准确地解决布局规划问题。我们提出了一种高效的布局规划问题表示方法，并引入了一种生成适用于模型微调的高质量数据集的方法。我们对具有指定模块数量的数据集进行LLMs微调，以测试LLMs是否能模拟人类快速计数和排列物品的能力。实验结果表明，微调后的LLMs，尤其是GPT4o-mini，在成功率和优化率方面表现出色，同时平均死空间相对较低。这些发现凸显了LLMs作为VLSI设计中复杂优化任务有前途解决方案的潜力。

> We present a novel approach to solving the floorplanning problem by leveraging fine-tuned Large Language Models (LLMs). Inspired by subitizing--the human ability to instantly and accurately count small numbers of items at a glance--we hypothesize that LLMs can similarly address floorplanning challenges swiftly and accurately. We propose an efficient representation of the floorplanning problem and introduce a method for generating high-quality datasets tailored for model fine-tuning. We fine-tune LLMs on datasets with a specified number of modules to test whether LLMs can emulate the human ability to quickly count and arrange items. Our experimental results demonstrate that fine-tuned LLMs, particularly GPT4o-mini, achieve high success and optimal rates while attaining relatively low average dead space. These findings underscore the potential of LLMs as promising solutions for complex optimization tasks in VLSI design.

[Arxiv](https://arxiv.org/abs/2504.12076)