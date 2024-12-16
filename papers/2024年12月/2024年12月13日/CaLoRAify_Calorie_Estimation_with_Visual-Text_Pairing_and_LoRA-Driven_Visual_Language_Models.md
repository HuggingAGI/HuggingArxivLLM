# CaLoRAify：借助视觉 - 文本配对和 LoRA 驱动的视觉语言模型来估算卡路里

发布时间：2024年12月13日

`LLM应用` `医疗健康` `饮食营养`

> CaLoRAify: Calorie Estimation with Visual-Text Pairing and LoRA-Driven Visual Language Models

# 摘要

> 肥胖现象，也就是所谓的重大问题，是全球范围内可预防慢性疾病的一个主要诱因。传统的卡路里估算工具往往依赖特定的数据格式或复杂的流程，这在实际场景中限制了其实用性。近来，视觉语言模型（VLMs）在理解现实情境和实现对话交互方面表现出众，因而成为成分分析等下游任务的理想之选。然而，将 VLMs 应用于卡路里估算需要特定领域的数据和对齐策略。为此，我们精心整理了 CalData，这是一个包含 33 万组图像 - 文本对的数据集，专门用于成分识别和卡路里估算，它将大规模的食谱数据集与详细的营养说明相结合，以进行强大的视觉语言训练。基于这个数据集，我们推出了 CaLoRAify，这是一个新型的 VLM 框架，通过视觉 - 文本对训练来实现成分识别和卡路里估算的对齐。在推理时，用户仅需一张单目食物图像就能估算卡路里，同时还能保留基于代理的对话交互的灵活性。凭借低秩自适应（LoRA）和检索增强生成（RAG）技术，我们的系统提升了基础 VLMs 在卡路里估算垂直领域的性能。我们的代码和数据在 https://github.com/KennyYao2001/16824-CaLORAify 完全开源。

> The obesity phenomenon, known as the heavy issue, is a leading cause of preventable chronic diseases worldwide. Traditional calorie estimation tools often rely on specific data formats or complex pipelines, limiting their practicality in real-world scenarios. Recently, vision-language models (VLMs) have excelled in understanding real-world contexts and enabling conversational interactions, making them ideal for downstream tasks such as ingredient analysis. However, applying VLMs to calorie estimation requires domain-specific data and alignment strategies. To this end, we curated CalData, a 330K image-text pair dataset tailored for ingredient recognition and calorie estimation, combining a large-scale recipe dataset with detailed nutritional instructions for robust vision-language training. Built upon this dataset, we present CaLoRAify, a novel VLM framework aligning ingredient recognition and calorie estimation via training with visual-text pairs. During inference, users only need a single monocular food image to estimate calories while retaining the flexibility of agent-based conversational interaction. With Low-rank Adaptation (LoRA) and Retrieve-augmented Generation (RAG) techniques, our system enhances the performance of foundational VLMs in the vertical domain of calorie estimation. Our code and data are fully open-sourced at https://github.com/KennyYao2001/16824-CaLORAify.

[Arxiv](https://arxiv.org/abs/2412.09936)