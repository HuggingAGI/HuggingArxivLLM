# # FunBench：多模态大语言模型的视盘阅片能力评测
FunBench 是一个专注于评测多模态大语言模型在视盘阅片技能方面的基准测试，旨在全面评估模型在这一领域的表现。

发布时间：2025年03月02日

`LLM应用` `计算机视觉`

> FunBench: Benchmarking Fundus Reading Skills of MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在医学图像分析中展现了巨大潜力，但在眼科关键技能——眼底图像解读方面，其能力尚未得到充分评估。现有基准测试未能细致划分任务，也未能对模型的两大核心模块——大型语言模型（LLM）和视觉编码器（VE）——进行模块化分析。本文推出FunBench，一个全新的视觉问答（VQA）基准测试，旨在全面评估MLLMs在眼底图像解读方面的能力。FunBench采用层次化任务组织结构，涵盖四个层级：模态感知、解剖感知、病变分析和疾病诊断。它还提供三种针对性评估模式：基于线性探针的VE评估、基于知识提示的LLM评估，以及整体评估。在九个开源MLLMs及GPT-4o上的实验显示，这些模型在眼底图像解读方面存在显著不足，尤其在左右眼识别等基础任务上表现欠佳。这些结果凸显了当前MLLMs的局限性，强调了领域特定训练及改进LLMs和VEs的必要性。

> Multimodal Large Language Models (MLLMs) have shown significant potential in medical image analysis. However, their capabilities in interpreting fundus images, a critical skill for ophthalmology, remain under-evaluated. Existing benchmarks lack fine-grained task divisions and fail to provide modular analysis of its two key modules, i.e., large language model (LLM) and vision encoder (VE). This paper introduces FunBench, a novel visual question answering (VQA) benchmark designed to comprehensively evaluate MLLMs' fundus reading skills. FunBench features a hierarchical task organization across four levels (modality perception, anatomy perception, lesion analysis, and disease diagnosis). It also offers three targeted evaluation modes: linear-probe based VE evaluation, knowledge-prompted LLM evaluation, and holistic evaluation. Experiments on nine open-source MLLMs plus GPT-4o reveal significant deficiencies in fundus reading skills, particularly in basic tasks such as laterality recognition. The results highlight the limitations of current MLLMs and emphasize the need for domain-specific training and improved LLMs and VEs.

[Arxiv](https://arxiv.org/abs/2503.00901)