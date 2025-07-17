# AutoVDC：基于视觉-语言模型的自动视觉数据清洗

发布时间：2025年07月16日

`LLM应用` `自动驾驶` `计算机视觉`

> AutoVDC: Automated Vision Data Cleaning Using Vision-Language Models

# 摘要

> 自动驾驶系统的训练需要大量精确标注的数据集，但人工标注难免存在不完美之处，通常需要多次迭代才能生成高质量的数据集。然而，手动审查大型数据集成本高昂且耗时费力。本文提出了一种名为AutoVDC（自动化视觉数据清洗）的框架，并探讨了视觉语言模型（VLMs）在自动识别视觉数据集中错误标注方面的应用，从而帮助提升数据质量。我们通过KITTI和nuImages数据集验证了我们的方法，这两个数据集包含自动驾驶目标检测基准。为了测试AutoVDC的效果，我们创建了带有故意注入错误标注的数据集变体，并观察了我们的方法的错误检测率。此外，我们还比较了不同VLMs的检测率，并研究了VLM微调对我们的pipeline的影响。实验结果表明，我们的方法在错误检测和数据清洗实验中表现出色，有望显著提高自动驾驶大规模生产数据集的可靠性和准确性。

> Training of autonomous driving systems requires extensive datasets with precise annotations to attain robust performance. Human annotations suffer from imperfections, and multiple iterations are often needed to produce high-quality datasets. However, manually reviewing large datasets is laborious and expensive. In this paper, we introduce AutoVDC (Automated Vision Data Cleaning) framework and investigate the utilization of Vision-Language Models (VLMs) to automatically identify erroneous annotations in vision datasets, thereby enabling users to eliminate these errors and enhance data quality. We validate our approach using the KITTI and nuImages datasets, which contain object detection benchmarks for autonomous driving. To test the effectiveness of AutoVDC, we create dataset variants with intentionally injected erroneous annotations and observe the error detection rate of our approach. Additionally, we compare the detection rates using different VLMs and explore the impact of VLM fine-tuning on our pipeline. The results demonstrate our method's high performance in error detection and data cleaning experiments, indicating its potential to significantly improve the reliability and accuracy of large-scale production datasets in autonomous driving.

[Arxiv](https://arxiv.org/abs/2507.12414)