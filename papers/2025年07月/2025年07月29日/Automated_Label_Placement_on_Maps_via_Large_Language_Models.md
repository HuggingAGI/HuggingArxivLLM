# 利用大型语言模型实现地图标签的自动化放置

发布时间：2025年07月29日

`LLM应用` `地图设计` `地理信息系统`

> Automated Label Placement on Maps via Large Language Models

# 摘要

> 标注放置是地图设计的重要组成部分，作为空间注释的一种形式，直接影响地图的清晰度和可解读性。尽管标注放置至关重要，但目前仍主要依赖人工操作，难以实现规模化应用，因为现有的自动化系统难以整合制图规范、适应上下文或解读标注指令。在这项研究中，我们提出了一种新的自动标注放置（ALP）范式，将标注放置任务转化为数据编辑问题，并利用大型语言模型（LLMs）实现上下文感知的空间注释。为了支持这一研究方向，我们整理了MAPLE，这是首个已知的基准数据集，用于在真实地图上评估ALP性能，涵盖了多种地标类型和标注放置注释，数据来源于开源数据。我们的方法通过检索增强生成（RAG）检索与每种地标类型相关的标注指南，并将这些指南整合到提示中，然后使用经过指令微调的LLMs生成理想的标注坐标。我们在MAPLE上评估了四个开源LLMs，分析了它们的整体性能以及在不同地标类型上的泛化能力，包括零样本和指令微调性能。实验结果表明，当LLMs在结构化提示和领域特定检索的指导下，能够学习执行准确的空间编辑，使生成的输出与专家制图标准相一致。总体而言，我们的工作为AI辅助地图制作提供了一个可扩展的框架，并展示了基础模型在结构化数据编辑任务中的潜力。代码和数据可在https://github.com/HarryShomer/MAPLE获取。

> Label placement is a critical aspect of map design, serving as a form of spatial annotation that directly impacts clarity and interpretability. Despite its importance, label placement remains largely manual and difficult to scale, as existing automated systems struggle to integrate cartographic conventions, adapt to context, or interpret labeling instructions. In this work, we introduce a new paradigm for automatic label placement (ALP) that formulates the task as a data editing problem and leverages large language models (LLMs) for context-aware spatial annotation. To support this direction, we curate MAPLE, the first known benchmarking dataset for evaluating ALP on real-world maps, encompassing diverse landmark types and label placement annotations from open-source data. Our method retrieves labeling guidelines relevant to each landmark type leveraging retrieval-augmented generation (RAG), integrates them into prompts, and employs instruction-tuned LLMs to generate ideal label coordinates. We evaluate four open-source LLMs on MAPLE, analyzing both overall performance and generalization across different types of landmarks. This includes both zero-shot and instruction-tuned performance. Our results demonstrate that LLMs, when guided by structured prompts and domain-specific retrieval, can learn to perform accurate spatial edits, aligning the generated outputs with expert cartographic standards. Overall, our work presents a scalable framework for AI-assisted map finishing and demonstrates the potential of foundation models in structured data editing tasks. The code and data can be found at https://github.com/HarryShomer/MAPLE.

[Arxiv](https://arxiv.org/abs/2507.22952)