# MM-AttacKG：基于大型语言模型的多模态攻击图构建方法

发布时间：2025年06月20日

`LLM应用` `网络安全` `情报分析`

> MM-AttacKG: A Multimodal Approach to Attack Graph Construction with Large Language Models

# 摘要

> 网络威胁情报解析的目标是从海量数据中提取关键威胁信息，转化为可操作的情报，提升威胁检测与防御效率，包括攻击图构建、情报融合与威胁指标提取。其中，攻击图构建是理解威胁事件潜在攻击路径的关键。现有方法主要基于文本数据构建攻击图，揭示实体间的逻辑威胁关系，但忽视了视觉模态中的具体威胁信息。因此，我们提出了一种基于多模态大语言模型 (MLLMs) 的框架 MM-AttacKG，从威胁图像中提取关键信息并整合到攻击图构建中，提升攻击图的全面性和准确性。该框架首先通过威胁图像解析模块提取关键信息并生成描述，然后构建迭代问答管道精炼图像理解，最后通过 MLLMs 实现攻击图与图像答案的内容级整合，完成威胁信息增强。实验结果表明，MM-AttacKG 能够准确识别威胁图像中的关键信息，显著提升多模态攻击图构建的质量，弥补现有方法的不足。

> Cyber Threat Intelligence (CTI) parsing aims to extract key threat information from massive data, transform it into actionable intelligence, enhance threat detection and defense efficiency, including attack graph construction, intelligence fusion and indicator extraction. Among these research topics, Attack Graph Construction (AGC) is essential for visualizing and understanding the potential attack paths of threat events from CTI reports. Existing approaches primarily construct the attack graphs purely from the textual data to reveal the logical threat relationships between entities within the attack behavioral sequence. However, they typically overlook the specific threat information inherent in visual modalities, which preserves the key threat details from inherently-multimodal CTI report. Therefore, we enhance the effectiveness of attack graph construction by analyzing visual information through Multimodal Large Language Models (MLLMs). Specifically, we propose a novel framework, MM-AttacKG, which can effectively extract key information from threat images and integrate it into attack graph construction, thereby enhancing the comprehensiveness and accuracy of attack graphs. It first employs a threat image parsing module to extract critical threat information from images and generate descriptions using MLLMs. Subsequently, it builds an iterative question-answering pipeline tailored for image parsing to refine the understanding of threat images. Finally, it achieves content-level integration between attack graphs and image-based answers through MLLMs, completing threat information enhancement. The experimental results demonstrate that MM-AttacKG can accurately identify key information in threat images and significantly improve the quality of multimodal attack graph construction, effectively addressing the shortcomings of existing methods in utilizing image-based threat information.

[Arxiv](https://arxiv.org/abs/2506.16968)