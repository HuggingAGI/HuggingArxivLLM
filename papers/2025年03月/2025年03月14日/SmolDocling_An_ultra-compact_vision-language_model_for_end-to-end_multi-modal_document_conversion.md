# SmolDocling：一款专为端到端多模态文档转换设计的超紧凑视觉-语言模型

发布时间：2025年03月14日

`LLM应用

理由：这篇论文介绍了SmolDocling，一个专注于端到端文档转换的视觉语言模型，属于大型语言模型在特定任务中的应用，因此归类为LLM应用。` `文档处理` `信息抽取`

> SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion

# 摘要

> 我们很高兴推出SmolDocling——一款专注于端到端文档转换的超紧凑视觉语言模型。通过生成全新的通用标记格式DocTags，SmolDocling能够完整捕获页面元素及其位置。与依赖大型基础模型或多个专业模型的手工流水线集成方案不同，SmolDocling在2.56亿参数的视觉语言模型中提供了一个端到端的转换方案，能够准确捕捉文档元素的内容、结构和空间位置。在商业文档、学术论文、技术报告、专利和表格等多种文档类型中，SmolDocling都能出色地处理代码列表、表格、公式、图表、列表等元素，其应用范围远超通常仅关注科学论文的限制。此外，我们还为图表、表格、公式和代码识别贡献了新的公开数据集。实验结果表明，SmolDocling不仅能够与规模大27倍的其他视觉语言模型相媲美，还大幅降低了计算需求。目前该模型已开放使用，相关数据集也将很快公开发布。


> We introduce SmolDocling, an ultra-compact vision-language model targeting end-to-end document conversion. Our model comprehensively processes entire pages by generating DocTags, a new universal markup format that captures all page elements in their full context with location. Unlike existing approaches that rely on large foundational models, or ensemble solutions that rely on handcrafted pipelines of multiple specialized models, SmolDocling offers an end-to-end conversion for accurately capturing content, structure and spatial location of document elements in a 256M parameters vision-language model. SmolDocling exhibits robust performance in correctly reproducing document features such as code listings, tables, equations, charts, lists, and more across a diverse range of document types including business documents, academic papers, technical reports, patents, and forms -- significantly extending beyond the commonly observed focus on scientific papers. Additionally, we contribute novel publicly sourced datasets for charts, tables, equations, and code recognition. Experimental results demonstrate that SmolDocling competes with other Vision Language Models that are up to 27 times larger in size, while reducing computational requirements substantially. The model is currently available, datasets will be publicly available soon.

[Arxiv](https://arxiv.org/abs/2503.11576)