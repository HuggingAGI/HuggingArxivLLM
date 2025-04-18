# # ChatEXAONEPath：一款专为病理学设计的专家级多模态大型语言模型，基于全切片图像提供专业分析。

发布时间：2025年04月17日

`LLM应用

理由：这篇论文主要讨论了大型语言模型在医学领域的应用，特别是多模态LLMs在组织病理学中的诊断能力。研究展示了如何通过整合全切片图像和组织病理学报告来提升模型的诊断准确性，并提出了具体的应用场景和评估方法。因此，这篇论文属于LLM应用类别。` `组织病理学`

> ChatEXAONEPath: An Expert-level Multimodal Large Language Model for Histopathology Using Whole Slide Images

# 摘要

> 近期研究在医学领域开发大型语言模型（LLMs）方面取得了显著进展，这些模型不仅能回答专家级问题，还能在现实临床场景中为临床医生提供辅助支持。研究发现，将多种模态与现有LLMs结合，能更好地理解复杂临床背景，因为这些背景本质上是多方面的。尽管已有研究展示了多模态LLMs在组织病理学中基于图像回答问题的能力，但受限于公共数据集中信息有限的补丁级别数据，它们在理解全面临床背景方面仍有不足。因此，开发基于全切片图像（WSIs）的多模态LLMs在组织病理学中具有重要意义，能提升其可扩展性和适用性。

在这项研究中，我们推出了一款专家级的组织病理学多模态LLMs——ChatEXAONEPath，该模型基于WSIs构建。我们提出了一种基于检索的数据生成流水线，利用来自癌症基因组图谱（TCGA）的10,094对WSIs和组织病理学报告。我们还展示了一个人工智能评估协议，以全面理解来自多模态信息的医学背景，并将生成的回答与原始组织病理学报告进行比较评估。实验结果表明，ChatEXAONEPath能够基于1,134对WSIs和报告，以62.9%的接受率准确诊断给定的组织病理学图像。我们的模型不仅能够理解多种癌症类型的全切片图像，还能全面解析临床背景。通过整合多种模态，我们的模型有望全面理解全切片图像的复杂形态，从而为临床医生提供更精准的癌症诊断支持。

> Recent studies have made significant progress in developing large language models (LLMs) in the medical domain, which can answer expert-level questions and demonstrate the potential to assist clinicians in real-world clinical scenarios. Studies have also witnessed the importance of integrating various modalities with the existing LLMs for a better understanding of complex clinical contexts, which are innately multi-faceted by nature. Although studies have demonstrated the ability of multimodal LLMs in histopathology to answer questions from given images, they lack in understanding of thorough clinical context due to the patch-level data with limited information from public datasets. Thus, developing WSI-level MLLMs is significant in terms of the scalability and applicability of MLLMs in histopathology. In this study, we introduce an expert-level MLLM for histopathology using WSIs, dubbed as ChatEXAONEPath. We present a retrieval-based data generation pipeline using 10,094 pairs of WSIs and histopathology reports from The Cancer Genome Atlas (TCGA). We also showcase an AI-based evaluation protocol for a comprehensive understanding of the medical context from given multimodal information and evaluate generated answers compared to the original histopathology reports. We demonstrate the ability of diagnosing the given histopathology images using ChatEXAONEPath with the acceptance rate of 62.9% from 1,134 pairs of WSIs and reports. Our proposed model can understand pan-cancer WSIs and clinical context from various cancer types. We argue that our proposed model has the potential to assist clinicians by comprehensively understanding complex morphology of WSIs for cancer diagnosis through the integration of multiple modalities.

[Arxiv](https://arxiv.org/abs/2504.13023)