# 结合文本与视觉数据增强大型语言模型，实现全球地理空间数据的对话式可视化

发布时间：2025年01月16日

`LLM应用

理由：该论文提出了一种通过融合文本和视觉数据来增强大型语言模型（LLM）的方法，使其能够在科学数据可视化中实现精准问答。这属于LLM在实际应用中的改进和扩展，因此归类为LLM应用。` `数据可视化`

> Augmenting a Large Language Model with a Combination of Text and Visual Data for Conversational Visualization of Global Geospatial Data

# 摘要

> 我们提出了一种方法，通过融合文本和视觉数据来增强大型语言模型（LLM），使其能够在科学数据可视化中实现精准问答，从而开启对话式可视化的大门。LLM在处理视觉数据交互等任务时往往力不从心，因为它们缺乏上下文视觉信息。为此，我们将可视化和数据集的文本描述与可视化快照相结合，提取其核心特征并生成高度紧凑且描述性强的结构化文本文件，从而在不进行微调的情况下，为LLM提供丰富的上下文信息。该方法适用于任何已渲染完成且附带文本描述的可视化。

> We present a method for augmenting a Large Language Model (LLM) with a combination of text and visual data to enable accurate question answering in visualization of scientific data, making conversational visualization possible. LLMs struggle with tasks like visual data interaction, as they lack contextual visual information. We address this problem by merging a text description of a visualization and dataset with snapshots of the visualization. We extract their essential features into a structured text file, highly compact, yet descriptive enough to appropriately augment the LLM with contextual information, without any fine-tuning. This approach can be applied to any visualization that is already finally rendered, as long as it is associated with some textual description.

[Arxiv](https://arxiv.org/abs/2501.09521)