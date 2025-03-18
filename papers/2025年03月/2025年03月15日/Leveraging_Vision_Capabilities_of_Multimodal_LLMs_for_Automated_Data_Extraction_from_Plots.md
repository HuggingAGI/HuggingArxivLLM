# 挖掘多模态大语言模型的视觉能力，实现图表数据的自动化提取

发布时间：2025年03月15日

`LLM应用` `数据科学` `人工智能`

> Leveraging Vision Capabilities of Multimodal LLMs for Automated Data Extraction from Plots

# 摘要

> 从研究文本中自动提取数据的能力一直在稳步提升，而大型语言模型（LLMs）的出现更是为这一领域注入了新的活力。然而，从研究论文中的图表提取数据却一直是项复杂的工作，以至于主要依赖于手动操作。我们发现，现有的多模态大型语言模型，只要搭配合适的指令和经过精心设计的工作流程，便能准确地从图表中提取数据。这种能力根植于预训练模型之中，我们无需进行额外的微调，只需使用我们称之为PlotExtract的零样本工程提示链式思考序列即可实现。在这里，我们展示了PlotExtract的实际效果，并对其在合成图表和已发表图表上的表现进行了评估。本次分析仅专注于具有两个坐标轴的图表。对于那些被判定为可提取的图表，PlotExtract能够以超过90%的精准度定位数据点（召回率同样达到约90%），并且在x和y坐标上的误差控制在5%或更低。这些结果充分证明，多模态LLMs为图表数据的高效提取开辟了一条可行的道路，并且在诸多场景下，它能够取代传统的人工数据提取方式。

> Automated data extraction from research texts has been steadily improving, with the emergence of large language models (LLMs) accelerating progress even further. Extracting data from plots in research papers, however, has been such a complex task that it has predominantly been confined to manual data extraction. We show that current multimodal large language models, with proper instructions and engineered workflows, are capable of accurately extracting data from plots. This capability is inherent to the pretrained models and can be achieved with a chain-of-thought sequence of zero-shot engineered prompts we call PlotExtract, without the need to fine-tune. We demonstrate PlotExtract here and assess its performance on synthetic and published plots. We consider only plots with two axes in this analysis. For plots identified as extractable, PlotExtract finds points with over 90% precision (and around 90% recall) and errors in x and y position of around 5% or lower. These results prove that multimodal LLMs are a viable path for high-throughput data extraction for plots and in many circumstances can replace the current manual methods of data extraction.

[Arxiv](https://arxiv.org/abs/2503.12326)