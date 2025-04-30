# # AKIBoards：结构化多智能体系统，专为预测急性肾损伤设计

发布时间：2025年04月28日

`Agent` `多智能体系统`

> AKIBoards: A Structure-Following Multiagent System for Predicting Acute Kidney Injury

# 摘要

> 诊断推理是医生基于假设或已知的共同视角构建局部（心理）模型，通过证据支持对患者观察结果进行临床评估的过程。但在复杂情况下，多个专家会协同合作，结合各自观点优化健康评估和决策。这种共识驱动的推理反映了个体知识对患者整体视角的贡献。在此背景下，我们提出了面向多智能体系统的结构化推理框架（STRUC-MAS），该框架能够自动化学习全局模型，并将其作为多智能体系统（MAS）中智能体的先验信念进行整合。我们通过一个多智能体系统的应用案例展示了这一概念的可行性，该应用旨在预测急性肾损伤（AKI）。实验结果表明，引入全局结构使多个智能体在预测AKI发作前48小时的表现（平均精度，AP）优于基线模型（平衡精确率加权召回率加权投票）。值得注意的是，初始轮次中，召回率较高的SF-FT智能体在真阳性及假阴性案例中表现出较低的信心水平。但在显式交互后，其对决策的信心有所提升（表明信念的强化）。相比之下，召回率最低的SF-FT智能体在真阳性及假阴性案例中的信心水平下降（表明新信念的形成）。这一方法表明，在多智能体系统中学习和利用全局结构是实现具有竞争力分类与诊断推理性能的必要前提。


> Diagnostic reasoning entails a physician's local (mental) model based on an assumed or known shared perspective (global model) to explain patient observations with evidence assigned towards a clinical assessment. But in several (complex) medical situations, multiple experts work together as a team to optimize health evaluation and decision-making by leveraging different perspectives. Such consensus-driven reasoning reflects individual knowledge contributing toward a broader perspective on the patient. In this light, we introduce STRUCture-following for Multiagent Systems (STRUC-MAS), a framework automating the learning of these global models and their incorporation as prior beliefs for agents in multiagent systems (MAS) to follow. We demonstrate proof of concept with a prosocial MAS application for predicting acute kidney injuries (AKIs). In this case, we found that incorporating a global structure enabled multiple agents to achieve better performance (average precision, AP) in predicting AKI 48 hours before onset (structure-following-fine-tuned, SF-FT, AP=0.195; SF-FT-retrieval-augmented generation, SF-FT-RAG, AP=0.194) vs. baseline (non-structure-following-FT, NSF-FT, AP=0.141; NSF-FT-RAG, AP=0.180) for balanced precision-weighted-recall-weighted voting. Markedly, SF-FT agents with higher recall scores reported lower confidence levels in the initial round on true positive and false negative cases. But after explicit interactions, their confidence in their decisions increased (suggesting reinforced belief). In contrast, the SF-FT agent with the lowest recall decreased its confidence in true positive and false negative cases (suggesting a new belief). This approach suggests that learning and leveraging global structures in MAS is necessary prior to achieving competitive classification and diagnostic reasoning performance.

[Arxiv](https://arxiv.org/abs/2504.20368)