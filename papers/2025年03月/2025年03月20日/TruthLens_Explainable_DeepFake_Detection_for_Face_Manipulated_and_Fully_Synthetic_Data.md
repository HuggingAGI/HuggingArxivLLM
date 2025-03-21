# # TruthLens：用于检测人脸篡改和完全合成数据的可解释深度伪造检测方法

发布时间：2025年03月20日

`LLM应用` `深度伪造` `计算机视觉`

> TruthLens: Explainable DeepFake Detection for Face Manipulated and Fully Synthetic Data

# 摘要

> **深度伪造检测**已成为一个关键研究领域，因为AI图像生成器的普及让创建人脸篡改和完全合成内容变得轻而易举，但现有方法往往局限于简单的二分类（真实 vs. 伪造）且缺乏解释性。为解决这一难题，我们提出了 TruthLens，一个创新且高度通用的深度伪造检测框架。它不仅能判断图像真伪，还能提供详细的文字推理，解释预测结果。
    与传统方法不同，TruthLens 能够有效应对人脸篡改的深度伪造和完全由AI生成的内容，甚至可以回答“眼睛/鼻子/嘴巴看起来真实还是伪造？”等细节问题。TruthLens 的架构巧妙结合了多模态大型语言模型（如PaliGemma2）的全局理解能力和仅视觉模型（如DINOv2）的局部特征提取能力，充分发挥两种模型的互补优势，实现对细微篡改的精准检测，同时保持结果的可解释性。
    在多种数据集上的大量实验表明，TruthLens 在检测准确性和可解释性方面均优于现有最先进方法（提升2%-14%），并且在跨数据设置中也表现出色，能够有效应对传统和新兴的各类篡改技术。
    

> Detecting DeepFakes has become a crucial research area as the widespread use of AI image generators enables the effortless creation of face-manipulated and fully synthetic content, yet existing methods are often limited to binary classification (real vs. fake) and lack interpretability. To address these challenges, we propose TruthLens, a novel and highly generalizable framework for DeepFake detection that not only determines whether an image is real or fake but also provides detailed textual reasoning for its predictions. Unlike traditional methods, TruthLens effectively handles both face-manipulated DeepFakes and fully AI-generated content while addressing fine-grained queries such as "Does the eyes/nose/mouth look real or fake?"
  The architecture of TruthLens combines the global contextual understanding of multimodal large language models like PaliGemma2 with the localized feature extraction capabilities of vision-only models like DINOv2. This hybrid design leverages the complementary strengths of both models, enabling robust detection of subtle manipulations while maintaining interpretability. Extensive experiments on diverse datasets demonstrate that TruthLens outperforms state-of-the-art methods in detection accuracy (by 2-14%) and explainability, in both in-domain and cross-data settings, generalizing effectively across traditional and emerging manipulation techniques.

[Arxiv](https://arxiv.org/abs/2503.15867)