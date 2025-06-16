# # 通过多模态大语言模型实现的以人为本交互式学习，用于文本到图像的行人再识别  
本研究聚焦于基于多模态大语言模型的以人为本交互式学习方法，致力于提升文本到图像的行人再识别能力。

发布时间：2025年05月20日

`LLM应用` `跨模态学习` `跨模态交互`

> Human-centered Interactive Learning via MLLMs for Text-to-Image Person Re-identification

# 摘要

> 尽管文本到图像的人脸重新识别（TIReID）在跨模态嵌入模型的突破下取得了显著进展，但现有方法往往由于网络架构和数据质量等内在限制，难以区分具有挑战性的候选图像。为了解决这些问题，我们提出了一种交互式跨模态学习框架（ICL），该框架借助以人类为中心的交互，通过外部多模态知识提升文本查询的区分能力。为此，我们提出了一种即插即用的测试时人本交互（THI）模块，该模块专注于人类特征的视觉问答，并与多模态大语言模型（MLLM）进行多轮交互，以使查询意图与潜在目标图像对齐。具体而言，THI基于MLLM的响应对用户查询进行优化，缩小与最佳匹配图像的差距，从而提高排序准确性。此外，为了解决低质量训练文本的局限性，我们引入了一种基于信息丰富化和多样性增强的新型重新组织数据增强（RDA）策略，通过丰富、分解和重新组织人员描述来增强查询的区分能力。在CUHK-PEDES、ICFG-PEDES、RSTPReid和UFine6926四个TIReID基准上的广泛实验表明，我们的方法实现了显著的性能提升。

> Despite remarkable advancements in text-to-image person re-identification (TIReID) facilitated by the breakthrough of cross-modal embedding models, existing methods often struggle to distinguish challenging candidate images due to intrinsic limitations, such as network architecture and data quality. To address these issues, we propose an Interactive Cross-modal Learning framework (ICL), which leverages human-centered interaction to enhance the discriminability of text queries through external multimodal knowledge. To achieve this, we propose a plug-and-play Test-time Humane-centered Interaction (THI) module, which performs visual question answering focused on human characteristics, facilitating multi-round interactions with a multimodal large language model (MLLM) to align query intent with latent target images. Specifically, THI refines user queries based on the MLLM responses to reduce the gap to the best-matching images, thereby boosting ranking accuracy. Additionally, to address the limitation of low-quality training texts, we introduce a novel Reorganization Data Augmentation (RDA) strategy based on information enrichment and diversity enhancement to enhance query discriminability by enriching, decomposing, and reorganizing person descriptions. Extensive experiments on four TIReID benchmarks, i.e., CUHK-PEDES, ICFG-PEDES, RSTPReid, and UFine6926, demonstrate that our method achieves remarkable performance with substantial improvement.

[Arxiv](https://arxiv.org/abs/2506.11036)