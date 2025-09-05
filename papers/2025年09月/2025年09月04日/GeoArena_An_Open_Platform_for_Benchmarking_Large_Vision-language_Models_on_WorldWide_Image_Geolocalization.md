# GeoArena：用于大型视觉-语言模型全球图像地理定位基准测试的开放平台

发布时间：2025年09月04日

`LLM应用` `交通运输`

> GeoArena: An Open Platform for Benchmarking Large Vision-language Models on WorldWide Image Geolocalization

# 摘要

> 图像地理定位旨在预测全球各地拍摄图像的地理位置，但其全球性却带来了不小的挑战。当前的评估方法存在两大局限。其一，数据泄露问题：先进方法多依赖大型视觉语言模型（LVLMs）预测图像位置，而这些模型常以测试数据集为预训练数据，导致评估模型真实地理定位能力的准确性大打折扣。其二，现有指标主要通过精确地理坐标评估预测结果，这不仅忽略了模型的推理过程，还在涉及用户级位置数据时引发隐私担忧。为解决上述问题，我们提出了GeoArena——首个评估LVLMs全球图像地理定位任务表现的开放平台，它能提供真实的野外场景和以人为中心的基准测试。该平台已在线部署两个月，期间收集了数千条投票记录。基于这些数据，我们开展了详细分析，并构建了不同LVLMs在图像地理定位任务上的性能排行榜。

> Image geolocalization aims to predict the geographic location of images captured anywhere on Earth, but its global nature presents significant challenges. Current evaluation methodologies suffer from two major limitations. First, data leakage: advanced approaches often rely on large vision-language models (LVLMs) to predict image locations, yet these models are frequently pretrained on the test datasets, compromising the accuracy of evaluating a model's actual geolocalization capability. Second, existing metrics primarily rely on exact geographic coordinates to assess predictions, which not only neglects the reasoning process but also raises privacy concerns when user-level location data is required. To address these issues, we propose GeoArena, a first open platform for evaluating LVLMs on worldwide image geolocalization tasks, offering true in-the-wild and human-centered benchmarking. GeoArena enables users to upload in-the-wild images for a more diverse evaluation corpus, and it leverages pairwise human judgments to determine which model output better aligns with human expectations. Our platform has been deployed online for two months, during which we collected over thousands voting records. Based on this data, we conduct a detailed analysis and establish a leaderboard of different LVLMs on the image geolocalization task.

[Arxiv](https://arxiv.org/abs/2509.04334)