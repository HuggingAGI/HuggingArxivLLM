# 灵枢：统一多模态医学理解与推理的通用基础模型

发布时间：2025年06月08日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）在医学应用中的有效性及其改进方法，属于对大型语言模型的具体应用研究。` `多模态`

> Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）在理解常见视觉元素方面展现出了卓越的能力，这主要得益于其大规模数据集和先进的训练策略。然而，由于医疗场景中的数据和任务与通用领域之间存在固有差异，MLLMs在医学应用中的有效性仍然有限。具体而言，现有的医学MLLMs面临以下关键限制：（1）医学知识覆盖范围有限，不仅限于医学成像；（2）由于数据整理流程不够优化，导致幻觉现象更加严重；（3）缺乏针对复杂医学场景的推理能力。

为了解决这些挑战，我们首先提出了一种全面的数据整理流程，该流程能够高效获取丰富的医学知识数据，不仅来自医学成像，还来自广泛的医学文本和通用领域数据；并能够合成准确的医学描述、视觉问答（VQA）和推理样本。因此，我们构建了一个富含广泛医学知识的多模态数据集。基于整理好的数据，我们引入了我们的医学专用MLLM：Lingshu。Lingshu通过多阶段训练嵌入医学专业知识，并逐步增强其任务解决能力。

此外，我们初步探索了将具有可验证奖励范式的强化学习应用于提升Lingshu的医学推理能力的潜力。另外，我们开发了MedEvalKit，这是一个统一的评估框架，整合了领先的多模态和文本医学基准，以实现标准化、公平和高效的模型评估。我们在三个基础医学任务上评估了Lingshu的性能，包括多模态问答、基于文本的问答和医学报告生成。结果表明，Lingshu在大多数任务上始终优于现有的开源多模态模型……

> Multimodal Large Language Models (MLLMs) have demonstrated impressive capabilities in understanding common visual elements, largely due to their large-scale datasets and advanced training strategies. However, their effectiveness in medical applications remains limited due to the inherent discrepancies between data and tasks in medical scenarios and those in the general domain. Concretely, existing medical MLLMs face the following critical limitations: (1) limited coverage of medical knowledge beyond imaging, (2) heightened susceptibility to hallucinations due to suboptimal data curation processes, (3) lack of reasoning capabilities tailored for complex medical scenarios. To address these challenges, we first propose a comprehensive data curation procedure that (1) efficiently acquires rich medical knowledge data not only from medical imaging but also from extensive medical texts and general-domain data; and (2) synthesizes accurate medical captions, visual question answering (VQA), and reasoning samples. As a result, we build a multimodal dataset enriched with extensive medical knowledge. Building on the curated data, we introduce our medical-specialized MLLM: Lingshu. Lingshu undergoes multi-stage training to embed medical expertise and enhance its task-solving capabilities progressively. Besides, we preliminarily explore the potential of applying reinforcement learning with verifiable rewards paradigm to enhance Lingshu's medical reasoning ability. Additionally, we develop MedEvalKit, a unified evaluation framework that consolidates leading multimodal and textual medical benchmarks for standardized, fair, and efficient model assessment. We evaluate the performance of Lingshu on three fundamental medical tasks, multimodal QA, text-based QA, and medical report generation. The results show that Lingshu consistently outperforms the existing open-source multimodal models on most tasks ...

[Arxiv](https://arxiv.org/abs/2506.07044)