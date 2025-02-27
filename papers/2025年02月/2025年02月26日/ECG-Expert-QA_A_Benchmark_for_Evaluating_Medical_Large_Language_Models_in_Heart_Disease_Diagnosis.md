# ECG-Expert-QA：评估医疗大型语言模型在心脏病诊断中的基准测试

发布时间：2025年02月26日

`LLM应用

理由：这篇论文主要介绍了一个用于评估医学语言模型在心电图诊断方面能力的数据集，属于大型语言模型的实际应用场景。` `心电图诊断`

> ECG-Expert-QA: A Benchmark for Evaluating Medical Large Language Models in Heart Disease Diagnosis

# 摘要

> 我们推出 ECG-Expert-QA，这是一个全面的多模态数据集，旨在评估心电图解释的诊断能力，整合了真实临床数据与系统生成的合成案例。数据集涵盖六项基本诊断任务，包含 47,211 个精心整理的问题-答案对，覆盖了从基础心律分析到复杂病例解读的多种临床场景。通过严格的医学知识引导过程模拟具有挑战性的临床案例，ECG-Expert-QA 不仅提高了标注诊断数据的可用性，还显著增加了临床表现的复杂性和多样性，包括罕见心脏状况和时间进展模式。这种设计使医学语言模型能够在诊断准确性、临床推理和知识整合等多个维度进行全面评估。为了促进全球研究合作，ECG-Expert-QA 提供了中文和英文两个版本，并通过严格的质量控制确保语言和临床的一致性。该数据集的具有挑战性的诊断任务，包括复杂心律失常的解读、微小缺血性变化的识别以及临床背景的整合，使其成为推进 AI 辅助心电图解读和推动现有诊断模型边界的有效基准。我们的数据集是开源的，可在 https://github.com/Zaozzz/ECG-Expert-QA 获取。

> We present ECG-Expert-QA, a comprehensive multimodal dataset designed for evaluating diagnostic capabilities in ECG interpretation, integrating real clinical data with systematically generated synthetic cases. The dataset encompasses six fundamental diagnostic tasks, comprising 47,211 meticulously curated question-answer pairs that span a spectrum of clinical scenarios, from basic rhythm analysis to complex case interpretation. By simulating challenging clinical cases through a rigorous medical knowledge-guided process, ECG-Expert-QA not only enhances the availability of annotated diagnostic data but also significantly increases the complexity and diversity of clinical presentations, including rare cardiac conditions and temporal progression patterns. This design enables comprehensive evaluation of medical language models across multiple dimensions, including diagnostic accuracy, clinical reasoning, and knowledge integration. To facilitate global research collaboration, ECG-Expert-QA is available in both Chinese and English versions, with rigorous quality control ensuring linguistic and clinical consistency. The dataset's challenging diagnostic tasks, which include interpretation of complex arrhythmias, identification of subtle ischemic changes, and integration of clinical context, establish it as an effective benchmark for advancing AI-assisted ECG interpretation and pushing the boundaries of current diagnostic models. Our dataset is open-source and available at https://github.com/Zaozzz/ECG-Expert-QA

[Arxiv](https://arxiv.org/abs/2502.17475)