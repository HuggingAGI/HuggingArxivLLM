# RSUniVLM：一个通过面向粒度的专家混合实现的用于遥感的统一视觉语言模型

发布时间：2024年12月07日

`LLM应用` `图像理解`

> RSUniVLM: A Unified Vision Language Model for Remote Sensing via Granularity-oriented Mixture of Experts

# 摘要

> 遥感视觉语言模型（RS VLMs）在遥感图像理解任务方面进展显著。尽管在多模态推理和多轮对话中表现出色，但现有模型缺少像素级理解，处理多图像输入时也颇为吃力。在本研究中，我们推出了 RSUniVLM，这是一个统一的端到端遥感视觉语言模型，致力于达成涵盖图像级、区域级和像素级任务等的多粒度综合视觉理解。RSUniVLM 在多图像分析上也成效显著，像变化检测和变化描述等。为在不增大模型规模的前提下提升模型在不同层级捕获视觉信息的能力，我们设计了一种名为面向粒度的专家混合的新型架构，将模型参数控制在约 10 亿左右。我们还基于遥感和通用领域的各类现有数据集构建了一个大规模的遥感指令遵循数据集，涵盖对象定位、视觉问答和语义分割等诸多任务。开展了大量实验来验证所提出的 RSUniVLM 在各类遥感任务中的优越性，达到了前沿水平。代码和模型可在 \href{https://github.com/xuliu-cyber/RSUniVLM}{此处} 获取。

> Remote Sensing Vision-Language Models (RS VLMs) have made much progress in the tasks of remote sensing (RS) image comprehension. While performing well in multi-modal reasoning and multi-turn conversations, the existing models lack pixel-level understanding and struggle with multi-image inputs. In this work, we propose RSUniVLM, a unified, end-to-end RS VLM designed for comprehensive vision understanding across multiple granularity, including image-level, region-level, and pixel-level tasks. RSUniVLM also performs effectively in multi-image analysis, with instances of change detection and change captioning. To enhance the model's ability to capture visual information at different levels without increasing model size, we design a novel architecture called Granularity-oriented Mixture of Experts to constraint the model to about 1 billion parameters. We also construct a large-scale RS instruction-following dataset based on a variety of existing datasets in both RS and general domain, encompassing various tasks such as object localization, visual question answering, and semantic segmentation. Substantial experiments have been conducted to validate the superiority of the proposed RSUniVLM up to state-of-the-art across various RS tasks. Code and model will be available at \href{https://github.com/xuliu-cyber/RSUniVLM}{here}.

[Arxiv](https://arxiv.org/abs/2412.05679)