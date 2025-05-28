# # 眼科视觉问答基准测试：使用OphthalWeChat评估大型多模态模型

发布时间：2025年05月26日

`LLM应用

理由：这篇论文专注于开发一个双语多模态视觉问答基准，用于评估视觉语言模型在眼科领域的应用。它详细描述了如何收集数据、生成问答对以及评估模型性能，属于LLM的实际应用。` `计算机视觉`

> Benchmarking Large Multimodal Models for Ophthalmic Visual Question Answering with OphthalWeChat

# 摘要

> **目的**：开发一个双语多模态视觉问答（VQA）基准，用于评估眼科视觉语言模型（VLMs）。  
**方法**：从2016年1月1日至2024年12月31日期间，收集微信公众号上发布的眼科图像帖子及其说明。基于这些说明，使用GPT-4o-mini生成中英文双语问答（QA）对。根据问题类型和语言，将QA对分为六个子集：二元（Binary_CN，Binary_EN）、单选（Single-choice_CN，Single-choice_EN）和开放（Open-ended_CN，Open-ended_EN）。该基准用于评估GPT-4o、Gemini 2.0 Flash和Qwen2.5-VL-72B-Instruct三个VLM的性能。  
**结果**：最终的OphthalWeChat数据集包含3,469张图像和30,120个QA对，涵盖9个眼科亚专科、548种疾病、29种成像方式和68种模态组合。Gemini 2.0 Flash以0.548的最高整体准确率领先，优于GPT-4o（0.522，P < 0.001）和Qwen2.5-VL-72B-Instruct（0.514，P < 0.001）。它在中文（0.546）和英文子集（0.550）中均表现最佳。具体来看，Gemini 2.0 Flash在Binary_CN（0.687）、Single-choice_CN（0.666）和Single-choice_EN（0.646）中表现突出，而GPT-4o在Binary_EN（0.717）、Open-ended_CN（BLEU-1: 0.301; BERTScore: 0.382）和Open-ended_EN（BLEU-1: 0.183; BERTScore: 0.240）中排名第一。  
**结论**：本研究首次提出眼科领域的双语VQA基准，以其真实世界背景和包含每位患者的多种检查而脱颖而出。该数据集真实反映了临床决策场景，为评估VLM提供了定量依据，助力开发准确、专业且值得信赖的眼科AI系统。

> Purpose: To develop a bilingual multimodal visual question answering (VQA) benchmark for evaluating VLMs in ophthalmology. Methods: Ophthalmic image posts and associated captions published between January 1, 2016, and December 31, 2024, were collected from WeChat Official Accounts. Based on these captions, bilingual question-answer (QA) pairs in Chinese and English were generated using GPT-4o-mini. QA pairs were categorized into six subsets by question type and language: binary (Binary_CN, Binary_EN), single-choice (Single-choice_CN, Single-choice_EN), and open-ended (Open-ended_CN, Open-ended_EN). The benchmark was used to evaluate the performance of three VLMs: GPT-4o, Gemini 2.0 Flash, and Qwen2.5-VL-72B-Instruct. Results: The final OphthalWeChat dataset included 3,469 images and 30,120 QA pairs across 9 ophthalmic subspecialties, 548 conditions, 29 imaging modalities, and 68 modality combinations. Gemini 2.0 Flash achieved the highest overall accuracy (0.548), outperforming GPT-4o (0.522, P < 0.001) and Qwen2.5-VL-72B-Instruct (0.514, P < 0.001). It also led in both Chinese (0.546) and English subsets (0.550). Subset-specific performance showed Gemini 2.0 Flash excelled in Binary_CN (0.687), Single-choice_CN (0.666), and Single-choice_EN (0.646), while GPT-4o ranked highest in Binary_EN (0.717), Open-ended_CN (BLEU-1: 0.301; BERTScore: 0.382), and Open-ended_EN (BLEU-1: 0.183; BERTScore: 0.240). Conclusions: This study presents the first bilingual VQA benchmark for ophthalmology, distinguished by its real-world context and inclusion of multiple examinations per patient. The dataset reflects authentic clinical decision-making scenarios and enables quantitative evaluation of VLMs, supporting the development of accurate, specialized, and trustworthy AI systems for eye care.

[Arxiv](https://arxiv.org/abs/2505.19624)