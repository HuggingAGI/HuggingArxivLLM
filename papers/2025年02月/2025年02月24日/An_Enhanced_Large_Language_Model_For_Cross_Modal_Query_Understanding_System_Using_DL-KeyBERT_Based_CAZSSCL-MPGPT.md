# 基于DL-KeyBERT的增强型跨模态查询理解系统——CAZSSCL-MPGPT

发布时间：2025年02月24日

`LLM应用` `图像处理` `计算机视觉`

> An Enhanced Large Language Model For Cross Modal Query Understanding System Using DL-KeyBERT Based CAZSSCL-MPGPT

# 摘要

> 大型语言模型（LLMs）是一种先进的深度学习模型，能够理解和生成人类语言，并与图像处理模型协同工作，实现跨模态理解。然而，现有方法常常面临“回音室效应”的挑战，冗余的视觉模式降低了模型的泛化能力和准确性。为此，我们提出了一种基于DL-KeyBERT的CAZSSCL-MPGPT框架，用于增强跨模态查询理解能力。我们收集并预处理了图像和文本数据，利用Easom-You Only Look Once (E-YOLO)对图像进行目标分割，并生成目标骨架和知识图谱。通过条件随机知识图（CRKG）技术提取特征，并使用Fossa Optimization Algorithm (FOA)选择最优特征。文本部分则通过DL-KeyBERT进行词嵌入处理。最终，跨模态查询理解系统利用CAZSSCL-MPGPT生成准确且语境相关的图像描述文本。在COCO dataset 2017上，CAZSSCL-MPGPT的准确率达到了99.14%，而在vqav2-val dataset上则为98.43%。

> Large Language Models (LLMs) are advanced deep-learning models designed to understand and generate human language. They work together with models that process data like images, enabling cross-modal understanding. However, existing approaches often suffer from the echo chamber effect, where redundant visual patterns reduce model generalization and accuracy. Thus, the proposed system considered this limitation and developed an enhanced LLM-based framework for cross-modal query understanding using DL-KeyBERT-based CAZSSCL-MPGPT. The collected dataset consists of pre-processed images and texts. The preprocessed images then undergo object segmentation using Easom-You Only Look Once (E-YOLO). The object skeleton is generated, along with the knowledge graph using a Conditional Random Knowledge Graph (CRKG) technique. Further, features are extracted from the knowledge graph, generated skeletons, and segmented objects. The optimal features are then selected using the Fossa Optimization Algorithm (FOA). Meanwhile, the text undergoes word embedding using DL-KeyBERT. Finally, the cross-modal query understanding system utilizes CAZSSCL-MPGPT to generate accurate and contextually relevant image descriptions as text. The proposed CAZSSCL-MPGPT achieved an accuracy of 99.14187362% in the COCO dataset 2017 and 98.43224393% in the vqav2-val dataset.

[Arxiv](https://arxiv.org/abs/2502.17000)