# SheetDesigner：MLLM驱动的融合规则与视觉双驱动反思的电子表格布局生成

发布时间：2025年09月09日

`LLM应用` `工业与制造`

> SheetDesigner: MLLM-Powered Spreadsheet Layout Generation with Rule-Based and Vision-Based Reflection

# 摘要

> 电子表格是数据类任务的核心工具，凭借丰富的结构化布局实现高效信息传递。手动设计表格布局耗时且对专业能力要求高，因此自动化方案的需求日益迫切。但现有自动化布局模型并不适用于电子表格，主要问题在于：（1）将组件视为带连续坐标的轴对齐矩形，忽略了表格固有的离散网格结构；（2）忽视了表格特有的关联语义，如数据依赖和上下文链接。本文中，我们首先形式化定义了电子表格布局生成任务，并构建了七项评估标准协议与包含3,326个表格的数据集作为支撑。随后，我们提出SheetDesigner——一款基于多模态大型语言模型（MLLMs）的零样本免训练框架，通过融合规则逻辑与视觉反思实现组件布局与内容填充。在五项基线测试中，SheetDesigner性能提升至少22.6%。我们还发现，借助视觉模态，MLLMs擅长处理重叠与平衡问题，却在对齐上表现不佳，因此需采用规则与视觉反思混合策略。相关代码与数据已开源至Github。

> Spreadsheets are critical to data-centric tasks, with rich, structured layouts that enable efficient information transmission. Given the time and expertise required for manual spreadsheet layout design, there is an urgent need for automated solutions. However, existing automated layout models are ill-suited to spreadsheets, as they often (1) treat components as axis-aligned rectangles with continuous coordinates, overlooking the inherently discrete, grid-based structure of spreadsheets; and (2) neglect interrelated semantics, such as data dependencies and contextual links, unique to spreadsheets. In this paper, we first formalize the spreadsheet layout generation task, supported by a seven-criterion evaluation protocol and a dataset of 3,326 spreadsheets. We then introduce SheetDesigner, a zero-shot and training-free framework using Multimodal Large Language Models (MLLMs) that combines rule and vision reflection for component placement and content population. SheetDesigner outperforms five baselines by at least 22.6\%. We further find that through vision modality, MLLMs handle overlap and balance well but struggle with alignment, necessitates hybrid rule and visual reflection strategies. Our codes and data is available at Github.

[Arxiv](https://arxiv.org/abs/2509.07473)