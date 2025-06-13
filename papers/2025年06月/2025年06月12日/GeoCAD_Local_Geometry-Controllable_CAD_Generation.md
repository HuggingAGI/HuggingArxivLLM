# GeoCAD：局部几何可控的CAD生成工具

发布时间：2025年06月12日

`LLM应用` `CAD` `设计自动化`

> GeoCAD: Local Geometry-Controllable CAD Generation

# 摘要

> 局部几何可控的CAD生成技术旨在自动修改CAD模型的局部部分，从而提升设计效率。它确保新生成的局部形状严格遵循用户指定的几何指令，例如等腰直角三角形或截角矩形。然而，现有方法在实现这一目标时存在明显局限：要么无法有效解析文本指令，要么无法精准聚焦于局部区域。为了解决这些问题，我们推出了GeoCAD——一种用户友好且高度可控的CAD生成方法。GeoCAD采用创新的互补标注策略，通过基于顶点和基于VLLM的双轨标注方式，系统性地处理简单与复杂局部结构，总计标注了约221,000个不同局部部件。在训练过程中，系统随机遮盖CAD模型中的某个局部区域，利用剩余部分及几何指令作为输入，引导大型语言模型预测被遮盖区域。在实际应用中，用户可自由选择任何局部区域进行修改，并根据需求选择多种预设几何规则。大量实验结果表明，GeoCAD在生成质量、有效性和文本到CAD一致性方面均表现出色。项目代码已开源，地址为https://github.com/Zhanwei-Z/GeoCAD。

> Local geometry-controllable computer-aided design (CAD) generation aims to modify local parts of CAD models automatically, enhancing design efficiency. It also ensures that the shapes of newly generated local parts follow user-specific geometric instructions (e.g., an isosceles right triangle or a rectangle with one corner cut off). However, existing methods encounter challenges in achieving this goal. Specifically, they either lack the ability to follow textual instructions or are unable to focus on the local parts. To address this limitation, we introduce GeoCAD, a user-friendly and local geometry-controllable CAD generation method. Specifically, we first propose a complementary captioning strategy to generate geometric instructions for local parts. This strategy involves vertex-based and VLLM-based captioning for systematically annotating simple and complex parts, respectively. In this way, we caption $\sim$221k different local parts in total. In the training stage, given a CAD model, we randomly mask a local part. Then, using its geometric instruction and the remaining parts as input, we prompt large language models (LLMs) to predict the masked part. During inference, users can specify any local part for modification while adhering to a variety of predefined geometric instructions. Extensive experiments demonstrate the effectiveness of GeoCAD in generation quality, validity and text-to-CAD consistency. Code will be available at https://github.com/Zhanwei-Z/GeoCAD.

[Arxiv](https://arxiv.org/abs/2506.10337)