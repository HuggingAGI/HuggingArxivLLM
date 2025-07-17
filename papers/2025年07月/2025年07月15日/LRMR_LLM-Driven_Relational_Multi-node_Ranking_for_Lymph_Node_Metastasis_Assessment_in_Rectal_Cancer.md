# LRMR: LLM驱动的多节点关联排序，助力直肠癌淋巴结转移诊断

发布时间：2025年07月15日

`LLM应用` `医学影像分析`

> LRMR: LLM-Driven Relational Multi-node Ranking for Lymph Node Metastasis Assessment in Rectal Cancer

# 摘要

> 精准的术前淋巴结 (LN) 转移评估在直肠癌中对治疗决策具有指导意义，然而，基于形态学标准的常规 MRI 评估显示出有限的诊断效能。虽然一些人工智能模型已经被开发出来，但它们通常作为黑箱运行，缺乏临床信任所需的可解释性。此外，这些模型通常孤立地评估淋巴结，忽视了患者层面的上下文。为了解决这些问题，我们引入了 LRMR，一个由 LLM 驱动的关系型多节点排序框架。这种方法将诊断任务从直接分类问题重新定义为结构化推理和排序过程。LRMR 框架分为两个阶段：首先，一个多模态大型语言模型 (LLM) 分析来自患者的所有 LN 的复合蒙太奇图像，生成一份详细描述十种不同放射学特征的结构化报告；其次，一个基于文本的 LLM 对不同患者之间的这些报告进行配对比较，根据不良特征的严重程度和数量建立相对风险排序。我们在 117 例直肠癌患者的回顾性队列中评估了我们的方法，LRMR 达到了 0.7917 的曲线下面积 (AUC) 和 0.7200 的 F1 分数，优于包括 ResNet50 (AUC 0.7708) 在内的多种深度学习基线。消融研究证实了我们两个主要贡献的价值：移除关系型排序阶段或结构化提示阶段会导致性能显著下降，AUC 分别降至 0.6875 和 0.6458。我们的工作表明，通过两阶段 LLM 框架将视觉感知与认知推理解耦，为评估直肠癌淋巴结转移提供了一种强大、可解释且有效的全新范式。

> Accurate preoperative assessment of lymph node (LN) metastasis in rectal cancer guides treatment decisions, yet conventional MRI evaluation based on morphological criteria shows limited diagnostic performance. While some artificial intelligence models have been developed, they often operate as black boxes, lacking the interpretability needed for clinical trust. Moreover, these models typically evaluate nodes in isolation, overlooking the patient-level context. To address these limitations, we introduce LRMR, an LLM-Driven Relational Multi-node Ranking framework. This approach reframes the diagnostic task from a direct classification problem into a structured reasoning and ranking process. The LRMR framework operates in two stages. First, a multimodal large language model (LLM) analyzes a composite montage image of all LNs from a patient, generating a structured report that details ten distinct radiological features. Second, a text-based LLM performs pairwise comparisons of these reports between different patients, establishing a relative risk ranking based on the severity and number of adverse features. We evaluated our method on a retrospective cohort of 117 rectal cancer patients. LRMR achieved an area under the curve (AUC) of 0.7917 and an F1-score of 0.7200, outperforming a range of deep learning baselines, including ResNet50 (AUC 0.7708). Ablation studies confirmed the value of our two main contributions: removing the relational ranking stage or the structured prompting stage led to a significant performance drop, with AUCs falling to 0.6875 and 0.6458, respectively. Our work demonstrates that decoupling visual perception from cognitive reasoning through a two-stage LLM framework offers a powerful, interpretable, and effective new paradigm for assessing lymph node metastasis in rectal cancer.

[Arxiv](https://arxiv.org/abs/2507.11457)