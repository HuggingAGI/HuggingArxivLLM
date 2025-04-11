# Zeus：多模态医学影像联合分割的零样本 LLM 指令

发布时间：2025年04月09日

`LLM应用` `医学图像处理`

> Zeus: Zero-shot LLM Instruction for Union Segmentation in Multimodal Medical Imaging

# 摘要

> 医学图像分割借助UNet和Transformer模型的持续突破取得了显著进展。然而，真实世界的临床诊断往往需要整合领域知识，尤其是文本信息。多模态学习被视为一种解决方案，但收集配对的视觉-语言数据集成本高昂且耗时，带来了巨大挑战。受大型语言模型（LLMs）在跨模态任务中的卓越表现启发，我们提出了一种全新的视觉-LLM联合框架来解决这些问题。具体而言，我们引入冻结的LLMs进行基于医学图像的零样本指令生成，模拟放射科检查和报告生成过程。为了更好地逼近真实世界的诊断流程，我们从多模态放射图像（如T1加权或T2加权MRI和CT）中生成更精确的文本指令。基于LLMs在语义理解和丰富知识方面的强大能力，这一过程着重于提取不同模态的特殊特征，并将信息整合以实现最终的临床诊断。通过生成的文本指令，我们提出的联合分割框架能够在没有预先收集的视觉-语言数据集的情况下处理多模态分割任务。为了评估我们提出的方法，我们进行了全面的实验，与有影响力的基线方法进行对比。统计结果和可视化案例研究表明，我们的新方法具有显著优势。

> Medical image segmentation has achieved remarkable success through the continuous advancement of UNet-based and Transformer-based foundation backbones. However, clinical diagnosis in the real world often requires integrating domain knowledge, especially textual information. Conducting multimodal learning involves visual and text modalities shown as a solution, but collecting paired vision-language datasets is expensive and time-consuming, posing significant challenges. Inspired by the superior ability in numerous cross-modal tasks for Large Language Models (LLMs), we proposed a novel Vision-LLM union framework to address the issues. Specifically, we introduce frozen LLMs for zero-shot instruction generation based on corresponding medical images, imitating the radiology scanning and report generation process. {To better approximate real-world diagnostic processes}, we generate more precise text instruction from multimodal radiology images (e.g., T1-w or T2-w MRI and CT). Based on the impressive ability of semantic understanding and rich knowledge of LLMs. This process emphasizes extracting special features from different modalities and reunion the information for the ultimate clinical diagnostic. With generated text instruction, our proposed union segmentation framework can handle multimodal segmentation without prior collected vision-language datasets. To evaluate our proposed method, we conduct comprehensive experiments with influential baselines, the statistical results and the visualized case study demonstrate the superiority of our novel method.}

[Arxiv](https://arxiv.org/abs/2504.07336)