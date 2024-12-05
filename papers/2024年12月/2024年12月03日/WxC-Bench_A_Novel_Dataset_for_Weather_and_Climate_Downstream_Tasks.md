# WxC-Bench：一个用于天气和气候下游任务的全新数据集

发布时间：2024年12月03日

`其他`

> WxC-Bench: A Novel Dataset for Weather and Climate Downstream Tasks

# 摘要

> 高质量的机器学习（ML）就绪数据集对于开发新的人工智能（AI）模型或对现有模型进行微调以用于天气和气候分析等科学应用起着基石般的作用。然而，令人遗憾的是，尽管用于天气和气候的新深度学习模型不断涌现，但经过精心整理和预处理的机器学习（ML）就绪数据集却十分稀缺。为开发新模型整理这类高质量数据集颇具挑战，尤其是因为针对解决不同大气尺度（空间和时间）的不同下游任务，输入数据的模式差异显著。在此，我们推出 WxC-Bench（天气和气候基准），这是一个多模态数据集，旨在助力开发适用于天气和气候研究下游用例的通用人工智能模型。WxC-Bench 被设计成用于为复杂的天气和气候系统开发 ML 模型的数据集集合，针对选定的下游任务作为机器学习现象。WxC-Bench 涵盖了从中尺度-β（20 - 200 公里）到天气尺度（2500 公里）的若干大气过程，如航空湍流、飓风强度和轨迹监测、天气类比搜索、重力波参数化以及自然语言报告生成。我们对该数据集进行了全面阐述，并为基线分析提供了技术验证。该数据集以及用于准备 ML 就绪数据的代码已在 Hugging Face 上公开——https://huggingface.co/datasets/nasa-impact/WxC-Bench

> High-quality machine learning (ML)-ready datasets play a foundational role in developing new artificial intelligence (AI) models or fine-tuning existing models for scientific applications such as weather and climate analysis. Unfortunately, despite the growing development of new deep learning models for weather and climate, there is a scarcity of curated, pre-processed machine learning (ML)-ready datasets. Curating such high-quality datasets for developing new models is challenging particularly because the modality of the input data varies significantly for different downstream tasks addressing different atmospheric scales (spatial and temporal). Here we introduce WxC-Bench (Weather and Climate Bench), a multi-modal dataset designed to support the development of generalizable AI models for downstream use-cases in weather and climate research. WxC-Bench is designed as a dataset of datasets for developing ML-models for a complex weather and climate system, addressing selected downstream tasks as machine learning phenomenon. WxC-Bench encompasses several atmospheric processes from meso-$β$ (20 - 200 km) scale to synoptic scales (2500 km), such as aviation turbulence, hurricane intensity and track monitoring, weather analog search, gravity wave parameterization, and natural language report generation. We provide a comprehensive description of the dataset and also present a technical validation for baseline analysis. The dataset and code to prepare the ML-ready data have been made publicly available on Hugging Face -- https://huggingface.co/datasets/nasa-impact/WxC-Bench

[Arxiv](https://arxiv.org/abs/2412.02780)