# SCA3D: 利用3D形状与配对文本描述的数据增强提升跨模态3D检索效果

发布时间：2025年02月26日

`LLM应用` `机器人` `人工智能`

> SCA3D: Enhancing Cross-modal 3D Retrieval via 3D Shape and Caption Paired Data Augmentation

# 摘要

> 跨模态3D检索旨在实现文本与3D形状的相互匹配，有望显著提升自然语言与3D环境的交互能力，特别是在机器人和具身AI领域。然而，现有方法受限于3D数据的稀缺性与成本，严重依赖有限的3D形状特征，导致泛化能力不足。为解决这一问题，我们提出了一种全新的跨模态3D检索数据增强方法——SCA3D。该方法基于LLaVA模型构建组件库，为数据集内每个3D形状的分割部分生成描述。通过互相关和相关距离整合组件生成新3D形状，确保组件不重叠且紧密贴合。同时，利用文本模板生成新的描述，并采用单模态编码器提取增强数据集的嵌入表示。通过EMD计算细粒度跨模态相似性，并结合对比学习提升匹配效果，实现文本与3D形状的双向检索。实验结果表明，SCA3D在Text2Shape数据集上显著优于现有方法，Shape-to-Text RR@1分数从20.03提升至27.22，Text-to-Shape RR@1分数从13.12提升至16.67。代码已开源，访问地址为https://github.com/3DAgentWorld/SCA3D。

> The cross-modal 3D retrieval task aims to achieve mutual matching between text descriptions and 3D shapes. This has the potential to enhance the interaction between natural language and the 3D environment, especially within the realms of robotics and embodied artificial intelligence (AI) applications. However, the scarcity and expensiveness of 3D data constrain the performance of existing cross-modal 3D retrieval methods. These methods heavily rely on features derived from the limited number of 3D shapes, resulting in poor generalization ability across diverse scenarios. To address this challenge, we introduce SCA3D, a novel 3D shape and caption online data augmentation method for cross-modal 3D retrieval. Our approach uses the LLaVA model to create a component library, captioning each segmented part of every 3D shape within the dataset. Notably, it facilitates the generation of extensive new 3D-text pairs containing new semantic features. We employ both inter and intra distances to align various components into a new 3D shape, ensuring that the components do not overlap and are closely fitted. Further, text templates are utilized to process the captions of each component and generate new text descriptions. Besides, we use unimodal encoders to extract embeddings for 3D shapes and texts based on the enriched dataset. We then calculate fine-grained cross-modal similarity using Earth Mover's Distance (EMD) and enhance cross-modal matching with contrastive learning, enabling bidirectional retrieval between texts and 3D shapes. Extensive experiments show our SCA3D outperforms previous works on the Text2Shape dataset, raising the Shape-to-Text RR@1 score from 20.03 to 27.22 and the Text-to-Shape RR@1 score from 13.12 to 16.67. Codes can be found in https://github.com/3DAgentWorld/SCA3D.

[Arxiv](https://arxiv.org/abs/2502.19128)