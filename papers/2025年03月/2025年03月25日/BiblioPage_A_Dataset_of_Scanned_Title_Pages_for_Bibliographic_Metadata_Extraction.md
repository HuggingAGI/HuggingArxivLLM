# # **BiblioPage**: 扫描标题页数据集，用于图书文献元数据提取

发布时间：2025年03月25日

`LLM应用` `图书馆学` `文档理解`

> BiblioPage: A Dataset of Scanned Title Pages for Bibliographic Metadata Extraction

# 摘要

> 人工提取书目元数据费时费力，尤其是面对格式多样的历史和现实档案时。尽管机器学习技术不断进步，但缺乏专门的元数据提取数据集限制了自动化应用。为解决这一问题，我们推出了BiblioPage数据集，包含标注了结构化书目元数据的扫描标题页。该数据集汇集了来自14家捷克图书馆的约2,000本专著的标题页，涵盖广泛的出版时期、排版风格和布局结构。每一页都标注了16个书目属性，包括标题、贡献者和出版信息，以及精确的边界框位置信息。我们评估了YOLO和DETR等目标检测模型与基于Transformer的OCR技术的结合，实现了最高52的mAP和59的F1分数。此外，我们还测试了LlamA 3.2-Vision和GPT-4o等视觉大语言模型，其中最佳模型达到了67的F1分数。BiblioPage为书目元数据提取提供了现实世界的基准，助力文档理解、问答和信息提取。数据集和评估脚本可在以下链接获取：https://github.com/DCGM/biblio-dataset

> Manual digitization of bibliographic metadata is time consuming and labor intensive, especially for historical and real-world archives with highly variable formatting across documents. Despite advances in machine learning, the absence of dedicated datasets for metadata extraction hinders automation. To address this gap, we introduce BiblioPage, a dataset of scanned title pages annotated with structured bibliographic metadata. The dataset consists of approximately 2,000 monograph title pages collected from 14 Czech libraries, spanning a wide range of publication periods, typographic styles, and layout structures. Each title page is annotated with 16 bibliographic attributes, including title, contributors, and publication metadata, along with precise positional information in the form of bounding boxes. To extract structured information from this dataset, we valuated object detection models such as YOLO and DETR combined with transformer-based OCR, achieving a maximum mAP of 52 and an F1 score of 59. Additionally, we assess the performance of various visual large language models, including LlamA 3.2-Vision and GPT-4o, with the best model reaching an F1 score of 67. BiblioPage serves as a real-world benchmark for bibliographic metadata extraction, contributing to document understanding, document question answering, and document information extraction. Dataset and evaluation scripts are availible at: https://github.com/DCGM/biblio-dataset

[Arxiv](https://arxiv.org/abs/2503.19658)