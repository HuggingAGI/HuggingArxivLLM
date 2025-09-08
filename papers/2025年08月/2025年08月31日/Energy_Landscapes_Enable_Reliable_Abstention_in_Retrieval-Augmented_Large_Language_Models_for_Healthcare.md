# 能量景观助力医疗健康领域检索增强大型语言模型实现可靠拒答

发布时间：2025年08月31日

`RAG` `医疗健康`

> Energy Landscapes Enable Reliable Abstention in Retrieval-Augmented Large Language Models for Healthcare

# 摘要

> 可靠的弃权机制对检索增强生成（RAG）系统而言至关重要，尤其在女性健康这类安全关键领域——错误回答可能造成严重危害。我们提出一种基于能量的模型（EBM），它在包含260万条指南衍生问题的密集语义语料库上学习平滑的能量分布，从而让系统能自主决策生成回答或选择弃权。我们在简单和困难弃权任务分割上，将EBM与校准softmax基线、k近邻（kNN）密度启发式方法展开基准测试——困难案例特指语义复杂的近分布查询。在语义困难案例中，EBM的弃权性能显著优于基线：AUROC达0.961（softmax为0.950），同时FPR@95也从0.331降至0.235。在简单负例任务上，各方法性能不相上下；但在安全关键的困难分布场景中，EBM的优势尤为突出。通过控制负样本采样与公平数据暴露的综合消融实验发现，模型稳健性主要源于能量评分头；而特定负例类型（困难、简单、混合）的取舍虽能锐化决策边界，但对困难案例的泛化能力并非关键。这些结果证实，基于能量的弃权评分比基于概率的softmax置信度更能提供可靠的置信信号，为构建安全的RAG系统奠定了可扩展、可解释的基础。

> Reliable abstention is critical for retrieval-augmented generation (RAG) systems, particularly in safety-critical domains such as women's health, where incorrect answers can lead to harm. We present an energy-based model (EBM) that learns a smooth energy landscape over a dense semantic corpus of 2.6M guideline-derived questions, enabling the system to decide when to generate or abstain. We benchmark the EBM against a calibrated softmax baseline and a k-nearest neighbour (kNN) density heuristic across both easy and hard abstention splits, where hard cases are semantically challenging near-distribution queries. The EBM achieves superior abstention performance abstention on semantically hard cases, reaching AUROC 0.961 versus 0.950 for softmax, while also reducing FPR@95 (0.235 vs 0.331). On easy negatives, performance is comparable across methods, but the EBM's advantage becomes most pronounced in safety-critical hard distributions. A comprehensive ablation with controlled negative sampling and fair data exposure shows that robustness stems primarily from the energy scoring head, while the inclusion or exclusion of specific negative types (hard, easy, mixed) sharpens decision boundaries but is not essential for generalisation to hard cases. These results demonstrate that energy-based abstention scoring offers a more reliable confidence signal than probability-based softmax confidence, providing a scalable and interpretable foundation for safe RAG systems.

[Arxiv](https://arxiv.org/abs/2509.04482)