# MarkushGrapher：马库什结构的视觉与文本联合识别

发布时间：2025年03月20日

`LLM应用` `材料科学` `药物开发`

> MarkushGrapher: Joint Visual and Textual Recognition of Markush Structures

# 摘要

> 化学文献的自动化分析有望加速材料科学和药物开发等领域的发现。特别是在专利文件中搜索化学结构和马库什结构（化学结构模板）的能力具有价值，例如用于先期技术搜索。尽管从文本和图像中自动提取化学结构方面已经取得了一些进展，但马库什结构由于其复杂的多模态特性，仍然鲜有研究。在这项工作中，我们提出了MarkushGrapher，这是一种用于识别文档中马库什结构的多模态方法。我们的方法通过Vision-Text-Layout编码器和Optical Chemical Structure Recognition视觉编码器联合编码文本、图像和布局信息。这些表示被合并，并用于自动生成马库什结构的序列图表示以及定义其变量组的表格。为了解决真实世界训练数据的缺乏问题，我们提出了一种合成数据生成管道，能够生成广泛的真实马库什结构。此外，我们提出了M2S，这是第一个标注的现实世界马库什结构基准数据集，以推动这一具有挑战性的任务的研究。广泛的实验表明，我们的方法在大多数评估设置中优于现有的特定于化学和通用的视觉-语言模型。代码、模型和数据集将开放获取。

> The automated analysis of chemical literature holds promise to accelerate discovery in fields such as material science and drug development. In particular, search capabilities for chemical structures and Markush structures (chemical structure templates) within patent documents are valuable, e.g., for prior-art search. Advancements have been made in the automatic extraction of chemical structures from text and images, yet the Markush structures remain largely unexplored due to their complex multi-modal nature. In this work, we present MarkushGrapher, a multi-modal approach for recognizing Markush structures in documents. Our method jointly encodes text, image, and layout information through a Vision-Text-Layout encoder and an Optical Chemical Structure Recognition vision encoder. These representations are merged and used to auto-regressively generate a sequential graph representation of the Markush structure along with a table defining its variable groups. To overcome the lack of real-world training data, we propose a synthetic data generation pipeline that produces a wide range of realistic Markush structures. Additionally, we present M2S, the first annotated benchmark of real-world Markush structures, to advance research on this challenging task. Extensive experiments demonstrate that our approach outperforms state-of-the-art chemistry-specific and general-purpose vision-language models in most evaluation settings. Code, models, and datasets will be available.

[Arxiv](https://arxiv.org/abs/2503.16096)