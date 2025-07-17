# MapIQ：多模态大语言模型的地图问答基准评测

发布时间：2025年07月15日

`LLM应用` `社会科学`

> MapIQ: Benchmarking Multimodal Large Language Models for Map Question Answering

# 摘要

> 多模态大型语言模型（MLLMs）的近期突破性进展激发了研究者探索这些模型解读数据可视化（如柱状图、散点图）的能力。研究焦点逐渐转向地图问答（Map-VQA），但现有研究主要局限于渐层填充地图，这类地图在主题类别和视觉分析任务上的覆盖范围有限。为填补这一研究空白，我们推出了MapIQ基准数据集，包含14,706个问答对，涵盖渐层填充地图、卡图和比例符号地图三种类型，主题涉及住房、犯罪等六个领域。通过六项视觉分析任务评估了多个MLLMs的表现，并与人类基线进行对比。此外，我们还研究了地图设计变更（如颜色方案调整、图例设计修改、地图元素移除）对MLLMs的影响，以此探讨其鲁棒性、敏感性、对内部地理知识的依赖性，以及提升Map-VQA性能的潜在途径。

> Recent advancements in multimodal large language models (MLLMs) have driven researchers to explore how well these models read data visualizations, e.g., bar charts, scatter plots. More recently, attention has shifted to visual question answering with maps (Map-VQA). However, Map-VQA research has primarily focused on choropleth maps, which cover only a limited range of thematic categories and visual analytical tasks. To address these gaps, we introduce MapIQ, a benchmark dataset comprising 14,706 question-answer pairs across three map types: choropleth maps, cartograms, and proportional symbol maps spanning topics from six distinct themes (e.g., housing, crime). We evaluate multiple MLLMs using six visual analytical tasks, comparing their performance against one another and a human baseline. An additional experiment examining the impact of map design changes (e.g., altered color schemes, modified legend designs, and removal of map elements) provides insights into the robustness and sensitivity of MLLMs, their reliance on internal geographic knowledge, and potential avenues for improving Map-VQA performance.

[Arxiv](https://arxiv.org/abs/2507.11625)