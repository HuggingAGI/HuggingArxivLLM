# 大禹：探索USV图像描述技术，助力水道监控及场景解析

发布时间：2025年06月23日

`LLM应用

理由：这篇论文探讨了如何将视觉-语言模型应用于水道环境的自动感知，特别是通过引入新的数据集和多模态大语言模型来提升无人水面船的环境理解能力。论文的重点在于将LLM技术应用到实际场景中，因此属于“LLM应用”类别。` `无人船` `多模态模型`

> Da Yu: Towards USV-Based Image Captioning for Waterway Surveillance and Scene Understanding

# 摘要

> 水道环境的自动感知是实现无人水面船理解环境并做出决策的关键。现有模型主要聚焦于实例级物体检测与分割，但复杂的水道环境让现有数据集和模型难以实现全局语义理解，限制了大规模监测和结构化日志的生成。基于视觉-语言模型的突破，我们推出专为水道环境设计的 WaterCaption 数据集，专注于细粒度、多区域的长文本描述，为视觉地理理解和空间场景认知开辟新方向。WaterCaption 包含 20.2k 图片-文本配对数据，涵盖 180 万词汇。我们还提出了适用于无人船的多模态大语言模型 Da Yu，其中创新性地引入 Nano Transformer Adaptor (NTA) 技术，完美平衡计算效率与视觉特征建模能力，显著提升长文本生成能力。Da Yu 在性能与效率间达到最佳平衡，在 WaterCaption 以及多个字幕基准测试中超越现有最优模型。

> Automated waterway environment perception is crucial for enabling unmanned surface vessels (USVs) to understand their surroundings and make informed decisions. Most existing waterway perception models primarily focus on instance-level object perception paradigms (e.g., detection, segmentation). However, due to the complexity of waterway environments, current perception datasets and models fail to achieve global semantic understanding of waterways, limiting large-scale monitoring and structured log generation. With the advancement of vision-language models (VLMs), we leverage image captioning to introduce WaterCaption, the first captioning dataset specifically designed for waterway environments. WaterCaption focuses on fine-grained, multi-region long-text descriptions, providing a new research direction for visual geo-understanding and spatial scene cognition. Exactly, it includes 20.2k image-text pair data with 1.8 million vocabulary size. Additionally, we propose Da Yu, an edge-deployable multi-modal large language model for USVs, where we propose a novel vision-to-language projector called Nano Transformer Adaptor (NTA). NTA effectively balances computational efficiency with the capacity for both global and fine-grained local modeling of visual features, thereby significantly enhancing the model's ability to generate long-form textual outputs. Da Yu achieves an optimal balance between performance and efficiency, surpassing state-of-the-art models on WaterCaption and several other captioning benchmarks.

[Arxiv](https://arxiv.org/abs/2506.19288)