# # MMCircuitEval：面向电路的多模态综合基准，用于评估大型语言模型

发布时间：2025年07月20日

`LLM应用

理由：这篇论文探讨了多模态大语言模型（MLLMs）在电子设计自动化（EDA）领域的应用，并通过开发一个新的基准测试MMCircuitEval来评估这些模型在电路设计中的表现。研究重点在于模型的实际应用和评估，属于LLM的应用层面。` `EDA` `电路设计`

> MMCircuitEval: A Comprehensive Multimodal Circuit-Focused Benchmark for Evaluating LLMs

# 摘要

> 多模态大语言模型 (MLLMs) 的诞生为电子设计自动化 (EDA) 领域带来了革命性的机遇。然而，现有基准测试的局限性使得全面评估这些模型在电路设计中的表现仍然充满挑战。为了解决这一问题，我们推出了 MMCircuitEval —— 这是首个专为全面评估多模态大语言模型在各类 EDA 任务中性能而设计的多模态基准测试。

MMCircuitEval 包含了 3614 个经过精心筛选的问题与答案 (QA) 对，涵盖了从数字电路到模拟电路，贯穿EDA设计全流程的关键阶段，从基础知识和规范到前端和后端设计。每个 QA 对均源自教科书、技术题库、数据手册和实际文档，并经过严格的专业审核以确保准确性和相关性。我们的基准测试还根据设计阶段、电路类型、测试能力（知识、理解、推理、计算）和难度级别对问题进行了独特的分类，从而能够对模型的能力和局限性进行详细分析。

通过全面评估，我们发现现有大语言模型在后端设计和复杂计算方面存在显著性能差距，这凸显了针对训练数据集和建模方法进行定向优化的迫切需求。MMCircuitEval 为推动多模态大语言模型在 EDA 领域的发展提供了坚实的基础，有助于它们在实际电路设计工作流中的集成与应用。我们的基准测试现已开源，访问地址为 https://github.com/cure-lab/MMCircuitEval。
    

> The emergence of multimodal large language models (MLLMs) presents promising opportunities for automation and enhancement in Electronic Design Automation (EDA). However, comprehensively evaluating these models in circuit design remains challenging due to the narrow scope of existing benchmarks. To bridge this gap, we introduce MMCircuitEval, the first multimodal benchmark specifically designed to assess MLLM performance comprehensively across diverse EDA tasks. MMCircuitEval comprises 3614 meticulously curated question-answer (QA) pairs spanning digital and analog circuits across critical EDA stages - ranging from general knowledge and specifications to front-end and back-end design. Derived from textbooks, technical question banks, datasheets, and real-world documentation, each QA pair undergoes rigorous expert review for accuracy and relevance. Our benchmark uniquely categorizes questions by design stage, circuit type, tested abilities (knowledge, comprehension, reasoning, computation), and difficulty level, enabling detailed analysis of model capabilities and limitations. Extensive evaluations reveal significant performance gaps among existing LLMs, particularly in back-end design and complex computations, highlighting the critical need for targeted training datasets and modeling approaches. MMCircuitEval provides a foundational resource for advancing MLLMs in EDA, facilitating their integration into real-world circuit design workflows. Our benchmark is available at https://github.com/cure-lab/MMCircuitEval.

[Arxiv](https://arxiv.org/abs/2507.19525)