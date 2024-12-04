# 用于病理学的多模态全切片基础模型

发布时间：2024年11月29日

`LLM应用` `病理学`

> Multimodal Whole Slide Foundation Model for Pathology

# 摘要

> 摘要：在计算病理学领域，基础模型的最新进展带来了变革，其通过自监督学习（SSL）将组织病理学的感兴趣区域（ROIs）编码为通用且可迁移的特征表示。但要将这些成果用于解决患者和切片层面的复杂临床难题，仍受特定疾病队列中有限临床数据的制约，尤其是针对罕见临床状况。我们提出了 TITAN，这是一个多模态全切片基础模型，通过视觉自监督学习、与相应病理报告的视觉语言对齐，利用 335,645 个 WSI 进行了预训练，还使用了由多模态生成式 AI 病理学助手生成的 423,122 个合成标题。无需任何微调或临床标签，TITAN 能够提取通用的切片表示，并生成适用于资源有限临床场景（如罕见疾病检索和癌症预后）的病理报告。我们在多种临床任务中对 TITAN 进行了评估，发现其在诸如线性探测、少样本和零样本分类、罕见癌症检索和跨模态检索以及病理报告生成等机器学习设置中，表现均优于 ROI 和切片基础模型。

> 
Abstract:The field of computational pathology has been transformed with recent advances in foundation models that encode histopathology region-of-interests (ROIs) into versatile and transferable feature representations via self-supervised learning (SSL). However, translating these advancements to address complex clinical challenges at the patient and slide level remains constrained by limited clinical data in disease-specific cohorts, especially for rare clinical conditions. We propose TITAN, a multimodal whole slide foundation model pretrained using 335,645 WSIs via visual self-supervised learning and vision-language alignment with corresponding pathology reports and 423,122 synthetic captions generated from a multimodal generative AI copilot for pathology. Without any finetuning or requiring clinical labels, TITAN can extract general-purpose slide representations and generate pathology reports that generalize to resource-limited clinical scenarios such as rare disease retrieval and cancer prognosis. We evaluate TITAN on diverse clinical tasks and find that TITAN outperforms both ROI and slide foundation models across machine learning settings such as linear probing, few-shot and zero-shot classification, rare cancer retrieval and cross-modal retrieval, and pathology report generation.
    

[Arxiv](https://arxiv.org/pdf/2411.19666)