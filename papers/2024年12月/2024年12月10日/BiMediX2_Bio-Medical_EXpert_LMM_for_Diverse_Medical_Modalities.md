# BiMediX2：适用于多种医疗模式的生物医学专家 LMM

发布时间：2024年12月10日

`LLM应用` `多模态模型`

> BiMediX2: Bio-Medical EXpert LMM for Diverse Medical Modalities

# 摘要

> 这篇论文介绍了 BiMediX2，这是一个双语（阿英）的生物医学专家大型多模态模型（LMM），其统一架构融合了文本与视觉模态，可实现出色的图像理解及医疗应用。BiMediX2 借助 Llama3.1 架构，整合了文本和视觉能力，便于英语和阿拉伯语的无缝交互，支持文本输入及涉及医疗图像的多轮对话。该模型基于一个庞大的双语医疗保健数据集训练而成，此数据集包含 160 万个不同医疗交互样本，涵盖文本和图像模态，且混合了阿语和英语。我们还提出了首个基于双语 GPT-4o 的医疗 LMM 基准，名为 BiMed-MBench。BiMediX2 在基于文本和图像的任务中均进行了基准测试，在多个医疗基准测试中达到了领先水平。它在医疗 LLM 评估基准中超越了近期的先进模型。我们的模型在多模态医疗评估中也树立了新标杆，英语评估提升超 9%，阿拉伯语评估提升超 20%。此外，在 UPHILL 事实准确性评估中比 GPT-4 约高 9%，在各类医疗视觉问答、报告生成及报告总结任务中表现卓越。包括源代码和训练模型的项目页面可在 https://github.com/mbzuai-oryx/BiMediX2 访问。

> This paper introduces BiMediX2, a bilingual (Arabic-English) Bio-Medical EXpert Large Multimodal Model (LMM) with a unified architecture that integrates text and visual modalities, enabling advanced image understanding and medical applications. BiMediX2 leverages the Llama3.1 architecture and integrates text and visual capabilities to facilitate seamless interactions in both English and Arabic, supporting text-based inputs and multi-turn conversations involving medical images. The model is trained on an extensive bilingual healthcare dataset consisting of 1.6M samples of diverse medical interactions for both text and image modalities, mixed in Arabic and English. We also propose the first bilingual GPT-4o based medical LMM benchmark named BiMed-MBench. BiMediX2 is benchmarked on both text-based and image-based tasks, achieving state-of-the-art performance across several medical benchmarks. It outperforms recent state-of-the-art models in medical LLM evaluation benchmarks. Our model also sets a new benchmark in multimodal medical evaluations with over 9% improvement in English and over 20% in Arabic evaluations. Additionally, it surpasses GPT-4 by around 9% in UPHILL factual accuracy evaluations and excels in various medical Visual Question Answering, Report Generation, and Report Summarization tasks. The project page including source code and the trained model, is available at https://github.com/mbzuai-oryx/BiMediX2.

[Arxiv](https://arxiv.org/abs/2412.07769)