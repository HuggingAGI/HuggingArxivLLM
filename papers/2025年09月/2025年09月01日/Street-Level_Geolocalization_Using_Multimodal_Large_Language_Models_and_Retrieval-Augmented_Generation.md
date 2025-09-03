# 基于多模态大语言模型与检索增强生成的街道级地理定位

发布时间：2025年09月01日

`RAG` `交通运输`

> Street-Level Geolocalization Using Multimodal Large Language Models and Retrieval-Augmented Generation

# 摘要

> 基于图像的街道级地理定位在导航、位置推荐、城市规划等众多关键应用与服务中都扮演着至关重要的角色。如今，社交媒体数据激增，智能手机摄像头也愈发普及，这使得传统计算机视觉技术在图像定位任务中面临的挑战日益加剧，但其价值也愈发凸显。本文提出了一种创新方法，将开源可访问的多模态大型语言模型与检索增强生成技术相融合。该方法利用SigLIP编码器在两个大规模数据集（EMP-16和OSV-5M）上构建向量数据库。在交由多模态大型语言模型处理前，查询图像会先通过提示词进行增强，这些提示词包含从该数据库中检索到的相似及不相似地理定位信息。我们的方法在三个广泛使用的基准数据集（IM2GPS、IM2GPS3k和YFCC4k）上均表现出最先进的性能，准确率显著提升。重要的是，该方案无需昂贵的微调或重新训练，还能无缝扩展以整合新数据源。本文证明，基于检索增强生成的多模态大型语言模型在地理定位估计中成效显著，这为依赖从头训练模型的传统方法提供了全新替代方案，也为GeoAI领域更易获取、更具扩展性的解决方案打开了新的大门。

> Street-level geolocalization from images is crucial for a wide range of essential applications and services, such as navigation, location-based recommendations, and urban planning. With the growing popularity of social media data and cameras embedded in smartphones, applying traditional computer vision techniques to localize images has become increasingly challenging, yet highly valuable. This paper introduces a novel approach that integrates open-weight and publicly accessible multimodal large language models with retrieval-augmented generation. The method constructs a vector database using the SigLIP encoder on two large-scale datasets (EMP-16 and OSV-5M). Query images are augmented with prompts containing both similar and dissimilar geolocation information retrieved from this database before being processed by the multimodal large language models. Our approach has demonstrated state-of-the-art performance, achieving higher accuracy compared against three widely used benchmark datasets (IM2GPS, IM2GPS3k, and YFCC4k). Importantly, our solution eliminates the need for expensive fine-tuning or retraining and scales seamlessly to incorporate new data sources. The effectiveness of retrieval-augmented generation-based multimodal large language models in geolocation estimation demonstrated by this paper suggests an alternative path to the traditional methods which rely on the training models from scratch, opening new possibilities for more accessible and scalable solutions in GeoAI.

[Arxiv](https://arxiv.org/abs/2509.01341)