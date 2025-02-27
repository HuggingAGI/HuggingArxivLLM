# MEDDxAgent：一个统一的模块化智能体框架，用于实现可解释的自动鉴别诊断

发布时间：2025年02月26日

`Agent

理由：论文重点在于设计和实现一个模块化的智能体框架MEDDxAgent，用于交互式鉴别诊断。该框架整合了多个组件，如编排器、病史采集模拟器和知识检索代理，强调智能体在诊断推理中的应用和性能提升。因此，它属于Agent类别。`

> MEDDxAgent: A Unified Modular Agent Framework for Explainable Automatic Differential Diagnosis

# 摘要

> 鉴别诊断（DDx）是临床决策中的关键而复杂的环节。医生通过症状、病史和医学知识，逐步细化可能疾病的排序列表。尽管大型语言模型在支持DDx方面展现出潜力，现有方法仍存在重要局限，包括单一数据集评估、孤立的组件优化、对完整患者档案的不切实际假设，以及单次诊断尝试。我们提出了一种模块化可解释的DDx代理（MEDDxAgent）框架，专为交互式DDx设计，其中诊断推理通过迭代学习演进，而非假设完整患者档案可获取。MEDDxAgent整合了三个模块化组件：(1) 一个编排器（DDxDriver），(2) 一个病史采集模拟器，(3) 两个专门用于知识检索和诊断策略的代理。为了确保稳健评估，我们引入了一个全面的DDx基准，涵盖呼吸、皮肤和罕见疾病。我们分析了单轮诊断方法，并展示了在患者档案初始不可用时，迭代细化的重要性。我们的广泛评估表明，MEDDxAgent在交互式DDx中实现了超过10%的准确率提升，适用于大小型LLM，同时提供了对其诊断推理过程的关键解释性。


> Differential Diagnosis (DDx) is a fundamental yet complex aspect of clinical decision-making, in which physicians iteratively refine a ranked list of possible diseases based on symptoms, antecedents, and medical knowledge. While recent advances in large language models have shown promise in supporting DDx, existing approaches face key limitations, including single-dataset evaluations, isolated optimization of components, unrealistic assumptions about complete patient profiles, and single-attempt diagnosis. We introduce a Modular Explainable DDx Agent (MEDDxAgent) framework designed for interactive DDx, where diagnostic reasoning evolves through iterative learning, rather than assuming a complete patient profile is accessible. MEDDxAgent integrates three modular components: (1) an orchestrator (DDxDriver), (2) a history taking simulator, and (3) two specialized agents for knowledge retrieval and diagnosis strategy. To ensure robust evaluation, we introduce a comprehensive DDx benchmark covering respiratory, skin, and rare diseases. We analyze single-turn diagnostic approaches and demonstrate the importance of iterative refinement when patient profiles are not available at the outset. Our broad evaluation demonstrates that MEDDxAgent achieves over 10% accuracy improvements in interactive DDx across both large and small LLMs, while offering critical explainability into its diagnostic reasoning process.

[Arxiv](https://arxiv.org/abs/2502.19175)