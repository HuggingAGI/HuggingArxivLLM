# MDTeamGPT: 基于LLM的自进化多智能体框架，专为多学科团队医疗咨询设计

发布时间：2025年03月17日

`LLM应用` `知识图谱`

> MDTeamGPT: A Self-Evolving LLM-based Multi-Agent Framework for Multi-Disciplinary Team Medical Consultation

# 摘要

> 大型语言模型（LLMs）在多个领域取得了显著进展，但在多学科团队（MDT）医疗咨询方面仍面临挑战。目前的研究通过角色分配、任务分解和积累医学经验来提升推理能力。然而，MDT咨询中的多角色协作往往导致对话历史过长，增加了模型的认知负担，降低了效率和准确性。一些方法仅存储治疗历史，未能有效提取经验或反思错误，限制了知识的泛化和系统进化。我们提出了一种基于LLMs的多智能体MDT医疗咨询框架，以解决这些问题。我们的框架采用共识聚合和多轮咨询的残差讨论结构，并利用正确答案知识库（CorrectKB）和链式思维知识库（ChainKB）积累咨询经验。这些机制使框架能够进化，持续提升诊断合理性和准确性。实验结果表明，在MedQA和PubMedQA数据集上，我们的框架分别达到了90.1%和83.9%的准确率，且构建的知识库在两个数据集的测试集上均实现了有效泛化。

> Large Language Models (LLMs) have made significant progress in various fields. However, challenges remain in Multi-Disciplinary Team (MDT) medical consultations. Current research enhances reasoning through role assignment, task decomposition, and accumulation of medical experience. Multi-role collaboration in MDT consultations often results in excessively long dialogue histories. This increases the model's cognitive burden and degrades both efficiency and accuracy. Some methods only store treatment histories. They do not extract effective experience or reflect on errors. This limits knowledge generalization and system evolution. We propose a multi-agent MDT medical consultation framework based on LLMs to address these issues. Our framework uses consensus aggregation and a residual discussion structure for multi-round consultations. It also employs a Correct Answer Knowledge Base (CorrectKB) and a Chain-of-Thought Knowledge Base (ChainKB) to accumulate consultation experience. These mechanisms enable the framework to evolve and continually improve diagnosis rationality and accuracy. Experimental results on the MedQA and PubMedQA datasets demonstrate that our framework achieves accuracies of 90.1% and 83.9%, respectively, and that the constructed knowledge bases generalize effectively across test sets from both datasets.

[Arxiv](https://arxiv.org/abs/2503.13856)