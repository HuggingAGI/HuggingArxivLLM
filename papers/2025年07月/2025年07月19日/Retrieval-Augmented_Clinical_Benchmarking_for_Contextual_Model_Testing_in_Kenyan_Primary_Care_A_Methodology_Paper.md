# 针对肯尼亚基层医疗的情境模型测试，采用基于检索增强的临床基准测试方法：方法学论文

发布时间：2025年07月19日

`RAG` `知识图谱`

> Retrieval-Augmented Clinical Benchmarking for Contextual Model Testing in Kenyan Primary Care: A Methodology Paper

# 摘要

> 大型语言模型（LLMs）在改善资源匮乏地区的医疗获取方面展现出巨大潜力，但其在非洲初级保健中的有效性仍研究尚不充分。我们提出了一种针对肯尼亚二级和三级临床护理的基准数据集和评估框架构建方法。我们的方法采用检索增强生成（RAG）技术，将临床问题与肯尼亚国家指南相结合，确保与本地标准保持一致。这些指南经过数字化处理、分块化和语义检索索引。随后，使用 Gemini Flash 2.0 Lite 通过提示工程生成基于指南摘录的现实临床场景、多选题和基于英文和斯瓦希里语的解释性答案。肯尼亚医师参与了数据集的共同创建和优化，盲审专家评审流程确保了临床准确性、清晰度和文化适用性。最终的 Alama Health QA 数据集包含数千个与监管标准对齐的问答对，涵盖常见门诊疾病。除了准确性，我们还引入了评估指标，测试临床推理、安全性和适应性，如罕见病例检测（Needle in the Haystack）、逐步逻辑（Decision Points）和情境适应性。初步结果显示，当 LLMs 应用于本地化场景时，性能存在显著差距，这一结果与 LLM 在非洲医学内容上的准确性低于基于美国的基准测试结果一致。本研究为基于指南的动态基准测试提供了一个可复制的模型，支持非洲卫生系统的安全 AI 部署。

> Large Language Models(LLMs) hold promise for improving healthcare access in low-resource settings, but their effectiveness in African primary care remains underexplored. We present a methodology for creating a benchmark dataset and evaluation framework focused on Kenyan Level 2 and 3 clinical care. Our approach uses retrieval augmented generation (RAG) to ground clinical questions in Kenya's national guidelines, ensuring alignment with local standards. These guidelines were digitized, chunked, and indexed for semantic retrieval. Gemini Flash 2.0 Lite was then prompted with guideline excerpts to generate realistic clinical scenarios, multiple-choice questions, and rationale based answers in English and Swahili. Kenyan physicians co-created and refined the dataset, and a blinded expert review process ensured clinical accuracy, clarity, and cultural appropriateness. The resulting Alama Health QA dataset includes thousands of regulator-aligned question answer pairs across common outpatient conditions. Beyond accuracy, we introduce evaluation metrics that test clinical reasoning, safety, and adaptability such as rare case detection (Needle in the Haystack), stepwise logic (Decision Points), and contextual adaptability. Initial results reveal significant performance gaps when LLMs are applied to localized scenarios, consistent with findings that LLM accuracy is lower on African medical content than on US-based benchmarks. This work offers a replicable model for guideline-driven, dynamic benchmarking to support safe AI deployment in African health systems.

[Arxiv](https://arxiv.org/abs/2507.14615)