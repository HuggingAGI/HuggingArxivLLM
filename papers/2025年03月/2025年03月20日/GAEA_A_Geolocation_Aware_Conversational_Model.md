# # 摘要
GAEA 是一个地理位置感知的对话模型，它能理解和利用位置信息，从而提供更相关、更个性化的回复。GAEA 将地理位置数据融入决策过程，能够根据用户的实际位置调整回复，使对话更自然、更贴合情境。这一功能在需要基于位置的服务或推荐时特别实用。

发布时间：2025年03月20日

`LLM应用` `计算机视觉` `地理信息`

> GAEA: A Geolocation Aware Conversational Model

# 摘要

> 图像地理定位是一项具有广泛应用前景的挑战性任务。传统方法依赖AI模型预测图像的精确GPS坐标，但用户只能从中获取坐标信息，无法进一步丰富对地理位置的了解；模型缺乏对地理位置的理解，也无法与用户进行有效沟通。近期，随着大型多模态模型（LMMs）的快速发展，研究人员尝试将其应用于图像地理定位。然而，这一方法在面对专业性更强的地理定位任务时仍显不足。为此，我们提出了GAEA对话模型，它能够根据用户需求提供有关图像地理位置的详细信息。为支持这一研究，我们构建了一个包含80万张图像和160万个问答对的全面数据集GAEA，利用OpenStreetMap（OSM）属性和地理环境线索进行构建。在评估方面，我们设计了一个包含4千张图像-文本对的多样化基准数据集，涵盖多种问题类型，用于全面评估对话能力。我们对11个先进的开源和专有LMMs进行了对比实验，结果显示GAEA在最佳开源模型LLaVA-OneVision上取得了25.69%的显著提升，在最佳专有模型GPT-4o上提升了8.28%。我们的数据集、模型和代码均已公开，以促进相关研究的发展。

> Image geolocalization, in which, traditionally, an AI model predicts the precise GPS coordinates of an image is a challenging task with many downstream applications. However, the user cannot utilize the model to further their knowledge other than the GPS coordinate; the model lacks an understanding of the location and the conversational ability to communicate with the user. In recent days, with tremendous progress of large multimodal models (LMMs) proprietary and open-source researchers have attempted to geolocalize images via LMMs. However, the issues remain unaddressed; beyond general tasks, for more specialized downstream tasks, one of which is geolocalization, LMMs struggle. In this work, we propose to solve this problem by introducing a conversational model GAEA that can provide information regarding the location of an image, as required by a user. No large-scale dataset enabling the training of such a model exists. Thus we propose a comprehensive dataset GAEA with 800K images and around 1.6M question answer pairs constructed by leveraging OpenStreetMap (OSM) attributes and geographical context clues. For quantitative evaluation, we propose a diverse benchmark comprising 4K image-text pairs to evaluate conversational capabilities equipped with diverse question types. We consider 11 state-of-the-art open-source and proprietary LMMs and demonstrate that GAEA significantly outperforms the best open-source model, LLaVA-OneVision by 25.69% and the best proprietary model, GPT-4o by 8.28%. Our dataset, model and codes are available

[Arxiv](https://arxiv.org/abs/2503.16423)