# 探究视觉语言模型在点云车辆分类中的应用

发布时间：2025年04月10日

`LLM应用` `智能交通` `视觉处理`

> Investigating Vision-Language Model for Point Cloud-based Vehicle Classification

# 摘要

> 重型卡车因其体积庞大和操纵性有限，相较于乘用车辆，带来了显著的安全挑战。为了提升协同自动驾驶的安全性，深入了解卡车特性至关重要。传统的基于LiDAR的卡车分类方法依赖大量手动标注，导致工作量大且成本高昂。大型语言模型（LLMs）在海量数据上的快速发展，为利用其少量样本学习能力进行卡车分类提供了机会。然而，现有的视觉语言模型（VLMs）主要在图像数据集上进行训练，这使得直接处理点云数据变得困难。本研究提出了一种创新框架，将路边LiDAR点云数据与VLMs相结合，以实现高效准确的卡车分类，从而支持合作与安全的驾驶环境。本研究带来了三项关键创新：（1）利用真实世界的LiDAR数据集进行模型开发；（2）设计了一个预处理管道，将点云数据适配为VLM输入，包括用于密集3D渲染的点云配准和增强特征表示的数学形态学技术；（3）利用上下文学习与少量样本提示，实现仅需少量标注训练数据的车辆分类。实验结果表明，该方法表现优异，不仅减少了标注工作量，还提高了分类精度，展示了其巨大潜力。

> Heavy-duty trucks pose significant safety challenges due to their large size and limited maneuverability compared to passenger vehicles. A deeper understanding of truck characteristics is essential for enhancing the safety perspective of cooperative autonomous driving. Traditional LiDAR-based truck classification methods rely on extensive manual annotations, which makes them labor-intensive and costly. The rapid advancement of large language models (LLMs) trained on massive datasets presents an opportunity to leverage their few-shot learning capabilities for truck classification. However, existing vision-language models (VLMs) are primarily trained on image datasets, which makes it challenging to directly process point cloud data. This study introduces a novel framework that integrates roadside LiDAR point cloud data with VLMs to facilitate efficient and accurate truck classification, which supports cooperative and safe driving environments. This study introduces three key innovations: (1) leveraging real-world LiDAR datasets for model development, (2) designing a preprocessing pipeline to adapt point cloud data for VLM input, including point cloud registration for dense 3D rendering and mathematical morphological techniques to enhance feature representation, and (3) utilizing in-context learning with few-shot prompting to enable vehicle classification with minimally labeled training data. Experimental results demonstrate encouraging performance of this method and present its potential to reduce annotation efforts while improving classification accuracy.

[Arxiv](https://arxiv.org/abs/2504.08154)