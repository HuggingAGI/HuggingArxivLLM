# MapQaTor：一个实现地图查询数据集高效标注的系统

发布时间：2024年12月30日

`LLM应用` `地理空间` `地图服务`

> MapQaTor: A System for Efficient Annotation of Map Query Datasets

# 摘要

> 像谷歌地图、苹果地图、Openstreet 地图这类映射和导航服务，对于获取各类基于位置的数据极为重要，然而它们常常难以应对自然语言地理空间查询。大型语言模型（LLMs）的最新进展在问答（QA）领域展现出良好前景，但从地图服务创建可靠的地理空间 QA 数据集仍困难重重。我们推出了 MapQaTor 这一网络应用，它简化了可重现、可追溯的基于地图的 QA 数据集的创建流程。凭借其即插即用的架构，MapQaTor 能够与任何地图 API 实现无缝集成，让用户能以最少的设置从多种来源收集并可视化数据。通过缓存 API 响应，该平台确保了一致的基础事实，即便现实世界的信息不断变化，也能增强数据的可靠性。MapQaTor 将数据检索、标注和可视化集中于一个平台，为评估基于 LLM 的地理空间推理的现状以及提升其能力以增进地理空间理解提供了独特契机。评估指标显示，与手动方法相比，MapQaTor 至少将标注过程提速 30 倍，凸显了其在开发地理空间资源（如复杂的地图推理数据集）方面的潜力。该网站的网址为：https://mapqator.github.io/ ，演示视频可在：https://youtu.be/7_aV9Wmhs6Q 查看。

> Mapping and navigation services like Google Maps, Apple Maps, Openstreet Maps, are essential for accessing various location-based data, yet they often struggle to handle natural language geospatial queries. Recent advancements in Large Language Models (LLMs) show promise in question answering (QA), but creating reliable geospatial QA datasets from map services remains challenging. We introduce MapQaTor, a web application that streamlines the creation of reproducible, traceable map-based QA datasets. With its plug-and-play architecture, MapQaTor enables seamless integration with any maps API, allowing users to gather and visualize data from diverse sources with minimal setup. By caching API responses, the platform ensures consistent ground truth, enhancing the reliability of the data even as real-world information evolves. MapQaTor centralizes data retrieval, annotation, and visualization within a single platform, offering a unique opportunity to evaluate the current state of LLM-based geospatial reasoning while advancing their capabilities for improved geospatial understanding. Evaluation metrics show that, MapQaTor speeds up the annotation process by at least 30 times compared to manual methods, underscoring its potential for developing geospatial resources, such as complex map reasoning datasets. The website is live at: https://mapqator.github.io/ and a demo video is available at: https://youtu.be/7_aV9Wmhs6Q.

[Arxiv](https://arxiv.org/abs/2412.21015)