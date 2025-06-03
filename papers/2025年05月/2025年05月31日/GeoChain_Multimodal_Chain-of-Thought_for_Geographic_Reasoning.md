# GeoChain：为地理推理设计的多模态链式思考模型

发布时间：2025年05月31日

`LLM应用` `地理推理` `多模态模型`

> GeoChain: Multimodal Chain-of-Thought for Geographic Reasoning

# 摘要

> 本文介绍了GeoChain，一个用于评估多模态大型语言模型（MLLMs）逐步地理推理能力的大规模基准测试。基于146万张Mapillary街景图像，GeoChain为每张图像配对了一个21步的思维链（CoT）问题序列（超过3000万组问答对）。这些序列引导模型从粗略属性到细粒度定位，涵盖视觉、空间、文化及精准地理位置四个推理类别，并按难度进行标注。图像还配有语义分割（150个类别）和视觉可定位性评分。我们对当代MLLMs（GPT-4.1变体、Claude 3.7、Gemini 2.5变体）进行基准测试，选取了多样化的2088张图像子集，结果显示模型在以下方面面临持续挑战：视觉定位能力较弱、推理表现不稳定，且难以实现精准定位，尤其在推理复杂性增加时更为明显。GeoChain提供了一套强大的诊断方法，这对推动MLLMs在复杂地理推理领域取得重大进展至关重要。

> This paper introduces GeoChain, a large-scale benchmark for evaluating step-by-step geographic reasoning in multimodal large language models (MLLMs). Leveraging 1.46 million Mapillary street-level images, GeoChain pairs each image with a 21-step chain-of-thought (CoT) question sequence (over 30 million Q&A pairs). These sequences guide models from coarse attributes to fine-grained localization across four reasoning categories - visual, spatial, cultural, and precise geolocation - annotated by difficulty. Images are also enriched with semantic segmentation (150 classes) and a visual locatability score. Our benchmarking of contemporary MLLMs (GPT-4.1 variants, Claude 3.7, Gemini 2.5 variants) on a diverse 2,088-image subset reveals consistent challenges: models frequently exhibit weaknesses in visual grounding, display erratic reasoning, and struggle to achieve accurate localization, especially as the reasoning complexity escalates. GeoChain offers a robust diagnostic methodology, critical for fostering significant advancements in complex geographic reasoning within MLLMs.

[Arxiv](https://arxiv.org/abs/2506.00785)