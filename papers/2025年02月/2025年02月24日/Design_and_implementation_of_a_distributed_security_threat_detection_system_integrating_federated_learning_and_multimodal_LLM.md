# 设计并构建融合联邦学习与多模态大语言模型的分布式安全威胁检测系统

发布时间：2025年02月24日

`LLM应用` `分布式系统`

> Design and implementation of a distributed security threat detection system integrating federated learning and multimodal LLM

# 摘要

> 传统安全防护方法难以应对大规模分布式系统中的复杂攻击向量，尤其是在平衡检测准确性与数据隐私问题方面。本文提出了一种结合联邦学习与多模态大语言模型（LLMs）的新型分布式安全威胁检测系统。我们的系统通过联邦学习保障数据隐私，同时利用多模态LLMs处理网络流量、系统日志、图像和传感器数据等异构数据源。在10TB分布式数据集上的实验结果显示，我们的方法实现了96.4%的检测准确率，较传统基线模型高出4.1个百分点。该系统将误报率和漏报率分别降低了1.8和2.4个百分点。性能分析表明，我们的系统在分布式环境中保持了高效的处理能力，模型训练需时180秒，分布式网络中的威胁检测耗时3.8秒。这些结果表明，我们的方法在检测准确性和计算效率方面均有显著提升，同时保障了数据隐私，为大规模安全系统的实际部署提供了有力支持。

> Traditional security protection methods struggle to address sophisticated attack vectors in large-scale distributed systems, particularly when balancing detection accuracy with data privacy concerns. This paper presents a novel distributed security threat detection system that integrates federated learning with multimodal large language models (LLMs). Our system leverages federated learning to ensure data privacy while employing multimodal LLMs to process heterogeneous data sources including network traffic, system logs, images, and sensor data. Experimental evaluation on a 10TB distributed dataset demonstrates that our approach achieves 96.4% detection accuracy, outperforming traditional baseline models by 4.1 percentage points. The system reduces both false positive and false negative rates by 1.8 and 2.4 percentage points respectively. Performance analysis shows that our system maintains efficient processing capabilities in distributed environments, requiring 180 seconds for model training and 3.8 seconds for threat detection across the distributed network. These results demonstrate significant improvements in detection accuracy and computational efficiency while preserving data privacy, suggesting strong potential for real-world deployment in large-scale security systems.

[Arxiv](https://arxiv.org/abs/2502.17763)