# OpenFACADES：基于街景图像的建筑描述与属性数据增强开放框架

发布时间：2025年04月01日

`LLM应用`

> OpenFACADES: An Open Framework for Architectural Caption and Attribute Data Enrichment via Street View Imagery

# 摘要

> 建筑属性（如高度、用途和材料构成）在空间数据基础设施中发挥着重要作用，支持能源模拟、风险评估和环境建模等应用。尽管如此，全面且高质量的建筑属性数据在许多城市地区仍然稀缺。近期研究利用遥感和街景图像实现了客观建筑属性的提取与标注，但如何整合多源开放数据集、大规模获取整体建筑图像并推断全面建筑属性仍是一个重要挑战。本研究作为首批探索之一，通过OpenFACADES框架填补了这一空白。该框架利用多模态众包数据，结合多模态大型语言模型，为建筑档案添加了客观属性和语义描述。我们的方法分为三步：首先，通过等视线分析将Mapillary的街景图像元数据与OpenStreetMap的几何数据相结合，识别出适合观察目标建筑的视角图像；其次，实现全景图像中建筑立面的自动检测，并设计重投影方法将物体转换为整体透视视图，近似真实观察效果；最后，提出一种创新方法，利用开源大型视觉-语言模型（VLM）进行多属性预测和开放词汇描述生成，基于来自七个城市的30,180张标注图像的全球数据集。评估表明，微调后的VLM在多属性推理方面表现出色，优于单一属性计算机视觉模型和零样本ChatGPT-4o。


> Building properties, such as height, usage, and material composition, play a crucial role in spatial data infrastructures, supporting applications such as energy simulation, risk assessment, and environmental modeling. Despite their importance, comprehensive and high-quality building attribute data remain scarce in many urban areas. Recent advances have enabled the extraction and tagging of objective building attributes using remote sensing and street-level imagery. However, establishing a method and pipeline that integrates diverse open datasets, acquires holistic building imagery at scale, and infers comprehensive building attributes remains a significant challenge. Among the first, this study bridges the gaps by introducing OpenFACADES, an open framework that leverages multimodal crowdsourced data to enrich building profiles with both objective attributes and semantic descriptors through multimodal large language models. Our methodology proceeds in three major steps. First, we integrate street-level image metadata from Mapillary with OpenStreetMap geometries via isovist analysis, effectively identifying images that provide suitable vantage points for observing target buildings. Second, we automate the detection of building facades in panoramic imagery and tailor a reprojection approach to convert objects into holistic perspective views that approximate real-world observation. Third, we introduce an innovative approach that harnesses and systematically investigates the capabilities of open-source large vision-language models (VLMs) for multi-attribute prediction and open-vocabulary captioning in building-level analytics, leveraging a globally sourced dataset of 30,180 labeled images from seven cities. Evaluation shows that fine-tuned VLM excel in multi-attribute inference, outperforming single-attribute computer vision models and zero-shot ChatGPT-4o.

[Arxiv](https://arxiv.org/abs/2504.02866)