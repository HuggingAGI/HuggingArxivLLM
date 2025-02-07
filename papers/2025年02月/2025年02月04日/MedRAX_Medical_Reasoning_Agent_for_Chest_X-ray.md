# MedRAX: 胸部X光医学推理助手

发布时间：2025年02月04日

`LLM应用

理由：这篇论文介绍了MedRAX，一个将CXR分析工具与多模态大型语言模型整合的框架，用于处理复杂医疗查询。这属于将大型语言模型应用于特定领域（医疗）的实际应用场景，因此归类为LLM应用。` `放射学`

> MedRAX: Medical Reasoning Agent for Chest X-ray

# 摘要

> 胸部X光片（CXRs）在疾病管理和患者护理中发挥着关键作用，推动着重要决策的制定。尽管近期创新催生了多种CXR解读任务的专门模型，但这些模型往往孤立运作，限制了其在临床实践中的实际应用。我们推出了MedRAX，这是首个将顶尖CXR分析工具与多模态大型语言模型无缝整合的统一框架。MedRAX无需额外训练，便能动态调用这些模型处理复杂医疗查询。为全面评估其能力，我们推出了ChestAgentBench，一个涵盖7大类共2,500个复杂医疗查询的综合基准。实验结果显示，MedRAX在性能上超越了开源和专有模型，标志着自动化CXR解读系统迈向实际应用的重要一步。数据和代码已公开于https://github.com/bowang-lab/MedRAX。

> Chest X-rays (CXRs) play an integral role in driving critical decisions in disease management and patient care. While recent innovations have led to specialized models for various CXR interpretation tasks, these solutions often operate in isolation, limiting their practical utility in clinical practice. We present MedRAX, the first versatile AI agent that seamlessly integrates state-of-the-art CXR analysis tools and multimodal large language models into a unified framework. MedRAX dynamically leverages these models to address complex medical queries without requiring additional training. To rigorously evaluate its capabilities, we introduce ChestAgentBench, a comprehensive benchmark containing 2,500 complex medical queries across 7 diverse categories. Our experiments demonstrate that MedRAX achieves state-of-the-art performance compared to both open-source and proprietary models, representing a significant step toward the practical deployment of automated CXR interpretation systems. Data and code have been publicly available at https://github.com/bowang-lab/MedRAX

[Arxiv](https://arxiv.org/abs/2502.02673)