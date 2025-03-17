# 理解大型多模态模型中的图形感知

发布时间：2025年03月13日

`LLM应用` `多模态模型` `信息图表`

> Towards Understanding Graphical Perception in Large Multimodal Models

# 摘要

> 尽管大型多模态模型（LMMs）在复杂视觉语言任务中表现优异，但我们在研究中发现，这些模型在处理仅需感知能力的简单信息图任务时却表现不佳。现有基准主要关注需要多种能力的最终任务，对模型感知能力的局限性缺乏细致的洞察。为弥补这一研究空白，我们基于图形感知理论，开发了一个评估框架，用于分析LMMs在图表中的感知能力差距。该框架通过自动化任务生成和响应评估设计，能够全面且有控制地测试LMMs在各种图表类型、视觉元素和任务类型中的图形感知能力。我们利用这一框架，深入评估和诊断了最先进LMMs的感知能力，分别从图表、视觉元素和像素三个粒度级别进行研究。研究结果揭示了当前LMMs（包括GPT-4o）的三大关键局限：跨图表类型泛化能力不足、难以理解基础视觉元素、以及无法在图表内进行值的交叉引用。这些发现为未来提升LMMs的感知能力提供了重要指导。我们的评估框架和标注数据已在GitHub上公开发布，欢迎访问https://github.com/microsoft/lmm-graphical-perception了解详情。

> Despite the promising results of large multimodal models (LMMs) in complex vision-language tasks that require knowledge, reasoning, and perception abilities together, we surprisingly found that these models struggle with simple tasks on infographics that require perception only. As existing benchmarks primarily focus on end tasks that require various abilities, they provide limited, fine-grained insights into the limitations of the models' perception abilities. To address this gap, we leverage the theory of graphical perception, an approach used to study how humans decode visual information encoded on charts and graphs, to develop an evaluation framework for analyzing gaps in LMMs' perception abilities in charts. With automated task generation and response evaluation designs, our framework enables comprehensive and controlled testing of LMMs' graphical perception across diverse chart types, visual elements, and task types. We apply our framework to evaluate and diagnose the perception capabilities of state-of-the-art LMMs at three granularity levels (chart, visual element, and pixel). Our findings underscore several critical limitations of current state-of-the-art LMMs, including GPT-4o: their inability to (1) generalize across chart types, (2) understand fundamental visual elements, and (3) cross reference values within a chart. These insights provide guidance for future improvements in perception abilities of LMMs. The evaluation framework and labeled data are publicly available at https://github.com/microsoft/lmm-graphical-perception.

[Arxiv](https://arxiv.org/abs/2503.10857)